# 🚀 React FastAPI: Full Stack Web Application Template

Welcome to the **React FastAPI** repository! This project serves as a full stack, modern web application template, combining powerful technologies like FastAPI, React, SQLModel, PostgreSQL, and Docker. With built-in GitHub Actions, automatic HTTPS, and more, this template is designed to help you build robust applications efficiently.

[![Releases](https://img.shields.io/badge/Releases-View%20Latest%20Releases-brightgreen)](https://github.com/RAAJSURIYAA/react-fastapi/releases)

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **FastAPI Backend**: Build APIs quickly with FastAPI's modern features.
- **React Frontend**: Create interactive user interfaces with React.
- **PostgreSQL Database**: Utilize a powerful relational database for data management.
- **SQLModel**: Simplify database interactions with SQLModel.
- **Docker Support**: Easily containerize your application for consistent environments.
- **Automatic HTTPS**: Secure your application with automatic HTTPS using Let's Encrypt.
- **GitHub Actions**: Automate your workflows with CI/CD.
- **OpenAPI & Swagger**: Generate API documentation automatically.
- **TypeScript Support**: Enhance code quality with TypeScript.
- **State Management**: Manage application state effectively using TanStack Query and Router.
- **Chakra UI**: Build accessible React applications with Chakra UI.

## Technologies Used

This repository includes the following technologies:

- **Backend**: FastAPI, PostgreSQL, SQLModel, Python
- **Frontend**: React, TypeScript, Chakra UI
- **Containerization**: Docker
- **Automation**: GitHub Actions
- **Security**: Let's Encrypt, JWT
- **API Documentation**: OpenAPI, Swagger
- **Data Management**: TanStack Query, TanStack Router

## Getting Started

To get started with the **React FastAPI** template, follow these steps:

### Prerequisites

Make sure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Node.js](https://nodejs.org/)
- [Python](https://www.python.org/)
- [PostgreSQL](https://www.postgresql.org/)

### Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/RAAJSURIYAA/react-fastapi.git
cd react-fastapi
```

### Set Up Environment Variables

Create a `.env` file in the root directory and add your configuration variables. Here’s a sample:

```env
DATABASE_URL=postgresql://user:password@localhost/dbname
SECRET_KEY=your_secret_key
```

### Build and Run with Docker

To build and run the application using Docker, execute the following command:

```bash
docker-compose up --build
```

This command will set up the backend and frontend services, along with the PostgreSQL database.

### Access the Application

Once the application is running, you can access it in your web browser:

- Frontend: [http://localhost:3000](http://localhost:3000)
- Backend API: [http://localhost:8000/docs](http://localhost:8000/docs)

## Folder Structure

Here’s an overview of the folder structure in this repository:

```
react-fastapi/
├── backend/                # FastAPI backend
│   ├── app/               # Application code
│   ├── Dockerfile          # Dockerfile for backend
│   ├── requirements.txt    # Python dependencies
│   └── main.py             # Entry point for FastAPI
├── frontend/               # React frontend
│   ├── public/             # Public assets
│   ├── src/                # Source code
│   ├── Dockerfile          # Dockerfile for frontend
│   └── package.json        # Node.js dependencies
├── docker-compose.yml      # Docker Compose configuration
└── .env                    # Environment variables
```

## Usage

### API Endpoints

The backend API exposes several endpoints. You can explore them using the Swagger UI at [http://localhost:8000/docs](http://localhost:8000/docs).

Here are some example endpoints:

- `GET /items/`: Retrieve all items.
- `POST /items/`: Create a new item.
- `GET /items/{item_id}`: Retrieve a specific item.
- `PUT /items/{item_id}`: Update a specific item.
- `DELETE /items/{item_id}`: Delete a specific item.

### Frontend Components

The frontend consists of various components that utilize Chakra UI for styling. You can find the main components in the `src` directory.

To run the frontend separately, navigate to the `frontend` directory and run:

```bash
npm install
npm start
```

## Contributing

We welcome contributions! To contribute to the **React FastAPI** project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

Please ensure your code follows the project's coding standards and passes all tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

For the latest releases, visit [here](https://github.com/RAAJSURIYAA/react-fastapi/releases). You can download the latest version and execute it to get started.

Feel free to explore the code, make changes, and use this template for your projects!