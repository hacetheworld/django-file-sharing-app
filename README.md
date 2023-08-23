# My Simple Django Project

Welcome to My Simple Django Project! This README will guide you through setting up the project.

## Getting Started

1. **Python**: Make sure you have Python and virtualenv install if not install
                - pip install virtualenv


2. **Virtual Environment (Optional but Recommended)**:
   - Open your terminal/command prompt.
   - Navigate to your project folder: `cd path/to/your/project`
   - Create a virtual environment: 
     ```
     python -m venv nameofvirtualenv      # Windows
     ```
     now start the env you just created and remeber always start the env every time you start writing code i meant when you came back to this project make sure your env is activated
    - to start :
     ```
    nameofvirtualenv\Scripts\activate
     ```
    and the name of your env should show in your terminal in the left side 
3. **Install Django**:
   - While inside the virtual environment, run: 
     ```
     pip install django
     ```

4. **Create a Django Project**:
   - Inside your project folder, run: 
     ```
     django-admin startproject myproject .
     ```

5. **Run the Development Server**:
   - Navigate to your project folder in the terminal.
   - Activate the virtual environment (if not activated already).
   - Run the development server: 
     ```
     python manage.py runserver
     ```
   - Access the development server at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## Contributing

Contributions are welcome! If you want to contribute:
- Fork the repository.
- Create a new branch: `git checkout -b feature/your-feature`
- Make your changes and test thoroughly.
- Submit a pull request to the `main` branch.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to reach out to your.email@example.com for any questions or support. Happy coding!
