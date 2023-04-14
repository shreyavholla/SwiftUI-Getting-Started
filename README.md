# SwiftUI-Getting-Started
SwiftUI : Getting Started !!!!

## What is Declarative Programing ?
Declarative programming focuses on the end result, while imperative programming focuses on how to get there. 
For example, when you jump in a taxi, you declare to the driver where you want to go. You don't tell him how to get there by providing turn-by-turn directions.

## Views in SwiftUI
----------------------
### a) implementing a view protocol : 
when you create a view, you start by creating a struct that conforms to the view protocol.
the view protocol implements the body property.
The body contains the code on how you want the view to behave and what it will look like.
The body can return only one view.
Multiple views can be wrapped inside a container 
eg. 
``` struct ContentView: View {
  var body: some View {
    Text("Hello World")
    Color.blue
  }
}
```

##### NOTE: keyword `some` :
- introduced in swift 5.1 
- tells the compiler what the underlying type is without exposing the type to the outside world

### b) SwiftUI Containers (STACKS):
      1. HSTACK : ogranizes views in horizontal direction
      2. VSTACK : organizes views in vertical direction
      3. ZSTACK : organizes views on top of each other from which they are declared in scope
  
### c) SWIFTUI Container Layouts :


#### SOME USEFUL KEYS: 
- `Command + 5 ` : brings up the issue navigator
- `Command + option + [ / ]` : moves lines up and down resp
-  Adding your custom hotkey in xcode : 
    - hit `Command + , ` for prefrences
    - go to Key Bindings tab 
    - eg. type delete line in the filter text box - and add your custom hotkey : for instance `Command + CTRL + k`
- `Command + option + P` : to resume preview

