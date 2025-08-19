# Intro Java Exercises

A collection of small Java programs and practice exercises. Each file is a standalone class intended for learning basic Java syntax, control flow, and simple algorithms.

## What's included

```
/src
  - RabbitBaby2.java
  - Quiz8.java
  - Rabbit2.java
  - Quiz5.java
  - PetrolRunningTotal2.java
  - practise2.java
  - EmployeePay.java
  - HexaicosadecimalNumber.java
  - Employee.java
  - ConcatenateStrings.java
```

> Filenames like `RabbitBaby (2).java` were normalised to remove spaces/parentheses for Git compatibility (e.g., `RabbitBaby2.java`). Class names inside the files are unchanged.

## How to compile & run

1. Ensure you have the Java JDK installed (17+ recommended).
2. From the project root:

```bash
# compile all classes into ./bin
mkdir -p bin
javac -d bin src/*.java
```

3. Run any class that has a `public static void main(String[] args)` method, for example:

```bash
java -cp bin Employee
```

> If a class does not have a `main` method, it is likely a helper model (e.g., `Employee`) used by another class (e.g., `EmployeePay`).

## Suggested Git workflow

```bash
git init
git add .
git commit -m "Initial commit: add Java practice files"
git branch -M main
git remote add origin https://github.com/<your-username>/intro-java-exercises.git
git push -u origin main
```

## Notes
- No external dependencies or build tools are required.
- You can import this folder into IntelliJ IDEA or VS Code (with Java extension) and run files directly.
