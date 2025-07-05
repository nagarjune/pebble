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
