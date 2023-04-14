# SwiftUI-Getting-Started
SwiftUI : Getting Started !!!!

## What is Declarative Programing ?
Declarative programming focuses on the end result, while imperative programming focuses on how to get there. 
For example, when you jump in a taxi, you declare to the driver where you want to go. You don't tell him how to get there by providing turn-by-turn directions.

## Views in SwiftUI
----------------------
a) implementing a view protocol : 
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
}```
##### NOTE: keyword `some` :
- introduced in swift 5.1 
- tells the compiler what the underlying type is without exposing the type to the outside world
