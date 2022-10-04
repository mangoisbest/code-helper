[Return Home](https://mangoisbest.github.io/code-helper/)

[Edit this page on Github](https://github.com/mangoisbest/code-helper/edit/main/src/pages/Kotlin/Kotlin.md)

Page Last Modifed: 4 Oct 2022 7:40pm AEST Time

# Welcome to the Koltin Programming Langauge!

Kotlin is a universal, cross-platform, statically typed programming language with type inference. Kotlin is designed to be fully compatible with Java and the JVM version of Kotlin's standard library is based on the Java class library, but type inference provides more concise syntax.

# Variables

Variables play an important role in Kotlin because they need to store and persist values ​​for each project.

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

Kotlin functions are declared using the ```fun``` keyword:
```kotlin
fun double(x: Int): Int {
    return 2 * x
}
```