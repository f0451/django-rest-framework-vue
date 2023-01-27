# About
Website with Django (Django Rest Framework) backend and Vue frontend.

Admin panel, models and views, authorization, category filter, cart and `.vue` pages.

# Setup

Create and activate a virtual environment:

```
python -m venv .venv
.\.venv\Scripts\Activate
```
Install the required libraries for backend:
```
pip install -r requirements.txt
```
Install the required libraries for frontend:
```
npm install -g @vue/cli
cd .\f0451_vue\
npm install axios
npm install bulma
```
# Run 
Execute the following command:
```
cd .\f0451_website\
python manage.py runserver
```
After create the other terminal:
```
cd .\f0451_vue\
npm run serve
```
# Libraries 
- Django
- Django Rest Framework
- - djoser, django-cors-headers, pillow, stripe
- Vue
- - axios, bulma

