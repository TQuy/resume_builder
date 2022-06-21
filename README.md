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
# Running with docker
1. Install `docker` and `docker compose`
1. run 
    ```
    docker compose up
    ```
1. access the website via `http://192.168.18.2:81/`
