# django-tasks-api
Demo API made with Python and Django Rest Framework.

## Run demo locally
With the command line, go to the "/venv/Scripts/" folder and execute the "activate" file to activate the Python virtual environment.
```bash
cd venv/Scripts/
```
```bash
activate
```
With the same command line, return to the main project folder and install needed Python dependencies defined in requirements file.
```bash
pip install -r requirements.txt
```
Turn on the server.
```bash
python manage.py runserver
```
Once the server is running, you can test the API.

## Admin Panel
You can go to the admin panel (http://localhost:8000/admin/) and log-in with the following credentials.
- User: admin
- Password: 12345678

## API Documentation
You can also check the API documentation going to http://localhost:8000/tasks/docs/ (server needs to be running).
