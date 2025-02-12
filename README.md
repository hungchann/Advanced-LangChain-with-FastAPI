# Advanced LangChain with FastAPI

This project demonstrates the integration of LangChain with FastAPI to build advanced language processing applications.

## Installation

To install the dependencies, follow these steps:

1. Clone the repository:
    ```bash
    https://github.com/hungchann/Advanced-LangChain-with-FastAPI.git
    cd Advanced-LangChain-with-FastAPI
    ```

2. Create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

To run the FastAPI application, use the following command:

```bash
uvicorn main:app --reload
```

This will start the server at `http://127.0.0.1:8000`. You can access the API documentation at `http://127.0.0.1:8000/docs`.

## License

This project is licensed under the MIT License.