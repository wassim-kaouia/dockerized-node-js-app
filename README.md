# Minimal Node.js Hello World example

This repo contains a minimal hello world application written in Node.

## Run locally

```bash
npm install
npm start
```

## Run in a container

```bash
docker build -t node-hello-world:latest .
docker run -it -p 8080:8080 --name node-hello-world node-hello-world:latest
```


Wassim Kaouia
DevOps Training ...