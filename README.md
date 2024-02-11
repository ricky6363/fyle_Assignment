# fyle_Assignment
Assignment
# Angular SPA Assignment

This repository contains the Angular single-page application (SPA) developed as part of the Fyle internship challenge.

## Getting Started

To run the application locally, follow these steps:

1. Install Node.js and npm if not already installed.
2. Clone this repository to your local machine.
3. Navigate to the project directory and run `npm install` to install dependencies.
4. Run `ng serve` to start the development server.
5. Open your browser and navigate to `http://localhost:4200` to view the application.

## Unit Tests

The project includes unit tests for the `AppComponent` and `ApiService`.

To run the tests, execute the following command:

ng test


This will run the tests using Jasmine and Karma and display the test results in the terminal.

## Hosting the SPA

The application is hosted on [Netlify](https://www.netlify.com/). You can access the live demo [here](https://example.com).

## Caching API Calls

The `ApiService` includes caching logic to cache GET requests to external APIs. Caching is implemented using local storage to improve performance and reduce redundant API calls.

