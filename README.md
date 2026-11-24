# Python Dasar

A hands-on practice repository covering the fundamentals of Python programming, from basic syntax to object-oriented programming, file handling, modules and packages. Each chapter is added as a separate, well-documented commit with an execution screenshot as proof of the result.



## About the Project

All example code lives in `python-dasar.py` and grows chapter by chapter. Chapters 18 and 19 also use a custom module (`kalkulator.py`) and a custom package (`perhitungan/`). The project uses only the Python standard library, so no third-party packages are required.

## Topics Covered

| Chapter | Topic | Description |
|---|---|---|
| 1 | Introduction & Python Installation | First program, checking the Python version |
| 2 | Python Program Structure | Comments, `print()`, indentation, input |
| 3 | Basic Data Types | `str`, `int`, `float`, `bool`, type casting |
| 4 | Variables | Declaration, naming rules, swapping values |
| 5 | Constants | Uppercase naming convention |
| 6 | Operators | Arithmetic, comparison, logical, assignment |
| 7 | Control Flow | `if`/`elif`/`else`, `for`, `while`, `break`, `continue` |
| 8 | Functions | Parameters, return values, default values |
| 9 | List, Tuple and Set | Ordered, immutable and unique collections |
| 10 | Dictionary | Key-value data and iteration |
| 11 | Class & Object | Attributes, constructors, methods |
| 12 | Encapsulation | Public, protected, private, `@property` |
| 13 | Inheritance | Parent and child classes, `super()` |
| 14 | Polymorphism | Method overriding |
| 15 | Abstraction | Abstract classes with `abc` |
| 16 | Exception Handling | `try`/`except`/`else`/`finally`, `raise`, custom exceptions |
| 17 | File Handling | Read, write and append files |
| 18 | Module | Built-in and custom modules |
| 19 | Package | Custom package with `__init__.py` |
| 20 | README.md & requirements.txt | Documentation and dependency list |

## Project Structure

```text
python-dasar/
├── perhitungan/
│   ├── __init__.py
│   └── kalkulator.py
├── screenshots/
├── .gitignore
├── kalkulator.py
├── python-dasar.py
├── README.md
└── requirements.txt
```

## Prerequisites

- [Python 3.8+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)
- A code editor such as [Visual Studio Code](https://code.visualstudio.com/)

```bash
python --version
git --version
```

## Installation

```bash
git clone https://github.com/kaylaccccc/python-dasar.git
cd python-dasar
python -m venv venv
venv\Scripts\activate
python -m pip install -r requirements.txt
```

On macOS / Linux, activate with `source venv/bin/activate`.

## Usage

```bash
python python-dasar.py
```

Chapter 17 creates a `catatan.txt` file in the working directory. It is listed in `.gitignore`.

## Screenshots

| Chapter | Screenshot |
|---|---|
| 1. Introduction & Python Installation | [bab01](screenshots/bab01-pengenalan-instalasi-python.png) |
| 2. Python Program Structure | [bab02](screenshots/bab02-struktur-dasar-program.png) |
| 3. Basic Data Types | [bab03](screenshots/bab03-tipe-data-dasar.png) |
| 4. Variables | [bab04](screenshots/bab04-variable.png) |
| 5. Constants | [bab05](screenshots/bab05-konstanta.png) |
| 6. Operators | [bab06](screenshots/bab06-operator.png) |
| 7. Control Flow | [bab07](screenshots/bab07-control-flow.png) |
| 8. Functions | [bab08](screenshots/bab08-function.png) |
| 9. List, Tuple and Set | [bab09](screenshots/bab09-list-tuple-set.png) |
| 10. Dictionary | [bab10](screenshots/bab10-dictionary.png) |
| 11. Class & Object | [bab11](screenshots/bab11-class-object.png) |
| 12. Encapsulation | [bab12](screenshots/bab12-encapsulation.png) |
| 13. Inheritance | [bab13](screenshots/bab13-inheritance.png) |
| 14. Polymorphism | [bab14](screenshots/bab14-polymorphism.png) |
| 15. Abstraction | [bab15](screenshots/bab15-abstraction.png) |
| 16. Exception Handling | [bab16](screenshots/bab16-exception-handling.png) |
| 17. File Handling | [bab17](screenshots/bab17-file-handling.png) |
| 18. Module | [bab18](screenshots/bab18-module.png) |
| 19. Package | [bab19](screenshots/bab19-package.png) |
| 20. README.md & requirements.txt | [bab20](screenshots/bab20-readme-requirements.png) |

## Commit Convention

This project follows the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```text
<type>(<scope>): <short description>

- <detail 1>
- <detail 2>

Refs: <reference>
```

| Type | Purpose |
|---|---|
| `feat` | Adding new code or examples |
| `chore` | Configuration and repository setup |
| `docs` | Documentation changes |

## Author

**kaylaccccc**

- GitHub: [@kaylaccccc](https://github.com/kaylaccccc)