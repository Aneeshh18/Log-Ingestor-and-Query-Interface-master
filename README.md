# Log Ingester and Query Interface

## Components

- **Log Ingestor:** Responsible for receiving and storing logs.
- **Query Interface:** Facilitates querying and retrieving logs based on filters.

### Technologies Used

- Backend:
  ![Node.js](https://img.shields.io/badge/Node%20js-v14.17.6-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
  ![Express.js](https://img.shields.io/badge/Express%20js-000000?style=for-the-badge&logo=express&logoColor=white)
  ![Mongoose](https://img.shields.io/badge/Mongoose-4EA94B?style=for-the-badge&logo=mongoose&logoColor=white)

- Frontend:
  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

- Other Tools: MongoDB Compass (for database management)

### API Endpoints

- **Create Log:** `http://localhost:3000/api/logs/create`
- **Fetch Logs:** `http://localhost:3000/api/logs/getFilteredLogs`

### Scalability and Performance

- Database indexing

## Features

### 1. Add Logs

- **Description:** This feature allows users to add new logs to the system.
- **Usage:** Developers can use the provided API endpoint or user interface to add logs.

### 2. Get All Logs

- **Description:** Fetches all logs present in the system.
- **Usage:** Access the provided API endpoint or user interface to retrieve all logs.

### 3. Get Filtered Logs

- **Description:** Retrieves logs based on specified filters such as level, message, resourceId, timestamp, etc.
- **Usage:** Use the API endpoint with filters or the provided user interface to get logs based on filter criteria.

### Getting Started

**1. Clone the Repository**

```bash
git clone https://github.com/Aneeshh18/Log-Ingestor-and-Query-Interface-master.git
```

### Navigate to 'Log-ingester' and 'query-interface' folders and run this app-

```
cd Log-ingester
```

```
npm install
```

```
cd query-interface
```

```
npm install
```

## MongoDB Configuration

- Install MongoDB Compass or use any preferred MongoDB management tool.
- Create a .env file in the 'log-ingester' folder.
- Add the MongoDB URL in the .env file.

```
DB_URL=mongodb://localhost:27017/log-ingester
```
