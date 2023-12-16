# Go Cheat Sheet

## Table of Contents

- data types

## data types

```go
// int
var i int8 = 127 // -128 to 127
var i int16 = 32767 // -32768 to 32767
var i int32 = 2147483647 // -2147483648 to 2147483647
var i int64 = 9223372036854775807 // -9223372036854775808 to 9223372036854775807
var i int = 9223372036854775807 // depends on the platform (32 or 64 bit)

// uint
var i uint8 = 255 // 0 to 255
var i uint16 = 65535 // 0 to 65535
var i uint32 = 4294967295 // 0 to 4294967295
var i uint64 = 18446744073709551615 // 0 to 18446744073709551615
var i uint = 18446744073709551615 // depends on the platform (32 or 64 bit)

// float (for general purpose)
var f float32 = 3.40282346638528859811704183484516925440e+38 // 1.18e-38 to 3.4e+38
var f float64 = 1.797693134862315708145274237317043567981e+308 // 2.23e-308 to 1.79e+308

// complex (for statistics or scientific calculations)
var c complex64 = 1 + 2i // 32 bit real and imaginary numbers
var c complex128 = 1 + 2i // 64 bit real and imaginary numbers

// alias

// byte is an alias of uint8
var b byte = 255 // 0 to 255

// rune is an alias of int32
var r rune = 2147483647 // -2147483648 to 2147483647

// string
var s string = "Hello World"

// boolean
var b bool = true // true or false

```
