# Python Learning Notebooks 🐍

A structured, beginner-friendly Python learning path made of 18 Jupyter notebooks. All notebook explanations, examples, comments, and exercises are written in English. Each notebook includes runnable demonstrations, practical edge cases, common errors and exceptions, practice tasks, suggested solutions, and key takeaways. Examples are intentionally short and focused rather than long projects.

## Learning roadmap

| # | Folder | Topics |
|---:|---|---|
| 1 | `1. Introduction` | What Python is, first program, comments, values and types |
| 2 | `2. Numbers & Operators` | Numeric types, arithmetic, comparisons, logic, identity, membership, bitwise operations, precedence |
| 3 | `3. Variable & Assignment` | Names, assignment, unpacking, type conversion, object references |
| 4 | `4. Input` | `input()`, conversion, cleaning, validation |
| 5 | `5. Strings` | Indexing, slicing, methods, f-strings, immutability |
| 6 | `6. Lists` | Indexing, mutation, methods, copying, comprehensions |
| 7 | `7. Tuple` | Immutable sequences, unpacking, tuple operations |
| 8 | `8. Set` | Unique values, set operations, membership, frozen sets |
| 9 | `9. Dictionary` | Key-value data, iteration, nested mappings, comprehensions |
| 10 | `10. Condition` | `if`, `elif`, `else`, Boolean logic, truthiness |
| 11 | `11. Loop` | `for`, `while`, `range`, `break`, `continue`, `enumerate`, `zip` |
| 12 | `12. Function` | Parameters, return values, defaults, `*args`, `**kwargs`, type hints |
| 13 | `13. Generator` | Iterables, `yield`, lazy evaluation, generator expressions |
| 14 | `14. Modules & Packages` | Imports, standard library, custom modules, packages, virtual environments |
| 15 | `15. Regex` | Pattern syntax, search, extraction, replacement, validation limitations |
| 16 | `16. File Handling` | Text files, file modes, paths, CSV, JSON |
| 17 | `17. Exception Handling` | `try`, `except`, `else`, `finally`, raising and custom exceptions |
| 18 | `18. Object Oriented Programming` | Classes, instances, methods, properties, inheritance, dataclasses, composition |

## Getting started

### Option A: Use Jupyter locally

1. Install Python 3.10 or newer.
2. Create and activate a virtual environment if you want an isolated setup.
3. Install Jupyter:

   ```bash
   python -m pip install notebook
   ```

4. Start Jupyter from the project directory:

   ```bash
   jupyter notebook
   ```

5. Open `01_introduction.ipynb` inside `1. Introduction` and run the cells from top to bottom.

### Option B: Use VS Code or a hosted notebook service

Open a notebook with a Python/Jupyter-enabled editor or upload an `.ipynb` file to a notebook service that supports Jupyter notebooks. Follow the cells in numerical order.

## Recommended learning routine

1. Read a concept and predict the output of the next code cell.
2. Run the code and compare the actual result with your prediction.
3. Change values, names, or conditions and run it again.
4. Complete the practice tasks before checking the suggested solutions.
5. Keep your own notes and commit your progress to Git.

## Design choices

- **English throughout:** explanations, code comments, identifiers, and exercises are in English.
- **Beginner-first:** concepts are introduced in a deliberate sequence, with small examples before broader applications.
- **Runnable examples:** code cells use Python's standard library and are intended to work in a typical Python 3.10+ environment.
- **Safe file exercises:** examples that create files use temporary directories so that running a notebook does not leave sample data scattered throughout the repository.
- **No mandatory third-party data libraries:** the core learning path does not require NumPy, pandas, or other third-party packages.

## Project structure

```text
python-learning-notebooks/
├── README.md
├── 1. Introduction/
│   └── 01_introduction.ipynb
├── 2. Numbers & Operators/
│   └── 02_numbers_and_operators.ipynb
├── 3. Variable & Assignment/
│   └── 03_variable_and_assignment.ipynb
├── 4. Input/
│   └── 04_input.ipynb
├── 5. Strings/
│   └── 05_strings.ipynb
├── 6. Lists/
│   └── 06_lists.ipynb
├── 7. Tuple/
│   └── 07_tuple.ipynb
├── 8. Set/
│   └── 08_set.ipynb
├── 9. Dictionary/
│   └── 09_dictionary.ipynb
├── 10. Condition/
│   └── 10_condition.ipynb
├── 11. Loop/
│   └── 11_loop.ipynb
├── 12. Function/
│   └── 12_function.ipynb
├── 13. Generator/
│   └── 13_generator.ipynb
├── 14. Modules & Packages/
│   └── 14_modules_and_packages.ipynb
├── 15. Regex/
│   └── 15_regex.ipynb
├── 16. File Handling/
│   └── 16_file_handling.ipynb
├── 17. Exception Handling/
│   └── 17_exception_handling.ipynb
└── 18. Object Oriented Programming/
    └── 18_object_oriented_programming.ipynb
```

## Notes

- Input examples are kept non-interactive by default so automated execution does not pause for keyboard input; a commented `input()` example is provided for manual experimentation.
- Some outputs such as set display order or the current date may vary between runs.
- Suggested solutions are illustrative. Try to develop your own solution before checking them.

## License

No license has been selected for this repository yet. Add a license file if you want to specify how others may reuse the material.
