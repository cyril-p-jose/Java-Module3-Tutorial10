# Java Package Programs

This repository contains two Java programs based on the concept of **packages, classes, methods, and importing packages**.

## 📚 Programs Included

### 1. Classes in Different Packages

This program demonstrates how to define two classes in two different packages and use them in another Java class.

**Packages used:**

* `pack1` → contains `Man` class
* `pack2` → contains `Woman` class

**Classes:**

* `Man.java`
* `Woman.java`
* `Main.java`

**Concepts Covered:**

* Creating packages
* Defining classes inside packages
* Constructors
* Data members
* Methods
* Importing classes from different packages
* Creating and using objects

**Project Structure:**

```text
src/
├── Main.java
├── pack1/
│   └── Man.java
└── pack2/
    └── Woman.java
```

**Sample Output:**

```text
Man's Name: Smith, Age: 40
Woman's Name: Jane, Age: 35
```

---

### 2. Even Number Package

This program demonstrates how to create a custom Java package named `evenpackage` containing a class `Even` with a static method to check whether a number is even or not.

**Package used:**

* `evenpackage` → contains `Even` class

**Classes:**

* `Even.java`
* `TestEven.java`

**Concepts Covered:**

* Creating a user-defined package
* Importing a package/class
* Static methods
* Boolean return values
* Modulus (`%`) operator
* Conditional statements

**Project Structure:**

```text
src/
├── TestEven.java
└── evenpackage/
    └── Even.java
```

**Sample Output:**

```text
24 is an even number
```

---

## 🛠️ Technologies Used

* **Language:** Java
* **IDE:** Eclipse
* **Concepts:** Packages, Classes, Objects, Constructors, Methods, Static Methods, Import

## ▶️ How to Run

1. Open **Eclipse**.
2. Create a Java Project.
3. Create the required packages and classes according to the project structures above.
4. Add the Java source code.
5. Run the main class:

   * `Main.java` for Program 1
   * `TestEven.java` for Program 2
6. View the output in the Eclipse Console.

## 🎯 Learning Objective

The purpose of these programs is to understand how Java packages are created and used, how classes can be organized into different packages, and how classes and methods from packages can be imported and accessed from another class.

---

## 👨‍💻 Author

**Cyril P Jose**

B.Tech Computer Science and Engineering Student
