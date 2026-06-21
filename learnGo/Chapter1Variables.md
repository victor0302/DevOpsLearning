# Variables
## Learn Go
### Learning Goals
Understand the basic syntac of the Go Programming Language
Understand best practices for wriiting clean, efficient, and maintable Go code
Learn about the differences between Go and other popular programming languages
Master advanced Go concepts like concurrency, interfaces, and generics

## Derclaring a Variable
The var keyword is used to declare a variable.
create a new varaible, it defaults to 0
var mySkillIssues int
mySkillIssues = 42

## Basic Variables
Some of Go's most common variables types are 
int: a signed integer
bool: a bolean value, either true or false
string: a sequence of characters
float64: a floating-point number
byte: exactly what is sounds like: 8 bits of data

## Short Variable Declaration
mySkillIssues := 42
The walrus operator, :=, declares a new variable and assigns a value to it one line. It's type inefernce, because GO can infer that the var is an int because of 42.

## Why Go?

## Comments
// This a single line comment
/*Multi line comment

*/

## The Compliatation Process
We need to convert our high-level (Go) code into machine leanguage, which is really just a set of intructions that some specific hardware can understand it.

The Go complier's job is to take Go code and produce machine code, an .exe file on Windows or a standard executable on Mac/Linux

1. package main lets the Go compiler know that we want this code to compile and run as a standalone program, as opposed to being a library that's imported by other programs.
2. import "fmt" import the fmt (formatting) package from the standard library. It allows us to use fmt.Println to print to the console
3. func main() defines the main function, the entry point for a Go program.

Two Kinds of Errors
Generally speaking, there are two kinds of errors in programming:
1. Compilation errors: Occur when code is complied. It's generally better to have compliation errors because they'll never accidently make it into production.
2. Runtime erros. Occurs when a program is running.

## Fast and Compiled
Generally speaking, languages that compile directly to machine code produce programs that are faster than interpreted programs.

Go is one of the fastest programming languages

Go doesnt run quite as fast as its compiled Rust,Zig, and C.

##