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
  * **compile-time polymorphism**: by method overloading.
  * **runtime polymorphism**: by method overriding.

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
---

* **Composition** (strong HAS-A Relationship) owner object contains member objects as a part of its state. 

* **Aggregation** (weak HAS-A Relationship) owner object contains member objects as a part of its state.

* **Association** the objects only "know" each others.

---

* **Interface** 

