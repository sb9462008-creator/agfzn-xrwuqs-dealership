# agfzn-xrwuqs-dealership

## Project Name: Best Cars Dealership - Full Stack Web Application

### Repository Name: agfzn-xrwuqs-dealership

## Description

A national car dealership web application built with Django, React, Flask, Node.js, MongoDB, and SQLite. Users can browse dealership branches, view and submit reviews, and get sentiment analysis on reviews.

## Technologies Used

- **Frontend**: React.js, HTML5, CSS3, Bootstrap
- **Backend**: Django (Python), Flask (Sentiment Analysis)
- **Database**: SQLite (Django), MongoDB (Reviews & Dealers)
- **Microservices**: Node.js (Dealer/Review API), Flask (Sentiment Analysis)
- **Deployment**: Docker, Kubernetes, IBM Cloud Code Engine
- **CI/CD**: GitHub Actions

## Project Structure

```
agfzn-xrwuqs-dealership/
â”œâ”€â”€ server/
â”‚   â”œâ”€â”€ frontend/
â”‚   â”‚   â”œâ”€â”€ static/
â”‚   â”‚   â”‚   â”œâ”€â”€ About.html
â”‚   â”‚   â”‚   â””â”€â”€ Contact.html
â”‚   â”‚   â””â”€â”€ src/
â”‚   â”‚       â””â”€â”€ components/
â”‚   â”‚           â””â”€â”€ Register/
â”‚   â”‚               â””â”€â”€ Register.jsx
â”‚   â”œâ”€â”€ djangoapp/
â”‚   â”‚   â”œâ”€â”€ models.py
â”‚   â”‚   â”œâ”€â”€ views.py
â”‚   â”‚   â””â”€â”€ urls.py
â”‚   â””â”€â”€ manage.py
â”œâ”€â”€ .github/
â”‚   â””â”€â”€ workflows/
â”‚       â””â”€â”€ ci-cd.yml
â””â”€â”€ README.md
```

## Setup

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```