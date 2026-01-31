# ITPM Assignment 1 – Playwright Automation  
**Course:** IT3040 – IT Project Management  
**Degree:** BSc (Hons) in Information Technology  
**Year:** 3  
**Semester:** 1  

---

## 📌 Project Description

This project contains automated functional test cases for a **Singlish → Sinhala transliteration web application** using **Playwright (JavaScript)**.

The automation covers:
- 24 positive (correct behavior) scenarios  
- 10 negative (failure / incorrect behavior) scenarios  
- 1 UI-related scenario  

All scenarios are derived according to the requirements provided in the assignment brief and are **not copied from the sample template**.

---

## 🧪 Application Under Test

**Website:** https://www.swifttranslator.com/  
**Input Language:** Singlish  
**Target Language:** Sinhala  

---

## 🛠️ Technologies Used

- Node.js  
- Playwright (JavaScript)  
- VS Code  
- Chromium browser (via Playwright)

---

## 📂 Project Structure

ITPM_Assignment_1
node_modules
tests
translator-all.spec.js
playwright.config.js
package.json
package-lock.json
README.md


---

## ⚙️ Installation Instructions

### Step 1: Install prerequisites
- Install **Node.js (LTS version)**  
  👉 https://nodejs.org/

- Install **VS Code**  
  👉 https://code.visualstudio.com/

---

### Step 2: Open the project
1. Open **VS Code**
2. Click **File → Open Folder**
3. Select the project folder

---

### Step 3: Install dependencies

Open the VS Code terminal and run:

```bash
npm install
npx playwright install
