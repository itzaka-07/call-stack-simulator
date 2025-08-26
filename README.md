# 🌀 Call Stack Simulator — Recursion & Function Visualization

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue?style=flat-square)](
https://itzaka-07.github.io/call-stack-simulator/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-yellow?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

Ever wondered **what’s happening inside your program when recursion kicks in**?  
This interactive **Call Stack Simulator** lets you _see_ the execution flow of recursive functions in real-time — with a **stack view** and a **tree view**.  

> TL;DR: Press **Start**, watch calls stack up, results bubble down. Geeky and gorgeous. ✨

---

## 🖼 Preview
![Call Stack Simulator Preview](https://github.com/user-attachments/assets/88c2655e-1148-4a71-af44-e0845414eabe)  
*Example: Fibonacci (n = 5) visualized in Tree View.*
---

## 🚀 Features
- **Visualize Recursion**
  - Watch how function calls are pushed to and popped from the stack.
  - Explore branching in a tree diagram for each recursive step.
- **Built-in Algorithms**
  - ✅ Factorial
  - ✅ Fibonacci
  - ✅ Greatest Common Divisor (Euclidean GCD)
  - ✅ Power (x^n)
  - ✅ Sum of Array (recursive)
- **Execution Controls**
  - Start ⏯ Pause ⏸ Step ⏭ Reset ↺
  - Adjustable **animation speed**
- **Learning Aids**
  - Time & Space complexity
  - **Call count** and **Execution time** metrics
- **Zero dependencies** — vanilla **HTML/CSS/JS** + Canvas API

---

## 📦 Project Structure
```
call-stack-simulator/
├─ index.html # Main UI
├─ style.css # Styling & micro-animations
├─ functions.js # Recursive algorithms
├─ stackVisualizer.js # Call stack rendering + controls
├─ treeVisualizer.js # Tree diagram rendering
├─ main.js # App bootstrapping & glue code
├─ README.md
├─ LICENSE
└─ .gitignore
```
---

## 🔧 How to Run Locally
### Option A — Super easy way
1. **Download/clone** the repo  
2. **Open `index.html`** in your browser (double-click). That’s it.

### Option B — Local server (recommended)
```bash
# Python 3
python -m http.server 5500
# or
npx serve .
```

Open http://localhost:5500
 in your browser.

---

## 🌐 Live Demo  
[![Live Demo](https://img.shields.io/badge/Visit-Call%20Stack%20Simulator-blue?style=for-the-badge)](https://itzaka-07.github.io/call-stack-simulator/)  

--- 

🧪 Try These Inputs

Factorial: n = 5

Fibonacci: n = 6 (warning: exponential calls!)

GCD: a = 48, b = 18

Power: x = 2, n = 8

Sum of Array: 1, 2, 3, 4, 5

---
🛣 Roadmap / Ideas

⏩ Memoized Fibonacci

🧩 Add more algorithms: Tower of Hanoi, QuickSort, MergeSort

🎛 UI polish: dark mode, keyboard shortcuts

💾 Export trace as JSON

---
🤝 Contributing

Pull requests are welcome!

Fork the repo

Create a feature branch

Commit changes and open a PR
