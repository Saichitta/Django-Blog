# Django Blog Website
This is a simple blog website built using Django. It allows users to create accounts, and write and publish blog posts. A user can delete and update his post.

## The link to the live demo can be found below. I invite you to explore the functionality at your convenience.
    https://drive.google.com/file/d/1O5Iiu5b3qaeTqqsjeALGeNNMVN8RwZ5k/view?usp=sharing

## Installation

  1. Clone the Repository:
  
      ```bash
      git clone https://github.com/your-username/django-blog.git
      cd django-blog
      ```
  
  2. Create a Virtual Environment:
  
      ```bash
      python -m venv venv
      ```
  
  3. Activate the Virtual Environment:
  
          ```bash
          venv\Scripts\activate
          ```
  
  4. Install Dependencies:
  
      ```bash
      pip install -r requirements.txt
      ```
  
  5. Apply Database Migrations:
  
      ```bash
      python manage.py migrate
      ```
  
  6. Create Superuser (Admin):
  
      ```bash
      python manage.py createsuperuser
    ```
    
## Usage

  1. Run the Development Server:
  
      ```bash
      python manage.py runserver
      ```
  
  2. Access the Admin Panel:
  
      Visit `http://127.0.0.1:8000/admin/` and log in with the superuser credentials.
  
  3. Access the Blog Website:
  
      Visit `http://127.0.0.1:8000/` in your web browser to view the blog.

