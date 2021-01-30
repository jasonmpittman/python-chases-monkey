---
title: Python Chases Monkey
subtitle: An Introduction to Python Programming  
author: 
    - Jason M. Pittman
documentclass: scrartcl
rights: © 2021 Jason M. Pittman, CC BY-SA 4.0
---

# Chapter 3
## Python Wakes Up

## Introduction
[done]()
Okay, maybe creating pythons and monkeys wasn't the most exciting programming experience you can imagine. That's because the python and monkey didn't do anything. They simply existed. I reckon a philospher would find existence worthy of course-level inquirty but we programmers need action, we need movement. Well, we ought to be interested in existence too but just not in the same context as philosphy.

Anyway, in view of the last chapter largely centering around nouns, it is a natural segue to take a deep descent into verbs now. With this, we get the action we crave and we get our python and monkey to do something. If we want to refresh or more adequately prepare, there is the overview call-ahead in the **methods** section of chapter 2. 

We're going to expand our knowledge concerning methods in this chapter. Not only are we going to explore different types of methods but we can going to juxtapose methods and a very similar construct called **functions**. Further, we're going to emphasize two important aspects of object-oriented design as a natural byproduct of how we model and create behaviors for our animals. 

In the meantime, imagine we're back in the jungle scene. The wind is still gently blowing the tree canpoy back and forth. Where our python was once coiled in slumber, it now stirs and begins to rouse. The monkey takes notice of the slight movement...

## Learning Objectives
1. Explain how functions and methods are used to encapsulate logic
2. Describe components needed to define functions and methods
3. Implement functions and methods according to object oriented design principles

### Functions
A good place to begin is with a definition. We can take a a **function** to be a discrete unit of work. Technically speaking, there are three types of functions which we refer to as *built-in*, *user-defined*, and *lamba*. We're going to focus primarily on the user-defined type although we constantly use the built-in. Lamba functions are an advanced topic and best left for a later discussion. 

Let's give our python the ability to move.

```
Example 1
(1) def slither(newX, newY):
(2)     x += newX
(3)     y += newY 
(4)
```
We also learn a new operation here, `+=`. We read this as, *increase the value of the left variable by the value on the right*. 

#### Modifiers


#### Pure


### Methods
Let's look at an example before we dive into technical details. In comparing **Example 1** above and **Example 2** below, what would can we assert as differences?

```
Example 2
(1) def slither(self, newX, newY):
(2)     x += newX
(3)     y += newY 
(4)
```
That's right, the only visible difference is the appearance of the `self` parameter in **Example 2**. Otherwise, the two code blocks are identical. However, if we zoom at a little, we can see another difference which not only explains why we have **self** but also reveals the true difference between a **function** and a **method**.

```
Example:
(1) class Python(object):
(2)     def slither(self, newX, newY):
(2)         x += newX
(3)         y += newY 
(4)
```
Let's introduce a definition now to cement the difference. Whereas a **function** is a discrete unit of work, a **method** is a function that belongs to a **class**. I think it is fair to articulate that all methods are functions but not all functions are methods.

By now we should be wondering why we need *methods* if we have *functions* and vice-versa. Put simply, not all `Python` programs are object-oriented. Since **functions** are not associated with **classes**, we use those when we want to develop a discrete block of task-scope work. On the flip, we define **methods** when we need the same programming construct within the context of a **class**.

That's not terribly complicated. However, there are some implicit differences we ought to spend the rest of our time investigating. Let's start with the `self` parameter and the move onto what we can do differently with a **method** in contrast to a **function**. 

I should point out: I argue that leveraging object-oriented design principles leads to superior software in all but the most rudimentary problems. Further, if we know how to design using OOP and understand how **methods** operate, we can always opt to have a simple procedural program using **functions** but we cannot always do the opposite.

### Self

### Init and Constructors

### Overloads

### Polymorphism

## Excecises

## Questions