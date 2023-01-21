# Start with Go

## Create new module 
```
$ go mod init example.com/module_name
```

## Import module
```Go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}

```

## Run Golang file
```
$ go run .
```

## Golang Help
```
$ go help
```

## Import external package
```Go
package main

import "fmt"

import "rsc.io/quote"

func main() {
    fmt.Println(quote.Go())
}
```

## Sync the imported module
```
$ go mod tidy
```