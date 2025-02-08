# Employee Management System (EMS) Frontend

This project is a frontend application for an Employee Management System (EMS) built using React and Vite. The application allows users to perform CRUD (Create, Read, Update, Delete) operations on employee data. It uses React Router for navigation and Axios for making HTTP requests to a backend API.

## Project Structure

The project has the following structure:

```
ems-frontend/
  .gitignore
  eslint.config.js
  index.html
  package.json
  public/
    vite.svg
  README.md
  src/
    App.css
    App.jsx
    assets/
      react.svg
    components/
      EmployeeComponent.jsx
      FooterComponent.jsx
      HeaderComponent.jsx
      ListEmployeeComponent.jsx
    HelloWorld.jsx
    index.css
    main.jsx
    services/
      EmployeeService.js
  vite.config.js
```

### Key Files and Directories

- **index.html**: The main HTML file that includes the root div and script to load the React application.
- **eslint.config.js**: Configuration file for ESLint, specifying rules and plugins for linting the code.
- **package.json**: Contains project metadata, dependencies, and scripts for building and running the application.
- **public/**: Contains static assets like the Vite logo.
- **src/**: Contains the source code for the React application.
  - **App.css**: Global CSS styles for the application.
  - **App.jsx**: The main application component that sets up routing and includes the header, footer, and main content.
  - **components/**: Contains React components used in the application.
    - **EmployeeComponent.jsx**: Component for adding and updating employee details.
    - **FooterComponent.jsx**: Footer component displayed at the bottom of the page.
    - **HeaderComponent.jsx**: Header component displayed at the top of the page.
    - **ListEmployeeComponent.jsx**: Component for displaying the list of employees and providing options to add, update, or delete employees.
  - **HelloWorld.jsx**: A simple component that displays "Hello, World!".
  - **index.css**: Additional CSS styles for the application.
  - **main.jsx**: Entry point for the React application, rendering the `App` component.
  - **services/**: Contains service files for making HTTP requests.
    - **EmployeeService.js**: Service file for making HTTP requests related to employee data.

## Dependencies

The project uses the following dependencies:

- **axios**: For making HTTP requests.
- **bootstrap**: For styling the application.
- **react**: The core React library.
- **react-dom**: For rendering React components in the DOM.
- **react-router-dom**: For handling routing in the application.

## Dev Dependencies

The project uses the following development dependencies:

- **@eslint/js**: ESLint configuration for JavaScript.
- **@types/react**: TypeScript type definitions for React.
- **@types/react-dom**: TypeScript type definitions for React DOM.
- **@vitejs/plugin-react**: Vite plugin for React.
- **eslint**: Linter for JavaScript and JSX.
- **eslint-plugin-react**: ESLint plugin for React-specific linting rules.
- **eslint-plugin-react-hooks**: ESLint plugin for React hooks-specific linting rules.
- **eslint-plugin-react-refresh**: ESLint plugin for React Fast Refresh.
- **globals**: Global variables for ESLint.
- **vite**: Build tool for modern web projects.

## Scripts

The following scripts are defined in the `package.json` file:

- **dev**: Starts the development server using Vite.
- **build**: Builds the application for production using Vite.
- **lint**: Runs ESLint to lint the code.
- **preview**: Previews the production build using Vite.

## Running the Project

To run the project locally, follow these steps:

1. **Install dependencies**: Run `npm install` to install all the required dependencies.
2. **Start the development server**: Run `npm run dev` to start the development server. The application will be available at `http://localhost:3000`.
3. **Build the application**: Run `npm run build` to build the application for production. The build output will be in the `dist` directory.
4. **Preview the production build**: Run `npm run preview` to preview the production build.

## ESLint Configuration

The project uses ESLint for linting the code. The configuration is defined in the `eslint.config.js` file. It includes rules and plugins for React, React hooks, and React Fast Refresh.

## Vite Configuration

The project uses Vite as the build tool. The configuration is defined in the `vite.config.js` file. It includes the React plugin and sets the development server port to 3000.

## Components

### EmployeeComponent

The `EmployeeComponent` is used for adding and updating employee details. It includes form validation and makes HTTP requests to the backend API to save or update employee data.

### FooterComponent

The `FooterComponent` displays a footer at the bottom of the page with a copyright message.

### HeaderComponent

The `HeaderComponent` displays a header at the top of the page with the application title.

### ListEmployeeComponent

The `ListEmployeeComponent` displays a list of employees and provides options to add, update, or delete employees. It makes HTTP requests to the backend API to fetch and manipulate employee data.

## Services

### EmployeeService

The `EmployeeService` file contains functions for making HTTP requests related to employee data. It uses Axios to send requests to the backend API.

- **listEmployees**: Fetches the list of employees.
- **createEmployee**: Creates a new employee.
- **getEmployee**: Fetches details of a specific employee.
- **updateEmployee**: Updates details of a specific employee.
- **deleteEmployee**: Deletes a specific employee.

## Styling

The project uses Bootstrap for styling. Additional styles are defined in the `App.css` and `index.css` files.

## License

This project is licensed under the MIT License.
