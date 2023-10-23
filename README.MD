# Django Blog Website
This is a Django Blog Website.

Reference: [Django Tutorials - Corey Schafer](https://www.youtube.com/playlist?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p)

## Features

- Home page.
- About page.
- Admin page
- User Profile
- User register, login, logout.
- User reset password.
- Update username, email, and profile image.
- View all user posts.
- Create a new post.
- Update post.
- Delete post.

## Requirements

- asgiref: 3.7.2
- crispy-bootstrap4: 2023.1
- Django: 4.2.6
- django-crispy-forms: 2.1
- Pillow: 10.1.0
- sqlparse: 0.4.4
- tzdata: 2023.3

## Installation and Run

Download source code from Github: `https://github.com/Nanashi0it/django_blog.git`

**NOTE BEFORE RUNNING PROJECT:**

Before running the application you need to create some environment variables for the **password reset** function:

- `EMAIL_USER` for `EMAIL_HOST_USER`: Email address that is used to send password reset email.
- `EMAIL_PASSWORD` for `EMAIL_HOST_PASSWORD`: Password of the email you used above. This password should be [App Password](https://support.google.com/mail/answer/185833?hl=vi) if you user Gmail.

Go to directory: `cd django_blog/django_project`

Run in command line: `python manage.py runserver` or `py manage.py runserver`
