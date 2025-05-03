# ALX Backend User Data

This repository contains projects and modules related to user data management, authentication, and security. It is organized into multiple directories, each focusing on a specific aspect of backend development.

## Project Structure

### `0x00-personal_data`
This directory focuses on handling personal data securely, including:
- **`filtered_logger.py`**: Implements logging with sensitive data redaction.
- **`encrypt_password.py`**: Provides utilities for password hashing and validation.
- **`user_data.csv`**: Sample CSV file containing user data for testing purposes.

### `0x01-Basic_authentication`
This directory introduces basic authentication mechanisms:
- **`models/`**: Contains the base and user models for managing user data.
- **`api/`**: Implements API endpoints for user management and authentication.
- **`requirements.txt`**: Lists dependencies for this project.

### `0x02-Session_authentication`
This directory extends authentication to include session-based mechanisms:
- **`models/`**: Includes models for user sessions and user data.
- **`api/`**: Implements session-based authentication and API endpoints.
- **`requirements.txt`**: Lists dependencies for this project.

### `0x03-user_authentication_service`
This directory provides a complete user authentication service:
- **`app.py`**: Flask application implementing user authentication features.
- **`auth.py`**: Handles authentication logic, including session and password management.
- **`db.py`**: Manages database interactions for user data.
- **`main.py`**: Contains end-to-end integration tests for the authentication service.

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/alx-backend-user-data.git
   cd alx-backend-user-data
   ```

2. Install dependencies for each project:
   ```bash
   pip install -r <project-directory>/requirements.txt
   ```

3. Run the Flask applications:
   ```bash
   python3 <project-directory>/app.py
   ```

## Usage

- Use the provided API endpoints to manage users, sessions, and authentication.
- Run the integration tests in `0x03-user_authentication_service/main.py` to validate the service.

## Author

This repository is part of the ALX Backend curriculum.
