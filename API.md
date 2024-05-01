# API Documentation for PetFinder

## Endpoints

### Get All Pets
- **GET** `/api/pets`
- **Description**: Retrieves a list of all available pets.
- **Response**:
  ```json
  [{
    "name": "Max",
    "image_url": "/static/assets/max.jpg",
    "description": "A friendly dog"
  }]

### Get Single Pet

- **GET** `/api/pets/{id}`
- **Description**: Retrieves detailed information about a specific pet.
- **Response**:
  ```json
  [{
    "name": "Max",
    "image_url": "/static/assets/max.jpg",
    "description": "A friendly dog",
    "fun_fact": "Loves playing fetch"
    }]
