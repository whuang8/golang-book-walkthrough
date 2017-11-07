## Problems

1. How are integers stored on a computer?

Integers are stored as bits and represented as binary. Several Go integer types allow for certain numbers of bits to represent an integer.

2. What's the largest 8-digit number in binary

11111111

3. Write a program that computes `321325 x 424521` and prints it to the terminal

```go
package main

import "fmt"

func main() {
    fmt.Println(321325 * 424521)
}

```

4. What is a string? How do you find its length

A string is a sequence of letters(bytes). `len("string")` finds the length of `"string"`

5. What is the value of the expression `(true && false) || (false && true) || !(false && false)`

`true`

