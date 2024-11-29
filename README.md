# gas_utility_service
Gas utility service using Django
Features
1. Submit Service Requests: Users can submit service requests online, providing details such as the type of request and any relevant attachments.
2. Customer Management: The system allows for the management of customer information, enabling efficient handling of service requests.

# Gas Utility Service

This is a Gas Utility Service application built using Django. It provides modules for account management, utility services, and more.

## Project Structure

### Root Directory:
- `customer_service/`
  - `gas_utility/`
    - `__init__.py`
    - `asgi.py`
    - `settings.py`
    - `urls.py`
    - `wsgi.py`
  - `media/`
    - `attachments/`
      - `My_Resume.pdf`
  - `utility_services/`
    - `migrations/`
    - `templates/`
      - `requests_submitted.html`
      - `submit_request.html`
      - `track_request.html`
    - `__init__.py`
    - `admin.py`
    - `apps.py`
    - `forms.py`
    - `models.py`
    - `tests.py`
    - `urls.py`
    - `views.py`
  - `db.sqlite3`
  - `manage.py`

- `gas_utility/`
  - `accounts/`
    - `migrations/`
    - `templates/`
      - `accounts/`
        - `account_info.html`
        - `track_requests.html`
      - `registrations/`
        - `register.html`
    - `__init__.py`
    - `admin.py`
    - `apps.py`
    - `forms.py`
    - `models.py`
    - `tests.py`
    - `urls.py`
    - `views.py`
  - `gas_utility/`
    - `__init__.py`
    - `asgi.py`
    - `settings.py`
    - `urls.py`
    - `views.py`
    - `wsgi.py`
  - `media/`
    - `attachments/`
      - `My_Resume.pdf`
  - `utility_services/`
    - `migrations/`
    - `templates/`
      - `utility_services/`
        - `request_submitted.html`
      - `submit_request.html`
      - `track_request.html`
    - `__init__.py`
    - `admin.py`
    - `apps.py`
    - `forms.py`
    - `models.py`
    - `tests.py`
    - `urls.py`
    - `views.py`
  - `db.sqlite3`
  - `manage.py`

- `README.md`

## Features

- **Customer Service Module:**
  - Manage utility services and submit requests.
  - Upload media such as attachments.

- **Accounts Module:**
  - User registration and login.
  - Track and view account requests.

- **Utility Services Module:**
  - Submit, track, and review service requests.
  - Organized templates for user interaction.

## How to Run

1. Clone this repository:
   
   git clone https://github.com/your-username/gas-utility-service.git
   cd gas-utility-service

2. Set up a virtual environment:

    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
 
3. Install dependencies:

    pip install -r requirements.txt

4. Run migrations:

    python manage.py migrate

5. Start the development server:

    python manage.py runserver

6. Open the application in your browser:

    http://127.0.0.1:8000

License
This project is licensed under the MIT License.


					
					