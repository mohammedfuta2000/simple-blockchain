# Simple Golang Blockchain Implementation


## Getting Started

Follow the steps below to run the Golang Blockchain application:

1. Run the application using the following command:

    ```bash
    $ go run main.go
    ```

## Testing with Postman

Follow the steps outlined below to interact with the API.

### 1. Create a Book Item

- **Method:** POST
- **URL:** http://localhost:3000/new
- **Body:**
    ```json
    {
        "title": "lorem ipsum",
        "author": "John Doe",
        "isbn": "909090",
        "publish_date": "2024-05-26"
    }
    ```

### 2. Create a Block with a Checkout Book Item

- **Method:** POST
- **URL:** http://localhost:3000
- **Body:**
    ```json
    {
        "book_id": "02ebbba046abb6b826ce987b108da9c7",
        "user": "mn_jadda",
        "checkout_date": "2024-05-26"
    }
    ```
### 3. Get the entire blockchain
- **Method:** GET
- **URL:** http://localhost:3000
