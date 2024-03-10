# Restful Svelte + Docker

A ready to go Single Page App in a container set up by Poetry featuring Django, Django Rest Framework, and  Svelte.

1. `git clone`
2. `cd restful_svelte_docker`
3. `cd frontend`
4. `npm install`
5. `cd ..`
6. `docker-compose up`
7. Open a new terminal
8. `cd backend`
9. `docker-compose exec backend bash`
10. `poetry shell`
11. `python manage.py migrate`

## That's all there is to it

Navigate to `localhost:8000` and you're up and running and ready to start building your own SPA.

The api is set at `localhost:8000/api` 
