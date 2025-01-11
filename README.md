# Facebook PA Agent

An intelligent AI agent built with Django that autonomously manages Facebook accounts by posting content, reading engagement metrics, and interacting with audiences.

## Features

- **Automated Posting**: Schedule and publish posts automatically
- **Content Management**: Create and manage multiple content types (text, images, links)
- **Engagement Monitoring**: Track likes, comments, shares, and reach
- **Interactive Responses**: Auto-respond to comments and messages
- **Analytics Dashboard**: View performance metrics and engagement statistics
- **Multi-account Support**: Manage multiple Facebook pages/accounts

## Technology Stack

- **Backend**: Django 4.x
- **Database**: PostgreSQL
- **Authentication**: Facebook OAuth
- **API**: Facebook Graph API
- **Task Queue**: Celery (for scheduled posts)
- **Cache**: Redis

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/facebook-pa-agent.git
cd facebook-pa-agent
```

2. Initialize the Django project:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
