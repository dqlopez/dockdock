# dockdock
Your so-so dockerized local playground.

## Installation

Copy the environment template and update values accordingly:

```
cp env-template .env
```

Build and initialize Docker container:

```
docker-compose up --build -d
```

Access nginx localhost URL:

```
http://127.0.0.1/
```