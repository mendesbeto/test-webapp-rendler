# Test WebApp Rendler

This project is a web application developed in Python, using the Flask framework, to demonstrate the implementation of a machine learning model for sales prediction in the context of the Rossmann drugstore chain.

## Project Structure

- `handler.py`: Main file containing the Flask application logic and routes for interacting with the prediction model.
- `model/`: Directory storing the trained machine learning model.
- `parameter/`: Directory containing the parameters used by the model.
- `rossmann/`: Directory with data and scripts related to the Rossmann use case.
- `Procfile`: File used to define the commands executed by the web server in the production environment.
- `requirements.txt`: List of dependencies required to run the application.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mendesbeto/test-webapp-rendler.git
   cd test-webapp-rendler
Create and activate a virtual environment:

bash
Copiar código
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the dependencies:

bash
Copiar código
pip install -r requirements.txt
Running the Application
Start the Flask application:

bash
Copiar código
python handler.py
Access the application in the browser:

Open http://localhost:5000 to interact with the application.

Usage
The application allows users to input data related to Rossmann stores and receive sales predictions based on the implemented machine learning model.

Contribution
Contributions are welcome! Feel free to open issues or submit pull requests with improvements or fixes.

License
This project is licensed under the MIT License.

Copiar código

Se precisar de mais ajustes ou personalizações, é só avisar! 😊
