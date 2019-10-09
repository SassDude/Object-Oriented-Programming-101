### Method
The behaviours of a class and tells what a method can do. They are defined within a class, and so objects of that class type are able to call upon these methods to perform the required task. 

* Public - any object that has a reference can call it or instance of the object
* Private - only the object can call it.
* Protected - only the object and its own children class can call it.

For example, the class human would need to define a method called `AssignFamily()`, which would contain code that would assign the human to a particular class.

### Interface
Interfaces allow the computer to enforce certain properties on an object normally a class. They are a description of the actions that an object can do. This can help if you have multiple classes within programs will need to be able to do or have the same thing.

An example of this would be we have Phone, Light and a  Router class, all of these are going to need to know how to turn on so we need a turn_on() method.

### Class
A blueprint about the capability of an object that can create many instances of the same kind of object. This includes locals functions as wells as local data. They can be useful as they allow multiple different objects to be created, all of which share the same requirements.

For example a class would be a Human which would contain properties for age, height, gender and there would also be a method called `GetAge()`.

### Objects
Objects are instances of a data structure defined by a class and a working entity of the class.

An example of an object would be `Human _pat = new Human("pat");` This would create a new object called _pat, which is a type of Human.

### Instance
An Instance variable belonging to an object as each object is an instance of a class and each object has its own instance variables.

### Field
Fields are attributes that store a data value. 
* Static - native to the class itself and hence is shared amongst all instances of that class.
* Instance - every object created and only changed depending on each object

