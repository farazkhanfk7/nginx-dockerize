# Dockerizing Python Web Apps
> Deploy on local webserver

A sample boilerplate to deploy your flask application using **Docker, Nginx and uwsgi**

## Setup
1. ```$ git clone https://github.com/farazkhanfk7/nginx-dockerize.git```

2. ```$ cd nginx-dockerize```

3. Build both flask and nginx Dockerfiles using ```$ docker-compose build```

4. Run containers using docker-compose ```$ docker-compose up```

5. Below is the directory structure I've created :

```
app
├── docker-compose.yml
├── flask
│   ├── Dockerfile
│   ├── .dockerignore
│   ├── app
│   │   ├── __init__.py
│   │   └── views.py
│   ├── app.ini
│   ├── requirements.txt
│   └── run.py
├── nginx
│   ├── Dockerfile
│   └── nginx.conf
├── .gitignore
└── readme.md
```
