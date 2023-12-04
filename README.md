# Django Newspaper Project

This repository contains the code for a newspaper website project based on the "Newspaper" project from the book "Django for Beginners: Build websites with Python and Django" by William S. Vincent.

## Overview

This Django project allows users to:

- Browse various articles with different categories.
- Read detailed content for each article.
- Create and edit articles through an intuitive interface (for authorized users).
- Manage articles, users, and website content using Django's admin panel.

## Technologies Used

- Django: Backend web framework for Python.
- HTML/CSS: Frontend layout and styling.
- SQLite: Database management system for storing articles and user data.

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/newspaper-project.git
    ```

2. Install project dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

4. Create a superuser to access the admin panel:

    ```bash
    python manage.py createsuperuser
    ```

5. Run the development server:

    ```bash
    python manage.py runserver
    ```

6. Access the website at `http://localhost:8000/` and the admin panel at `http://localhost:8000/admin/`.

## Usage

- Admin Panel: Log in with the created superuser credentials to manage articles and user data.
- Creating Articles: Authenticated users can create articles via the "Create" option in the navigation bar.
- Editing Articles: Authors can edit their articles by clicking the "Edit" button on the article page.

## Contributions

Contributions are welcome! If you find bugs or want to add new features, feel free to submit a pull request. Please follow the existing code style and include relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- William S. Vincent for the insightful guidance in "Django for Beginners."
- Django community for the robust framework and resources.
