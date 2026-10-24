# PHP and MySQL CRUD App

A simple CRUD application built with PHP and MySQL and run using Docker. It lets you create, view, update, and delete user records.

## How it works

The PHP application and MySQL database run in separate Docker containers. The app connects to the database through a shared Docker network.

## Features

- Create user records
- View saved users
- Update user details
- Delete users

## Run with Docker

Pull the PHP and MySQL images from Docker Hub, then start the containers on the same Docker network. Configure the PHP app with the database container name, database name, username, and password.

Open the application at:

[http://localhost:8081](http://localhost:8081)

## Technologies

- PHP
- MySQL
- Docker
