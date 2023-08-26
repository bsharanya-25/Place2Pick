# MERN Project README

Welcome to the MERN project! This is a full-stack web application built using the MongoDB, Express.js, React, and Node.js stack.

## Table of Contents

- [Installation](#installation)
  - [Clone the repository](#clone-the-repository)
  - [Navigate to the project directory](#navigate-to-the-project-directory)
  - [Install server dependencies](#install-server-dependencies)
  - [Install client dependencies](#install-client-dependencies)
- [Configuration](#configuration)
  - [Create a `.env` file in the `server` directory](#create-a-env-file-in-the-server-directory)
  - [Modify client-side configuration](#modify-client-side-configuration)
- [Running the Project](#running-the-project)
  - [Start the server](#start-the-server)
  - [Start the client](#start-the-client)
- [Project Structure](#project-structure)
- [Contributing](#contributing)


## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-mern-project.git

2. **Navigate to the project directory:**
    ```bash
    cd your-mern-project

3. **Install server dependencies:**
    ```bash
    cd server 
    npm install

4. **Install client dependencies:**
    ```bash
    cd ../client
    npm install

## Configuration
1. Create a .env file in the server directory based on the .env.example template. Add your MongoDB connection URI and any other required environment variables.

2. Modify client-side configuration if necessary. For example, update API endpoints if they differ from the default.


## Running the Project

1. **Start the server:**
```bash```
    cd ../server
    npm start 

2. **In a separate terminal, start the client:**
```bash```
    cd ../client
    npm start

3. **Your MERN project should now be accessible at http://localhost:3000 in your browser.**

## Project Structure

- `client`: React frontend code.
- `server`: Express.js backend code.

Feel free to explore each directory for more details.

## Contributing
If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a feature branch: git checkout -b feature/your-feature-name
3. Commit your changes: git commit -m "Add some feature"
4. Push the branch: git push origin feature/your-feature-name
5. Create a pull request in this repository.

Also feel free to contribute :)
~ Sharanya