# README #

A simple Flask-SQLAlchemy application for testing a python server setup.

### Test DB setup ###

Ensure you have the env variable

    DATABASE_URL

Create database

    >>> from app import db
    >>> db.create_all()