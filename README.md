# 🐍 Python CI Project with GitHub Actions

This project demonstrates **Continuous Integration (CI)** using **GitHub Actions** for a Python application. It includes automated linting and testing to ensure code quality and stability on every push or pull request.

---

## 📂 Project Overview

- Python project with CI pipeline using **GitHub Actions**
- Linting integrated with `pylint`
- Testing handled using `pytest`
- Pipeline runs automatically on every `push` or `pull_request` event

---

## 🐞 Issues Faced During Setup

### ❌ 1. Linting Errors (pylint)

- Multiple `pylint` issues were reported initially such as:
  - Unused imports
  - Incorrect naming conventions
  - Line length violations
- These were fixed to ensure code follows proper Python coding standards.

### ❌ 2. Testing Errors (test_main.py)

- Tests failed initially due to:
  - Assertion errors
  - Incorrect expected values
- The logic and tests were corrected, and all tests now pass successfully.

---

## ✅ Final Result

- The CI pipeline runs **automatically** on every commit.
- Both **linting and testing steps pass successfully**.
- GitHub Actions shows a green check ✅ once all jobs complete.

⚠️ **Note:** This project currently has only CI (no deployment yet). Deployment can be integrated later using platforms like Heroku, AWS, or Netlify.

---


