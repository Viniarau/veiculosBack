# Vehicles API

## Overview
This is a simple Node.js API project for managing vehicles data. It provides basic CRUD operations for vehicles stored in a JSON file.

## Prerequisites
Before running this project, make sure you have the following installed:

Node.js
npm (Node Package Manager)

# Installation
1. Clone this repository to your local machine:
```
git clone https://github.com/Viniarau/veiculosBack.git
```
2. Navigate to the project directory:
```
cd veiculosBack
```
3. Install dependencies:
```
npm install
```

# Usage

1. Start the server:
```
npm start
```
2. The server will start running at http://localhost:3000.

# API Endpoints

## Get All Vehicles

* URL: /vehicles
* Method: GET
* Description: Retrieves all vehicles stored in the database.
* Response: JSON array of vehicle objects.

## Get Vehicle by ID

* URL: /vehicles/:id
* Method: GET
* Description: Retrieves a specific vehicle by its ID.
* Response: JSON object representing the vehicle.

## Create Vehicle

* URL: /vehicles
* Method: POST
* Description: Creates a new vehicle.
* Request Body: JSON object representing the new vehicle.
* Response: JSON object representing the created vehicle.

## Update Vehicle

* URL: /vehicles/:id
* Method: PUT
* Description: Updates an existing vehicle by its ID.
* Request Body: JSON object representing the updated vehicle.
* Response: JSON object representing the updated vehicle.

## Delete Vehicle

* URL: /vehicles/:id
* Method: DELETE
* Description: Deletes a vehicle by its ID.
* Response: Success message.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

License
This project is licensed under the MIT License.
