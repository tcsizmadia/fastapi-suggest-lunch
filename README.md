# My FastAPI App

This is a FastAPI application that provides an API for suggesting lunch using AI with Ollama & Langchain.

## Project Structure

The project has the following structure:

```
fastapi-suggest-lunch
├── app
│   ├── __init__.py
│   ├── main.py
│   └── schemas.py
├── tests
│   └── test_main.py
├── requirements.txt
└── README.md
```

- `app/__init__.py`: This file is an empty file that marks the `app` directory as a Python package.

- `app/main.py`: This file is the main entry point of the FastAPI application. It contains the FastAPI app instance and defines the API routes and their corresponding handlers.

- `app/schemas.py`: This file contains the Pydantic models (schemas) for the application. It defines the structure and validation rules for the data sent and received by the API.

- `tests/test_main.py`: This file contains the unit tests for the `main.py` file. It tests the API routes and their handlers to ensure they are working correctly.

- `requirements.txt`: This file lists the Python dependencies required for the project. It specifies the packages and their versions that need to be installed for the project to run.

## Getting Started

To set up and run the FastAPI application, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/my-fastapi-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd my-fastapi-app
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the FastAPI application:

   ```bash
   uvicorn app.main:app --reload
   ```

5. The FastAPI application is now running. You can access the API at `http://localhost:8000`.

## API Documentation

The API documentation is automatically generated by FastAPI and can be accessed at `http://localhost:8000/docs`.

## Running Tests

To run the unit tests for the FastAPI application, use the following command:

```bash
pytest
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).