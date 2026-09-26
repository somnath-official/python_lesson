# 100 Days of Python

A day-by-day Python learning journey built with Jupyter notebooks. Each day is a
self-contained folder containing the lesson notebook(s) and hands-on challenges
that reinforce the concepts covered.

**Status:** Days 1–4 complete — ongoing.

## Progress

| Day | Topic | Lessons | Challenges | Status |
| --- | --- | --- | --- | --- |
| 1 | [Variables and Printing](day_1/README.md) | 1 | 2 | ✅ |
| 2 | [Data Types and Type Conversion](day_2/README.md) | 1 | 1 | ✅ |
| 3 | [Operators and Control Flow](day_3/README.md) | 2 | 7 | ✅ |
| 4 | [Python Lists](day_4/README.md) | 1 | 0 | ✅ |

## Curriculum

### Day 1 — Python Variables and Printing
Printing output, variables, user input, f-strings, and `len()`.

### Day 2 — Python Data Types and Type Conversion
Built-in data types, mutable vs immutable types, and explicit/implicit type
conversion. Includes handling conversion errors with `try`/`except`.

### Day 3 — Python Operators and Control Flow
Arithmetic, comparison, assignment, logical, bitwise, membership, identity, and
unary operators. Conditionals (`if`/`elif`/`else`), loops (`for`, `while`), and
jump statements (`break`, `continue`, `pass`).

### Day 4 — Python Lists
Creating and indexing lists (including negative indexing), mutability, adding and
removing elements, slicing, built-in functions and list methods, membership
checks, looping, and nested lists.

## Repository Structure

```
.
├── day_1/
│   ├── README.md
│   ├── python_variables_and_printing.ipynb
│   └── challenges/
├── day_2/
│   ├── README.md
│   ├── python_data_types_and_type_conversion.ipynb
│   └── challenges/
├── day_3/
│   ├── README.md
│   ├── python_operators.ipynb
│   ├── python_control_flow.ipynb
│   └── challenges/
└── day_4/
    ├── README.md
    └── python_lists.ipynb
```

Every day follows the same layout: a `README.md` describing the day's topics, a
lesson notebook (or notebooks), and a `challenges/` folder with small practice
problems.

## Getting Started

Requires **Python 3.12**. The `.venv/` directory is gitignored, so set up the
environment after cloning.

```bash
git clone git@github.com:somnath-official/python_lesson.git
cd python_lesson

python3.12 -m venv .venv
source .venv/bin/activate
```

Install `ipykernel` so Jupyter and VS Code can execute the notebooks:

```bash
pip install ipykernel
```

That is all that is required. Each notebook records its kernel as `python3`,
which resolves to the `python3` kernelspec created inside `.venv` — so the
notebooks run against the virtual environment automatically, with no manual
kernel registration. VS Code additionally labels this kernel `.venv (3.12.3)` in
the kernel picker.

Optionally install a Jupyter server to browse the notebooks in a browser:

```bash
pip install notebook
```

> **Note:** `ipykernel` alone is enough if you use VS Code's Jupyter extension.
> `notebook` or `jupyterlab` is only needed for a browser-based server.

## How to Run

With the environment activated, from the repository root:

```bash
jupyter notebook
```

Other options:

- `jupyter lab` — if you prefer JupyterLab
- **VS Code** — open the repository folder and run cells directly with the
  Jupyter extension; select the `.venv (3.12.3)` kernel
- Run each notebook top to bottom, or cell by cell, and answer the `input()`
  prompts in the console

## License

Released under the [MIT License](LICENSE). Copyright (c) 2026 Somnath Sardar.
