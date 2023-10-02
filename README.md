# phase-4-super-heroes

This is a simple RESTful API for managing superheroes and their associated information.

Before running the API, make sure you have the following installed:

- Python 3
- Flask
- Flask-RESTful
- Flask-SQLAlchemy
- SQLAlchemy
- Other project-specific dependencies (install using `pip`)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/kibetbrayo/superheroes-api.git
   cd superheroes-api

2. install the required dependancies
      pip install -r requirements.txt

3. setup the database migration
    - flask db upgrade

4. run api
    - flask run

## usage

## Endpoints

Index
## GET '/'

- Description: Welcome message
- Response: Welcome message in JSON format

Superheroes
## GET /superheroes

- Description: Get a list of all superheroes
- Response: List of superheroes in JSON format

## POST /superheroes

- Description: Create a new superhero
- Request: JSON data with superhero details
-Response: JSON representation of the created superhero

## GET /superheroes/int:id

- Description: Get details of a superhero by their ID
- Response: JSON representation of the superhero

## PATCH /superheroes/int:id

- Description: Update details of a superhero
- Request: JSON data with updated superhero details
- Response: JSON representation of the updated superhero

## DELETE /superheroes/int:id

- Description: Delete a superhero by their ID
- Response: No content (204) if successful
Superhero Abilities
## GET /superhero_abilities

- Description: Get a list of all superhero-ability relationships
- Response: List of superhero-ability relationships in JSON format

## POST /superhero_abilities

- Description: Create a new superhero-ability relationship
- Request: JSON data with relationship details
- Response: JSON representation of the created relationship

## Contributing

Contributions are welcome! Please fork the repository and create a pull request for any improvements or bug fixes.
