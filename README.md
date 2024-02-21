# Roxiler Frontend

Welcome to the Roxiler Frontend repository! This project provides a user interface to interact with the backend APIs for managing and analyzing product transactions.

## Usage

To utilize the frontend application, please follow these steps:

1. Ensure the backend API is deployed and accessible.
2. Clone this repository to your local machine.
3. Install the necessary dependencies using npm or yarn:

   ```bash
   npm install
   ```

4. Start the frontend application:

   ```bash
   npm start
   ```

5. Access the application through your web browser at http://localhost:3000.

## Features

### Transactions Table

- **Select Month Dropdown**: Allows users to choose a specific month for viewing transactions. The default selection is March.
- **Transactions List**: Displays transactions based on the selected month and search criteria.
  - The search functionality filters transactions by title, description, or price.
  - Pagination controls enable navigation through transaction pages.

### Transactions Statistics

- Presents insights such as total sale amount, total sold items, and total unsold items for the chosen month.

### Transactions Bar Chart

- Illustrates a bar chart representing price ranges and the corresponding number of items sold within each range for the selected month.

## Deployment

Here are the deployment steps to run the frontend application on localhost:

1. **Ensure Backend API is Running**: Before deploying the frontend, make sure the backend API is deployed and accessible.

2. **Clone Repository**: Clone the frontend repository to your local machine using Git. Open your terminal and run the following command:

git clone <frontend_repository_url>

Replace `<frontend_repository_url>` with the URL of your frontend repository.

3. **Navigate to Project Directory**: Move into the project directory using the `cd` command:

   cd roxiler-frontend

4. **Install Dependencies**: Use npm or yarn to install the necessary dependencies:

   npm install

5. **Start Development Server**: Start the development server to run the frontend application locally:

   npm start

6. **Access Application**: Once the server is running, access the frontend application through your web browser at [http://localhost:3000](http://localhost:3000).
