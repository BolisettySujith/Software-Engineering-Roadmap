![Markdown Logo](assets/images/clean_code.jpg)
<small>Visual: Unsplash / 
Safar Safarov</small>
<br/><br/>

<div align="center">

# **Clean Code 🧼**
#### Learn how to write clean readable, understandable and scalable code that any developer can read, maintain and change easily.


<br>


[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/humamaboalraja) [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)


</div>

---

<br/>

## - [**Table of content**](#table-of-content)


- 1 . [Getting started](#getting-started)

- 2 . [Learning Checklist ✅](#learning-checklist-)

- 3 . [Naming Variables, Constant, Functions Classes & More](#naming-variables,-constant-functions,-classes-&-more)

- 4 . [Code Structure, Comments & Formatting](#code-structure,-comments-&-formatting)

- 5 . [Functions & Methods](#functions-and-methods)

- 6 . [Control Structures & Errors](#control-structures-&-errors-handling)

- 7 . [Objects, Classes & Data Containers / Structures](#Objects,-classes-&-data-containers-/-structures)
  - 1 . [Cohesion, Coupling and Interfaces](#cohesion-coupling-and-Interfaces)
  - 2 . [Polymorphism; Inheritance and Composition](#polymorphism-inheritance-and-composition)
  - 3 . [Classes, Data Structures, Encapsulation](#polymorphism-inheritance-and-composition)
- 8 . [SOLID principles](#solid-principles)
  - 1 . [Single-Responsibility-Principle (SRP)](#single-responsibility-principle-srp)
  - 2 . [Open-Closed Principle (OCP)](#open-closed-principle-OCP)
  - 3 . [Liskov Substitution Principle](#liskov-substitution-principle)
  - 4 . [Interface Segregation Principle](#interface-segregation-principle)
  - 5 . [Dependency Inversion Principle](#dependency-inversion-principle)
- 8 .  [Code smells](#code-smells)
    - 1 . [Bloaters](#bloaters)
      - 1 . [Long method](#long-method)
      - 2 . [Large class](#large-class)
      - 3 . [Primitive Obsession](#long-method)
      - 4 . [Long Parameter List](#long-parameter-list)
      - 5 . [Data Clumps](#data-clumps)
    - 2 . [Object-Orientation Abusers](#object-orientation-abusers)
      - 1 . [Switch Statements](#switch-statements)
      - 2 . [Temporary Field](#temporary-field)
      - 3 . [Refused Bequest](#refused-bequest)
      - 4 . [Alternative Classes with Different Interfaces](#alternative-classes-with-different-interfaces)
    - 3 . [Change Preventers](#change-preventers)
      - 1 . [Divergent Change](#divergent-change)
      - 2 . [Shotgun Surgery](#shotgun-surgery)
      - 3 . [Parallel Inheritance Hierarchies](#parallel-inheritance-hierarchiesy)
      - 4 . [Parallel Inheritance Hierarchies](#parallel-inheritance-hierarchiesy)
    - 4 . [Dispensables](#dispensables)
      - 1 . [Comments](#comments)
      - 2 . [Duplicate Code](#duplicate-code)
      - 3 . [Lazy Class](#lazy-class)
      - 4 . [Data Class](#data-class)
      - 5 . [Dead Code](#dead-code)
      - 6 . [Speculative Generality](#speculative-generality)
    - 5 . [Couplers](#couplers)
      - 1 . [Feature Envy](#feature-envy)
      - 2 . [Inappropriate Intimacy](#inappropriate-intimacy)
      - 3 . [Message Chains](#message-chains)
      - 4 . [Middle Man](#middle-man)
    - 6 . [Other smells](#incomplete-library-class)
      - 1 . [Incomplete Library Class](#incomplete-library-class)

- 9 . [Refactoring techniques](#refactoring-techniques)
  - 1 . 

  #### Further Learning Resource

  - 9 . [Articles 📰](#-articles-)
  - 10 . [Books 📚](#-books-)
  - 11 . [Courses 💻](#-courses-)

---

<br/>





# 1

## **Getting started**

<details open>
  <summary>Let's first get to know What Clean Code is | <b>Click to expand</b></summary>
</br>

  <div align="center">

  ![](https://media.giphy.com/media/FHEjBpiqMwSuA/giphy.gif)
  
  <br>

  ## **What's a Clean Code?**
  
  </div>

  Clean Code is a readable, understandable and scalable code that any developer other than the original author can read, maintain and change easily, a code that can be adapted to changing requirements and with understandability comes readability, changeability, extensibility and maintainability.

  ---

  and of the things that a Clean Code is certinaly not is not a code that (**just works**)
  and Martin Fowler describes clean code in one of the places:

  > Any fool can write code that a computer can understand. Good programmers write code that humans can understand. (<small>Martin Fowler</small>)

  <br>

---

<br> 

## **Characteristics of a Clean code:**

<br>

<details>
<summary>What are the Characteristics of a Clean code? | <b>Read more</b></summary>

#### 1. It should be elegant readable and meaningful
   -  Clean code should be pleasing to read. Reading it should make you smile the way a well-crafted music box or well-designed car would.

#### 2. Should avoid unintiuitive names, complex nesting, and big code blocks.
  
#### 3. Clean code is focused
   -  Each function, each class, each module exposes a single-minded attitude that remains entirely undistracted, and unpolluted, by the surrounding details.
#### 4. Clean code is taken care of.
   - Someone has taken the time to keep it simple and orderly. They have paid appropriate attention to details. They have cared.

#### 5. Runs all the tests
   - You know your code is dirty when only 95% of your tests passed. You know you’re screwed when you test coverage is 0%.

#### 6. Clean code is easier and cheaper to maintain!


#### 7. Contains no duplication and reduces cognitive load
   - Each time you have to make a change in a duplicate code, you have to remember to make the same change to every instance. This increases the cognitive load and slows down the progress, so Minimize the number of entities such as classes, methods, functions, and the like.

#### 8. Minimize the number of entities such as classes, methods, functions, and the like.
  - Less code is less stuff to keep in your head. Less code is less maintenance. Less code is fewer bugs. Code is liability, keep it short and simple.


#### 9. Should follow common best practices and patterns.

</details>

---

<br>

## **What's not a Clean code**

a code that grows more and more disorganized as it is changed over time, leading to slower and slower development,
and that's why it's crucial to master how to write Clean Code as a Software engineer.

---

<br>

## **What are we going to learn**:

<details>
<summary>A list of the things we're going to learn 🔥 | <b>Read more</b></summary>

<br>

- Modularity
- Single Responsibility Principle (SRP)
- Interfaces in general, characteristics of clean interfaces
- YAGNI (You Ain't Gonna Need It)
- Principle of least astonishment
- Good identifier names
- Good functions: size, arguments, return values
- Error handling and exceptions
- Appropriate use of data types
- How to recognize and write high-quality data structures, classes, and interfaces, leveraging the following concepts as appropriate:
  - Encapsulation and information hiding
  - Internal cohesion and external coupling
  - Inheritance and composition
  - Dependency inversion

- SOLID Principles
- how to practically write code that has high quality
- how to recognize potential quality issues (“bad smells”)
- how to improve code quality by refactoring
- knowledge and are able to use it in practice.


</details>

---

</details>
<br/>
<br/>
<br/>

# 2
## **Learning Checklist ✅**

<details open>
  <summary>A handy checklist to keep track of your progress, and know when you master your Clean code advancement path 💈. <b>Click to expand</b></summary>
</br>


---



</details>



# 8


## **Articles 📰**

___

Article           | Provider (Platform) | Used as reference|
--------------------- | -------------- | -------|
[Clean code](https://refactoring.guru/refactoring/what-is-refactoring) | refactoring.guru | Yes ❤️
___
<br/><br/><br/>

# 9
## **Books 📚**
One of the most straight to the point Books 🔥🕹📟
___

Book name           | Provider (Platform) | Duration| Skill level |  Cost
--------------------- | -------------- | -------- | ---------- | -----
[Refactoring: Improving the Design of Existing Code](https://www.amazon.com/Refactoring-Improving-Existing-Addison-wesley-Signature/dp/0134757599/) | Amazon | 448 pages | Beginner | Hardcover $44.46 |
[Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.de/-/en/Robert-Martin/dp/0132350882) | oreilly | 464 pages | Beginner | Paperback $32.46 |
___

<br/> 

# 10

## **Courses 💻**
----
The most popular courses that teach Clean Code. Yes for real 🔥🕹📟

Course name           | Provider (Platform) | Duration| Skill level | Course Cost | Used as refrence
--------------------- | -------------- | -------- | ---------- | ----- | -----
[Dive Into REFACTORING](https://refactoring.guru/refactoring/course) | refactoring.guru | -- | Beginner | $35.70 discount | Yes ❤️
[Clean Code](https://www.udemy.com/course/writing-clean-code/) | Udemy | 6.5 hours | Beginner | $14.29 discount | Yes ❤️

---

<br/><br/><br/>

# 11

<!-- Tables -->
## **Resources**
*[Resources to learn Clean Code from]()* 🐱
<br/>

---
<br/>


> Learn by watching/ doing
>
Title | Description
------------ | -------------
-- | --
---
