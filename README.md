# Java Full Stack Workshop Exercises

Core Java practice from a college workshop, kept as a record of the exercises completed in **Day 1** and **Day 2**.

## What the exercises cover

- Classes, objects, and constructors
- Inheritance and method overriding
- Abstraction
- Member and static inner classes
- Method overloading
- Passing objects to methods
- Basic calculators and console programs

## Structure

```text
Java-Full-Stack-/
├── Day1/
│   ├── Abc.java
│   ├── Abstest.java
│   ├── Calculator1.java
│   ├── Daughter.java / Father.java
│   ├── Employee.java
│   ├── One.java / Two.java
│   └── Outer.java
└── Day2/
    ├── Calculator1.java
    ├── Outer.java / Outer1.java
    ├── Testoverlaod.java
    └── overlosding.java
```

Several files contain more than one top-level class, with the `main` method in a helper class. The file name matches the public class.

## Compile and run

From the repository root (JDK 17+):

```bash
javac Day1/Outer.java
java -cp Day1 Outer
```

For a file whose entry point is a non-public class, run that class explicitly, for example:

```bash
javac Day2/Calculator1.java
java -cp Day2 UseCalculator1
```

Compiled `.class` files are ignored and are not part of the repository source.

## Scope

These are learning exercises, not a full application. There is no build tool, package structure, test suite, or framework code in this repository.
