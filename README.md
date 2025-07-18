# CMPT 276 Tutorial 7 – Automated Testing & CI/CD Demo

This repository contains the demo materials for Tutorial 7 of CMPT 276, focusing on introducing automated testing and continuous integration (CI) using GitHub Actions.

---

## Objectives

- Demonstrate how to add basic testing and automation to a simple web project (HTML, CSS, JS).
- Learn to configure GitHub Actions for automated testing upon push or pull request.
- Understand the basic flow of CI/CD for front-end projects.

---

## Project Structure
```
CMPT276-Tut-7/
├── .github/
│ └── workflows/
│ └── ci.yml # GitHub Actions workflow for CI
├── index.html # Main demo webpage
├── style.css # Basic styling
├── tutorial-html-css.markdown # Tutorial instructions
└── README.md # This file
```

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/kyon317/CMPT276-Tut-7.git
cd CMPT276-Tut-7

# If you have Python installed
python -m http.server
