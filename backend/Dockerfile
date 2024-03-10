FROM python:3

ENV PYTHONUNBUFFERED 1
WORKDIR /usr/src/app

COPY poetry.lock pyproject.toml /usr/src/app/
RUN pip3 install poetry
RUN poetry install

COPY . /usr/src/app/

# Expose the port on which your Django app runs (e.g., 8000)
EXPOSE 8000

# Run the Django development server
CMD ["poetry", "run", "python", "manage.py", "runserver", "0.0.0.0:8000"]