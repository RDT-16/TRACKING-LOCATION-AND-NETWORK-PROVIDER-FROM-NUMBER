# 📱 Phone Number Tracker using Python

This Python-based automation tool traces the **country location** and **network provider** of any phone number worldwide using the `phonenumbers` library.

---

## 🔍 Problem Statement

Python is a powerful language for automation, capable of tasks like messaging, web scraping, machine learning, and more.  
In this project, we focus on:

- Identifying the **geographic location** (country) of a phone number.
- Determining the **network/service provider** from the number.

---

## 🧪 Methodology / Procedure

1. **Create Project in PyCharm**
   - Open PyCharm → File → New Project → Name it (e.g., `tracking`)
   - Right-click project → New → Python File → `main.py`

2. **Install Required Library**
   - Open the terminal in PyCharm and run:
     ```bash
     pip install phonenumbers
     ```

3. **Create Files**
   - `text.py`: Contains the phone number to track.
   - `body.py`: Imports and analyzes the number.

---

## 🧾 Code Overview

### `text.py`

```python
number = "+XXXXXXXXXXXX"  # Replace with a valid number
