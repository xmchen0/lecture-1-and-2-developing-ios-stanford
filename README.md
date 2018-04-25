# lecture-1-and-2-developing-ios-stanford

# Lecture 1: Introduction to iOS 11, Xcode 9 and Swift 4
In this lecture we were introduced to Xcode and Swift programming language and learned what's in iOS. The goal of the lecture was to bring our attention to know what's there rather than completely and fully master the guidelines. We also put theory into practice with a demo of the app called "Concentration" which we will building over the next few lessons. 

# Key takeouts
+ Action creates method and outlet creates instance variables or properties
+ Access iOS documentations from our code by pressing down on 'option' button on the keyboard and use mouse to click on the code
+ We observed how debugging is conducted in Xcode with the use of print statements
+ API (Application Programming Interface) is a function or procedure that lists methods and variables in a class
+ Delcare arrays using variable (var) or constant (let) and create arrays in code using an array literal that automatically infers the array's Element type (i.e. Int or String or Class) Learn more: [Apple Swift Standard Library](https://developer.apple.com/documentation/swift/array)
+ The concept of optionals involves two possibilities: either there is a value and you can unwrap the optional to access the value, or there isn't a value at all. Learn more: [Apple Swift Standard Library](https://developer.apple.com/documentation/swift/optional) and [Tutorials Point](https://www.tutorialspoint.com/swift/swift_optionals.htm)


# Lecture 2: MVC (Model View Controller)
MVC is short for Model, View, and Controller. MVC makes our Concentration game smarter by way of organising our code, ensuring each section of the code has a different purpose and managing the communication. The idea is that MVC is divided into 3 "camps": 
1. Model - What your app is, not how it appears
2. Controller - How your model is presented 
3. View - Your controller's minions

# Key takeouts
+ MVC Communication: Controller can communicate to both Model and View. Model cannot communicate back to Controller without notification and KVO (Key-Value Observing). View can communicate back to Controller via dataSource and delegate. Model and View cannot communicate at all.
Example (below): MVC diagram
<a href="https://ibb.co/m3Qzbx"><img src="https://preview.ibb.co/n59gpH/mvc_kathy_chen.jpg" alt="mvc kathy chen" border="0" /></a>

+ Struct vs. Class: struct is a value type, class is a reference type and has inheritance capabilties. Learn more: [Apple Guides and Sample Code](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/ClassesAndStructures.html)
+ Dictionary<KeyType, ValueType>. Dictionary stores each value with an unique key which acts as an identifier for that value. You use a dictionary when you need to look up values based on their idenfitier. Learn more: [Apple Guides and Sample Code](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/CollectionTypes.html#//apple_ref/doc/uid/TP40014097-CH8-ID113)

# Acknowledgement
Paul Hegarty - Standford University - iTunes
+ [Developing iOS 11 Apps with Swift](https://itunes.apple.com/us/course/developing-ios-11-apps-with-swift/id1309275316)
