# Getting Started with Caderneta Application

## To set up the Caderneta Application, follow these steps:

### Step 1: Clone the Repository

### `git clone https://github.com/lucasfstmd/docker-compose-caderneta`

### `cd caderneta`

### Step 2: Import Dump to MySQL Database

Import the database dump to your MySQL service. Replace your-dump-file.sql with the actual dump file name.

### `docker exect -it db bin/sh`

### `mysql -u your-username -p your-database-name < your-dump-file.sql`

You will be prompted to enter your MySQL password.

### Step 3: Run Docker Compose

Make sure you have Docker installed on your machine. Then, run the following command to start the application using Docker Compose.

### `docker-compose up -d`

This command will launch the application in development mode. 
You can access it at https://localhost in your web-app and https://localhost:8080 to backend.
