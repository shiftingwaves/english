# Virtual Environment Setup Instructions

---

## Ubuntu/Linux Commands

**Create a virtual environment**
```bash
python3 -m venv .venv
```

**Activate the virtual environment**
```bash
source .venv/bin/activate
```

**Install the requirements**
```bash
pip install -r requirements.txt
```

**Update Packages**
```bash
pip3 install --upgrade -r requirements.txt
```

**Check if the virtual environment is activated**
```bash
which python
```

**Deactivate the virtual environment**
```bash
deactivate
```

**Remove the virtual environment**
```bash
rm -rf .venv
```



---

## Windows Commands

**Create a virtual environment**
```cmd
python -m venv .venv
```

**Activate the virtual environment**
```cmd
.venv\Scripts\activate
```

**Install the requirements**
```cmd
pip install -r requirements.txt
```
**Update Packages**
```cmd
pip install --upgrade -r requirements.txt
```

**Check if the virtual environment is activated**
```cmd
where python
```


**Deactivate the virtual environment**
```cmd
deactivate
```

**Remove the virtual environment**
```cmd
rmdir /s /q .venv
```

