# go

This repository contains my go modules/codes/README.

## Install go

1. Official Download: https://go.dev/doc/install
2. Webi Install: https://webinstall.dev/golang/

## Initialize go module

<details>
    <summary>Description</summary>
        <p>
        When your code imports packages contained in other modules, you manage those dependencies through your code's own module. That module is defined by a go.mod file that tracks the modules that provide those packages. That go.mod file stays with your code, including in your source code repository.
        In actual development, the module path will typically be the repository location where your source code will be kept. For example, the module path might be github.com/mymodule.
        Reference: https://go.dev/doc/tutorial/getting-started#code
        </p>

</details>

```console
go mod init <name-of-your-module>
```

## Run go

```console
go run <file-name>.go
```

## Download modules

```console
go mod download
```

## Download modules, satisfying all the imports

```console
go mod tidy
```

## Build go module

```console
go build -o <output-file-name>
```
