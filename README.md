# FunctionalPrograming
# ☕ Java 8 Functional Programming

A hands-on learning repository dedicated to **Java 8 Functional Programming**, featuring practical examples, code snippets, and concepts useful for Java developers and interview preparation.

## 📚 Topics Covered

### 1. Lambda Expressions
- Introduction to Lambda Expressions
- Lambda syntax and parameters
- Lambda with functional interfaces
- Single-line and multi-line lambda expressions

### 2. Functional Interfaces
- What is a Functional Interface?
- `@FunctionalInterface` annotation
- Built-in Functional Interfaces:
  - `Predicate<T>`
  - `Function<T, R>`
  - `Consumer<T>`
  - `Supplier<T>`
- `BiPredicate`, `BiFunction`, and `BiConsumer`
- Primitive functional interfaces

### 3. Method References
- Static method references
- Instance method references
- Arbitrary object method references
- Constructor references
- Method references vs. Lambda Expressions

### 4. Stream API
- Creating Streams from Collections and Arrays
- Intermediate Operations:
  - `filter()`
  - `map()`
  - `flatMap()`
  - `distinct()`
  - `sorted()`
  - `limit()` and `skip()`
- Terminal Operations:
  - `forEach()`
  - `collect()`
  - `count()`
  - `reduce()`
  - `min()` and `max()`
  - `anyMatch()`, `allMatch()`, and `noneMatch()`
- Collectors and grouping
- Sorting and filtering custom objects
- Lazy Evaluation
- Parallel Streams

### 5. Optional Class
- Creating Optional Objects
- `of()`, `ofNullable()`, and `empty()`
- `isPresent()` and `ifPresent()`
- `orElse()` and `orElseGet()`
- `orElseThrow()`
- `map()` and `flatMap()`

### 6. Practical Examples
- Filtering and sorting employee records
- Book management using Streams
- Finding maximum and minimum values
- Grouping data by category
- Calculating average salary and prices
- Removing duplicates from collections
- Converting collections using `map()`
- Solving coding problems with Java 8

## 🛠️ Technologies Used

- **Language:** Java
- **Version:** Java 8+
- **IDE:** IntelliJ IDEA / Eclipse / VS Code
- **Core Concepts:** OOP, Collections Framework, Functional Programming

## 📂 Repository Structure

```text
java-8-functional-programming/
│
├── LambdaExpressions/
├── FunctionalInterfaces/
│   ├── PredicateExample.java
│   ├── FunctionExample.java
│   ├── ConsumerExample.java
│   └── SupplierExample.java
│
├── MethodReferences/
├── StreamAPI/
│   ├── FilterExample.java
│   ├── MapExample.java
│   ├── SortedExample.java
│   ├── CollectExample.java
│   └── BookStreamExample.java
│
├── OptionalClass/
├── PracticalExamples/
│
└── README.md
```

*The folder structure is a suggested organization and can be updated as the repository grows.*

## 🚀 Getting Started

### Prerequisites
- Install JDK 8 or later.
- Install your preferred Java IDE.
- Basic knowledge of Java syntax, OOP, and Collections.

### Run an Example

1. Clone the repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the project in your IDE.
3. Navigate to any example.
4. Compile and run the Java file.

## 🎯 Learning Objectives

- Understand functional programming concepts in Java.
- Write cleaner and more readable code.
- Master built-in functional interfaces.
- Process collection data efficiently with Streams.
- Understand lazy evaluation and method references.
- Prepare for Java developer interviews.

## 📈 Learning Progress

- [ ] Lambda Expressions
- [ ] Functional Interfaces
- [ ] Method References
- [ ] Stream API
- [ ] Optional Class
- [ ] Collectors and Grouping
- [ ] Parallel Streams
- [ ] Interview Practice Problems

## 🤝 Contributions

Suggestions, improvements, and examples are welcome! Feel free to open an issue or submit a pull request.

## ⭐ Support

If you find this repository helpful in learning Java 8 Functional Programming, consider giving it a star ⭐.

---

**Happy Coding! 💻**

*Learn consistently. Practise daily. Build strong Java fundamentals.*
