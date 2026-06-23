# Python-IA

Some work I've done with python for systems that are knowledge based as well as techniques to represent knowledge.

## Virtual environment setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install jupyter ipykernel
python -m ipykernel install --user --name python-ai --display-name "Python-AI (.venv)"
```

The `ipykernel install` step makes your virtual environment selectable inside Jupyter as `Python-AI (.venv)`, so notebooks run with this project's packages instead of a global Python interpreter.

## Notebooks

A couple of starter notebooks are available in `/notebooks`:

- `notebooks/01_intro.ipynb`
- `notebooks/02_knowledge_basics.ipynb`

Run Jupyter from the project root:

```bash
jupyter notebook
```
