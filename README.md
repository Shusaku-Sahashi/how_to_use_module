# how_to_use_module
trial for go module.

https://github.com/golang/go/wiki/Modules

go module allows make working directory outside GOPATH.

0. activate go module mode
  go module is inactive in v1.11. So you must activate.

  `cd <GOPATH>`

  `export GO111MODULE=on`

1. Create working directory outside GOPATH.

  `mkdir ~/tmp/working/how_to_use_module`

2. Initalize modeule.

  `go mod init example.com/myapp/how_to_use_module`

3. Import modules

  `go build` or `go test`
