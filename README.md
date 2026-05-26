# CSharp-Notes

A learning repository for **C# Level 1** material. It includes:

- Concept notebooks for core C# syntax and fundamentals.
- Multiple Windows Forms practice projects (small apps and UI exercises).

---

## Repository Structure

```text
CSharp-Notes/
├── 14 - C# - Level 1/
│   ├── Main Syntax/         # Jupyter notebooks for C# basics
│   └── Windows Forms/       # Desktop app practice projects
├── auto commit.sh
└── .gitignore
```

---

## Prerequisites

To work with this repository locally:

- **.NET SDK** (for project restore/build tooling)
- **Visual Studio** (recommended for Windows Forms .NET Framework projects)
- **.NET Framework 4.8.1 Developer Pack** (required by several WinForms projects)
- Optional: **Jupyter** environment if you want to open the `.ipynb` files

> Note: In non-Windows environments, building WinForms projects that target `.NET Framework 4.8.1` may fail due to missing reference assemblies.

---

## Quick Start

### 1) Explore C# notebooks

Open files inside:

- `14 - C# - Level 1/Main Syntax/`

### 2) Run a Windows Forms project

1. Open a `.csproj` file from `14 - C# - Level 1/Windows Forms/` in Visual Studio.
2. Restore dependencies (if prompted).
3. Build and run (`F5`).

---

## Main Syntax Notebook Index

Location: `14 - C# - Level 1/Main Syntax/`

- `Hello C-Sharp.ipynb`
- `VarsAndDataType.ipynb`
- `Output.ipynb`
- `User Input.ipynb`
- `Type Casting.ipynb`
- `Operators.ipynb`
- `Control Flow.ipynb`
- `C# Strings.ipynb`
- `C# Methods.ipynb`
- `C# Math.ipynb`
- `Arrays.ipynb`
- `Date & Time.ipynb`
- `Exceptions And Rand.ipynb`
- `Problems_For_Training.ipynb`

---

## Windows Forms Project Index

Location: `14 - C# - Level 1/Windows Forms/`

### Named projects

- `Calculator`
- `Drawing`
- `Pizzza` (Pizza app exercises)
- `Simple Encryption`
- `SimpleCafeShop`
- `TheGaemForm` (TheGameForm)
- `Tic-Tac-Toe Refactored Ver`
- `Tic-Tac-Toe2`
- `To-Do-List`
- `Windows Power`

### Practice/sandbox projects

- `WindowsFormsApp`
- `WindowsFormsApp1` → `WindowsFormsApp16`

### Additional folder

- `SharedProject1` (shared/auxiliary folder)

---

## Existing Project-Specific Documentation

Some projects include dedicated readmes:

- `14 - C# - Level 1/Windows Forms/Tic-Tac-Toe Refactored Ver/README.md`
- `14 - C# - Level 1/Windows Forms/Tic-Tac-Toe Refactored Ver/Tic-Tac-Toe Game initial ver/packages/FastUI.WinForms.1.1.0/README.md`
- `14 - C# - Level 1/Windows Forms/Tic-Tac-Toe2/packages/FastUI.WinForms.1.1.0/README.md`
- `14 - C# - Level 1/Windows Forms/To-Do-List/README.md`
- `14 - C# - Level 1/Windows Forms/Windows Power/README.md`
- `14 - C# - Level 1/Windows Forms/WindowsFormsApp4/packages/FastUI.WinForms.1.1.0/README.md`

---

## Build Notes

A representative build check was run for:

- `14 - C# - Level 1/Windows Forms/To-Do-List/To-Do-List.csproj`

Current environment result:

- Fails with `MSB3644` because `.NETFramework,Version=v4.8.1` reference assemblies are not available in this Linux-based environment.

---

## Goal of This Repository

This repository is intended as a personal/course-style progression through C# fundamentals and Windows Forms practice, with many small projects used to learn syntax, events, UI controls, and application flow.
