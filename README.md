# How to start the application
```bash
cd rest_api_user
``
source env/bin/activate  # On Windows use `env\Scripts\activate`
```
If not have virtualenv, install it:
```bash
pip install virtualenv
# Create a virtual environment to isolate our package dependencies locally
python3 -m venv env
```
Install the dependencies:
```bash
pip install -r requirements.txt
```
Then apply the migrations:
```bash
python manage.py migrate
python manage.py makemigrations
```
Finally, run the development server:
```bash
python manage.py runserver
```
