
# Library System Django Project

This is a Django project named "library_system" designed to manage a library system. The project includes an app named "lsapp" and uses a database named "ls."

## Setup

1. **Virtual Environment:**
   - Make sure you have Python installed.
   - Create and activate a virtual environment (assuming the virtual environment name is "libenv"):

     ```bash
     python -m venv libenv
     source libenv/bin/activate  # On Linux/Mac
     .\libenv\Scripts\activate   # On Windows
     ```

2. **Install Django:**
   - Once the virtual environment is activated, install Django using the following command:

     ```bash
     pip install django
     ```

3. **Database Setup:**
   - Update the database configurations in `library_system/settings.py`:

     ```python
     DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': 'ls',
        'USER': 'root',
        'PASSWORD': 'Saimanu@7530',
        'HOST':'localhost',
        'PORT':'3306',
    }
}
     ```

4. **Apply Migrations:**
   - Run the following commands to apply migrations and create the necessary database tables:

     ```bash
     python manage.py makemigrations
     python manage.py migrate
     ```

## Run the Development Server

To start the development server, run the following command:

```bash
python manage.py runserver ```

## Dependencies
Django: https://www.djangoproject.com/

## Outputs:

![Home Page](https://github.com/Manogna7530/Library_System/assets/135147366/94464b79-5b86-47d9-8981-f255ae1a2e0d)
![Books Page](https://github.com/Manogna7530/Library_System/assets/135147366/f906cee6-a5c3-4c79-94e2-bebc06870943)
![Add Book](https://github.com/Manogna7530/Library_System/assets/135147366/4c35232f-a936-43f7-a5b8-d6809cc183ab)
![Added Book Successfully](https://github.com/Manogna7530/Library_System/assets/135147366/83a1572e-4635-4cc1-bb90-52ee3f2b8f90)
![View a Book](https://github.com/Manogna7530/Library_System/assets/135147366/3b6ba4be-dbc9-49c9-84a8-ab99b711568c)
![Delete a Book](https://github.com/Manogna7530/Library_System/assets/135147366/13ecbc39-299c-41f1-86f0-8cb818b2a421)
![Deleted a Book Successfully](https://github.com/Manogna7530/Library_System/assets/135147366/d3f0f0da-e2f9-4452-a3ed-9dcaa70e5a41)







