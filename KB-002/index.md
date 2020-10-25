# Kotlin Bootcamp
## KB-002: Kotlin for Java Developers
This module is intended for Java developers. It compares features in order to make easier to learn new concepts.

## Prerequisites
* [KB-000](../KB-000/index.md) Environment Setup
* [KB-001](../KB-001/index.md) Basics

# Language comparison
You can get a list of differences [here](https://kotlinlang.org/docs/reference/comparison-to-java.html).

# Interop
You can access [Java binaries from Kotlin](https://kotlinlang.org/docs/reference/java-interop.html) and [vice-versa](https://kotlinlang.org/docs/reference/java-to-kotlin-interop.html).

## Common pitfalls
* Kotlin's `Iterable` methods like `map` and `filter` creates a colleciton copy. If you want a pull approach (like Streams or Guave), you need conveting the `Iterable` to a `Sequence`by calling  `asSequence()`.
  * [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/)
  * [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/)

# Extras
* Kotlin for Java Developers at [Coursera](https://www.coursera.org/learn/kotlin-for-java-developers).
* Kotlin for Java Developers at [Udemy](https://www.udemy.com/course/kotlin-for-java-developers).
* Kotlin for Java Developers at [Android](https://developer.android.com/courses/pathways/kotlin-for-java).
