# Finch 

A full-featured scripting language written in Java.

## Features
- Support for variables, functions, and classes
- Built-in support for common data types such as numbers, strings, and arrays
- Support for conditional statements and loops
- Support for importing and using external Java libraries
- Easy-to-use syntax and intuitive design

## Getting Started

### Prerequisites

- Java 8 or later
- Maven (for building the project)

### Installation

1. Clone the repository:
  * ```git clone https://github.com/Adamlip1334/Finch.git```

2. Build the project using Maven:
  * ```cd src/xyz/adamlipson```
  * ```mvn clean install```

3. Run the interpreter:
  * ```java -jar target/finch-1.0-SNAPSHOT.jar```

### Usage

To execute a script, simply pass the file path as an argument to the interpreter:
java -jar target/finch-1.0-SNAPSHOT.jar path/to/script.fin

You can also use the interactive mode to execute commands directly in the interpreter:
java -jar target/finch-1.0-SNAPSHOT.jar -i

# Examples

## Print "Hello, World!"
print("Hello, World!")

## Declare a variable
x = 5

## Conditional statement
if x > 3:
    print("x is greater than 3")
else:
    print("x is not greater than 3")

# Acknowledgements

- [Java](https://www.java.com/)
- [Maven](https://maven.apache.org/)
