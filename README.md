# file_upload_django_react.js
# Project Title: Personal Document Management API with Django REST Framework

Objective: To create a RESTful API for a personal document management system
where users can upload, download, and manage documents in different formats (pdf,
docx, txt, etc.).

What I've done in this project:
1. User Registration, Login, Logout with API
2. User can upload Files only in approved format and in given size. Uploader name also will record in the database.
3. User upload with metadata 'Title', 'Description', 'Format', "Uploader/Owner". He can share with other and can be download the file also.
4. User Modify, Delete and Search their files.
5. doc/docx will be convert to PDF (UNOCONV package).

How to run the project:
1. To run the project first you have to install pipenv command.
2. Then you have to install packages using pipenv shell.
3. Then Migrate the database using command: # python maange.py migrate
4. After the migration, run the server in your localhost using command python maange.py runserver


# Screenshot

![upload](/media/uploads/upload.png)