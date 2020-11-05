# OOP (Object Oriented Programming)
In OOP everything is based on concept of object.

* **Object** is unit consists of Data(state) and Behaviour(methods/operation on data).

| Object  |
|---------|
|Data     |
|Behaviour|

* **Class** is a blueprint(template) for creating object. / **Object** an instance of a class.

* **Encapsulation** bundle the data and methods in a single unit (object).

* **Abstraction** hiding unnecessary details to reduce complexity.

* **Inheritance** (IS-A Relationship) one class (child) inherits all fields and methods of a parent class.

* **Polymorphism** (many forms) perform a single action in different ways.
  * **compile-time** polymorphism: by method overloading.
  * **runtime** polymorphism: by method overriding.

---

* **Coupling** the level of dependency between classes.
  * class **A** uses class **B** / **A** couple with **B**.
  * each modification in class **B** cause modification in class **A**.
  * you should reduce coupling as you can by **Abstraction**.

* **Dependency Injection** is a technique that removes the dependency from the code.
  * so, it can be easy to manage and test the application.
  * class shouldn't instantiate their dependencies.
    * constructor injection
    * setter injection
    * method injection
  * Spring is one of popular frameworks that provide **DI**.

* **Interface** is the contract between the class and the outside world.
  * used to build **loosely-coupled**, **extensible**, **testable** applications.
  * advantages:
    * test your classes in isolation. (unit testing)
    * extend your application. (with minimal impact)
    * swap implementation with another. (with minimal impact)

---

* **Composition** (strong HAS-A Relationship) owner object contains member objects as a part of its state.
  * strong because the member objects cannot exist without the owner object.
  * example: a building has rooms, a room belongs to a building.
  * if the building destroyed then all rooms will be destroyed with it.
  * but we can destroy a room and the building still exist.
![](https://github.com/shamy1st/oop/blob/main/composition.png)

* **Aggregation** (weak HAS-A Relationship) owner object contains member objects as a part of its state.
  * weak because the member objects can exist without the owner object.
  * example: a car has wheels / we can take off the wheels, and they'll still exist.
![](https://github.com/shamy1st/oop/blob/main/aggregation.png)

* **Association** the objects only "know" each others.
  * isn't "HAS-A" Relationship/ the weakest relationship / none of the object is part or member of another.
  * example: mother and her child.
![](https://github.com/shamy1st/oop/blob/main/association.png)

---

* **OOP Benefits**
  * Reduce Complexity (breaking down a large complex application into smaller objects)
  * Easier Maitenance
  * Code Reuse
  * Faster Development

---

* **Access Modifiers**

modifier  | class | package | subclass | global
----------|-------|---------|----------|-------
public    | Yes   | Yes     | Yes      | Yes
protected | Yes   | Yes     | Yes      | -
default   | Yes   | Yes     | -        | -
private   | Yes   | -       | -        | -

* **Abstract Class**

* **Abstract Method**

* **Final Class**

* **Final Method**

* **Multi-Inheritance**

* **Upcasting & Downcasting**

