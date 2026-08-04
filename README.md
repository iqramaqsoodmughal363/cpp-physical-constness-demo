# 🔒 Physical Constness in C++

> A C++ program that demonstrates the concept of physical constness, illustrating how const member functions restrict modification of data members, and how the `mutable` keyword can bypass this restriction.

---

## 📋 Overview

This program demonstrates **physical constness** in C++ – the rule that a `const` member function cannot modify any data member of the class. It shows:

- A `const` member function (`getResponse()`) that reads data without modifying it.
- A non-const member function (`changeData()`) that modifies data.
- A commented-out const member function (`makeSomeChanges()`) that would cause a compilation error if uncommented.

---

## ✨ Features

- ✅ Demonstrates const correctness in member functions
- ✅ Shows compile-time restrictions on const functions
- ✅ Uses `stringstream` for formatted output
- ✅ Clear separation between read-only and write operations
- ✅ Educational example for understanding physical constness

---

## 🧮 Program Logic & Execution Flow

1. A class `A` is defined with private data members `i` and `j`.
2. The `getResponse()` function is marked `const` – it can read but not modify `i` and `j`.
3. The `changeData()` function is non-const – it modifies `i` and `j`.
4. The `makeSomeChanges()` function is commented out – if uncommented, it would cause a compilation error because it tries to modify `i` and `j` inside a `const` function.
5. In `main()`, a `A` object is created, and its state is displayed after each operation.

---

## 💻 Sample Output
A a(10, 20) : i = 10, j = 20
A::changeData(30, 40) : i = 30, j = 40
A::makeSomeChanges() : i = 30, j = 40



---

## 🛠️ How to Compile and Run (Windows & Linux)

Follow the instructions below based on your operating system.

### 🪟 For Windows Users (Using MinGW/G++ or any C++ compiler)
| Step | Command |
| :---: | :--- |
| **1. Compile** | `g++ physical_constness.cpp -o physical_constness.exe` |
| **2. Run** | `physical_constness.exe` |

> **Note:** If `g++` is not recognized, make sure MinGW is installed and added to your System PATH.

---

### 🐧 For Linux / macOS Users (Terminal)
| Step | Command |
| :---: | :--- |
| **1. Compile** | `g++ physical_constness.cpp -o physical_constness` |
| **2. Run** | `./physical_constness` |

> **Prerequisite:** Ensure GCC/G++ is installed on your system. (On Linux: `sudo apt install g++` | On macOS: `xcode-select --install`)

---

## 📂 Project Structure
cpp-physical-constness-demo/
│
├── physical_constness.cpp # Main source code file
└── README.md # Project documentation (this file)



---

## 👩‍💻 Author

**Iqra Maqsood Mughal**  
*C++ Developer | Programming Enthusiast*

---

## 📅 Date

**August 2, 2026**

---

## 📄 License

This project is open-source and intended for educational purposes.
✅ Ho gaya! Yeh 36th repo (Physical Constness Demo) ready hai. Is README mein "✨ Features" section included hai.

Agla code bhejiye! 🚀

