# Hello World

Esse projeto é apenas para entender como subir construir uma aplicação .net core e colcoar dentro do Docker.

## Instruções

### Criando o Docker
```
docker build -t dotnetapp-dev .
```

### Executando o projeto
```
docker run --rm dotnetapp-dev Hello from Docker
```