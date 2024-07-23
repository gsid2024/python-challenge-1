# python-challenge-1
Challenge 2 July 22 2024
Challenge 2 July 22 2024
Overview:
The goal of this challenge is to develop an interactive order system for a food truck, which allows customers to select items from a categorized menu, specify quantities, and receive a summary of their order. This document provides an analysis of the implemented solution, outlining the functionality, user interactions, and code logic.
Functional Requirements
Menu Structure:
The system uses a predefined menu with categories: Snacks, Meals, Drinks, and Dessert.
Each category contains a list of items with corresponding prices, which may be nested (e.g., sub-categories like different types of pizza or drinks).
Ordering Process:
The system prompts users to select a menu category.
After category selection, users choose specific items and specify quantities.
The system calculates the total order cost and provides a summary.
User Interaction:
Users are guided through a series of prompts to ensure clear selection and input.
The system handles invalid inputs and offers options to continue or finalize the order.
Code Analysis:
- Initialization
The menu is initialized with categories and items, including nested items for more detailed selections.
An empty list is prepared to store the customer's order.
- Order Flow
Category Selection
Users are presented with a list of menu categories.
Input validation ensures the selected category is valid.
- Item Selection
Items within the selected category are displayed.
Nested items are properly formatted for clear presentation.
Users select items by number, with input validation to handle incorrect selections.
- Quantity Specification
Users specify the quantity for each selected item.
Default quantity is set to 1 if the input is invalid.
- Order Continuation
Users are asked if they want to continue ordering.
Input validation ensures proper handling of 'Yes' or 'No' responses.
- Output
A detailed receipt is generated, listing items with their prices and quantities.
The total cost of the order is calculated and displayed.
