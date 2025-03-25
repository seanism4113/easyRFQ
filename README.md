# EasyRFQ

[https://easyrfq.onrender.com/](https://easyrfq.onrender.com/)

EasyRFQ is a user-friendly platform designed to streamline the process of creating and managing customer Requests for Quotes (RFQs). With its intuitive interface, users can easily enter, track, and manage RFQs, simplifying the way businesses handle quoting and customer requests.

### EasyRFQs allows users to:

- Register an account and link it to your business
- Access and manage your company’s directory
- Easily create, view, and update items in Item Maintenance
- Manage and update customer information in Customer Maintenance
  - Set custom fixed or percentage markups per customer
- Create, view, and modify Requests for Quotes (RFQs) from customers
- Seamlessly convert RFQs into ready-to-send quotes for customers

## EasyRFQ | HomePage Logged In

![HomePage](EasyRFQ/readMeImages/EasyRFQ%20Home.png)

## EasyRFQ | Item Maintenance

![Item Maintenance](EasyRFQ/readMeImages/Item%20Maintenance.png)

## EasyRFQ | Customer Maintenance

![Customer Maintenance](EasyRFQ/readMeImages/Customer%20Maintenance.png)

## EasyRFQ | RFQ List

![RFQ List view](EasyRFQ/readMeImages/RFQ%20Details.png)

## EasyRFQ | Quote Template

![Quote Template](EasyRFQ/readMeImages/Quote%20Template.png)

## Setup

### Clone this repository

```bash
$ git clone https://github.com/seanism4113/easyRFQ.git
$ cd EasyRFQ
```

### Install full-stack dependencies

```bash
$ npm install
```

### Install backend dependencies

```bash
$ cd easyRFQ-backend
$ npm install
```

### Set backend .env constants

```bash
$ touch .env
```

- In the env file you will need to create a constant for:

```bash
DATABASE_URL
NODE_ENV
SECRET_KEY
```

DATABASE URL

- Connect to your local database or an online database. Example of connection to postgres:
  DATABASE_URL=postgresql:///easy_rfq

NODE_ENV

- NODE_ENV=production

SECRET_KEY

- Create your own secret key. Example SECRET_KEY = 'secretkey'

### Install frontend dependencies

```bash
$ cd ..
$ cd easyRFQ-frontend
$ npm install
```

### Return to main folder and Run project

```bash
$ cd ..
$ npm run dev
```

### Open backend in browser

- Go to http://localhost:3001/companies . Replace companies with database location you wish to see.

### Open frontend in browser

- Go to http://localhost:5173

## Technology Used

### Full-stack

- concurrently – Run multiple commands (e.g., start backend & frontend) simultaneously

### Backend

- bcrypt – Hash and compare passwords securely
- body-parser – Parse incoming request bodies in middleware
- colors – Add color to console logs for better readability
- cors – Enable Cross-Origin Resource Sharing (CORS) for API requests
- dotenv – Load environment variables from a .env file
- express – Minimalist web framework for Node.js
- jsonschema – Validate JSON data against a schema
- jsonwebtoken – Create and verify JSON Web Tokens (JWT) for authentication
- morgan – HTTP request logger for Express apps
- pg – PostgreSQL client for Node.js

Frontend

- axios – HTTP client for making API requests
- dotenv – Load environment variables in the frontend
- font-awesome – Icon library for adding scalable vector icons
- jwt-decode – Decode JWTs on the client side
- react – JavaScript library for building åuser interfaces
- react-dom – Render React components in the DOM
- react-icons – Import and use various icons as React components
- react-router-dom – Handle routing and navigation in a React app
