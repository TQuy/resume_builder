# Resume_builder

## Table of contents

- [How to clone this project](#how-to-clone-this-project)
- [Working with Django back-end](#working-with-django-back-end)
- [Working with ReactJS front-end](#working-with-reactjs-front-end)
- [Running with docker](#running-with-docker)

## How to clone this project

1. Clone the project
   ```
   git clone https://github.com/TQuy/resume_builder.git
   ```
2. Redirect to the project
   ```
   cd resume_builder
   ```
3. Clone submodules
   ```
   git submodule init
   git submodule update
   ```

## Working with Django back-end

### How to start Django

1. Redirect to `backend` directory
   ```
   cd backend
   ```
2. Create `python` environment and activate it.

   ```
   python -m venv venv-resume-builder
   source venv-resume_builder/bin/activate
   ```

3. Install dependencies
   ```
   pip install -r requirements.txt
   ```
4. Start `Django` server
   ```
   python manage.py runserver
   ```

### How to format python code

```
python scripts/autopep8.py
```

## Working with ReactJS front-end

### How to start ReactJS

1. Redirect to `frontend` directory
   ```
   cd frontend
   ```
2. Install dependencies
   ```
   npm install
   ```
3. Start React app
   ```
   npm start
   ```

### How to format front-end code

To format python codes

```
npm run prettier
```

## Running with docker

### From build context

1. Install `docker` and `docker compose`
1. Edit .env file
1. run
   ```
   docker compose up
   ```

### From image registry

Run

```
docker compose up -f docker-compose.prod.yml
```

To create and publish your own images, read `backend/README.md` and `frontend/README.md`.
