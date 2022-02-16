# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?

<!-- enter you answer in the space below -->

```encapsulation, inheritance, and polymorphism.

```

**2.** How would you access the `name` of the below object using the `property` variable?

```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey",
};
let property = "name";
```

<!-- enter you answer in the space below -->

```
staff["name"];
```

**3.** What is Encapsulation?

<!-- enter you answer in the space below -->

```object-oriented computer programming (OOP) languages, the notion of encapsulation (or OOP Encapsulation) refers to the bundling of data, along with the methods that operate on that data, into a single unit. Many programming languages use encapsulation frequently in the form of classes. A class is a program-code-template that allows developers to create an object that has both variables (data) and behaviors (functions or methods)

```

**4.** What does the S stand for in the `SOLID` principles?

<!-- enter you answer in the space below -->

```
S: The single-responsibility principle
O: The open-closed principle
L: The Liskov substitution principle
I: The interface segregation principle
D The dependency inversion principle

```

**5.** What the difference between a `class` and an instance of a `class`?

<!-- enter you answer in the space below -->

```
A class is a blueprint which you use to create objects. An object is an instance of a class - it's a concrete 'thing' that you made using a specific class. So, 'object' and 'instance' are the same thing, but the word 'instance' indicates the relationship of an object to its class.
```

**6.** What is a `Proxy` object?

<!-- enter you answer in the space below -->

```
Proxy object enables you to create a proxy for another object, which can intercept and redefine fundamental operations for that object.

```

**7.** What is the purpose of the `MVC` pattern?

<!-- enter you answer in the space below -->

```Model–view–controller (MVC) is a software design pattern commonly used for developing user interfaces that divide the related program logic into three interconnected elements. This is done to separate internal representations of information from the ways information is presented to and accepted from the user.

```

**8.** What is the job of the `Controller` in the `MVC` Pattern?

<!-- enter you answer in the space below -->

Controller: Controller act as a mediator between view and model. it is responsible to control the data transmission between the model and the view. It maps the user action into model updates. The controller layer is helpful to select the most appropriate view and delivers it to the user.

```

```

**9.** What is the job of the `Service` in `MVC`?

<!-- enter you answer in the space below -->

```the service layer is an application that mediates communication between a controller and repository layer. The service layer contains business logic. In particular, it contains validation logic.

```

**10.** What is the job of the `Model` in `MVC`?

<!-- enter you answer in the space below -->

```The model is the M in MVC. The data model represents the core information that your application is being used to access and manipulate. The model is the center of your application, the viewer and controller serve to connect the user with the data model in a friendly way.

```
