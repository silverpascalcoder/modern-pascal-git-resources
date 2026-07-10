# **modernpascal.gitignore**

A clean, practical `.gitignore` file tailored specifically for **Modern Pascal**, **FreePascal**, **Delphi‑style projects**, and **Pascal developers using Git**.   This repository provides a ready‑to‑use ignore list that keeps your repositories tidy, avoids accidental binary commits, and supports cross‑platform workflows.

---

## **What this repository contains**
- A complete **Modern Pascal–friendly `.gitignore`**  
- Patterns for:
  - Pascal build artifacts  
  - FreePascal / FPC output directories  
  - Lazarus intermediate files  
  - Temporary compiler files  
  - OS‑specific clutter (Windows, macOS, Linux)  
- Clean structure designed for cross‑platform development  
- Comments explaining *why* each ignore rule exists

---

## **🎯 Why this `.gitignore` matters**
Pascal projects often generate:

- `.ppu`, `.o`, `.a`, `.or`, `.rsj`  
- Build folders like `lib/`, `tmp/`, `backup/`  
- Lazarus `.lps` session files  
- IDE caches  
- Platform‑specific noise  

Accidentally committing these slows down repositories, bloats history, and causes merge conflicts.  
This `.gitignore` solves that problem with a **minimal, modern, Pascal‑focused rule set**.

---

## **🚀 How to use it**
### **Option 1 — Copy directly**
Download `modernpascal.gitignore` and place it in the root of your project. Make sure you rename to .gitignore

### **Option 2 — Use it globally**
```
git config --global core.excludesfile ~/.gitignore_global
```
Then copy the contents into `~/.gitignore_global`.

### **Option 3 — Extend it**
Add project‑specific rules such as:

- `/bin/`  
- `/dist/`  
- `/vendor/`  
- `/config/`  

This file is intentionally minimal so you can build on it.

---

## **For Modern Pascal Developers**
This file is designed for:

- Modern Pascal CLI projects  
- FreePascal / FPC workflows  
- Lazarus IDE users  
- HTMX + Pascal web apps  
- Cross‑platform builds  
- Educational and demo projects  

If you’re teaching Pascal, building tools, or maintaining long‑term projects, this `.gitignore` gives you a clean foundation.

---

## **Contributing**
Pull requests are welcome — especially improvements for:

- Additional Pascal toolchains  
- Lazarus / Delphi edge cases  
- Cross‑platform build directories  
- Editor/IDE support (VS Code, JetBrains, etc.)
