# Restful-booker API Testing with Postman

This project manual outlines the steps to set up and execute API testing for the Restful-booker API using Postman. Restful-booker is a demo API for testing and learning purposes.

## Pre-requisites

- **Postman**: Make sure you have Postman installed on your machine. If not, you can download it from [here](https://www.postman.com/downloads/).
- **Restful-booker API Access**: Ensure that you have access to the Restful-booker API. You can find more information about it [here](https://restful-booker.herokuapp.com/).

## Getting Started

1. **Clone Repository**: Clone this repository to your local machine.

    ```bash
    git clone <repository_url>
    ```

2. **Import Postman Collection**: Import the Postman collection provided in the repository.

    - Open Postman.
    - Click on "Import" button.
    - Choose the `Restful-booker.postman_collection.json` file from the cloned repository.

3. **Environment Setup**: Import the Postman environment provided in the repository.

    - In Postman, click on the gear icon at the top right corner.
    - Select "Manage Environments".
    - Click on "Import" button.
    - Choose the `Restful-booker.postman_environment.json` file from the cloned repository.

4. **Configure Environment Variables**: Configure the following environment variables in Postman environment:
   
   - `base_url`: Set it to the base URL of the Restful-booker API (e.g., `https://restful-booker.herokuapp.com`).

5. **Run Tests**: Execute the API tests using the imported collection.

    - In Postman, select the imported collection.
    - Click on "Run".
    - Choose the desired environment.
    - Click on "Run Restful-booker" button.

6. **View Results**: After running the tests, view the test results in the Postman Runner.

    - Check the test results for each request.
    - Analyze the responses and assertions.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or want to report issues, feel free to create a pull request or open an issue in this repository.

## License

This project is licensed under the [MIT License](LICENSE).
