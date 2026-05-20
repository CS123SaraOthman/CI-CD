# CI/CD Automation Project

## Project Description

This project implements a CI/CD workflow to automate the process of updating and deploying a website.

Whenever changes are made to the website files:

1. Changes are automatically pushed to GitHub.
2. Jenkins detects the new updates.
3. Jenkins starts the build process automatically.
4. Docker containers are updated and deployed.

## Technologies Used

- Git & GitHub
- Jenkins
- Docker
- Docker Compose
- Shell Scripts
- Unix/Linux

## Project Files

- `Dockerfile.txt` → Docker image configuration
- `docker-compose.yml` → Container management
- `auto_push.sh` → Automatically pushes updates to GitHub
- `auto_pull.sh` → Pulls updates automatically
- `env.txt` → Environment variables
- `build_steps.txt` → Build instructions

## Workflow

Website Update → GitHub Push → Jenkins Trigger → Build → Deployment

## Goal

The main goal of this project is to reduce manual work and automate the deployment process using CI/CD tools.

## Author

Sara Othman
