---
layout: page
title: The Java Programming Language, 4th Edition
permalink: /tjpl4e/
---

<small>by Ken Arnold, James Gosling and David Holmes (2005)</small>

**Table of Contents**

- [Source Code](#source-code)
- [Classes and Objects](#classes-and-objects)
- [Exercises](#exercises)

## Source Code

[tjpl4e](https://github.com/ADHwang/book-src/blob/master/tjpl4e)

## Classes and Objects

In Java, programmers must explicitly create an object. For example, in C++, `Body mercury;` will create an object with default values, but in Java, it is just a declaration; `mercury` is a reference to an object of type `Body`.

## Exercises

> Exercise 2.1: Write a simple `Vehicle` class that has fields for (at least) current speed, current direction in degrees, and owner name.

```java
class Vehicle {
    public float speed;
    public int degree;
    public String owner;
}
```

> Exercise 2.2: Write a `LinkedList` class that has a field of type `Object` and a reference to the next `LinkedList` element in the list.

```java
class LinkedList {
    public Object obj;
    public LinkedList next;
}
```