## Problems

1. What is whitespace?
Whitespace is a non visible character such as tabs, spaces, and newlines.

2. What is a comment? What are the two ways of writing a comment
A comment is text ignored by the Go compiler. Two ways of writing comments are `//` and `/* */`

3. Our program began with `package main`. What would the files in the `fmt` package begin with?
`package fmt`

4. We used the `Println` function defined in the `fmt` package. If we wanted to use the `Exit` function from the `os` package what would we need to do?
```go
package main

import "fmt"
import "os"

func main() {
    os.Exit()
}
```

5. Modify the program we wrote so that instead of printing `Hello World` it prints `Hello, my name is` followed by your name.

```go
package main

import "fmt"

func main() {
    // lmao
    fmt.Println("Hello, my name is William")
}
```


