# docker-wordpress
Base Docker Compose code to setup new or blank WordPress sites

## features
- Easy WordPress setup
- Customizable environment variables

## using the image
To get started, follow the instructions below. This guide assumes **Docker** is installed on your machine. If you need to install **Docker**, [read up](https://docs.docker.com/get-docker/)

> * Step 1: Create your **Wordpress** project folder: $ mkdir my-wordpress-website
> * Step 2: Clone the repository: $ git clone https://github.com/olawoye/docker-wordpress.git my-wordpress-website/
> * Step 3: Navigate to the project folder and create an .env file: $ cd my-wordpress-website && cp .env.example .env
> * Step 4: Configure your setup by editing the .env file as necessary: $ nano .env
> * Step 5: Power up the **WordPress** installation: $ docker-compose up -d
> * Step 6: Open your browser and visit http://localhost:10000 (or your preferred configured port) and setup **WordPress** as usual


## getting help
If you need additional help using the code, please [email](private_bj@yahoo.com)

## whats new
- customize environment variables

## license
This code is open-source software licensed under the [**MIT License**](https://www.mit.edu/~amini/LICENSE.md)
