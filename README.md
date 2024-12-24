# Problem Statements
Problem 1: Task Management System

Objective: Create a system to manage daily tasks dynamically.

Tasks:

Create an array of task objects. Each object should contain:

title (string): The name of the task.

status (string): Either "Pending" or "Completed".

priority (number): A value between 1 (low priority) and 5 (high priority).

Write the following functions:

Add Task: Use an arrow function to add a new task object to the array.

Filter by Status: Use filter() to return all tasks based on their status.

Find High Priority Task: Use find() to get the first task with a priority of 5.

Use map() to create a list of task titles with their status, formatted as: "Task: [Title], Status: [Status]".

Use template literals to log the details of all tasks in a readable format.

Problem 2: Online Shopping Cart

Objective: Develop a simple shopping cart system.

Tasks:

Create an array of product objects, where each object contains: productName (string), price (number), quantity (number).

Write the following functions:

Add Product: Function to add a new product to the cart.

Calculate Total: Use reduce() to calculate the total cost of all items in the cart.

Remove Product: Use an arrow function to remove a product by name.

Use destructuring to extract and log product details (e.g., name and price) for each product in the cart.

Use template literals to display a summary of the cart in this format: "Product: [Name], Price: $[Price], Quantity: [Quantity]".

Problem 3: Weather Forecast Tracker

Objective: Build a tracker to manage weather data for different cities.

Tasks:

Create an array of city weather objects, where each object contains: cityName (string), temperature (number in Celsius), condition (string, e.g., "Sunny", "Cloudy", "Rainy").

Write the following functions:

Add City Weather: Function to add a new city weather object.

Find Hottest City: Use find() to identify the city with the highest temperature.

Filter by Condition: Use filter() to list all cities with a specific weather condition.

Use map() to create a list of city names with their temperatures in the format: "City: [CityName], Temp: [Temperature]°C".

Use destructuring to extract and log details of the hottest city.

Use template literals to log a weather summary for all cities in this format: "City: [Name], Temp: [Temp]°C, Condition: [Condition]".

Add a feature to sort cities by temperature.

Include a function to convert temperatures between Celsius and Fahrenheit.
