# Classes

`Classes` are models or blueprints the `objects` we will use in our programs. By convention, `Classes` start with uppercase, for example, `Car.java`.  
Classes should have `access modifiers`, such as the `public` keyword, that allows this class to be access form outside without restrictions. Each class have `fields, members or properties`, which are all ways of referring to the internal characteristics of that class, they tend to be `private` unless it is necessary otherwise.  

Classes are meant to be `instantiated`, meaning creating an ocurrence of an object that follows the pattern of the class, with the following syntax pattern:
```java
ClassName className = new ClassName();
```

### Changing properties of classes
It is preferred to do it throgh `getters` and `setters`, in order to encapsulate and be able to apply validation or any kind of business logic as a side effect.