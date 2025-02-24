# Practica-IAW-5.4- «Dockerizar» una web estática y publicarla en Docker Hub.

## 1. Comando usado para montar la imagen del dockerfile y comprobar que la imagen esta montada correctamente

```bash
docker build -t alexrl0/2048 .
docker images
```

![5.4-parte-1](imagenes/docker-files-5.4-parte1.png)

## 2. Comando usado para crear un tag a la imagen ya montada

```bash
docker tag alexrl0/2048 alexrl0/2048:1.0
```

![5.1-parte-1](imagenes/docker-compose-5.1-parte1.png)
![5.1-parte-2](imagenes/docker-compose-5.1-parte2.png)
![5.1-parte-3](imagenes/docker-compose-5.1-parte3.png)