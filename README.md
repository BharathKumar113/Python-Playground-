---

# Python Playground

A Browser-Based Python IDE with Canvas-Style Layout

## Overview

Python Playground is a lightweight Python IDE that runs entirely in the browser using **Pyodide (Python compiled to WebAssembly)**. It uses a **canvas-style split layout** to provide a desktop-like coding experience directly on both desktop and mobile screens.

Everything is executed client-side in the browser. No backend server or installation is required.

---

## Why It’s Useful on Mobile Screens

* The **canvas-style layout** makes the editor and console adjustable even on small screens.
* Panels can be **dragged and resized by touch**, providing flexibility.
* The design is fully responsive, adapting automatically to phone and tablet displays.
* Code is saved in the browser using LocalStorage, so you can continue from where you left off.
* No apps or software are needed — just open in your mobile browser.

---

## How the Canvas Layout Works

* The IDE is structured like a **drawing canvas**, where panels (editor and console) are positioned and controlled dynamically.
* **Resizable split panels** allow users to allocate more space to code or output as needed.
* The layout is built with **HTML, CSS Flexbox, and JavaScript**, simulating a canvas where each component behaves like a draggable box.
* CodeMirror is integrated into the canvas for syntax highlighting and editing.
* Pyodide is embedded to run Python directly inside the same canvas workspace.

This combination creates a self-contained, IDE-like canvas where users can interact fluidly.

---

## Features

* Multi-tab Python editor with CodeMirror.
* Canvas-style split panels with drag and resize support.
* Run Python code instantly with Pyodide.
* Install additional Python packages using micropip.
* Error detection with highlighted lines.
* Save, load, and download code directly in the browser.
* Light and dark theme support.

---

## User Guide

### Run Online (Recommended)

1. Open the demo link in any browser:

   ```
   https://BharathKumar113.github.com/Python-Playground/
   ```
2. Start coding directly in the editor panel.
3. Press `Run` or `Ctrl + Enter` to execute Python.
4. Drag the border between editor and console to adjust space on mobile.
5. Save or download your code as needed.

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Python-Playground.git
   cd Python-Playground
   ```
2. Open `index.html` in a browser.
3. The IDE will load, and the canvas-style layout will be available for use.

---

## Tech Stack

* HTML5, CSS3, JavaScript (Canvas layout with flex and draggable panels)
* CodeMirror (editor)
* Pyodide (Python runtime in WebAssembly)
* LocalStorage (persistent saving in browser)

---

## Use Cases

* Learning Python on mobile devices.
* Running quick code snippets without installing Python.
* Teaching Python interactively in classrooms.
* Sharing code that runs entirely in-browser.

---
