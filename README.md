# Shopify Back-End

Backend application for the Shopify e-commerce project built with Node.js, Express.js, and MongoDB Atlas.

## Overview

The Shopify Backend Part handles API communication, provides endpoints for the frontend, and utilizes MongoDB Atlas as the database.

## Table of Contents
- [Installation](#installation)
- [Features](#features)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Installation

To set up the Shopify Backend locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/nikhilgugwad/Shopify-Back-End.git
cd backend
```

2. Install the dependencies:

```bash
npm install
```

## Features

1. **API Endpoints:**
   Define endpoints to handle communication with the frontend.

2. **MongoDB Atlas Integration:**
   Utilize MongoDB Atlas as the database for storing and managing product data.

## Dependencies

The backend is built using Node.js and Express.js for API development. MongoDB Atlas is used as the database. Ensure the following dependencies are installed using the command provided in the installation steps:

- **cors**: ^2.8.5
- **express**: ^4.18.2
- **jsonwebtoken**: ^9.0.2
- **mongoose**: ^8.0.3
- **multer**: ^1.4.5-lts.1

## Usage

1. Start the server:

```bash
npm start
```

2. The server will run on [http://localhost:3001](http://localhost:3001) by default.

3. Connect the frontend to this backend by updating the API base URL.
