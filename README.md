
![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)
![Flask](https://img.shields.io/badge/flask-v3.0.0-blue)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-v1.4.x-blue)
![License](https://img.shields.io/badge/license-MIT-green)


# JOB Application Form Submission using Flask


This application is a Flask web application designed to handle form submissions. It stores the user's information in a SQLite database and sends an acknowledgment email using Flask-Mail. This application is ideal for simple contact forms or registration forms that require email confirmation.

## Features
- Form handling with data storage in SQLite database.
- Email notifications upon form submission.
- Environment variable management with `dotenv`.
- Simple and intuitive user interface with Flask templates.

## Prerequisites
- Python 3.11+
- Pip (Python package installer)

## Installation

First, clone the repository to your local machine:

```bash
git clone https://github.com/python-dev-og/job-app-form-flask.git
cd <repo name>
```

Then, install the required packages:

```bash
pip install -r requirements.txt
```

## Configuration

Create a `.env` file in the root directory of the project and add the following environment variables:

```env
SECRET=YourSecretKey
USER=YourEmail@gmail.com
PASSWORD=YourEmailPassword
```

## Running the Application

To run the application, execute the following command:

```bash
python app.py
```

The application will be accessible at `http://localhost:5001`.

## Contributing

Contributions, issues, and feature requests are welcome. 

## License

This project is licensed under the MIT License 

## Acknowledgments

- Flask community
- Contributors who participate in this project


## Final Look 

![jobapp-flask.png](images%2Fjobapp-flask.png)



