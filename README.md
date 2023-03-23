## Features

The project has the following features:

- **API Documentation:** The API documentation is available at `http://127.0.0.1:8000/docs`. It has been generated using Swagger UI and provides a user-friendly interface to interact with the API.

- **API Schema:** The API schema is available at `http://127.0.0.1:8000/openapi.json`. It provides a machine-readable description of the API in JSON format.

- **API Endpoints:** The project has several endpoints that perform various actions. These include:

    - `GET /`: Returns a JSON response with a welcome message.

    - `GET /items/{item_id}`: Returns a JSON response with the details of a specific item.

    - `POST /items/`: Creates a new item.

    - `PUT /items/{item_id}`: Updates the details of a specific item.

    - `DELETE /items/{item_id}`: Deletes a specific item.

- **API Validation:** The project uses Pydantic to validate the input and output data of the API endpoints. This ensures that only valid data is accepted by the API and that the API returns valid data.

- **API Testing:** The project includes unit tests for the API endpoints. The tests can be run using the command `pytest`.

## Dependencies

The project has the following dependencies:

- fastapi
- uvicorn
- pydantic
- pytest

These dependencies can be installed using the command `pip install -r requirements.txt`.

## Contributing

If you would like to contribute to the project, please fork the repository and create a pull request. Your contributions are welcome!

