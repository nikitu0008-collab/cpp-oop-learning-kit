# 🧩 OOP in C++ • Examples • Tasks • Theory

[![C++](https://img.shields.io/badge/C++-17%2F20-blue?logo=c%2B%2B)](https://isocpp.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)]()

> **One repository – four pillars of OOP.**  
> Clean C++ code, real‑world tasks, concise notes, and a full lecture.

---

## 📌 Why this repo?

- **Theory + practice** – each principle comes with working code  
- **Difficulty levels** – beginner → intermediate → advanced tasks  
- **Modern C++** – RAII, smart pointers, move semantics  
- **Ready to use** – just clone and compile

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/oop-in-cpp.git
cd oop-in-cpp
2. Build with CMake (optional, for all examples)
bash
mkdir build && cd build
cmake .. && make
3. Or run a single file directly
bash
g++ -std=c++17 examples/01_encapsulation.cpp -o demo && ./demo
Replace 01_encapsulation.cpp with any example file.

🧠 Code Examples
Principle	File
Encapsulation	examples/01_encapsulation.cpp
Inheritance	examples/02_inheritance.cpp
Polymorphism	examples/03_polymorphism.cpp
Abstraction	examples/04_abstraction.cpp
RAII	examples/05_raii_example.cpp
Short preview – polymorphism:

cpp
class Animal {
public:
    virtual ~Animal() = default;
    virtual std::string speak() const = 0;
};

class Dog : public Animal {
    std::string speak() const override { return "Woof!"; }
};
🤝 Contributing
Add more tasks, fix typos, improve examples.

Fork the repo

Create a branch (git checkout -b improve)

Commit and push

Open a Pull Request

📄 License
MIT – free to use, share, and modify.

⭐ Support
If this helped you, star the repo – it helps others find it.

Happy coding! 🚀
