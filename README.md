# cobol-pocs

A dedicated laboratory repository within the **[ortiz-cobol-labs](https://github.com/ortiz-cobol-labs)** organization for exploring COBOL syntax, data representation, file processing routines, and build automation.

This project serves as a foundational proving ground for legacy systems engineering and structured batch programming paradigms.

```

---

## 🎯 Scope & Learning Objectives

* **Core Language Mechanics:** Mastery of COBOL syntax divisions (`IDENTIFICATION`, `ENVIRONMENT`, `DATA`, and `PROCEDURE`).
* **Data Types & Memory Layouts:** Hands-on exercises with `PICTURE` clauses, numeric usages (`COMP`, `COMP-3`), arrays/tables (`OCCURS`), and strict memory alignment.
* **File Operations:** Sequential, line-sequential, and simulated indexed file handling (reading, writing, updating records).
* **Modular Design:** Structuring data layouts via reusable Copybooks (`.cpy`) and standalone subprograms (`CALL`).

---

## 🏗️ Repository Structure

```text
.
├── src/          # COBOL source files (.cbl)
├── docs/         # Study notes and syntax references
├── Makefile      # Simple build and execution script
└── README.md

```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have **GNUCobol** (`cobc`) and **Make** installed on your system.

```bash
# Ubuntu / Debian
sudo apt update
sudo apt install open-cobol build-essential

```

### Build & Run

1. **Clone the repository:**
```bash
git clone https://github.com/ortiz-cobol-labs/cobol-pocs.git
cd cobol-pocs

```


2. **Compile and execute all POCs:**
```bash
make build
make run

```


3. **Clean build artifacts:**
```bash
make clean

```



---

## 👨‍💻 Maintainer

**Ortiz David**

*Senior Software Engineer & Systems Architect*

[GitHub Profile](https://github.com/ortizdavid) • [Portfolio](https://ortizdavid.github.io)
