Pizzas Restaurants API
This is a Rails API application that allows you to track pizza restaurants and their associated pizzas. The API provides endpoints to manage restaurants, pizzas, and their relationships.

Requirements
Ruby 2.7.0 Rails 6.1.4 Getting Started To set up the application, follow these steps:

Clone the repository:git clone git@github.com:Freddy-ux/code-challenge.git

Start the Rails server :rails server The API will be accessible at http://localhost:3000.

Models and Associations
The application has the following models and associations:

Restaurant: Represents a pizza restaurant.

has many Pizza through RestaurantPizza Pizza: Represents a pizza.

has many Restaurants through RestaurantPizza RestaurantPizza: Represents the association between a restaurant and a pizza.

belongs to a Restaurant and belongs to a Pizza Endpoints The API provides the following endpoints:

GET /restaurants: Get a list of all restaurants. GET /restaurants/id Get detailed information about a specific restaurant. DELETE /restaurants/id Delete a restaurant by its ID. GET /pizzas: Get a list of all pizzas. POST /restaurant_pizzas: Create a new restaurant-pizza association. Please refer to the original requirements for the expected request and response formats of each endpoint.

Lisence
This project is licensed under the MIT License.

Author : Alfred Wambua 
Research : Google, ChatGPT