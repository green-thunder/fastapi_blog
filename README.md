# FastAPI Blog

A small blog built with FastAPI and Jinja2 templates. The same posts are rendered as an HTML page and exposed as a JSON API.

## Routes

| Route | Returns |
|---|---|
| `/` and `/posts` | Home page with all posts (HTML) |
| `/api/posts` | All posts as JSON |

Posts are kept in memory in `main.py`.

## Run

```bash
pip install fastapi uvicorn jinja2
uvicorn main:app --reload
```

Then open http://127.0.0.1:8000.

## Stack

FastAPI · Jinja2 · HTML, CSS and JavaScript (static files, web manifest and app icons)
