# Django dev steps

python -m venv .venv

VS Code ext: Python Auto Venv

.gitignore
    .venv/
    .vscode/

pip freeze > _requirements.txt
    {% de repetat de fiecare data cand instalez ceva %}

pip install Django==3.2.3

---
($      indicate the linux shell prompt)<br>
(...\>  indicate windows command prompt)

VS Code ext: PowerShell (il propune VSC dupa ce rulezi ceva in $ shell propmt)

...\>  python
import django
print(django.get_version())
>>>3.2.3
---
sau
...\> python -m django --version
>>>3.2.3
---

<https://docs.djangoproject.com/en/3.2/intro/tutorial01/>

...\>  django-admin startproject dj1_app (creaza un nou proiect, folder, init, manage, etc)

---

settings.py: ALLOWED_HOSTS = ['192.168.0.123']

python manage.py runserver 192.168.0.123:8000

---
