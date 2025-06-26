🔐 Password Strength Checker

A simple command-line tool written in Python to evaluate the strength of user-provided passwords based on length, character variety, and entropy. Designed for beginner cybersecurity learners to understand password security principles and practice regex and CLI scripting.

## 📌 Features

- Checks for:
  - Minimum length
  - Presence of uppercase, lowercase, digits, and special characters
  - Common patterns and repetitions
  - Estimated entropy
- Provides feedback and strength rating (Weak – Medium – Strong – Very Strong)
- Hides user input for security (`getpass` module)
- Lightweight and easy to run in terminal

## 💻 Technologies Used

- Python 3.x
- `re` (Regex for pattern matching)
- `getpass` (Secure password input)
- `math` (for entropy calculation)

## 🚀 How to Run

```bash
python3 password_checker.py 
```
📚 Learning Objectives
Practice regex and control flow in Python

Understand password strength metrics

Build logic-based CLI tools as an entry-level cybersecurity exercise

🧑‍💻 Author

- Chí Công – Entry-level Cyber Security
