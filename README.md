# Flask Weight App

A simple Flask application to convert weights between kilograms, grams, and pounds.

## Installation

Install the application by running `pip install -r requirements.txt`.

## Usage

Run the application with `python app.py`.

Open a web browser and navigate to `http://localhost:5000`.

Enter a value and select the units to convert from and to. Click the "Convert" button to see the result.

## Tests

Run the tests with `python -m pytest tests`.

## Deployment

The application is designed to be deployed on an AWS EC2 instance. The Ansible playbooks in the `ansible` directory can be used to provision the instance and deploy the application.

## License

The application is licensed under the MIT License. See `LICENSE` for more information.