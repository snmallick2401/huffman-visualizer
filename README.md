# 🌳 Huffman Coding Visualizer

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

A modern, interactive web-based visualizer and C++ implementation for **Huffman Coding**—a popular lossless data compression algorithm. Watch the tree build itself, generate binary codes, and simulate the decoding process in real-time.

**🚀 Live Demo:** [View Visualizer on Netlify](https://69f2419735615e71552d7f1f--animated-sable-c3cd47.netlify.app/)

---

## ✨ Features

### 🎨 Web Visualizer (`index.html`)
* **Interactive Tree Generation:** Type any text and watch the Huffman tree build dynamically.
* **Smooth SVG Animations:** Edges draw themselves, and nodes pop in with satisfying spring physics.
* **Step-by-Step Decoding:** Simulates traversing the tree bit-by-bit to decode binary strings back into text with glowing highlights.
* **Modern UI/UX:** Features a beautiful Glassmorphism design with a dotted background grid.
* **☀️/🌙 Light & Dark Mode:** Fully responsive theme toggler that remembers your preference via Local Storage.
* **Real-Time Stats:** Calculates original ASCII size vs. compressed Huffman size to show exact compression percentages.

### 💻 Core Algorithm (`huffman.cpp`)
* Clean, memory-safe C++ implementation using a Priority Queue (`std::priority_queue`).
* Demonstrates the raw algorithmic logic behind frequency mapping, tree building, and code generation.

---

## 🛠️ Usage & Installation

### 1. Running the Web Visualizer
Because the visualizer is built with Vanilla HTML/CSS/JS, no build tools or package managers are required!
* Simply clone the repository:
  ```bash
  git clone [https://github.com/snmallick2401/huffman-visualizer.git](https://github.com/snmallick2401/huffman-visualizer.git)
