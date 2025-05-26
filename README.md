# 🧪 Palindrome Sign Checker

A simple JavaScript application that checks if any of the provided signs (text inputs) is a **palindrome**. If at least one palindrome is found, it displays `"OPEN"`; otherwise, it shows `"TRASH"`.

## 📋 What is a Palindrome?

A **palindrome** is a word, phrase, or sequence that reads the same backward as forward (ignoring spaces, punctuation, and capitalization).

Examples:
- `RACECAR`
- `MADAM`
- `A MAN A PLAN A CANAL PANAMA`

## 🔍 Project Features

- Checks 4 user-provided input fields for palindromes.
- Displays either:
  - `OPEN` – if at least one palindrome is found ✅
  - `TRASH` – if no palindromes are found ❌
- Includes unit tests for both the palindrome checker and sign validator.
- Tests run in the browser console instead of modifying the DOM.

## 🛠️ How to Use

1. Open the HTML file in your browser.
2. Enter text into the four input boxes.
3. Click the **"Check Signs"** button to see the result.
4. Run `runTests()` in the browser console to verify logic correctness.

## 🧪 Testing

All tests are logged to the **browser console**, not the page itself. You can see results by:
- Opening **Developer Tools (F12)**.
- Going to the **Console** tab.
- Typing `runTests()` and pressing Enter.

---

### 🎯 Purpose

This project demonstrates:
- String manipulation in JavaScript.
- Conditional logic based on input.
- Writing and running basic unit tests in the browser.
