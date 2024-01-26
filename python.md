
# venv
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
## further reading
Guide from [python.land](https://python.land/virtual-environments/virtualenv) and [python venv primer](https://realpython.com/python-virtual-environments-a-primer/)

# requirements
```
pip freeze > requirements.txt
pip install -r requirements.txt
```
