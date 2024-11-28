# flask-htmx-example
This repository features an example Flask application using the HTMX library. This project evolves from the foundational blog app tutorial found on the official [Flask documentation page](https://flask.palletsprojects.com/), enhancing it by implementing HTMX. HTMX is a powerful JavaScript library that provides dynamic interactions on websites without requiring complex JavaScript code or frameworks, making it easier to build modern, responsive web applications. This example not only demonstrates a fundamental integration of Flask with HTMX but also delves into the nuances of scaling the application with more complex events and functionalities, providing a practical, in-depth guide for developers looking to leverage HTMX within their Flask projects.

## HtmxBlog
"HtmxBlog" is an enhanced version of the 'flaskr' blogging application, originally introduced in the Flask official documentation as a tutorial for new developers.

---

### Installation Instructions for HTMX Blog

Follow these steps to get HtmxBlog up and running on your local machine. This guide assumes you have Git and Python installed on your system.

#### 1. Clone the Repository

First, clone the Pony Blog repository from GitHub to your local machine using the following command:

```bash
git clone https://github.com/forgineer/flask-htmx-example.git
```

#### 2. Navigate to the Project Directory

Change your current working directory to the `flask-htmx-example` folder:

```bash
cd flask-htmx-example
```

#### 3. Create and Activate a Python Virtual Environment

Create a virtual environment in the project directory. This isolates the project dependencies from your global Python environment.

To create a virtual environment, run:

```bash
python -m venv venv
```

Activate the virtual environment:

- On Windows, use:

  ```bash
  .\venv\Scripts\activate
  ```

- On Unix or MacOS, use:

  ```bash
  source venv/bin/activate
  ```

#### 4. Install the Application and Dependencies

With the virtual environment activated, install Pony Blog and its dependencies using pip:

```bash
pip install .
```

This command installs everything needed to run the application, including a recent copy of the HTMX library inside the `static` directory.

Before running the application, initialize the SQLite database that will store all user accounts and blog entries:

```bash
flask --app HtmxBlog init-db
```

#### 5. Run the Application

Start the HTMX Blog application with Flask’s development server:

```bash
flask --app HtmxBlog run
```

#### 6. Access the Application

Once the application is running, open your web browser and navigate to:

```
http://localhost:5000
```

You should now be able to interact with the HTMX Blog application.
