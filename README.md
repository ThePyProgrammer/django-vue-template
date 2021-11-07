# Django + Vue Template

In this template, we introduce a Vue.js and Django REST Framework Integration.

## How to Run

### Server

Install all packages:

```sh
cd server
pip install django djangorestframework gunicorn whitenoise dj-database-url psycopg2-binary
```

Now, we run the server:

```sh
python manage.py runserver
```

### Client

Install all packages:

```sh
cd client
yarn install
```

Run the application:

```sh
npm run serve
```

This should give you the final application.
