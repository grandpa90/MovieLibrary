# MovieLibrary Project

The MovieLibrary project is a web application built with Python, Flask, MongoDB, WTForms, and Passlib to manage a collection of movies.

## Features

- Add, edit, and delete movies from the library.
- View details of each movie, including title, genre, release date, and more.
- Search and filter movies based on various criteria.
- Secure user authentication and password hashing.
- Simple and user-friendly interface.

## Technologies Used

- **Python**: The main programming language.
- **Flask**: A lightweight web framework for building web applications.
- **HTML5**: Used for structuring the templates/views.
- **PyMongo**: A Python driver for MongoDB, used for database interactions.
- **WTForms**: A library for handling web forms in Flask applications.
- **Passlib**: Used for secure password hashing.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python (version X.X.X)
- Flask (`pip install Flask`)
- MongoDB (Make sure MongoDB is installed and running)
- WTForms (`pip install WTForms`)
- Passlib (`pip install passlib`)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/grandpa90/MovieLibrary.git
    ```

2. Install dependencies:

    ```bash
    cd MovieLibrary
    pip install -r requirements.txt
    ```

3. Configure MongoDB:

    - Ensure that MongoDB is running.
    - Update the MongoDB connection details in `config.py`.

4. Run the application:

    ```bash
    python app.py
    ```

5. Open your web browser and go to [http://localhost:5000](http://localhost:5000) to access the MovieLibrary application.

## Project Structure

- `app.py`: The main application file.
- `templates/`: HTML templates for rendering views.
- `static/`: Static files (CSS, JavaScript, images, etc.).
- `config.py`: Configuration file for database connection and other settings.
- `forms.py`: WTForms for handling web forms.
- `password_utils.py`: Utility functions for password hashing and validation.

## Contributing

Contributions are welcome! If you find a bug or have a suggestion, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
