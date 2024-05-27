
# Taco Recipes

## Taco Recipes is a short project demonstrating how to transform JSON data into a JavaScript object using Express.

To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone git@github.com:Nickgalant/Taco-Recipes.git

2. Clone the repository:
   ```bash
   npm install

3. Run the server:
   ```bash
   npm start

## Overview
Taco Recipes is a simple Express.js application that reads taco recipes stored in JSON format and transforms them into JavaScript objects. It's a basic demonstration of how to use Express with EJS templates to serve dynamic content.

## Features
 * Parses JSON data using Express.
 * Serves the parsed data to clients using EJS templates.
 * Basic HTML interface to display the taco recipes.

## Usage
   * GET /recipes/
: Retrieves a specific taco recipe by ID and renders it using EJS templates.

## Project Structure
The project structure is as follows:
 * `index.js`: Main Express application file.
 * `recipe.json`: JSON file containing taco recipes.
 * `public/`: Directory containing static files (CSS).
 * `views/`: Directory containing EJS templates.

## Dependencies
 * Express.js: Fast, unopinionated, minimalist web framework for Node.js.
 * EJS: Embedded JavaScript templates for rendering dynamic content.
 * body-parser: Node.js body parsing middleware, required for handling POST requests.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.