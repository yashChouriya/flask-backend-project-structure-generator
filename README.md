# Flask Backend Project Structure Generator

This Python script, `template.py`, is a tool designed to help you quickly generate the foundational structure for a Flask backend project. It automates the creation of essential files and directories needed to kickstart your project.

## How to Use

1. Set your project name by modifying the `PROJECT_NAME` variable within the script.

2. Add or remove file paths in the `LIST_FILES` list to match your specific project requirements.

3. Run the script, and it will create the specified directories and empty files in your project structure.

## Project Structure

- **Project Name:**
  - *Defined by you in the script*

- **Files and Directories:**
  - `Dockerfile`: Docker configuration file
  - `.env`: Environment variables configuration file
  - `.gitignore`: Git ignore file
  - `app.py`: Flask application entry point
  - `init_setup.py`: Initial setup script
  - `README.md`: Project documentation
  - `requirements.txt`: Python package dependencies
  - `src/`: Main source code directory
    - `__init__.py`: Initialization file for the source code
    - `config/`: Configuration files
      - `__init__.py`: Initialization file for the configuration
      - `config.py`: General configuration settings
      - `dev_config.py`: Development-specific configuration settings
      - `production.py`: Production-specific configuration settings
    - `controllers/`: Controllers for different functionalities
      - `__init__.py`: Initialization file for the controllers
      - `auth_controller.py`: Authentication controller
    - `middlewares/`: Middlewares for request processing
      - `__init__.py`: Initialization file for the middlewares
    - `models/`: Data models and database interaction
      - `__init__.py`: Initialization file for the models
      - `user_model.py`: User data model
    - `services/`: Business logic and services
      - `__init__.py`: Initialization file for the services
      - `jwt_service.py`: JSON Web Token (JWT) service
    - `routes.py`: API routes configuration
    - `utils.py`: Utility functions and helpers

## Notes

This script provides a convenient way to establish a consistent and organized Flask backend project structure. Customize it further to suit your specific project requirements and preferences.
