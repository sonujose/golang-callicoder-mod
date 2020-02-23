# GO Project
sample Go project that has multiple custom packages with a bunch of source code files and see how the same concept of package declaration, imports, and exports apply to custom packages as well (https://www.callicoder.com/golang-packages/).


## Initialize a Go module by typing the following commands:

```s
mkdir packer 
cd packer
go mod init github.com/callicoder/packer
```

Now create some source files and place them in different packages inside our project.

```s
# Building the Go module
$ go build
```

## Package Alias
You can use package alias to resolve conflicts between different packages of the same name, or just to give a short name to the imported package

## Manually installing packages
You can use go get command to download 3rd party packages from remote repositories.

```s
$ go get -u github.com/jinzhu/gorm
```
