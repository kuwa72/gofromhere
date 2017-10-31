Go from here
============

A command of go project initializer with direnv.

It's create .envrc, basic go directories and basic project files.

.envrc set current directory to GOPATH and regenerate PATH with $GOPATH/bin.

Basic directories is "bin" and "src".

If run gofromhere with repository url (like `gofromhere github.com/you/libname`), create project directories under src direcotry, create simple source file (contains hello world) and git init.

Beware, this script is not check arguments. If you use unsecure strings for arguments, this script brake your system.

Please check [example directory](https://github.com/kuwa72/gofromhere/tree/master/example).

## usage

```
$ mkdir projectdir
$ cd projectdir
$ gofromhere github.com/you/libname
$ direnv allow
```
