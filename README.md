# Angular HTTP Request Handling Example

This is an Angular application that demonstrates how to fetch data from a mock REST API using Angular's `HttpClient`, handle HTTP requests, and display the fetched data in a component. The application also includes error handling for failed HTTP requests.

## Features

- Fetch data from a mock REST API.
- Display the fetched data in a responsive layout.
- Implement error handling for HTTP request failures.
- Sort data by title.

## Prerequisites

Make sure to have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or later)
- [Angular CLI](https://angular.io/cli) (install it globally using `npm install -g @angular/cli`)

## Setup Instructions

1. **Navigate to the frontend folder:**
 cd pathToFolder

## Install dependencies:

## Run the following command to install the necessary packages:

npm install

## Start the development server with the following command:

ng serve

## Open the application in browser:

# Navigate to http://localhost:4200 in your web browser and see the application running.

## Application Structure
src/app: Contains the application modules and components.
data-display: Contains the component responsible for displaying data.
data.service.ts: Contains the service that handles HTTP requests.

## Usage
The application fetches data from the mock REST API when it is loaded.
You can click the "Sort Data" button to sort data.
Any errors that occur during the fetch operation will be displayed in a user-friendly alert.
