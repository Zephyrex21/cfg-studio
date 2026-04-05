# 🚀 CFG Studio

### Interactive Context-Free Grammar Explorer

> A modern, interactive web application to design, analyze, and visualize **Context-Free Grammars (CFGs)** — powered by a full **Earley Parsing Engine**.

---

## 🌐 Live Demo

👉 https://cfg-studio.netlify.app/

---

## ✨ Features

### 🧩 Grammar Designer

* Define CFG rules using intuitive syntax
* Supports multiple formats (`→`, `=>`, `::=`)
* Automatic validation and formatting

### 🔍 Derivation Visualizer

* Step-by-step **Leftmost** and **Rightmost** derivations
* Interactive controls to navigate derivation steps
* Random valid string generation

### 🌳 Parse Tree Generator

* Dynamic **SVG-based parse tree visualization**
* Supports complex and recursive grammars
* Clean node layout with animations

### ⚠️ Ambiguity Checker

* Detects ambiguous grammars
* Generates **multiple parse trees** for the same string
* Demonstrates real ambiguity cases (e.g., expressions, dangling else)

### 📚 Applications Section

* Real-world uses of CFGs in:

  * Compiler Design
  * Programming Languages
  * NLP
  * Document Parsing
  * Bioinformatics

---

## 🧠 Core Concepts Implemented

* Context-Free Grammar Parsing
* **Earley Parsing Algorithm**
* Leftmost & Rightmost Derivations
* Parse Tree Construction
* Ambiguity Detection

---

## ⚙️ Tech Stack

* **HTML5**
* **Tailwind CSS** (UI Styling)
* **Vanilla JavaScript**
* **SVG Rendering** (for trees)

---



## 🚀 Getting Started

### Run Locally

```bash
git clone https://github.com/Zephyrex21/CFG-Studio.git
cd CFG-Studio
```

Then simply open:

```
index.html
```

---

## 📸 Preview

> Add screenshots here (UI, parse tree, derivation steps)

---

## 🔥 Highlights

* Implements a **full Earley Parser from scratch**
* Handles:

  * Left recursion
  * Right recursion
  * Epsilon productions
  * Ambiguous grammars
* Designed with a **modern glassmorphism UI**

---

## 🧪 Example Grammar

```
S -> a S b | a b
```

Input:

```
aabb
```

---

## 🛠️ Future Improvements

* Step-by-step Earley algorithm visualization
* Grammar saving & sharing
* Custom grammar library
* Performance optimization for large inputs

---

## 👨‍💻 Author

**Saurabh Raj Shekhar**

---

## 📄 License

This project is licensed under the MIT License.
