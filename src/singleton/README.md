# Singletom Pattern

This particular pattern is ensuring that a class has only one instance (an instance is a unique copy of a class) and via the Singleton we are provided a global point to accessing the instance.

## Motivation

When designing a system few components needs to have only one sharable instance where you want to prevent anyone from creating multiple copies of the component. For example the components like:

- A database connection
- An object factory
- Logger class, a more realistic example 

## When to use

- When you need a shared instance of your class i.e. share single instance all over
- When you want to avoid long initializations
- When you need cross class communication
- When you want to represent unique items

## Notes

- Directly depending on a Singleton is a bad idea.
- We can overcome the above fact by introducing a dependency instead.


