# E-commerce Back End

## Overview

This project utilizes an Express.js API, configured with Sequelize, to connect to a MySQL database. Also present is mysql2 and dotenv. The database features test data with categories, products, and tags related to retail items to give the user an idea of how they can view their inventory.

## User Story

As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies so that my company can compete with other e-commerce companies.

## How it Works

When MySQL credentials are added in an environment variable file, the user can connect to the database using Sequelize. The user must enter schema and seed commands, and a development database is created and is seeded with test data. The user can then enter the command to invoke the application, at which time the server is started and the Sequelize models are synced to the MySQL database.

Utilizing the Insomnia application, the user can open API GET routes for categories, products, or tags. The data for each of these routes is displayed in a formatted JSON. The user can then test API POST, PUT, and DELETE routes using Insomnia, will successfully be able to create, update, and delete data in the database.

## Demo Video
https://drive.google.com/file/d/17-wKOadprY6WIbZ1M2t8HwLdc7PTLROb/view
