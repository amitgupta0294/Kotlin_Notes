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
   
   (**NOTE** : _Immutable variable is not a constant because it can be initialized with the value of a variable. It means the         value of immutable variable doesn’t need to be known at compile-time, and if it is declared inside a construct that           is called repeatedly, it can take on a different value on each function call._)
   
   ### Scope of a variable 
   
   Scope of a variable remain inside the block it is declared. You cannot access a variable outside the block it is declared.
   For nested declaration the variable changes as per the declaration in the block
   
   ```
   {
      var a = 5
      ...
      ...
      
      {
      
         var a = 10        // a will become 10 
         ...
      }
      
      // a will again become 5 here
   }
   ```
   
## Kotlin Operators

   https://www.geeksforgeeks.org/kotlin-operators
   
## Kotlin Standard I/O   

   ###### output
   
   print("hello")       // prints "hello" in same line
   println("hello")     // prints "hello" in next line
   
   
   ###### input
   
   readLine()             // this function takes input from keyboard as string
   Scanner class          // this is used if we want to take input other than string 
   
   Usage of readLine
   
   ```
   var a = readline()!!    // !! is used to ensure the input is not empty
   ```
   
   Usage of Scanner: 
   
   ```
   var scanner = Scanner(System.`in`)
   var value = scanner.nextInt()
   ```
   
   
   
   
   
   
   
   
