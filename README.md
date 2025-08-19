# 📘 proyecto Analisis de datos



## ⚙️ Requirements
- [Python 3.10+](https://www.python.org/)  
- [uv package manager](https://github.com/astral-sh/uv)  
- [VS Code](https://code.visualstudio.com/) with the **Python** and **Jupyter** extensions  

---

## 🚀 Setup

Clone the repository:
```bash
git clone https://github.com/sam2800ml/Proyecto-Anlisis-de-datos-1
```

1. Install dependencies with uv
```bash
uv sync
```
This will create a .venv/ folder with all the required dependencies defined in pyproject.toml and locked in uv.lock.

2. Register the Jupyter kernel
```bash
uv run python -m ipykernel install --user --name=project-name --display-name "Python (project-name)"
```
--name=project-name → internal ID (use your project name)
--display-name → what will appear in VS Code’s kernel picker

3. Open in VS Code

Open the project folder in VS Code.
Open any .ipynb file.
Select the kernel Python (project-name) from the top-right kernel picker.