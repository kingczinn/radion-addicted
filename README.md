#Project Overview

App Description: A web-based todo list where users can add, edit, delete, and mark tasks as complete. It includes a backend API (handling CRUD operations with a lightweight database like SQLite or MongoDB) and a frontend for user interaction. This is simple enough to focus on DevOps without getting bogged down in app logic.
Why This Project?: It's scalable for DevOps demos—easy to containerize, test, and deploy. You can extend it later (e.g., add user auth or persistence).

#Tech Stack:
Backend: Node.js (Express.js for API).
Frontend: React.js (or vanilla JS if you want simpler).
Database: SQLite (file-based, no extra setup) or MongoDB Atlas (free tier for cloud-hosted).
Version Control: Git + GitHub.
Containerization: Docker.
CI/CD: GitHub Actions.
Hosting: Digital Ocean Droplet (for prod).
Domain: Point your domain to the droplet via DO's DNS or your registrar.
