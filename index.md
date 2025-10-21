# La Nakamurance 🌀

**Generic Language and Data Operand Syntax — Extension**  
Project EPITECH G-FUN-500  
By *The Dream Team*

---

## 🎯 Introduction

Nakamurance is a minimalist, expressive and funny programming language designed to be both readable and powerful.
It combines the simplicity of C, the flexibility of Lisp and the unique style of the Aya Nakamura universe.

The language is compiled into bytecode interpreted by the Glados VM.
Each keyword reflects a popular expression, making the code both meaningful and fun.

> "A language that speaks to both the machine and the developer"

---

## ⚙️ Philosophy

Nakamurance is based on three principles:
1. **Clarity**: Every keyword is memorable and intuitive.  
2. **Simplicity**: Minimal punctuation, linear and natural structure.  
3. **Fun**: Keywords and expressions make code enjoyable to read.

---

## 🔤 Keywords

| Keyword       | Equivalent (C / Lisp) | Description                         |
|---------------|-----------------------|-------------------------------------|
| **copine**    | `int`                 | Declare an integer variable         |
| **pookie**    | `function / lambda`   | Define a function                   |
| **fly**       | Function call         | Call a defined function             |
| **djadja**    | `if`                  | Conditional “if”                    |
| **comporté**  | `else`                | “else” block                        |
| **sapé**      | `while`               | Loop “while”                        |
| **aya**       | `return`              | Return a value                      |
| **coco**      | `print`               | Display a value                     |
| **Cale-cale** | `char`                | Declare a character                 |
| **Bandit**    | `bool`                | Declare a boolean                   |
| **Doggy**     | `double`              | Declare a double                    |
| **Fiesta**    | `float`               | Declare a float                     |

---

## 🧱 Basic Structure

Each Nakamurance program is composed of declarations, functions and control structures.
Instructions end with a semicolon, like in C.

```nakamurance
// Variable declaration
copine age = 21;

// Print
coco "Hello la Mif!";
```

---

## 🪩 Functions

Functions are declared using `pookie` and return values with `aya`.

```nakamurance
pookie presentation(name) {
    coco "Salut " + name;
    aya name;
}
```

Call a function:

```nakamurance
fly presentation("Aya");
```

---

## 💭 Conditions

Conditions use `djadja` and `comporté`.

```nakamurance
djadja (age > 18) {
    coco "T’es majeur";
} comporté {
    coco "Encore un bébé";
}
```

---

## 🔁 Loops

Loops with `sapé` execute code while a condition is true.

```nakamurance
sapé (age < 25) {
    coco "Toujours jeune";
    age = age + 1;
}
```

---

## 🧠 Types and Values

| Type | Description | Example |
|------|--------------|----------|
| **copine** | Signed integer | `copine x = 10;` |
| **Cale-cale** | Single character | `Cale-cale letter = 'A';` |
| **Bandit** | Boolean | `Bandit young = true;` |
| **Fiesta** | Floating-point number | `Fiesta weight = 52.3;` |
| **Doggy** | Double precision | `Doggy pi = 3.14159;` |

---

## 🧩 Compilation & Execution

The Nakamurance compiler translates source code into VM bytecode — a sequence of low-level instructions executed by the Glados Virtual Machine.

Example generated instructions:

```
Push 2
Push 3
Call Add
Print
Ret
```

These are then interpreted by the **Executor** module in the VM.

---

## 🧩 Example Program

```nakamurance
// Variable definitions
copine age = 19;
Cale-cale initiale = 'A';

// Function
pookie anniversaire() {
    coco "Joyeux anniversaire!";
    aya age + 1;
}

// Condition + loop
sapé (age < 22) {
    age = fly anniversaire();
    djadja (age == 21) {
        coco "T’as 21 ans, c’est la fête!";
    } comporté {
        coco "Toujours jeune!";
    }
}
```

---

## 🧮 Grammar (EBNF)

You can view the full Nakamurance grammar specification here:

[Click here to see the ebnf file](https://github.com/EpitechPGE3-2025/G-FUN-500-TLS-5-1-glados-7/blob/main/Nakamurance.ebnf)

---

## 💅 Spirit of Nakamurance

> “Programming, but make it fashion.”  
> — The Dream Team 🌀
> Y a pas moyen djadja -- slaay
