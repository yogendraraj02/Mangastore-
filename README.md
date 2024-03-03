# MangaStore - E-Commerce Project README

## Introduction

Welcome to MangaStore, a basic e-commerce project built using React and Redux. This project aims to provide a simple yet functional platform for purchasing manga comics online. The project utilizes local data stored in JSON format and utilizes JSON-server to serve this data. Key features of the project include product listing, sorting, searching, and cart management with the ability to adjust product quantities.

## Features

1. **Product Listing**: View a list of manga comics available for purchase.
2. **Sorting**: Sort manga comics based on various criteria such as price, popularity, etc.
3. **Searching**: Search for specific manga titles within the store.
4. **Cart Management**: Add manga comics to the cart, adjust quantities, and remove items.

## Technologies Used

- **React**: Frontend UI library for building user interfaces.
- **Redux**: State management library for managing application state.
- **JSON-server**: Lightweight JSON-based REST API server used for serving local data.
- **JavaScript**: Programming language for frontend logic.
- **HTML/CSS**: Markup and styling for the user interface.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

    ```
    git clone https://github.com/yogendraraj02/Mangastore-.git
    ```

2. Navigate to the project directory:

    ```
    cd mangastore
    ```

3. Install dependencies:

    ```
    npm install
    ```

4. Start JSON-server to serve local data:

    ```
    npm run our-json
    ```

5. Start the React application:

    ```
    npm start
    ```

6. Open your browser and navigate to `http://localhost:5173` to view the MangaStore application.

## Project Structure

- **src**: Contains the source code for the React application.
  - **components**: Contains reusable UI components.
  - **redux**: Contains Redux actions, reducers, and store configuration.
  - **pages**: Contains React components for different pages (e.g., ProductListingPage, CartPage).
  - **utils**: Contains utility functions used across the application.
- **db.json**: Contains sample data for manga comics.
- **package.json**: Configuration file for npm dependencies and scripts.
