# ExpressJS Authentication Server

This repository contains an ExpressJS server connected to MongoDB with authentication set up using JSON Web Tokens (JWT).

## Getting Started

Follow these steps to set up and run the server:

### Prerequisites

- Node.js installed on your machine
- MongoDB instance (local or cloud)

### Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd ExpressJS-authentication
    ```

2. Create a `.env` file in the root directory and add the following variables:
    ```env
    ACCESS_TOKEN_SECRET=<your-access-token-secret>
    REFRESH_TOKEN_SECRET=<your-refresh-token-secret>
    DATABASE_URI=<your-mongodb-uri>
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

4. Start the development server:
    ```sh
    npm run dev
    ```

### Usage

This server is intended for development purposes to facilitate easy startup and testing of authentication mechanisms.

### License

This project is licensed under the MIT License.