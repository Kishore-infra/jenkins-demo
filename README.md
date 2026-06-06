# Jenkins CI/CD Demo

## Project Overview
This project demonstrates a simple CI/CD pipeline using Jenkins, GitHub, and Flask.

## Technologies Used
- Git
- GitHub
- Jenkins
- Python
- Flask
- Linux (Ubuntu)
- AWS EC2

## CI/CD Flow

Developer
→ GitHub Push
→ GitHub Webhook
→ Jenkins Build Trigger
→ Jenkins Executes Shell Script
→ Flask Application Restarted
→ Updated Application Available

## Files

app.py - Flask application

requirements.txt - Python dependencies

## How to Run

```bash
pip install -r requirements.txt
python3 app.py
