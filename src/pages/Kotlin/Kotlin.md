[Return Home](https://mangoisbest.github.io/code-helper/)

[Edit this page on Github](https://github.com/mangoisbest/code-helper/edit/main/src/pages/Kotlin/Kotlin.md)

Page Last Modifed: 4 Oct 2022 8:00pm AEST Time

# Welcome to the Koltin Programming Langauge!

Kotlin is a general-purpose, cross-platform, statically typed programming language with type inference. Kotlin is intended to be fully compatible with Java, and the JVM version of Kotlin's standard library is based on the Java Class Library, but type inference allows for more concise syntax.

# Variables

Variables are important in Kotlin because they must store and persist values for each project.

### Syntax

```kotlin
var variableName = value
val variableName = value
```

### Example 

```kotlin
var name = "John"
val birthyear = 1975

println(name)          // Print the value of name
println(birthyear)     // Print the value of birthyear
```

# Functions

Functions in Kotlin are frequently used by developers and are critical for your projects to run specific bits of code and be stable once declared. The "'fun" keyword is used to declare Kotlin functions:
```kotlin
fun double(x: Int): Int {
    return 2 * x
}
```