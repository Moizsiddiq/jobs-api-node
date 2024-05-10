# Jobs API
Jobs API is a Node.js application that provides authentication endpoints (register and login) and CRUD operations for managing jobs. The authentication routes are public, while the job-related routes are protected.

## Getting Started

### Prerequisites

- Node.js (v12 or higher)
- npm (Node Package Manager)
- MongoDB (Make sure you have a running MongoDB instance)

### Installation

1. Clone the repository:  ``` git clone https://github.com/Kalutu/jobs-api ```
2. Change into the project directory:  ``` cd jobs-api```
3. Install dependencies:  ``` npm install ```

### Configuration
Create a .env file in the root directory with the following content:
- PORT=your port
- MONGO_URI=your connection string
- JWT_SECRET=your-secret-key

## API Endpoints

### Public Routes:

- `POST /api/v1/auth/register`: Register a new user.
- `POST /api/v1/auth/login`: Authenticate and log in a user.

### Protected Routes:

- `POST /api/v1/jobs`: Create a new job.
- `GET /api/v1/jobs`: Get all jobs.
- `GET /api/v1/jobs/:id`: Get a specific job by ID.
- `PUT /api/v1/jobs/:id`: Update a job by ID.
- `DELETE /api/v1/jobs/:id`: Delete a job by ID.


