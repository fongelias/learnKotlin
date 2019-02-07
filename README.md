# learnKotlin
repo for learning kotlin and taking notes

## Installation
With homebrew, run this command: `brew update && brew install kotlin`

## Creating/Compiling files
### Compiled files
Kotlin files are suffixed with `.kt`

Compile class files with the following command: `kotlinc [filename.kt]`
Compile jar files (which can be used as libraries for other kotlin applications) like so `kotlinc [filename.kt] -d [jarName.jar]`
And compile them as runnable jars: `kotlinc [filename.kt] -include-runtime -d [jarName.jar]`

Run the file as a jar with `java -jar [jarName.jar]`
Run the file as a binary `kotlin -classpath [jarName.jar] [mainClassName]`

### Scripts
Kotlin scripts are suffixed with `.kts`

Run scripts like so `kotlinc -script [script.kts]`

## Common commands
to start the repl: `kotlinc`

## Syntax
`fun` is used to create functions

`val` is used to define read-only local variables

`var` is used to define mutable variables

`$[varName]` or `${[evaluated expression]}` character used to insert values into strings

`?` marks references as nullable

`is` checks if an expression is an instance of a type

`when ([var]) {[match] -> [expression]}` is used for case expressions

`when {[boolean] -> [expression]}` is used for case expressions

`[int]...[int]` is used to represent a range of values

`for ([var] in [range/collection] step [int]) {}` is used to iterate over a range

`it` refers to the default variable name in a lambda

`listof([val], [val])` creates a list

`mapof([val] to [val], [val] to [val])` creates a map

`object [name] {}` creates a singleton

`value?.let {}` executes the `let` block if `value` is not null

`with([obj]) {}` allows you to call an object's functions in the block


## Trivia
statements can be executed via ternary


