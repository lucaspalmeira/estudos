### Listar as imagens

```bash
docker images
```

### Deletar uma imagem

```bash
docker rmi name_image
```

ou para forçar a deleção

```bash
docker rmi -f name_image
```

### Listar os contêiners

```bash
docker ps
```

### Construir uma imagem (sendo o nome app do diretório de trabalho)

```bash
docker build -t app .
```

### Executar conteiner

```bash
docker run -it --name nome-do-conteiner app
```

### Acessar o shell de um contêiner Docker em execução

```bash
docker exec -it -u root id-do-conteiner sh
```

### Inicia um contêiner interativo a partir da imagem app e abre um shell (sh) dentro do contêiner

```bash
sudo docker run -it app sh
```
### Construir a imagem antes de executar o conteiner em segundo plano (flag -d)
```bash
docker-compose up --build -d
```

### Construir imagens sem usar o cache

```bash
docker compose build
```
