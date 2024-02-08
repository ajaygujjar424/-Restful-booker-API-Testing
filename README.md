# Restful-booker API Manual Testing with Postman
This project focuses on conducting comprehensive API testing for the Restful-booker API using the Postman tool. The Restful-booker API serves as a demonstration API designed for educational and testing purposes. Through this project, we aim to ensure the reliability, functionality, and performance of the Restful-booker API endpoints.

# Project Overview

Welcome to the Restful-booker API Testing project! This project aims to help beginners in API testing learn and practice testing skills using the Restful-booker API with Postman. The Restful-booker API is a simple API designed for educational purposes, making it ideal for beginners to explore and understand API testing concepts.

# Key Objectives
**Learning**: Gain hands-on experience with API testing concepts, including sending requests, validating responses, and working with different HTTP methods.

Practical Skills: Develop practical skills in using Postman for testing API endpoints, including authentication, creating, updating, and deleting bookings.

Understanding: Enhance understanding of RESTful API principles, status codes, request headers, and request/response payloads.

This project manual outlines the steps to set up and execute API testing for the Restful-booker API using Postman. Restful-booker is a demo API for testing and learning purposes.

## Pre-requisites

- **Postman**: Make sure you have Postman installed on your machine. If not, you can download it from [here](https://www.postman.com/downloads/).
- **Restful-booker API Access**: Ensure that you have access to the Restful-booker API. You can find more information about it [here](https://restful-booker.herokuapp.com/).

## Getting Started

1. **Clone Repository**: Clone this repository to your local machine.

    ```bash
    git clone <repository_url>
    ```

2. **Import Postman Collection**: Import the provided Postman collection (`Restful-booker.postman_collection.json`) into your Postman workspace.

    - Open Postman.
    - Click on "Import".
    - Choose the `Restful-booker.postman_collection.json` file from the cloned repository.

3. **Import Postman Environment**: Import the Postman environment (`Restful-booker.postman_environment.json`) to configure environment variables.

    - In Postman, click on the gear icon.
    - Select "Manage Environments".
    - Click "Import".
    - Choose the `Restful-booker.postman_environment.json` file from the cloned repository.

4. **Configure Environment Variables**: Set `base_url` to the Restful-booker API base URL (e.g., `https://restful-booker.herokuapp.com`).

## Manual Testing

1. **Authentication Endpoint**:
   - Send a POST request to `/auth` with valid credentials.
   - Verify the response contains a valid token.

2. **Create Booking**:
   - Send a POST request to `/booking` with required booking details.
   - Verify the response contains the created booking ID.

3. **Retrieve Booking**:
   - Send a GET request to `/booking/{bookingId}` with a valid booking ID.
   - Verify the response contains details of the specified booking.

4. **Update Booking**:
   - Send a PUT request to `/booking/{bookingId}` with the booking ID and updated details.
   - Verify the response indicates a successful update.

5. **Delete Booking**:
   - Send a DELETE request to `/booking/{bookingId}` with a valid booking ID.
   - Verify the response indicates a successful deletion.


## Contributing

Contributions are welcome! If you have any suggestions, improvements, or want to report issues, feel free to create a pull request or open an issue in this repository.


