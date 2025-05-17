
# TDD & BDD Final Project 🧪
This project was developed as the final deliverable for the **"Introduction to Test Driven Development and Behavior Driven Development"** course, part of the IBM DevOps and Software Engineering Professional Certificate.

## 🧰 Tech Stack
- Python 3.9
- Flask
- Pytest (TDD)
- Behave (BDD)
- Docker

## 📌 Project Overview
This microservice simulates a simple product management API. The main goal of this project was to apply **TDD and BDD methodologies** in a realistic setting.

The following were implemented:
- Unit tests for service routes and models using `pytest`
- Feature scenarios using `behave` in Gherkin syntax
- API endpoints in `service/routes.py`
- Step definitions and BDD logic with `features/steps`

## 🧪 Test Examples
Unit tests are located in `tests/test_models.py` and `tests/test_routes.py`.

To run unit tests:
```
pytest
```
To run BDD scenarios:
```
behave
```
## 🚀 Getting Started
Clone repo and enter directory
```
git clone https://github.com/StivenHenao/tdd-bdd-final-project.git
cd tdd-bdd-final-project
```

# Setup environment

```
bash bin/setup.sh
```

## 📂 Project Structure
```
├── service/
│   └── routes.py
├── tests/
│   └── test_models.py
│   └── test_routes.py
├── features/
│   └── products.feature
│   └── steps/
```

## 📄 License
Apache 2.0

## Author
John Rofrano, Senior Technical Staff Member, DevOps Champion, @ IBM Research
