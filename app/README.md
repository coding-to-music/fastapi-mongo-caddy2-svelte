# FastAPI

This directory contains the Fast API

## Installation:

```java
sudo apt install pipenv

pipenv install
```

## Run

```java
uvicorn main:app --reload --host 0.0.0.0 --port 5000
```

Output:

```java
INFO:     Uvicorn running on http://0.0.0.0:5000 (Press CTRL+C to quit)
INFO:     Started reloader process [54820]
INFO:     Started server process [54823]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
INFO:     127.0.0.1:52688 - "GET / HTTP/1.1" 404 Not Found
INFO:     127.0.0.1:52688 - "GET /favicon.ico HTTP/1.1" 404 Not Found
```

At `localhost:5000` you can see the output of the FastAPI.

http://localhost:5000/

```java
{"detail":"Not Found"}
```

# Development

- CD in the `app` folder and start the `FastAPI` with `uvicorn main:app --reload --host 0.0.0.0 --port 5000` (see the api at `localhost:5000`);

```java
uvicorn main:app --reload --host 0.0.0.0 --port 5000
```

- CD in the `ui/your-prefered-framework` folder and start the ui with `npm run dev` (see the frontend at `localhost:3000`);
