# dianas-market

## Description
AS A manager at an internet retail company
I WANT a back end for my e-commerce website Diana's Market that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

Refer to the [Diana's Market Demo Video](https://github.com/bekkahhuss/dianas-market/blob/main/assets/dianas_market_demo.mp4) for this application. The demo will demonstrate the following:

<u>Launch</u>

- Ability to start the server and sync with the function Express.js API

<u>Categories</u>

- Use GET /api/categories to retrieve all categories
- Use GET /api/categories/:id to review a specific category
- Use POST /api/categories to create a new category
- Use PUT /api/categories to update an existing category
- Use DELETE /api/categories/:id to delete an existing category

<u>Products</u>

- Use GET /api/products to retrieve all products
- Use GET /api/products/:id to review a specific product
- Use POST /api/products to create a new product
- Use PUT /api/products to update an existing product
- Use DELETE /api/products/:id to delete an existing products

<u>Tags</u>

- Use GET /api/tags to retrieve all tags
- Use GET /api/tags/:id to review a specific tag
- Use POST /api/tags to create a new tag
- Use PUT /api/tagsto update an existing tag
- Use DELETE /api/tags/:id to delete an existing tag

## Installation
- `git clone git@github.com:bekkahhuss/dianas-market.git`
- Open the cloned folder in Visual Studio
- Open the terminal and login to mysql. Enter commands: 
    - CREATE DATABASE dianas_market
    - USE dianas_market
    -quit 
- Right click /seeds/index.js and select Open in Integrated Terminal
- Enter `node index.js` : this will load the seed files
- Enter `cd ..`
- Enter `node server.js` : this will start the Express.js server
- Open Insomnia and create GET, POST, PUT, DELETE requests as needed
- Use http://localhost:3001/api/ 
    - categories
    - products
    - tags

## Usage
- Express.js
- dotenv
- Insomnia
- MySQL2
- Sequelize

## Images
![Example Image](https://github.com/bekkahhuss/dianas-market/blob/main/assets/dianas_market_screenshot.png)/'p[=]