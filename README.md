# cwd_crm

## 01 Create Project cwd_cwm

[https://www.youtube.com/watch?v=pqWyUAT38e0]

Github - Final project source code
[https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbEVBX04zaHhlQzNSUjNkaUJVaHl6dXRuc0lQZ3xBQ3Jtc0trS1J0V1BJc0o2TzMtRFhYekdfRlQ4VTg0UWs0bHdtLU12SDdIT1htcHpRZjdYbF9hZ3ZtYmNVdGtvZ0V3MVl6ZldIaTFKelJiOFgtT2FzYzF4OGZPVkx5T19DbXgzd1pudnMwd0QxU1Z3M01GVERKOA&q=https%3A%2F%2Fgithub.com%2Fcloud-with-django%2FDjango-CRM-mastery-app-Project-1-YT&v=pqWyUAT38e0]


Navbar.html - mid-way source code (code-along):
[https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbjNHOFpPajgzOXFrakE2REswZTV2R0RvVTlMQXxBQ3Jtc0trVjFuc21WS3pBcUprZllleEVaalpnQjNMQ0g2czM1NmJNWHhxSGFmVVN0amxJaXU3NmtqOXN2VFdZX0QtYnRfWVdZUGNrZVItTENkd1JsT1JSSmxnRTJUcHpQWXhIMDdrRHlUTHNuTmtPLWZwb1FrTQ&q=https%3A%2F%2Fgithub.com%2Fcloud-with-django%2FDjango-CRM-mastery-app-Project-1-YT%2Fblob%2Fmain%2Fnavbar.html&v=pqWyUAT38e0]

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
```

## 04 Create webapp\templates\webapp folder and basic empty html files

```
```

## 05 User creation and authentication = Part 1

```
```

## 06 User creation and authentication = Part 2

```bash
pip install django-crispy-forms==1.14.0
```

## 06 User creation and authentication = Part 3

```
User authentication finished
```

# 07 CRUD - Read - Part 1

```
Current: 2:26:40
```

