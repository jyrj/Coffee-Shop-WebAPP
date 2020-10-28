# *Coffee Shop Project*



A ready to deploy web app to show the functionality of Identity Access management and authorization using Auth0. Implemented using FLASK RESTful API, PostgreSQL, SQLAlchemy.

The application meet follwing specifications:

1) Display graphics representing the ratios of ingredients in each drink.
2) Allow public users to view drink names and graphics.
3) Allow the shop baristas to see the recipe information.
4) Allow the shop managers to create new drinks and edit existing drinks.

## Web Application Structure

The App is structured into:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)

## About the Stack

Application is desiged with some key functional areas:

### Backend

The `./backend` directory contains a completed Flask server with a SQLAlchemy. Flask endpoints and API are tested on Python 3.7

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. When trying to deploy, define environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app. 

[View the README.md within ./frontend for more details.](./frontend/README.md)

### Dependency issue found when using Python 3.7.x (x>0)

Use a virtual environment and add the corresponding dependencies (preferrably using a conda environment)

### *Scope for improvement:*

- Although the endpoints are secured, still XSS hasn't been covered.
- Perfest AuthO authorization example, frontend needs to be improved.
- Currently learning ReactJS to implement frontend.

