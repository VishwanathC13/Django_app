# Django App

This repository contains a Django application project designed to provide a foundational structure for web development using the Django framework. The project includes various components essential for a typical web application, such as user authentication, media management, and static file handling.

## Features

- **User Authentication**: Registration, login, logout, and profile management.
- **Media Management**: Upload and manage media files.
- **Static Files**: Efficient handling of static files using Django's staticfiles app.
- **Templating**: Use of Django templates for dynamic HTML rendering.

## Project Structure

- `assets/`: Contains asset files.
- `media/`: Directory for media files.
- `myproject/`: Main project directory containing settings and URLs.
- `posts/`: Application managing posts and related features.
- `static/`: Directory for static files.
- `templates/`: HTML templates for the project.
- `users/`: User management application.

## Getting Started

### Prerequisites

- Python 3.x
- Django

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/VishwanathC13/Django_app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Django_app
    ```
3. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4. Apply migrations:
    ```sh
    python manage.py migrate
    ```
5. Run the development server:
    ```sh
    python manage.py runserver
    ```

### Deployment

This project is configured to be deployed on Vercel. Ensure you have the `vercel.json` configuration file set up for deployment.

## Credits

This project was developed with the help of the following YouTube tutorial: [Django Tutorial](https://www.youtube.com/watch?v=Rp5vd34d-z4).

## License

This project is licensed under the MIT License.

---

For more details, visit the [GitHub repository](https://github.com/VishwanathC13/Django_app).
