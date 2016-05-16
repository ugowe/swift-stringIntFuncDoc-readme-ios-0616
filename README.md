# String, their functions + Documentation

![Audrey](http://a4.files.biography.com/image/upload/c_fit,cs_srgb,dpr_1.0,q_80,w_620/MTE1ODA0OTcxNjU3NzU4MjIx.jpg)  
> Nothing is impossible, the word itself says 'I'm possible'!



## Learning Objectives - The student should be able to..

* Use Apple's documentation.
* Bring up Apple's documentation from the Playground file.
* Understand how to produce the following:

```swift
let nameCapitalized = name.uppercaseString
let fullName = name + " Hepburn"
```




## What the student can do at this point 

* Create functions with one/two arguments
* Create functions with return values (NOT tuples.... yet)
* Create variables and constants
* Knows how to use the print function
* Knows of the types String and Int


## Outline / Notes

*  Have the student create a `String` in a playground file.

```swift
let name: String = "Audrey"
```

* They know how to work with functions now. Have them type out the `name` variable followed by a `.` where they will be presented with the available instance methods/properties they can call on this `String` type. Show a screenshot of this. Explain that any of these are available to be used on an instance of any `String` type. This is Xcode knowing letting you know what's available to you. This might be the first time they see the word instance, which will be explained in more detail in a future readme.  
**[NOTES]** I'm unsure how best to go about this. This will be a lot of **firsts** being introduced here. They will have now gone through a few readme's and playground labs on functions. Can we transition nicely into this readme which explains how there are functions already made for us that we can use, where each type has their own set of functions we can use? Something like that?
* We might need to go into more detail than I think here. They will understand what a `String` type is, as well as an `Int` but this will be the first time they will be using an instance of something and calling functions on this instance.
* Command + Shift + 0 will bring up the Documentation where they can do some digging of their own (show screenshots of this).
* Also, if they option click the `name` variable, they are presented with a pop up window where they can then click `String` which brings up the documentation for them.
* Do we first challenge the student to google "how to uppercase a string in Swift" and see if they can just make it happen first before they read on?

```swift
let nameCapitalized = name.uppercaseString

print(nameCapitalized)
// prints "AUDREY"
```
* **Willing to discuss** : Do we show them the following (it would be useful to them):

```swift
let fullName = name + " Hepburn"

print(fullName)
// prints "Audrey Hepburn"
```

* I'm reluctant to show them any functions for `Int` as the following unit will introduce the various math operations they can perform. 



<a href='https://learn.co/lessons/Documentation' data-visibility='hidden'>View this lesson on Learn.co</a>
