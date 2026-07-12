# 🔐 PyPassword Generator

A simple command-line password generator built with Python. The program creates strong, randomized passwords based on the number of letters, numbers, and symbols specified by the user.

## ✨ Features

- Generate secure random passwords
- Customize the number of:
  - Letters (uppercase and lowercase)
  - Numbers
  - Symbols
- Randomly shuffles all characters for improved randomness
- Simple and beginner-friendly Python code
- No external dependencies required

## 📸 Example

```text
Welcome to the PyPassword Generator!

How many letters would you like in your password?
8
How many numbers would you like?
4
How many symbols would you like?
2

Your password is: aB8!kL2#Q7mR
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your computer

### Installation

Clone the repository:

```bash
git clone https://github.com/mutopia7/PyPassword.git
```

Navigate to the project folder:

```bash
cd PyPassword
```

## ▶️ Usage

Run the program with:

```bash
python main.py
```

Follow the prompts:

1. Enter the number of letters.
2. Enter the number of numbers.
3. Enter the number of symbols.
4. Receive your randomly generated password.

## 📂 Project Structure

```text
PyPassword/
│
├── main.py        # Main application
└── README.md      # Project documentation
```

## 🛠️ How It Works

The program:

1. Stores letters, numbers, and symbols in separate lists.
2. Asks the user how many characters of each type should be included.
3. Randomly selects characters using Python's `random.choice()`.
4. Combines all selected characters into a list.
5. Shuffles the list using `random.shuffle()`.
6. Joins the characters into a single password string.
7. Displays the generated password.

## 📚 Concepts Practiced

This project demonstrates several fundamental Python concepts:

- Lists
- Loops (`for`)
- User input
- String manipulation
- Random module
- List methods
- `random.choice()`
- `random.shuffle()`
- `"".join()`

## 🔒 Example Passwords

```text
mL8#qW2!Az4
9Fg*Rt5a&B
K2+eQ!7xLp
```

Each execution produces a different password.


## 📄 License

This project is open source and available under the **MIT License**.

---

Made with ❤️ and Python.
