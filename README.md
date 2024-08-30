# Nimap Django assignment

## Features
1. Register a client

2. Fetch clients info

3. Edit/Delete client info

4. Add new projects for a client and assign users to those projects.

5. Retrieve assigned projects to logged-in users.
   
## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Harshadaaaaaapawar/nimap.git
   cd nimap
2. **Create and Activate a Virtual Environment**:
   ```bash
    python -m venv env
    source env/bin/activate
3. **Setup the database**:
    ```
    a. Install MySQL and create a database.
    b. python manage.py migrate
4. **Create superuser**:
   ```bash
   python manage.py createsuperuser
5. **Run the server**:
   ```bash
   python manage.py runserver


