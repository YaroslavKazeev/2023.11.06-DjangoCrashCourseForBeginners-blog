# Posts App (Django Crash Course)

> Python Django app to create posts

## Quick Start

```bash
# Install dependencies
pipenv install

cd src

# Serve on localhost:8000
python manage.py runserver
```

## Routes

The application provides the following routes:

| Route | Method | Description |
|-------|--------|-------------|
| `/` | GET | Display list of all posts |
| `/posts/` | GET | Display list of all posts (alternative) |
| `/create/` | GET, POST | Create a new post |
| `/<post_id>/` | GET | Display details of a specific post |
| `/<post_id>/update/` | GET, POST | Update an existing post |
| `/<post_id>/delete/` | POST | Delete a post |
| `/admin/` | GET, POST | Django admin panel |

## References

Acknowledgement: This repo was created following the tutorial "Django crash course for beginners (JustDjango)" https://www.youtube.com/watch?v=_04toQWN5-8&t=3435s
