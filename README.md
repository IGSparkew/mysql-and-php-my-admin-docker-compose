# MySQL and phpMyAdmin Setup

This repository contains configuration files for setting up a MySQL database server with phpMyAdmin for database management through a web interface.

## Prerequisites

- Docker
- Docker Compose

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/mysql_phpmyadmin.git
    cd mysql_phpmyadmin
    ```

2. Create a `.env` file with your desired configuration:
    ```
    MYSQL_ROOT_PASSWORD=your_root_password
    MYSQL_DATABASE=your_database
    MYSQL_USER=your_user
    MYSQL_PASSWORD=your_password
    ```

## Running the Services

1. Start the containers:
    ```bash
    docker-compose up -d
    ```

2. Access phpMyAdmin:
    - Open your browser and navigate to `http://localhost:${PHP_MY_ADMIN_PORT}`
    - Login with your MySQL credentials



