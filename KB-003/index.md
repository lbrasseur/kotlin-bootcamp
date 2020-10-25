# Kotlin Bootcamp
## KB-003: Classes and Objects
This module how classes and objects are implemented.

## Prerequisites
* [KB-000](../KB-000/index.md) Environment Setup
* [KB-001](../KB-001/index.md) Basics

## Classes
The official documentation about classes can be found [here](https://kotlinlang.org/docs/reference/classes.html).

Kotlin allows creating *Data Classes*, which are useful for classes that are intended just for holding data. Common logic used on this scenario, like comparison and hashing, is automatically generated. You can read about them [here](https://kotlinlang.org/docs/reference/data-classes.html).

Kotlin expands the concept of enumeration with *Sealed Classes*. They can restrict the inheritance. You can read about them [here](https://kotlinlang.org/docs/reference/sealed-classes.html). On the other hand, documentation about ennumerations can be found [here](https://kotlinlang.org/docs/reference/enum-classes.html).  

You can nest classes inside other classes. You can read about the rules about class nesting [here](https://kotlinlang.org/docs/reference/nested-classes.html).

If class name is too long (like in many Java libraries!), you can rename it by using [Type Aliases](https://kotlinlang.org/docs/reference/type-aliases.html).

At the moment of writing, there is an alpha development of [Inline Classes](https://kotlinlang.org/docs/reference/inline-classes.html).

## Properties and Fields
The official documentation about properties and fields can be found [here](https://kotlinlang.org/docs/reference/properties.html).

## Interfaces 
The official documentation about interfaces can be found [here](https://kotlinlang.org/docs/reference/interfaces.html).

Just like Java, Kotlin uses *Single Abstract Method (SAM)* convention. You can read about it [here](https://kotlinlang.org/docs/reference/fun-interfaces.html).

## Visibility Modifiers 
The official documentation about visibility modifiers can be found [here](https://kotlinlang.org/docs/reference/visibility-modifiers.html).

## Extensions
The official documentation about extensions can be found [here](https://kotlinlang.org/docs/reference/extensions.html).

C# has a [similar concept](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/extension-methods). There is even a programming language completely based on extensions concept: [XTend](https://www.eclipse.org/xtend/). 

## Generics
The official documentation about generics can be found [here](https://kotlinlang.org/docs/reference/generics.html).

## Object Expressions and Declarations
Kotlin uses the general concept of object to implement/replace some concepts like:
* Static methods/fields
* Singletons
* Anonymous inner classes  

The official documentation about object expressions and declarations can be found [here](https://kotlinlang.org/docs/reference/object-declarations.html).

## Delegation
Kotlin provides language support for implementing the [Delegation Pattern](https://en.wikipedia.org/wiki/Delegation_pattern). You can read about it [here](https://kotlinlang.org/docs/reference/delegation.html). Properties can be also [delegated](https://kotlinlang.org/docs/reference/delegated-properties.html).
