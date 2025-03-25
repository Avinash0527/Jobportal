<div align="center">

<img src="./screenshots/illustration.png" alt="Job Interview" width="300" height="356.5">

# Django Job Portal

</div>

## Django Job Portal

#### An open source online job portal.



Used Tech Stack

1. Django
2. Sqlite

#### Install

1. Create a virtual environment

    `python -m venv envi`

2. Activate it

    ` envi\scripts\activate`

3. Clone the repository and install the packages in the virtual env:

    `pip install -r requirements.txt`

#### Run

1.With the venv activate it, execute:

    python manage.py collectstatic

*Note* : Collect static is not necessary when debug is True (in dev mode)

2. Create initial database:

  `python manage.py makemigrations`
   
    `python manage.py migrate'

5. Run server:

    `python manage.py runserver`

6. Default django admin credentials:

    `email: admin@admin.com`
    `password: admin`

#### Run test:
``python manage.py test``


