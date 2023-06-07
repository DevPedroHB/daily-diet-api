<h1 align="center">Daily Diet API</h1>

<p align="center">
  This API is intended for daily diet control, allowing users to record food consumed throughout the day, calculate nutritional information and track progress against established goals.
</p>

<p align="center">
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-services">Services</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-packages">Packages</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-features">Features</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-links">Links</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#-versioning">Versioning</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

## 🚀 Technologies

Here are the technologies used in this project.

- TypeScript 4.9.5
- NodeJS 18.13.0
- Fastify 4.12.0
- Vitest 0.28.4
- Knex 2.4.2

## 📋 Services

Here are the services used in this project.

- [GitHub](https://github.com/)

## 📦 Packages

Here are the packages used in this project.

- <b>@fastify/cookie</b> -> A plugin for the Fastify framework that allows developers to set, get and delete HTTP cookies.
- <b>zod</b> -> Used to validate and manipulate structured data with JavaScript.

## 🔥 Features

Here are the main features of the project.

- Application Rules
  - [x] Must be possible to create a user
  - [x] It must be possible to identify the user among the requests
  - [x] It must be possible to register a meal made, with the following information:
        _Meals must be related to a user._
    - Name
    - Description
    - Date and time
    - Is on or off the diet
  - [x] It must be possible to edit a meal, being able to change all the above data
  - [x] It must be possible to delete a meal
  - [x] It should be possible to list all meals of a user
  - [x] It should be possible to visualize a single meal
  - [x] It must be possible to retrieve a user's metrics
    - Total number of registered meals
    - Total amount of meals within the diet
    - Total number of meals outside the diet
    - Best sequence per day of meals within the diet
  - [x] User can only view, edit and delete meals which he created
- Endpoints:
  - POST /users: Create a new user if not exists.
  - GET /meals: List all meals.
  - POST /meals: Create a new meal.
  - PUT /meals: Update a meal.
  - GET /meals/:id: List all meals for a user.
  - PATCH /meals/:id: Lists a specific meal.
  - DELETE /meals/:id: Lists a meal.
  - GET /resume: Retrieve a user's metrics.

## 📎 Links

- Deploy on [](): Em breve
- Repository: https://github.com/DevPedroHB/daily-diet-api

## 🔰 Versioning

Here are the versions of the parts of the project.

- API -> 1.0.0

## :memo: License

This project is licensed under the MIT license.

---

Made with ♥ by Pedro Henrique 🚀 [Never stop learning!](https://github.com/DevPedroHB)
