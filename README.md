# DataFun-07-ML

## Project Overview

This is a guided machine learning project created for **Module 7** of the Data Analytics course. The purpose of this project is to explore applied data analysis using Python tools such as Jupyter notebooks, NumPy, Pandas, Matplotlib, and more.

There is no strict specification for this project; instructions and tasks are introduced gradually as we work through the module. The project emphasizes exploratory data work and basic machine learning workflows.

---

## Setup and Workflow

### 1. Repository Creation

- Created a new GitHub repo named `datafun-07-ml` with a default `README.md`.
- Cloned it locally into the `Documents` folder:
  ```bash
  git clone https://github.com/your-username/datafun-07-ml.git
  cd datafun-07-ml
  ```

- Opened the folder in VS Code.

### 2. .gitignore Setup

Added a `.gitignore` file with the following entries:
```
.vscode/
.venv/
.ipynb_checkpoints/
__pycache__/
```

### 3. First Commit and Push

```bash
git add .
git commit -m "Initial commit: project setup and .gitignore"
git push -u origin main
```

Repository verified at: [https://github.com/your-username/datafun-07-ml](https://github.com/your-username/datafun-07-ml)

---

## Virtual Environment Setup

### 1. Create the Environment

```bash
py -m venv .venv
```

### 2. Activate the Environment

- **Windows (PowerShell):**
  ```powershell
  .venv\Scripts\Activate.ps1
  ```
- **Mac/Linux (bash/zsh):**
  ```bash
  source .venv/bin/activate
  ```

### 3. Install Required Packages

```bash
py -m pip install --upgrade pip
py -m pip install jupyterlab numpy pandas pyarrow matplotlib seaborn scipy
```

Optionally, export installed packages:

```bash
py -m pip freeze > requirements.txt
```

---

## Running the Project

To start JupyterLab and work on your notebooks:

```bash
jupyter lab
```

Open `.ipynb` files inside JupyterLab to run and explore data analysis or machine learning experiments.

---

## Git Commands Reference

To track your changes and push updates to GitHub:

```bash
git add .
git commit -m "Your descriptive message here"
git push
```
