 # Real Estate Bot
![Screenshot] (https://cdn-langchain.netlify.app/Screenshot%202024-07-07%20at%2017-05-03%20Real%20Estate%20Bot.png)

## Installation:
To run this project, you'll need Python 3 installed on your system. 

1. Clone this repository to your local machine 

2. Create a virtual environment, execute the following command: 

``` python3 -m venv .venv ``` 

3. Activate the virtual environment by running: 

``` source .venv/bin/activate ``` 

4. Install dependencies using pip: 

``` pip3 install -r requirements.txt ``` 

## Configuration:

Go to https://mdb.ai/ register and login for generating a MindsDB API key.

Create an .env file and add your MindsDB API KEY:

``` MINDSDB_API_KEY=your_api_key ```

Add your database credentials to the .env file:

``` DATABASE_USER=database_user
DATABASE_PASSWORD=database_password
DATABASE_HOST=database_host
DATABASE_PORT=database_port
DATABASE_DATABASE=database_name
DATABASE_SCHEMA=database_schema
```


## Running:
To run the project, execute the following command: 
``` python3 app.py ```

## Usage:
In your browser go to 
``` http://localhost:8000/ ```

