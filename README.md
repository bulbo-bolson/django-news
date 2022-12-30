

## Fixes
- Fix para el error: **ModuleNotFoundError: No module named 'crispy_forms'**
  - Ejecutar asi el comando: `.venv/bin/python manage.py runserver`
  - [Fuente](https://www.pythonanywhere.com/forums/topic/14060/) 
  - Parece que el paquete crispy forms jode el interprete del virutalenv?
