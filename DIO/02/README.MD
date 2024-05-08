# Sobre

Repositório destinado ao Projeto de Processamento e Transformação de Dados com PowerBI e SQL do bootcamp Python Data Analytics da DIO

## Ferramentas Usadas

Docker
MySQL
PowerBI

### Docker

Caso não tenha o Docker, instale clicando [aqui](https://github.com/mauriciobenjamin700/docker-learning)

Com o decker instalado, precisamos da imagem do MySQL para poder criar instanciar e testalo. Confira se você já tem a imagem usando `docker images` para visualizar todos os seus containers em execução.

Caso não tenha a imagem do MySQL para poder criar instanciar e testalo, vamos baixar a imagem usando `docker pull mysql`

Para saber mais sobre a imagem do MySQL, acesse sua documentação no [dockerhub](https://hub.docker.com/_/mysql)

Após baixar a imagem vamos instanciar um conteiner com essa imagem, da seguinte forma

```bash
docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:tag
```

Detalhes:

- some-mysql: Troque pelo nome que você quiser dar para o seu banco de dados
- my-secret-pw: Troque pela senha que preferir
- tag: pode ser substituido pela versão do mysql que preferir usar
