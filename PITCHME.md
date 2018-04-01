# Tester's Golang Notes

- Golang Environment Setup
- Basic Golang
- Advanced Golang
- Golang Testing
- Golang Design Pattern

---

@title[Golang Environment Setup]
## Golang Environment Setup
- Install Golang
- Setup GOPATH

---

### Install Golang

- go to golang.org
- download the latest go installation file
- Setup GOROOT(How,just search it to solve)

---

### Setup GOPATH 

setup GOPATH 

```shell
WORKSPACE=`pwd`
echo "export GOPATH="${WORKSPACE}"">> ~/.zshrc
```

---

@title[Run Golang]
## Run Golang script

- helloworld.go

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello World!")
}
```
- go build

```sh
go build helloworld.go
```

- go run

```sh
go run helloworld.go 

```

---

@title[Elements in Golang]
## Elements in Golang

- package declaration
- imported package
- function
- statements
- comments

look at helloworld.go again:

```go

//package declaration
package main

//import package
import "fmt"

//function and main entry
func main() {
	//statement
	fmt.Println("Hello World!")
}
```

---