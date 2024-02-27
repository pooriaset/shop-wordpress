# Installation

### Environments

Copy the `.env` file to `.env.sample` for Docker Compose environment variables as shown below:

```
MYSQL_ROOT_PASSWORD=password
MYSQL_DATABASE=db_name
MYSQL_PASSWORD=password
WORDPRESS_DB_USER=root
WORDPRESS_DB_PASSWORD=password
WORDPRESS_DB_NAME=db_name
```

### Initialize Containers

Run the following command to initialize Docker containers:

```bash
docker compose up -d
```

Make sure to execute these steps properly to set up your environment.
