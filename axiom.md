---
layout: default
title: Axiom
nav_order: 1
description: "The home page for a compiler for my language: Axiom"
---

# *Axiom : A programming language based on C with classes and objects, but not as bloated as C++.*

**Authors:** Joel Mathew (Nightshade).  
**Date:** December 2025

---

## **Abstract**

Axiom is a modern, object-oriented systems language built on the foundations of C, designed to be powerful without the historical bloat of C++.  
It offers clear semantics, predictable performance, and a refined approach to low-level programming.

## **Core Design Principles**

1. **Deterministic, explicit behavior**  
   No hidden allocations, no magical type conversions, no implicit performance traps.

2. **Objects & Classes without Bloat**  
   Axiom features classes, methods, inheritance, and interfaces — but avoids deep inheritance chains, implicit casts, template explosion, and macro-driven magic.

3. **Modern Speech, Classic Control**  
   You get modern tooling and abstractions while keeping full control over memory, layout, and performance.

4. **Static, Strong Typing**  
   The type system is compile-time enforced and predictable.

5. **Low-level power with higher-level expressiveness**  
   Ideal for graphics, game engines, scientific computing, and embedded systems.


## Demonstration:

### "Hello, World!" in C:

```c
#include <stdio.h>

int main(){

  printf("Hello, World!\n");
  
  return 0;
}
```

### "Hello, World!" in Axiom:

```c
#include <axiom.h>
 int main(){

  writef("Hello, World!\n");

  return 0;
 }
```

<style>
  .link-container {
    display: flex;
    justify-content: flex-end; /* aligns content to the right */
    padding: 20px;             /* optional spacing */
    background-color: #333;    /* dark background */
  }

  .right-link {
    color: white;               /* makes the link white */
    text-decoration: none;      /* removes underline */
  }

  /* optional hover effect */
  .right-link:hover {
    text-decoration: underline;
  }
</style>

<div class="link-container">
  <a href="axiom-doc.html" class="right-link">Documentation for Axiom</a>
</div>

<br>

<div class="link-container">
  <a href="everfall.html" class="right-link">Next : Everfall</a>
</div>


