# Automata Programming Assignments
Collection of Automata Programming Assignments under Sir Bobby Sebial.

## Instructions

### 1. cd into directory
```bash
cd name-of-directory
```

### 2. Create venv
```bash
python -m venv venv
```

### 3. Activate venv
```bash
# Windows
.\venv\bin\activate

# Linux
source venv/bin/activate
```

### 4. Install requirements
```bash
pip install -r requirements.txt
```

### 5. Run program
```bash
python .\main.py
```

### 6. Build program
```bash
pyinstaller --onefile --noconsole main.py
```

### 7. Run output .exe file
```bash
.\dist\main.exe
```

---

## Extra Info

### Generate requirements.txt
```bash
pip freeze > requirements.txt
```