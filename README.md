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
