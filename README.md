# QuickHire - Job Portal (Server)

This is the backend server for the QuickHire job portal application.  
It provides REST APIs for job listings and job applications.

## 🚀 Features

- Create job postings
- Get all jobs
- Get single job details
- Apply for a job
- View user job applications
- Delete job applications
- MongoDB database integration

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB
- dotenv
- CORS

## ⚙️ Environment Variables

Create a `.env` file in the root directory and add:


DB_USER=quick-hire
DB_PASS=y480SIpGzh1ScR7L


These variables are used to connect to MongoDB.

## 📦 Installation

Clone the repository:
git clone https://github.com/Muhammad-Mirazul-Hasan-Rafee/quick-hire-server.git

Go to the server directory:
cd quichire-server

Install dependencies:
npm install

Run the server:

nodemon index.js
or
node index.js


The server will run on:


http://localhost:5000


## 📡 API Endpoints
### Jobs APIs
#### Get all jobs

GET /jobs


#### Get single job details

GET /jobs/:id

#### Create a job

POST /jobs

---

### Job Application APIs

#### Apply for a job

POST /job-application

#### Get applications by email

GET /job-application?email=user@email.com

#### Delete an application

DELETE /jobs/:id


## 🗄 Database Collections

jobs
job_applications
users

## 👨‍💻 Author

Hasan Rafee