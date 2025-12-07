# 💻 Universal Code Compiler (Browser-Based IDE)

<h3 align="center">A professional-grade, browser-based environment for multi-language code execution.</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Language%20Support-4%2B-blueviolet?style=for-the-badge&logo=codewars&logoColor=white" alt="Language Support"/>
  <img src="https://img.shields.io/badge/API%20Powered-Piston%20API-orange?style=for-the-badge&logo=api&logoColor=white" alt="API Powered"/>
  <img src="https://img.shields.io/badge/UI%2FUX-Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="UI/UX"/>
</p>

---

## 💡 Project Overview

The Universal Code Compiler is designed to be a lightweight, yet powerful, web-based Integrated Development Environment (IDE). It eliminates the need for local compiler setups by leveraging a remote execution engine, offering a seamless experience for students, developers, and competitive programmers.

### 🎯 Key Goals
1.  **Professional UX:** Deliver a high-quality coding experience similar to VS Code.
2.  **Zero Setup:** Run code for major languages directly in the browser.
3.  **Full Functionality:** Support standard input/output operations necessary for algorithmic tasks.

---

## ⚡ Features

* **Multi-Language Support:** Instant execution support for major languages.
    * **Java**
    * **C++**
    * **Python**
    * **JavaScript**
* **Smart Boilerplate Generation:** Automatically loads the required structure (e.g., `public class Main` for Java or necessary headers for C++) when switching languages, saving initial setup time.
* **Split Layout Design:** Dedicated, simultaneous panels for:
    1.  **Code Editor**
    2.  **Standard Input (Stdin)**
    3.  **Real-time Output (Stdout/Stderr)**
* **VS Code-like Editor:** Utilizes the **Ace Editor** library for robust syntax highlighting, indentation, and professional theming.
* **Responsive Dark Theme:** Built with **Tailwind CSS** for a modern, eye-friendly, and responsive user interface.

---

## 🛠️ Technology Stack

| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Editor** | **Ace Editor** | Provides the professional, embedded code editing experience. |
| **Styling** | **Tailwind CSS** | Utility-first CSS framework for rapid, modern UI development. |
| **Execution** | **Piston API** | Powerful, public engine for remote compilation and code execution. |
| **Architecture** | **Single-File JS/HTML** | Self-contained application for portability and easy deployment. |

---

## 🚀 How to Use (Local Setup)

This application is delivered as a single file, `index.html`, making it exceptionally easy to run.

1.  **Download:** Clone this repository or download the `index.html` file.
2.  **Run:** Open `index.html` directly in your web browser (Chrome, Firefox, Edge, etc.).
3.  **Select Language:** Use the dropdown menu in the top navigation bar to choose your language.
4.  **Provide Input:** If your code requires user input (e.g., `Scanner` in Java or `cin` in C++), enter the data line-by-line into the **Standard Input** box before running.
5.  **Execute:** Click the **Run Code** button and view the results immediately in the **Output** panel.

### 📝 Important Notes for Execution

* **Java Class Name:** For successful compilation, your main class in Java **must** be named `Main`.
* **Piston API:** This project relies on the Piston API service being available. Rate limits may apply for high-volume usage.
