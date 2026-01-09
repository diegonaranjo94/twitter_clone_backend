# Twitter Clone:

The purpose of this project is to explore the FastAPI library in depth, use as many features as possible and have fun thinking the possible endpoints twitter has for its users. The logic behind each endpoint and the database management are beyond the scope of this project, however It was a good opportunity to practive with different types of objects as you can see in each method.


## Technologies
- **Python 3.12+**
- **FastAPI**: For building the API.
- **Pydantic**: For data validation and settings management.
- **Uvicorn**: As the ASGI server.

## Project Structure
The core logic resides in the `Twitter` directory:
- `main.py`: The entry point of the application.
- `models.png`: A diagram of the data models.
- `*.json`: JSON files (`tweets.json`, `users.json`) used for data persistence.

## Installation and Running

### Prerequisites
- Python installed on your system.

### Steps
1. **Create a virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the server**:
   ```bash
   cd Twitter
   uvicorn main:app --reload
   ```

The API will be available at `http://127.0.0.1:8000`. You can verify it by visiting `http://127.0.0.1:8000/docs`.

There you can find two response models:

![alt text](https://github.com/imdiegodev1/Twitter_Clone/blob/main/Twitter/models.png?raw=true)

I  have also included the .json files created and used by the application in my laptop. Although the endpoints create all the necessary files, you can start playing and testing the endpoint without having to struggle to create new data. The .json files you will find are related to the models:

- Tweets
- Users

