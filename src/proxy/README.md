# Proxy Pattern

**Proxy** is a structural pattern. A proxy is an objet that controls access to another object, this another object is known as **Subject**. Both the Proxy and the Subject has same **interface** which allows us to easily swap one with the other.

Another name for this pattern is **Surrogate**.

## Motivation

This pattern is particularly very useful when you want to intercept or modify few or all the operations supposed to be executed by the **subject**. THe following are the situations where **Proxy Pattern** fits very well,

- Data Validation
- Caching
- Lazy Loading
- Logging
- Security

## Implementation Techniques

This pattern can be implemented using the following:

- Object Composition
- Object Augmentation aka Monkey Patching

## Notes

The various different types of a **Proxy** are:

- Value Proxy
- Property Proxy
- Protection Proxy
- Virtual Proxy
