# PythonPrograms

DevOps Assignment 3 — 20 common Python programs with `assert`-based test cases.

This project features Python applications, unit testing, Docker containerization, and CI/CD pipeline automation.

## Layout

```text
Python-Programs/
├── Code/         01_even_odd.py ... 20_word_frequency.py
└── Test_Code/    test_01_even_odd.py ... test_20_word_frequency.py
```

## Running a Test

From the repository root, run:

```bash
python Test_Code/test_01_even_odd.py
```

Expected output: `All test cases passed.`

Alternatively, run all tests using pytest:

```bash
pytest Test_Code/ -v
```
