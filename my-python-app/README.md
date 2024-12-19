# My Python App

This is a sample Python application that demonstrates how to structure a project with unit tests and coverage reporting using pytest.

## Project Structure

```
my-python-app
├── src
│   ├── __init__.py
│   ├── app.py
│   └── utils.py
├── tests
│   ├── __init__.py
│   ├── test_app.py
│   └── test_utils.py
├── .github
│   └── workflows
│       └── coverage.yml
├── requirements.txt
├── pytest.ini
└── README.md
```

## Requirements

To run this project, you need to have Python installed. You can install the required dependencies using:

```
pip install -r requirements.txt
```

## Running the Application

To run the application, execute the following command:

```
python -m src.app
```

## Running Tests

To run the tests, use the following command:

```
pytest
```

## Generating Coverage Report

To generate a coverage report, ensure that you have the coverage package installed and run:

```
pytest --cov=src tests/
```

## License

This project is licensed under the MIT License.