FarmTech MIS is designed to streamline farmer record management. It enables you to store, search, and analyze farmer details efficiently. With features like government scheme tracking and AI-driven analysis, it supports data-driven decisions for better productivity.

*Requirements

Before running the project, ensure you have the following installed:

- Python 3.x (recommended: Python 3.8+)
- Django 3.x or higher
- Pip (Python package manager)

*Installation

Follow these steps to get the project up and running locally.

1. Clone the repository

Start by cloning the repository to your local machine:

git clone https://github.com/notsoawesam/FarmTech-MIS.git
cd FarmTech-MIS

2. Create a virtual environment 

It’s a good practice to create a virtual environment for your project to manage dependencies.

python -m venv venv

Now, activate the virtual environment:

On windows:

venv\Scripts\activate

On macOS/Linux:

source venv/bin/activate

3. Install dependencies

Once your virtual environment is activated, install the required dependencies by running:

pip install -r requirements.txt

This will install all necessary Python packages listed in the requirements.txt file.

4. Set up the database

Run the following command to apply migrations and set up the database:

python manage.py migrate

5. Create a superuser (optional)

If you need access to the Django admin interface, you can create a superuser with:

python manage.py createsuperuser

Follow the prompts to create a superuser.
Running the Project

To run the development server locally, execute the following command:

python manage.py runserver

*License

This project is licensed under the MIT License - see the LICENSE file for details.
