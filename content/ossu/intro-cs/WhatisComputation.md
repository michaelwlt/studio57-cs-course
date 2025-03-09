---
title: "What is Computation?"
date: 2025-03-09T08:13:49+01:00
draft: false
---
# Introduction to Programming and Python: From Computer Basics to Your First Code

## The Journey Begins: Welcome to Programming

Welcome to the fascinating world of programming! If you're new to this journey, you might be experiencing a mix of excitement and trepidation—and that's perfectly normal. Programming is like developing any other skill: it requires practice, patience, and a willingness to experiment. The good news? You can't break your computer just by writing code. The worst that can happen is restarting your machine, so don't be afraid to dive in and try things out!

## The Roadmap to Programming Proficiency

Before we dive into Python specifically, let's understand what we're aiming to achieve in learning programming. Our journey can be mapped across three fundamental areas:

1. **Knowledge of Concepts** - Understanding the theory and principles behind programming
2. **Programming Skills** - Developing practical abilities to write functional code
3. **Problem-Solving** - Learning how to approach challenges methodically and develop solutions

Underlying all of these is the crucial element of practice. No one becomes proficient at programming by simply reading about it—you must write code regularly and often.

But what exactly will this practice lead to? Let's explore the skills you'll develop along the way.

## What We'll Learn: Building Your Programming Toolkit

Our curriculum breaks down into three interconnected sections that build upon each other:

### 1. Core Programming Fundamentals
- Creating objects and data structures to represent knowledge
- Implementing control flow to make decisions and direct program execution

These fundamentals form the foundation of all programming—like learning the alphabet before writing sentences. Once you understand these basics, you can begin constructing more complex programs.

### 2. Writing Quality Code
- Developing good programming style and readable code
- Organizing code in modular, understandable structures

This second aspect is particularly important because your code isn't just for computers—it's for humans too. Whether colleagues at a company or your future self returning to a project months later, readable code is essential for collaboration and maintenance. As you'll soon discover, there's a significant difference between code that merely works and code that works well.

### 3. Computer Science Concepts
- Comparing programs for efficiency
- Analyzing algorithms to determine their effectiveness
- Measuring performance to optimize solutions

Once you can write working, readable code, the final step is learning to write efficient code. This is where programming transforms into computer science—understanding not just how to solve a problem, but how to solve it optimally.

Now that we know where we're headed, let's take a step back and understand what computers actually do. This foundation will help make sense of everything that follows.

## What Computers Actually Do: The Magic Behind the Screen

At their most fundamental level, computers perform two primary functions:

1. **Execute calculations** - Modern computers can perform billions of calculations per second
2. **Store results** - Today's machines can store hundreds of gigabytes of information

While this might seem overly simplistic, these two capabilities form the basis of everything computers do, from playing video games to predicting the weather. The calculations computers perform come in two varieties:

- **Built-in primitive operations** - Basic functions like addition, subtraction, and multiplication
- **User-defined operations** - Complex functions created by combining primitive operations

One crucial insight that will serve you well in programming: computers only know what you tell them to do. They have no intuition or understanding—they simply follow instructions with remarkable speed and precision. This is why learning to communicate clearly with computers through programming languages is so essential.

But how do we communicate with computers? This brings us to an important distinction in types of knowledge.

## Types of Knowledge: The "What" and "How" of Programming

Understanding the distinction between two types of knowledge is fundamental to programming:

**Declarative Knowledge** consists of statements of fact. For example: "The square root of x is y such that y × y = x." This tells us *what* is true but not *how* to find the answer.

**Imperative Knowledge** provides a recipe or sequence of steps to follow. For example: "To find the square root of x, start with a guess, check if it's close enough, and if not, make a better guess and repeat." This tells us exactly *how* to accomplish something.

In programming, we're primarily concerned with imperative knowledge—the step-by-step instructions that tell a computer what to do. This is because computers need explicit instructions; they can't figure out the "how" from simply knowing the "what."

Let's make this concrete with a numerical example:

### A Square Root Algorithm: Imperative Knowledge in Action

- **Declarative Knowledge**: The square root of x is y such that y × y = x.
- **Imperative Knowledge**: To find the square root of x (let's say x = 16):
  1. Start with a guess g (let's say g = 3)
  2. Calculate g² = 9. Is this close enough to 16? No.
  3. Create a new guess by averaging g and x/g: (3 + 16/3)/2 = 3.67
  4. Calculate 3.67² = 13.47. Is this close enough? Not quite.
  5. Continue refining until we reach a satisfactory approximation.

This recipe contains three critical components that we'll see throughout programming:
1. A sequence of simple steps
2. Flow control (decisions and repetition)
3. A method to stop the process

This example demonstrates why computers need imperative knowledge—they need the exact steps to follow, not just the end goal. But how did computers evolve to follow these kinds of instructions?

## The Evolution of Computing: From Fixed to Flexible Machines

The history of computers reveals an important shift in how we approach computing tasks:

### From Fixed to Flexible Programs

Early computers were "fixed-program" machines, like basic calculators that could only perform specific functions. If you wanted to perform a different task, you needed a different machine—imagine having a separate calculator for addition, subtraction, and multiplication!

The revolution came with "stored-program" computers that could:
- Store sequences of instructions in memory
- Execute these instructions
- Change the instructions to perform different tasks

This flexibility is the foundation of modern computing and allows a single device to run everything from spreadsheets to video games.

### Basic Computer Architecture: The Brain of a Computer

To understand how computers execute programs, we need to explore their architecture. At the heart of every computer is a similar system:
- **Memory** - Stores data and instructions
- **Arithmetic Logic Unit (ALU)** - Performs primitive operations
- **Control Unit** - Contains the program counter that tracks which instruction to execute next
- **Input/Output** - Interfaces with the outside world

When you run a program, the computer loads your instructions into memory. The control unit then fetches each instruction one by one, sending it to the ALU for execution. Depending on the results, the control unit might proceed to the next instruction or jump to a different part of the program.

Understanding this process helps explain why programming languages are structured the way they are—they're designed to map efficiently onto this underlying architecture.

## The Power of Programming Languages: From Turing to Python

The theoretical foundation of programming languages was established by Alan Turing, who proved that with just six primitive operations (move left, move right, read, write, scan, and do nothing), you can compute anything that's computable. This remarkable insight led to a profound realization: if you can compute something in one programming language, you can theoretically compute the exact same thing in any other language.

Modern programming languages like Python provide a more convenient and intuitive set of primitives than Turing's minimal set, making coding more accessible. But all programming languages share the goal of translating human intentions into instructions a computer can execute.

This brings us to how programming languages work, which has interesting parallels to human languages.

## From Primitives to Expressions: The Grammar of Code

Programming languages have their own grammar and semantics, similar to human languages:

1. **Primitive Constructs** - In English, these are words; in Python, they include numbers, strings, and operators
2. **Syntax** - Rules for forming valid expressions (like grammatical rules in language)
3. **Static Semantics** - Rules for creating meaningful expressions
4. **Semantics** - The actual meaning of expressions

Let's see how this works in both English and Python:

In English, a phrase like "cat dog boy" has bad syntax—it's just nouns strung together. But "cat hugs boy" has good syntax (noun-verb-noun) and makes semantic sense.

Similarly, in Python, `5 + hello` has invalid static semantics even though the structure (operand-operator-operand) follows valid syntax. The issue is that you can't add a number to a word.

Unlike human languages, where phrases can have multiple interpretations (think of "flying planes can be dangerous"—is the act of flying planes dangerous, or are planes that are flying dangerous?), programs have exactly one meaning. However, this meaning might not be what the programmer intended—this is the source of bugs and errors!

Now that we understand how programming languages work at a conceptual level, let's dive into Python specifically.

## Python Basics: Objects, Types, and Operations

In Python, everything is an object, and every object has a type. The type determines what operations you can perform on the object, just as being human allows me certain capabilities while being a Wookiee (like Chewbacca) allows for different ones.

### Scalar Objects: The Building Blocks

These are the basic building blocks that cannot be subdivided:
- **Integers** - Whole numbers (e.g., 5, -3)
- **Floats** - Real numbers with decimal points (e.g., 3.14, -2.5)
- **Booleans** - True or False values (note the capitalization)
- **NoneType** - Represented by the value None, indicating absence of a value

You can find an object's type using the `type()` function:

```python
type(5)     # <class 'int'>
type(3.14)  # <class 'float'>
type(True)  # <class 'bool'>
```

And you can convert between types with functions like `int()`, `float()`, and `bool()`:

```python
float(3)    # 3.0
int(3.7)    # 3 (truncates, doesn't round)
bool(1)     # True
```

### Expressions and Operations: Combining Objects

By combining objects with operators, we create expressions that evaluate to values:

```python
# Basic arithmetic operations
3 + 4       # Addition: 7
5 - 2       # Subtraction: 3
2 * 3       # Multiplication: 6
6 / 2       # Division: 3.0 (always returns a float)
7 % 3       # Remainder: 1
2 ** 3      # Exponentiation: 8
```

The type of the result depends on the operation and the operands. For addition, subtraction, and multiplication, if all operands are integers, the result is an integer; if any operand is a float, the result is a float. Division always returns a float, regardless of the operands.

### Variables and Assignment: Storing Values

Variables allow us to store values for later use—a critical capability for writing useful programs:

```python
pi = 3.14159
radius = 2.2
area = pi * (radius ** 2)
```

The equal sign (`=`) in Python is an assignment operator, not a mathematical equality. It binds the name on the left to the value on the right. This is fundamentally different from math equations:

- In math: `x + y = 10` is a statement about the relationship between x and y
- In Python: `x = y + 10` assigns the value of `y + 10` to the variable `x`

This distinction is crucial for understanding how programming differs from mathematics. In programming, we always tell the computer exactly how to calculate a value, rather than describing relationships between values.

Variables make code more readable and reusable. Instead of repeating values, we can use descriptive names that clarify the purpose of the value:

```python
# Less readable
print(3.14159 * (2.2 ** 2))

# More readable
pi = 3.14159
radius = 2.2
area = pi * (radius ** 2)
print(area)
```

### Rebinding Variables: Changing Values

Variables can be reassigned, creating a new binding to a different value:

```python
radius = 2.2
area = pi * (radius ** 2)  # Calculate area with radius = 2.2
radius = radius + 1        # Rebind radius to 3.2
```

Importantly, changing a variable does not automatically update other variables that were calculated using its previous value. In the example above, `area` will not change when `radius` changes—the computer only does what it's explicitly told to do. If you want to update the area, you would need to recalculate it:

```python
radius = 3.2
area = pi * (radius ** 2)  # Recalculate area with the new radius
```

This behavior illustrates a fundamental principle: computers follow instructions exactly as given, without inferring relationships unless explicitly programmed to do so.

## Interaction and Output: Communicating with Users

To display information to users, you'll use the `print()` function:

```python
print("Hello, world!")  # Outputs: Hello, world!
print(3 + 2)           # Outputs: 5
```

This is different from simply typing an expression in the interactive console, which shows the value for your convenience but doesn't actually output anything in a program. Understanding the difference between evaluation and output is important for creating programs that interact meaningfully with users.

## The Journey Forward: Building on the Basics

Now that you understand the fundamentals of Python—objects, types, expressions, and variables—you're ready to build on this foundation. The next steps in your programming journey will include:

1. **Control Flow** - Adding decisions (if-else statements) and loops to your programs
2. **Functions** - Creating reusable blocks of code
3. **Data Structures** - Learning about lists, dictionaries, and other ways to organize data
4. **Modular Design** - Organizing code into logical components

As you progress, you'll move from writing simple scripts to developing complex programs that solve real-world problems. Along the way, you'll also explore more advanced computer science concepts like algorithm efficiency, which will help you write not just functional code, but optimal code.

To test your understanding of the concepts, you learned today you can take a short quiz at [MIT OpenCourseWare](https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/pages/in-class-questions-and-video-solutions/lecture-1/), which provides questions and video solutions based on this lecture material.

Remember that programming is a skill developed through practice. Don't be afraid to make mistakes—they're valuable learning opportunities. Each error message is not a failure but a clue that helps you understand how the computer interprets your instructions.

And most importantly, enjoy the process of creating and problem-solving through code! There's something profoundly satisfying about instructing a computer to perform tasks and watching your instructions come to life. Whether you're calculating the area of a circle or developing the next revolutionary application, the core principles remain the same: clear instructions, logical thinking, and a willingness to learn.

---

*This article is adapted from an MIT OpenCourseWare lecture by Professor Ana Bell for the course ["Introduction to Computer Science and Programming in Python."](https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/resources/lecture-1-what-is-computation/) - This page is licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)*
