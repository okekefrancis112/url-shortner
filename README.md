# URL Shortener

A Django web application for shortening URLs with a clean web interface.

## Overview

A URL shortening service built with Django that allows users to create short, memorable links that redirect to long URLs.

## Features

- **Shorten URLs** — Convert long URLs to short links
- **Redirect** — Short URLs redirect to original destinations
- **Web Interface** — Clean HTML form for URL submission
- **Persistent Storage** — SQLite database for URL mappings

## Tech Stack

- **Python** 3.9
- **Django** — Web framework
- **SQLite** — Database
- **HTML** — Frontend template

## Getting Started

```bash
git clone https://github.com/okekefrancis112/url-shortner.git
cd url-shortner/urlshortner
pip install django
python manage.py migrate
python manage.py runserver
```

Visit `http://localhost:8000` to start shortening URLs.

## Project Structure

```
└── urlshortner/
    ├── shortner/
    │   ├── models.py        # URL mapping model
    │   ├── views.py         # Shortening & redirect logic
    │   └── urls.py          # URL routes
    ├── templates/
    │   └── index.html       # URL submission form
    ├── manage.py
    └── db.sqlite3
```

## License

MIT
