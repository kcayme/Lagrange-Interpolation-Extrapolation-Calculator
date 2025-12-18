# Lagrange Interpolation–Extrapolation Calculator

This Python application performs Lagrange interpolation and extrapolation using numerical data and provides visual output.

---

## Prerequisites

Before running the application, ensure the following requirements are met:

- **Python 3.9 or higher**

---

## Setup

### Clone Repository

```bash
git clone https://github.com/kcayme/Lagrange-Interpolation---Extrapolation-Calculator.git
cd <repository-directory>
```

---

### Option 1 (Recommended): Use `uv`

[uv](https://docs.astral.sh/uv/https://docs.astral.sh/uv/) alternative to pip.

---

#### Install `uv` (if not yet installed)

```bash
pip install uv
```

Verify installation:

```bash
uv --version
```

---

#### Sync and Install Dependencies

If the repository already contains `pyproject.toml` and `uv.lock`:

```bash
uv sync
```

---

#### Run Application

```bash
uv run python main.py
```

---

### Run the Application

Run the Python application using the managed environment:

```bash
uv run python <filename>.py
```

---

## Option 2: Using `pip`

If you prefer the traditional `pip` workflow, you may install dependencies manually.

### (Optional) Update Package Tools

```bash
pip install --upgrade pip setuptools wheel
```

---

### Install Dependencies

```bash
pip install numpy pandas matplotlib
```

---

### Run the Application

```bash
python <filename>.py
```

---
