# API to predict individuals income

## Instructions to run:

To build docker images please run:

`sudo docker-compose build`

To start the docker images please run:

`sudo docker-compose up`

You should be able to see the running server at the address:

`http://0.0.0.0:8000/api/v1/`

## Example data format:

{ 
    "age": 37,
    
    "workclass": "Private",
    
    "fnlwgt": 34146,
    
    "education": "HS-grad",
    
    "education-num": 9,
    
    "marital-status": "Married-civ-spouse",
    
    "occupation": "Craft-repair",
    
    "relationship": "Husband",
    
    "race": "White",
    
    "sex": "Male",
    
    "capital-gain": 0,
    
    "capital-loss": 0,
    
    "hours-per-week": 68,
    
    "native-country": "United-States" 
    
}
