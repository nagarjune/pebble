# 🪨 Pebble Programming Language

**Pebble** is a new general-purpose language designed to be **easier than Python**, written in a **natural, English-like style**, and usable across **web, mobile, and software development**.

---

## ✨ Philosophy

- 🧠 **Readability First** – code should read like English
- 🚀 **Beginner Friendly** – perfect for new programmers
- 🌐 **Multi-platform** – CLI, Web, Mobile
- 🔁 **Transpile, not compile** – converts to Python, JS, Dart

---

## ✅ What Can You Do?

- Build websites & apps using `screen`, `input`, `button`
- Write scripts like Python
- Run Pebble in terminal or browser
- Create mobile apps with Flutter (coming soon)

---

## 👇 Sample Pebble Code

```pebble
ask "What is your name?"
let name be _
show "Hello, " plus name

define greet with who then
    show "Hi, " plus who

greet with name

# Pebble v0.2 Full

Pebble is a simple, natural-language-inspired programming language that supports:
- Variable assignment
- User input
- Math expressions (`plus`, `minus`, `times`, etc.)
- If/Else conditionals
- Repeat loops
- Multi-argument functions
- Function definitions and calls
- Web UI DSL (via transpiler)

# Pebble v0.3

Pebble is an English-like, beginner-first programming language designed for non-developers to build logic, apps, or automate tasks — without needing to learn traditional programming.

## 🌟 Highlights

- Write code using simple English
- No semicolons, no curly braces — just logic that reads like sentences
- Build real-world logic with functions, loops, conditionals, and more

## 🆕 New in v0.3

- Math and string expression parsing
- For-each loops
- Lists
- Function definition with arguments
- Improved if/else blocks
- Better error handling

## 📦 Example Code

```pebble
let name be "Pebble"
let x be 5
let y be 10
let total be x plus y
show "Total is " plus total

let fruits be ["apple", "banana"]
for each fruit in fruits do
    show "I like " plus fruit

define greet with person then
    show "Hello " plus person

greet with "Alice"

