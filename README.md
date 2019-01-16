# Flask REST API

A basic REST API using Python, Flask, SQLAlchemy, and Marshmallow.

## Setup

### Installation

```sh
python --version # using 3.7.2
brew install pipenv
pipenv install # Create a virtual environment and install dependencies
pipenv shell # Enter the virtual environment
python # Enter the Python shell
from app import db # import the initilized SQLAlchemy instance from app.py
db.create_all() # Seed the database
```

## Technology

### About SQLAlchemy

SQLAlchemy is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.

It provides a full suite of well known enterprise-level persistence patterns, designed for efficient and high-performing database access, adapted into a simple and Pythonic domain language.

### About Marshmallow

marshmallow is an ORM/ODM/framework-agnostic library for converting complex datatypes, such as objects, to and from native Python datatypes. In short, marshmallow schemas can be used to:

- Validate input data.
- Deserialize input data to app-level objects.
- Serialize app-level objects to primitive Python types. The serialized objects can then be rendered to standard formats such as JSON for use in an HTTP API.
