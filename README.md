# Full-Stack FastAPI and React Template

Welcome to the Full-Stack FastAPI and React template repository. This repository serves as a demo application for interns, showcasing how to set up and run a full-stack application with a FastAPI backend and a ReactJS frontend using ChakraUI.

## Project Structure

The repository is organized into two main directories:

- **frontend**: Contains the ReactJS application.
- **backend**: Contains the FastAPI application and PostgreSQL database integration.

Each directory has its own README file with detailed instructions specific to that part of the application.

## Prerequisites(backend)
- Python 3.8 or higher
- Poetry (for dependency management)
- PostgreSQL (ensure the database server is running)
  
## Prerequisites(frontend)
Node.js (version 14.x or higher)
npm (version 6.x or higher)

## Getting Started
### Backend

1. Clone the repository to your local machine.

    ```sh
    git clone <repository_url>
    ```

2. Navigate to the `backend` directory and install the Python dependencies
    ```sh
    cd backend
    poetry install
    ```
    
3. update the necessary configurations in the '.env' file, particularly the database configuration.

  
4. Set up the database with the necessary tables
    ```sh
    poetry run bash ./prestart.sh
    ```
    
5. Run the backend server
    ```
    poetry run uvicorn app.main:app --reload
    ```
### frontend
1. Clone the repository to your local machine.

    ```sh
    cd frontend
    ```

2. Navigate to the `frontend` directory and install the Frontend dependencies
    ```sh
    npm install
    ```

3. Update the configuration file in the `.env` with your own data

4. Run the deployment server
    ```sh
    npm run dev
    ```
## Docker Deployment

### Using Docker Compose

1. Install Docker Compose if you haven't already.
2. Run `docker-compose up -d` to start both the backend and frontend services.

- [Frontend README](./frontend/README.md)
- [Backend README](./backend/README.md)

