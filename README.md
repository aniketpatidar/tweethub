# TweetHub

A minimal Twitter-style app built with Django. Users can create an account, post tweets, edit or delete them, and attach images.

![TweetHub](https://github.com/aniketpatidar/TweetHub/blob/main/media/photos/Screenshot%20from%202024-06-22%2011-05-10.png)

## Features

- User sign up, login, and logout
- Create, edit, delete, and view tweets
- Image support for tweets

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x or later

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/aniketpatidar/TweetHub.git
   ```
2. Navigate to the project directory:

   ```bash
   cd TweetHub
   ```
3. Create and activate a virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
5. Apply the migrations:

   ```bash
   python manage.py migrate
   ```
6. Create a superuser to access the admin panel:

   ```bash
   python manage.py createsuperuser
   ```
7. Start the development server:

   ```bash
   python manage.py runserver
   ```
8. Open your web browser and go to [http://127.0.0.1:8000/tweet/](http://127.0.0.1:8000/tweet/) to see the application in action.

## Shoutout

Special thanks to [@hiteshchoudhary](https://github.com/hiteshchoudhary) for his amazing YouTube video that inspired this project.

[![Build a full stack project in Django for beginners](https://img.youtube.com/vi/opzK3E4Xx6o/0.jpg)](https://www.youtube.com/watch?v=opzK3E4Xx6o)
