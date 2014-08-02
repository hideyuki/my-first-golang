# My First Go-Lang

## Instalation

- Visit [http://golang.org/dl/](http://golang.org/dl/) and download pkg: e.g. [go1.3.darwin-amd64-osx10.8.pkg](http://golang.org/dl/go1.3.darwin-amd64-osx10.8.pkg)
- Install pkg
- Add config to ~/.bashrc

```
# golang
export GOROOT=/usr/local/go
export GOPATH=$HOME/.go
export PATH=$PATH:$GOROOT/bin:$GOPATH/bin
```

- add bash completion

```
$ sudo ln -s /usr/local/go/misc/bash/go /usr/local/etc/bash_completion.d/go
```

## How to build

```
$ go build hello.go
$ ./hello
Hello World!
```


