# Create a module
 
## Create new module 
```
$ go mod init example.com/module_name
```
 
## Use local module
```
$ go mod edit -replace example.com/greetings=../greetings
```

## Synchronize the module
```
$ go mod tidy
```
 
## Using map in Golang
### Format
```
make(map[key-type]value-type)
```

### In use
```
message := make(map[string]string)
map["Hello"] = "World"
```
## Function
### Can handle multiple return values
```Go
func Example(name type) (type1, type2, type3) {
    ...
    return value1, value2, value3
}
```

## Compile and Install
### Compile into executable file
```
$ go build
```

### Add Go install directory
```
$ go env -w GOBIN=/path/to/your/bin
```
### Install the package
```
$ go install
```

## Reference
https://go.dev/doc/tutorial/create-module