# Coffee Shop Full Stack

This is a full stack drink menu application. The application includes:

1) Display graphics representing the ratios of ingredients in each drink.
2) Allow public users to view drink names and graphics.
3) Allow the shop baristas to see the recipe information.
4) Allow the shop managers to create new drinks and edit existing drinks.

# What I have learned
I have learned to use Auth0 for authentication, authorization. 
I have practiced to use Postman for build up API backend program.
Also, I have understood about JWT and security issues with general password.

## Tasks

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)


### Backend

The `./backend` directory contains a partially completed Flask server with a pre-written SQLAlchemy module to simplify your data needs. You will need to complete the required endpoints, configure, and integrate Auth0 for authentication.  

#### Files modified from starter code.
./backend/src/api.py  
./backend/src/auth/auth.py  

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. You will only need to update the environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app.   

#### Files modified from starter code.
./frontend/src/environment/environment.ts  

[View the README.md within ./frontend for more details.](./frontend/README.md)
