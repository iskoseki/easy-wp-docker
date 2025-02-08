
# WordPress Docker Setup

This template allows you to easily set up a WordPress development environment using Docker.

## 🚀 Requirements

* [Docker](https://www.docker.com/) installed on your system.
* [Docker Compose](https://docs.docker.com/compose/) installed.

## 📌 Installation

1. Clone this repository:

   ```sh
   git clone https://github.com/iskoseki/easy-wp-docker.git
   cd wordpress-docker-setup
   ```
2. Create a `.env` file based on the example:

   ```sh
   cp .env.example .env
   ```

   Edit `.env` with the values you need.
3. Start the containers:

   ```sh
   docker-compose up -d
   ```
4. Access WordPress in your browser:

   ```
   http://localhost:8080
   ```

## 🛠️ Useful Commands

* **Stop the containers:**
  ```sh
  docker-compose down
  ```
* **Restart the containers:**
  ```sh
  docker-compose restart
  ```
* **View logs:**
  ```sh
  docker-compose logs -f
  ```

## 🏗️ Customization

You can modify the `docker-compose.yml` file to change configurations such as WordPress versions, MySQL, or volumes.

## 📜 License

This project is licensed under the [MIT](https://chatgpt.com/c/LICENSE) license.
