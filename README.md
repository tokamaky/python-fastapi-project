# python-fastapi-project
FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints.

It will create a database with 2 table: user and item for user to input their information and items
It can create user by emial and password(password will be hiden through respond_model after creating)
The relationship between user and item is one to many which means each user can have many items

# Usage
This project is actually an Inventory that user can have muiltple items With this project you can do create user, create item for user, read_user, read_user_id, read_item.

# Start
- to run this project needs to install SQLAlchemy with code: pip install sqlalchemy

- install FastAPI with code: pip install "fastapi[all]"

- to run the website to check please type: uvicorn main:app --reload 

- then open website:  http://127.0.0.1:8000/docs



- will continue doing the update to make it more completed # Start

# Advantage
- Protect user's information. It can create user by emial and password(password will be hiden through respond_model after creating)
- Easy to modify
