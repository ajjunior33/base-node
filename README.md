# Aplicação em NodeJS


Aplicação feita com NodeJS e o banco de dados usado foi o MongoDB.

# Startando MongoDB com Docker

```
docker run --name mongodb -p 27017:27017 -d mongo
docker ps -> retorna as imagens que estão rodando
docker ps -a -> Todas as imagens do docker
docker start [ nome da imagem ] => Para subir a imagem que você precisa
```

## Instalação

Fazer a instalação do **Robo 3T** ajuda na visualização dos arquivos criados dentro do MongoDB


# Pacotes

Os pacotes usado para essa aplicação foram: 

- express
- nodemon -D
- mongoose
- cors
- mongoose-paginate
