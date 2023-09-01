# Blog Website

Python-based web application built using Python and various libraries and tools for both the backend and frontend. This document will provide you with an overview of the project, instructions for setting it up, and details about its architecture.

## Prerequisites

Before you begin, ensure you have:
- Python 3.x
- pip
- Optional: Virtual environment for isolation

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/blog-website.git
   cd blog-website
   ```

2. Create a virtual environment (recommended):

   ```shell
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:

   ```shell
   pip install -r requirements.txt
   ```

## Backend

- Flask: Web framework for routing and handling requests.
- SQLAlchemy: ORM for database interactions.
- Psycopg2: PostgreSQL adapter.
- SQLite: For development and testing.
- PostgreSQL: For production (configure in `config.py`).

## Frontend

- HTML, CSS, Bootstrap: Templates and styling.
- WTForms: Simplifies form creation.
- Jinja: Template engine for dynamic content.

## Running the Application

1. Set up your database in `config.py`.

2. Initialize and migrate the database:

   ```shell
   flask db init
   flask db migrate
   flask db upgrade
   ```

3. Start the server:

   ```shell
   flask run
   ```

Access the application at `http://localhost:5000`.

## Deployment

Our Blog Website is deployed and accessible at [https://ghyorkas-blog-website.onrender.com](https://ghyorkas-blog-website.onrender.com).

## Contributing

To contribute, open issues or submit pull requests on GitHub: [Click here](https://github.com/ggg6r34t/ghyorka-blog-website)

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
