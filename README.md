

# Hospital Management System

This is a Hospital Management System built using Django. It allows hospitals to manage patients, doctors, appointments, and other related data.

## Requirements

- Python 3.x
- Django 3.x
- Other dependencies mentioned in `requirements.txt`

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/hospital-management-system.git
cd hospital-management-system
```

2. Create a virtual environment (optional but recommended):

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Perform database migrations:

```bash
python manage.py migrate
```

5. Create a superuser to access the Django admin panel:

```bash
python manage.py createsuperuser
```

## Usage

Run the development server:

```bash
python manage.py runserver
```

Visit the application at http://localhost:8000/ and access the admin panel at http://localhost:8000/admin/.

## Django Commands

Here are some useful Django commands you can run from the project root directory:

- **Run Development Server:**

  ```bash
  python manage.py runserver
  ```

- **Create Migrations:**

  ```bash
  python manage.py makemigrations
  ```

- **Apply Migrations:**

  ```bash
  python manage.py migrate
  ```

- **Create Superuser:**

  ```bash
  python manage.py createsuperuser
  ```

- **Run Tests:**

  ```bash
  python manage.py test
  ```

- **Collect Static Files:**

  ```bash
  python manage.py collectstatic
  ```

- **Create a New Django App:**

  ```bash
  python manage.py startapp app_name
  ```

- **Check for Django Management Commands:**

  ```bash
  python manage.py help
  ```

## Contributing

We welcome contributions to enhance the Hospital Management System. Feel free to submit issues and pull requests.

Developer: Tahir Bin Bashir 
Phn No: +91 6006693132
