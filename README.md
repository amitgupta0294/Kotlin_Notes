# Kotlin_Notes

## What is Kotlin ?

   Kotlin is a statically typed general-purpose programming language developed by Jetbrains.
   
  ```
  // hello world program in kotlin
   
   fun main(args : Array<String>) {
      println("Hello Kotlin")
   } 
   ```
   
## How to run a program in Kotlin ?

   - Compile a kotlin program :- kotlinc Hello.kt 
   - Run a program in Kotlin :- kotlinc HelloKt
   
## Data types in Kotlin 

   - Integer Data Type : byte, short, int, long
   - Floating Data Type : float, double
   - Boolean Data Type : boolean (true / false)
   - Character Data Type : char
   
## Variables in Kotlin 

   - Mutable Variables : var
   - Immutable Variables : val
   
   (**NOTE** : _Immutable variable is not a constant because it can be initialized with the value of a variable. It means the         value of immutable variable doesn’t need to be known at compile-time, and if it is declared inside a construct that is         called repeatedly, it can take on a different value on each function call._)
   
