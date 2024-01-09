RealWorld Example App
Django REST Framework and Couchbase Capella codebase.

Docker - Run commands using Docker Compose:
    e.g., docker-compose run --rm sh -c "python manage.py collectstatic"

Linting - Using flake8 for linting with docker-compose command:
    docker-compose run --rm app sh -c "flake8"

Testing - Test with docker-compose command:
    docker-compose run --rm app sh -c "python manage.py test"

Dev Server - Start dev server with docker-compose command:
    docker-compose up
    Then access server at 127.0.0.1:8000