### Listar as imagens

```bash
docker images
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
