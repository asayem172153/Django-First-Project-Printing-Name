# Django First Project: Printing Name

Welcome to Django First Project: Printing Name! This repository contains a basic Django project setup to print a name on the web page.

## Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

- Python 3.6 or higher
- Git
- Virtualenv (optional but recommended)

### Setting Up

1. **Create a new folder, setup virtual environment**

    ```bash
    # Create a new folder
    mkdir newFolder
    cd newFolder

    # Create a virtual environment named 'env'
    python -m venv env
    ```

2. **Open VS code**  
   goto the project folder
    # Open VS Code in the current directory
    ```bash
        code .
    ```
    # Activate the virtual environment (Windows)
    ``` bash
    .\env\Scripts\activate
    ```


2. **Install Django**

    ```bash
    # Install Django into your virtual environment
    pip install django
    ```
3. **Navigate to Project Directory**
   Move to the project directory where Django project files are located:
   ``` bash
   # For example:
   cd firstproject
   ```
4. **Create a New Django App**  
   Create a new Django app named 'newapp':
   ```bash
   django-admin startapp newapp # Name the app as per wish
   ```
5. **Run the Development Server**
   Start the Django development server
   ```bash
   python manage.py runserver
   ```

   
### Accessing the Application

Open your web browser and go to http://127.0.0.1:8000/ to see the printed name on the page.

## Contributing

Contributions are welcome! Feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

