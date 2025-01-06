## Overview

This project is a Flask-based web application that provides user authentication functionalities. It integrates user authentication to create a secure and efficient system.

## Project Structure

Here is the tree view of the project structure:

```
parent-folder
├── app/
│   ├── __init__.py
│   ├── routes.py
│   ├── models.py
│   ├── forms.py
│   └── templates/
│       ├── base.html
│       ├── login.html
│       ├── register.html
│       └── dashboard.html
├── static/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── scripts.js
├── config.py
├── run.py
└── README.md
```

## File Descriptions

- **app/**: This directory contains the main application code.
    - **__init__.py**: Initializes the Flask application and sets up configurations.
    - **routes.py**: Contains the route definitions for the web application.
    - **models.py**: Defines the database models for user data.
    - **forms.py**: Contains the form classes for user input handling.
    - **templates/**: Directory for HTML templates.
        - **base.html**: A base template that other templates extend from.
        - **login.html**: Template for the login page.
        - **register.html**: Template for the registration page.
        - **dashboard.html**: Template for the user dashboard.

- **static/**: Directory for static files like CSS and JavaScript.
    - **css/**: Directory for CSS files.
        - **styles.css**: Main stylesheet for the application.
    - **js/**: Directory for JavaScript files.
        - **scripts.js**: Main JavaScript file for the application.

- **config.py**: Configuration file for the Flask application.
- **run.py**: The entry point for running the Flask application.
- **README.md**: This file, provides an overview of the project.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:
     ```bash
     git clone <repository-url>
     ```

2. Navigate to the project directory:
     ```bash
     cd parent-folder
     ```

3. Install the required dependencies:
     ```bash
     pip install -r requirements.txt
     ```

4. Run the application:
     ```bash
     python run.py
     ```

## License

This project is licensed under the MIT License.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear and concise messages.
4. Push your changes to your forked repository.
5. Create a pull request to the main repository.

## Contact

For any questions or inquiries, please contact the project maintainer at [muh.shofuwan.a@mail.ugm.ac.id].
