

class: center, middle
# Design Patterns in React

Josh Martin

https://cjoshmartin.com

contact@cjoshmartin.com

---

# Who am I? 

*   Computer Engineering Junior (specializing in Software Design and Embedded Systems) 
*   Minoring Mathematics and Computer Science
*   Spend most of my time programming or dancing

---

# Introduction (1/3)

#### What is a Design Pattern?

A **Design Pattern** is a general repeatable solution to a commonly occurring problem in software design.

A **Anti-Pattern** is a common response to a recurring problem that is usually ineffective and risks being highly counterproductive


---

# Introduction (2/3)

#### Types of Design Patterns

1. Creational

2. Structural

3. Behavioral
---
# Introduction (3/3)

#### History of React(1/2)

.going-deeper[
#### Sources

* [Tom Occhino and Jordan Walke: JS Apps at Facebook](https://www.youtube.com/watch?v=GW0rj4sNH2w)

* [Facebook Engineer | Creator of React.js & Reason](https://www.reactiflux.com/transcripts/jordan-walke/)
* [React.js Conf 2015 Keynote](https://youtu.be/KVZ-P-ZI6W4)
]
* Jordan Walke is credited with creating React.JS 
    - While working at facebook

* React was created inside Facebook's Ads Organization
    - predecessor being [XHP](https://www.facebook.com/notes/facebook-engineering/xhp-a-new-way-to-write-php/294003943919/) (PHP framework)

* Created to improve speed of writing code, managing a huge codebase, and prevent cross site scripting

---
# Introduction (3/3)

#### History of React(2/2)

* React's state is immuablty so that somewhere deep in that app, the views change case a conflict in the state.(a Cascading Update) (provide example)

* React started out being used for the like and comment section of Facebook

* React became open source, out of a need to decouple itself from the Facebook site and be able to let instagram use the framework as well. (finished at JS Conf 2013)
---
# Coupling
---
# what an Object is in Javascript
---
# Class Keyword
   
* Classes have no since of system composition or type


https://www.youtube.com/watch?v=Tllw4EPhLiQ
---
## basic example of a class
<iframe width="100%" height="300" src="//jsfiddle.net/cjoshmartin/9LvjLL31/embedded/js,result/" allowpaymentrequest allowfullscreen="allowfullscreen" frameborder="0"></iframe>
---
## Functions
<iframe width="100%" height="400" src="//jsfiddle.net/cjoshmartin/8ehkrrgn/embedded/js,result/" allowpaymentrequest allowfullscreen="allowfullscreen" frameborder="0"></iframe>
---
## Inheritance
<iframe width="100%" height="500" src="//jsfiddle.net/cjoshmartin/hak37x3b/1/embedded/js,result/" allowpaymentrequest allowfullscreen="allowfullscreen" frameborder="0"></iframe>
---
# Inheritance
---
# Composition
---
# Compistion VS. Inhertance     
---
## Surprise!!
* Classes are just abstractions on top of the **Prototype Inheritance Model**

<iframe width="100%" height="400" src="//jsfiddle.net/cjoshmartin/7j8nxod1/embedded/js,result/" allowpaymentrequest allowfullscreen="allowfullscreen" frameborder="0">


https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain
---
# what is a Prototype?

* Creational Design Pattern
* Prototupes is how Javscript achieves inheritance
---
# Immutability in Javascript

---
# State
---
# Obserables
---
# Just so you know...
---
# if you didnt know
---
# React is a MVC framework

- Comparable to the Observer Pattern
- (define what MVC is!)
---
# Factories
---
 ![full_size_img](img/design-patterns-bureaucracy.png)
---
# End