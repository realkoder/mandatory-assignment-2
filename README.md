# PYTHON - Session 12 - Mandatory Assignment 2


### Virtual environment

```bash
# python -m venv venv
python -m venv <name>
```

To activate venv:
```bash
     source myenv/bin/activate
```

To deactivate virtual environment:
```bash
deactivate
```


Install the ipykernel package in your venv after it's instantiated to connect your Python virtual environment to a Jupyter notebook:
```bash
pip install ipykernel
```

Create a kernel using the Python interpreter from your virtual environment.
```bash
python -m ipykernel install --user --name=<your-virtual-environment-name>
```