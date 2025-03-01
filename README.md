# Simple Programming
Simple Programming is a programming paradigm that states,

**To make the most maintainable software: All input processors form a simple curve, for any base success case.** 

Here is a video explaining the Simple Programming Paradigm - https://youtu.be/rcns0WBB9Ww


## Glossary ##

**Base Success Case** - A "happy path" that runs the majority of a function/method's logic.

---

**Data** - An object whose main purpose is to be an information holder.

Examples:
* A String
* A List
* A HashMap
* A JSON object

---

**Non-Simple Closed Curve** - A non-simple curve that starts and ends at the same processor.

Examples:
* A -> B -> C -> B -> A
* A -> B -> C -> D -> B-> A

---

**Non-Simple Curve** - The usage of processors can only be placed on a [curve that croses itself](https://mathworld.wolfram.com/SimpleCurve.html).

Examples:
* A -> B -> C -> B
* A -> B -> C -> B -> D -> E

---

**Processor** - An object whose main purpose is to have its functions/methods be called.

Examples:
* A service that is @Autorwired, injected, or constructor injected
* A lambda passed into a function

---

**Simple Closed Curve** - A simple curve that starts and ends at the same processor.

Examples:
* A
* A -> B -> A

---

**Simple Curve** - The usage of processors can be placed on a [curve that does not cross itself](https://mathworld.wolfram.com/SimpleCurve.html).

Examples:
* A -> B
* A -> B -> C -> D -> E
