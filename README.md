# 🧩 OOP in C++ • Examples • Tasks • Theory

<p align="center">
  <img src="https://img.shields.io/badge/C++-17%2F20-blue?logo=c%2B%2B&style=for-the-badge" alt="C++17/20">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge&logo=opensourceinitiative" alt="MIT License">
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge&logo=git" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/Made%20with-%F0%9F%92%96-red?style=for-the-badge" alt="Made with love">
</p>

> **One repository – four pillars of OOP.**  
> Clean C++ code, real‑world tasks, concise notes, and a full lecture.

---

## ✨ Why this repo?

<table>
<tr>
<td>✅ &nbsp; <b>100% practical</b></td>
<td>Every principle comes with working, compilable code</td>
</tr>
<tr>
<td>📊 &nbsp; <b>3 difficulty levels</b></td>
<td>Beginner → Intermediate → Advanced tasks</td>
</tr>
<tr>
<td>🚀 &nbsp; <b>Modern C++17/20</b></td>
<td>RAII, smart pointers, move semantics, constexpr</td>
</tr>
<tr>
<td>⚡ &nbsp; <b>Zero config</b></td>
<td>Clone → compile one file → learn instantly</td>
</tr>
</table>

---

## 🚀 Quick Start

| Step | Command |
|------|---------|
| 📦 **Clone** | `git clone https://github.com/YOUR_USERNAME/oop-in-cpp.git` |
| 💻 **Enter** | `cd oop-in-cpp` |
| 🛠️ **Build all (CMake)** | `mkdir build && cd build && cmake .. && make` |
| 🚀 **Run one file directly** | `g++ -std=c++17 examples/01_encapsulation.cpp -o demo && ./demo` |

> 🔁 Replace `01_encapsulation.cpp` with any example file from the `examples/` folder.

---

## 🧠 Code Examples (ready to run)

| Principle | File | What you'll learn |
|-----------|------|--------------------|
| 🔒 **Encapsulation** | `examples/01_encapsulation.cpp` | Getters/setters, access control, validation |
| 👪 **Inheritance** | `examples/02_inheritance.cpp` | Base/derived classes, code reuse |
| 🎭 **Polymorphism** | `examples/03_polymorphism.cpp` | Virtual functions, dynamic binding |
| 🧱 **Abstraction** | `examples/04_abstraction.cpp` | Pure virtual, interfaces |
| 🧹 **RAII** | `examples/05_raii_example.cpp` | Resource acquisition is initialization |

### ✨ Preview – Polymorphism in action
```cpp
class Animal {
public:
    virtual ~Animal() = default;
    virtual std::string speak() const = 0; // pure virtual
};

class Dog : public Animal {
    std::string speak() const override { return "Woof! 🐕"; }
};

class Cat : public Animal {
    std::string speak() const override { return "Meow! 🐈"; }
};
Expected output:

text
Dog says: Woof! 🐕
Cat says: Meow! 🐈
📚 What's inside (without the tree)
Folder	Content
examples/	10+ fully commented C++ files – each standalone
tasks/	Problem sets + solutions (beginner → advanced)
notes/	Short theory: vtable, smart pointers, const correctness, move semantics
lecture/	One complete lecture (Markdown) explaining OOP from scratch
💡 All folders are structured for easy navigation – no deep nesting.

⚙️ Requirements
Compiler: g++ (7+), clang++ (8+), or MSVC 2019+ with C++17 support

Build system (optional): CMake 3.10+

OS: Linux, macOS, Windows (WSL or MinGW)

No external libraries required – pure standard C++.

🤝 Contributing
Want to add a new example, fix a typo, or improve a note?
You are very welcome!

Fork the repository

Create a new branch (git checkout -b feature/awesome-example)

Commit your changes (git commit -m 'Add awesome example')

Push to the branch (git push origin feature/awesome-example)

Open a Pull Request

📖 Please follow the existing coding style and add comments where helpful.

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.
Feel free to use, copy, modify, and distribute.

⭐ Show your support
If this repository helped you understand OOP in C++ better:

⭐ Star this repo to help others find it

🐦 Share it with your friends or on social media

✉️ Suggest improvements via Issues

<p align="center"> <i>Made with 💙 for the C++ community</i><br> <i>Happy coding! 🚀</i> </p> ```
