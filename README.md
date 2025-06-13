# 🔍 Implement strStr() in Python

This repository contains a Python solution for the classic **strStr()** problem — also known as **"Implement indexOf()"** — using Python's built-in `str.index()` method and exception handling.

---

## 📘 Problem Statement

Implement the function `strStr(haystack, needle)` that returns the index of the **first occurrence** of `needle` in `haystack`, or `-1` if `needle` is not part of `haystack`.

### Rules:
- Return `0` if `needle` is an empty string (as per problem definitions).
- Return `-1` if `needle` is not found.
- You **must not** use `find()` or `index()` if solving this manually — though this solution demonstrates a built-in version.

---

## 🧠 Approach

This version uses:
- Python’s built-in `str.index()` to search for `needle` in `haystack`.
- A `try-except` block to handle the `ValueError` if `needle` is not found.
