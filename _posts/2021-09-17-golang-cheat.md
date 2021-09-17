## github.com/johndstein/gohello1

```go.mod```

```go
module github.com/johndstein/gohello1

go 1.16

require github.com/johndstein/gohello2 v0.1.4

replace github.com/johndstein/gohello2 => ../gohello2
```

```main.go```

```go
package main

import (
	"github.com/johndstein/gohello2/hello"
)

func main() {
	hello.World()
}
```

## github.com/johndstein/gohello2

```go.mod```

```go
module github.com/johndstein/gohello2

go 1.16
```

```hello/hi.go```

```go
package hello

import "fmt"

func World() {
	fmt.Println("Hello, world 222.")
}
```
