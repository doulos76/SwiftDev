# The Basics

```Swift
//: # The Basics

//: ## Constants and Variables

//: ### Declaring Constants and Variables

let maximumNumberOfLoginAttempts = 10
var currentLoginAttempt = 0

var x = 0.0, y = 0.0, z = 0.0

//: ### Type Annotations

var welcomeMessage: String

var red, green, blue: Double

//: ### naming Constants and Variables

let π = 3.14159
let 你好 = "你好世界"
let 🐶🐮 = "dogcow"

var friendlyWelcome = "Hello"
friendlyWelcome = "Bonjour!"
// friendlyWelcom is now "Bonjour!"

//let languageName = "Swift"
//languageName = "Swift++"
// TheBasics.playground:30:1: note: change 'let' to 'var' to make it mutable

//: ### Printing Constants and Variables

print(friendlyWelcome)
// Prints "Bonjour!"

print("The current value of friendlyWelcome is \(friendlyWelcome)")
// Prints "The current value of friendlyWelcome is Bonjour!"


//: ### Comments

// This is a comments

/* This is also a comment
 but is written over multiple lines. */

/* This is the start of the first multiline comment.
 /* This is the second, nested multiline comment. */
This is the end of the first multiline comment. */

//: ### Semicolons

let cat = "🐱"; print(cat)
// Prints "🐱"

//: ### Integers

//: #### Integer Bounds

let minValue = UInt8.min  // -> 0
let maxValue = UInt8.max  // -> 255

//: #### Int
//: * On a 32-bit platform, `Int` is the same size as `Int32`
//: * On a 64-bit platform, `Int` is the same size as `Int64`

//: ### Floating-Point Numbers

//: * `Double` represents a 64-bit floating-point number
//: * `Float` represents a 32-bit floating-point number
```