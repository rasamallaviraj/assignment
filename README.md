# Employee Management System

A Vue.js application for managing employee records with CRUD operations using MockAPI.

## Setup

1. Install dependencies:
   ```
   npm install
   ```

2. Create a MockAPI project:
   - Go to https://mockapi.io/
   - Create a new project
   - Create a resource named "employees" with the following fields:
     - id (string)
     - name (string)
     - designation (string)
     - department (string)
     - salary (number)

3. Get your API URL, e.g., `https://your-project-id.mockapi.io/employees`

4. Replace the `API_URL` in `src/App.vue` with your MockAPI URL.

5. Run the development server:
   ```
   npm run dev
   ```

## Features

- Add new employees
- View all employees in a table
- Edit employee details
- Delete employees
- Responsive Bootstrap UI

## Technologies

- Vue.js 3
- Axios
- Bootstrap 5
- MockAPI