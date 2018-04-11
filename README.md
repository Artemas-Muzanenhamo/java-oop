# Object-Oriented Programming in Java

## Classes and Objects

### Objects
* _Object_ - An Object is an instance of a class.
    * Those new to Object-Oriented Programming find it hard to tell the difference between classes and object. 
    * One way to think of classes is as `blueprints` or `templates`.
    * Objects are `items` that are manufactured from these `blueprints` or `templates`.
    * So in other words an `Object`(_item_) is an instance of a `Class`(_blueprint_).
* _Class Definition_ - Describes the `behaviour` and `attributes` of typical instances of that class. The attributes are used to store the state values of its instances.
    * A _Class Definition_ lays down the `attributes` that object of the class will possess, and the way all will `behave`;
    but each object may have its own slightly different settings of those attributes to make it unique.

### Classes

_Classes_ - Allow us to `abstract` away from the exact details of any particular object and, instead, look for `general characteristics` possessed by objects in the system being modelled.

## Creating an Object

```java
// An illustrastion of object creation
class ShipMain1 {
    public static void main(String[] args) {
        // Define a method variable to refer to a Ship object.
        Ship argo;
        
        // Construct a new Ship object.
        argo = new Ship();
    }
}
```
* The first is a _variable declaration_: `Ship argo`
* The various symbols that make it up are:
    * A `Class` name - `Ship`.
    * An `identifier` - `argo`.
    * A terminating semicolon - `;`;
* _Variable Declaration_ - Defines a variable, which is something that is always used to store some information. 
    * A variable defined inside a method is called a `method variable`.
    * A variable always has a name, and the one defined here is called `argo`.
    * The information that can be stored in a variable is determined by the variable's type, which is always immediately written before its name in its declaration.
    * So the type of the `argo` variable is `Ship`.
    * Some varibles can store an `item` of numerical data, while others store an object reference.