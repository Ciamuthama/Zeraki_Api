 ### README.md

## Zeraki Sales Agent Dashboard Server

### Project Overview:
The Zeraki Sales Agent Dashboard Server is built using JSON Server to provide mock REST API functionality for the sales agent dashboard application. This server facilitates the simulation of real-time data updates without the need for a backend server, allowing seamless development and testing of the dashboard features related to school accounts, invoicing, and collections.

### Setup Instructions:
To set up and run the JSON Server for the Zeraki Sales Agent Dashboard locally, follow these steps:

1. Clone the repository from the GitHub link provided: [GitHub Repository](https://github.com/Ciamuthama/Zeraki_Api/).
2. Navigate to the project directory in your terminal.
3. Install JSON Server globally by running:

```bash
npm install -g json-server
```
4. Start the JSON Server using the provided mock JSON data file:

```bash
json-server --watch db.json --port 3000
```
5. Access the server endpoints at `http://localhost:3000`.

### Key Design Decisions:
1. **Framework**: JSON Server is utilized to create a full mock REST API using simple JSON files, enabling easy development of the sales agent dashboard application.
2. **Data Simulation**: Mock JSON data is used to mimic real data scenarios and interactions, facilitating front-end development without a live backend environment.
3. **Server Configuration**: The server is configured to watch the `db.json` file and expose RESTful endpoints for CRUD operations on the mock school, invoice, and collection data.

### Additional Information:
For access to the complete JSON Server repository and configurations, refer to the provided GitHub link. 

For any inquiries or support regarding the server setup and usage, please contact the project maintainers.

---
You can further customize this README to include specific details or instructions relevant to your project's JSON Server setup. Best of luck with your server development!  
