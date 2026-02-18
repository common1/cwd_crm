# cwd_crm

## 01 Create Project cwd_cwm

[https://www.youtube.com/watch?v=pqWyUAT38e0]

```bash
mkdir cwd_crm
cd cwd_crm
python -m venv .venv
# Windows
.venv\Scripts\activate
pip install django
django-admin startproject cwd_crm .
```
## 02 Create app webapp

```bash
django-admin startapp webapp

python manage.py migrate 
python manage.py createsuperuser
python manage.py runserver
```

## 03 Create webapp urls.py

```
File: settings.py
STATICFILES_DIRS = [BASE_DIR / 'static']

Create webapp\templates\webapp folder
```

Current: 44:35

