
# Ecommerce Website

This is a Django project for an ecommerce website.

## Prerequisites

- Python 3.7 or higher
- Git

## Installation and Setup

1. Open the command prompt (CMD) or PowerShell in your desired directory.

2. Clone the repository by running the following command:

   ```shell
   git clone https://github.com/ayushsaxenagithub/ecommerce_website.git
   ```

3. Create and activate a virtual environment by running the following commands:

   ```shell
   python -m venv myenv
   myenv\Scripts\activate
   ```

4. Navigate to the project directory by running the following command:

   ```shell
   cd ecommerce_website
   ```

5. Install the project dependencies by running the following command:

   ```shell
   pip install -r requirements.txt
   ```

## Configuration

1. Rename the `.env.example` file to `.env`.

2. Open the `.env` file in a text editor and provide the necessary configuration values such as the secret key.

## Database Setup

The project is configured to use SQLite as the default database. Follow these steps to set up the SQLite database:

1. Delete the existing `db.sqlite3` file in the project directory (if it exists).

2. Run the following command to create a new SQLite database:

   ```shell
   python manage.py migrate
   ```

## Running the Project

1. Once the virtual environment is activated and the dependencies are installed, run the following command to start the Django development server:

   ```shell
   python manage.py runserver
   ```

2. Open your web browser and visit `http://localhost:8000` to access the ecommerce website.

3. You can now interact with the website and explore its features.

## Admin Panel

To access the Django admin panel and manage the website's data, follow these steps:

1. In your web browser, visit `http://localhost:8000/admin`.

2. Log in using the superuser credentials.

   - If you haven't created a superuser yet, run the following command to create one:

     ```shell
     python manage.py createsuperuser
     ```

   - Provide a username, email (optional), and password when prompted.

3. Once logged in, you can manage various aspects of the website, such as adding products, managing orders, and more, through the admin interface.

## Additional Information

- To stop the Django development server, press `Ctrl + C` in the command prompt or PowerShell.

- Remember to deactivate the virtual environment once you are done working on the project. Run the following command in the command prompt or PowerShell:

  ```shell
  deactivate
  ```

- For more information about Django and its usage, refer to the official [Django documentation](https://docs.djangoproject.com/).
```

Please copy the updated content provided above and paste it into your `README.md` file.
