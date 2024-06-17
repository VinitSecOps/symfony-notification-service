# symfony-notification-service
Project Overview:
This project sets up a Symfony application with a MySQL database using Docker and Docker Compose. The setup includes services for the application and the database.

Services Description:
App: Runs the Symfony application.
DB: MySQL database service.

Setup Instructions:
1.	Clone the repository.
2.	Ensure Docker and Docker Compose are installed.
3.	Configure environment variables in the .env file.
4.	Build and start the containers: docker-compose up –build

Known Issues and Resolutions:
Composer Plugins Disabled: Ensure Composer runs as a non-root user and set COMPOSER_ALLOW_SUPERUSER=1 if needed.
Environment Variables: Double-check the .env file and docker-compose.yml for correct variable definitions.
