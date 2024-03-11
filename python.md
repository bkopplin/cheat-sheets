
# venv [^1][^2]
Creation
```bash
python -m venv venv # creates a venv
```
Activation
```bash
# In PowerShell
venv\Scripts\Activate.ps1
# Linux
source myvenv/bin/activate
```
Deactivation
```
deactivate
```

# requirements
```
pip freeze > requirements.txt
pip install -r requirements.txt
```

# Further Reading
[^1]: [python.land](https://python.land/virtual-environments/virtualenv)
[^2]: [python venv primer](https://realpython.com/python-virtual-environments-a-primer/)
