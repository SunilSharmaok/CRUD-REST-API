# CRUD REST API Project

## Overview

This project demonstrates CRUD (Create, Read, Update and Delete) operations using a REST API. Postman is used to send HTTP requests and test API responses.

## Features

- Create new records using POST.
- Retrieve records using GET.
- Update existing records using PUT.
- Delete records using DELETE.
- Test API endpoints using Postman.

## Tools and Technologies

- REST API
- Postman
- JSON
- Git and GitHub

## API Endpoints

The following are example endpoints for a CRUD API. Replace `/api/items` with the actual resource path used in your backend.

| Method | Endpoint | Description |
| --- | --- | --- |
| GET | `/api/items` | Retrieve all records |
| GET | `/api/items/{id}` | Retrieve a record by ID |
| POST | `/api/items` | Create a new record |
| PUT | `/api/items/{id}` | Update an existing record |
| DELETE | `/api/items/{id}` | Delete a record |

## Example Request Body

For POST and PUT requests, select **Body > raw > JSON** in Postman. An example body is:

```json
{
  "name": "Sample Item"
}
```

Use the fields required by your actual API.

## How to Run and Test

1. Download or clone this repository.
2. Start the backend server using its project-specific startup command.
3. Open Postman and click **Import**.
4. Select the exported `.postman_collection.json` file included in the repository.
5. Configure the base URL to match your running server.
6. Send the POST, GET, PUT and DELETE requests to test CRUD operations.

## Common HTTP Status Codes

| Status Code | Meaning |
| --- | --- |
| 200 | OK |
| 201 | Created |
| 204 | No Content |
| 400 | Bad Request |
| 404 | Not Found |
| 500 | Internal Server Error |

Actual response codes depend on the backend implementation.

## Learning Outcomes

- Understanding REST API architecture and HTTP methods.
- Performing CRUD operations.
- Sending JSON requests and testing responses in Postman.
- Managing and sharing projects using GitHub.

## Conclusion

This project provides practical experience in REST API development and testing using Postman.
