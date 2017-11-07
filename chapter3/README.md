## Notes | Chapter 3 | Types

- Go is [statically typed](https://en.wikipedia.org/wiki/Type_system#Static_type_checking)
**Integers**
- Integers represent numbers without decimal points
- Go's integer types are `uint8` `uint16` `uint32` `uint64` `int8` `int16` `int32` `int64`
- `uint` is unsigned and `int` is signed
- `byte` is an alias for `uint8`
- `rune` is an alias for `int32`
- machine dependent integer types are `uint` `int` `uintptr`

**Floating Point Numbers**
- Floating point numbers are real numbers
- Floats are unexact
```
1.01 - 0.99 = 0.020000000000000018

```
- Go's floating point types are `float32` `float64`
- `NaN` represents things like `0/0`
- `-∞` `+∞`

**Strings**
- Go strings are made up of individual bytes. Usually 1 per letter
- String literals created with double quotes or back ticks
- Double quoted strings allow special escape sequences
- \n gets replaced with newline and \t with a tab

**Boolean**
- Special 1 bit integer type
- Three logical operators used on booleans: `&&` `||` `!`

### Problems
[Answers for chapter 3](problems.md)
