# Gestao da despensa

Repositorio para desenvolvimento do modulo de gestao da despensa, que fornecera informacoes para lista de compras.

## Para rodar o projeto na maquina

```bash
$ npm install
$ npm start
```

Abrir o browser em localhost:3000

## Para rodar o projeto via docker

```bash
$ npm install
# $ npm start (testar)
$ docker-compose up --build
# Testar se eh necessario o --build
```

Abrir o browser em localhost:3000

## Problemas comuns no linux

### Usuario nao est'a adicionado ao grupo do docker:

Da erro ao chamar qualquer funcionalidade do docker. Exemplo:

```bash
$ docker ps
```

#### Para resolver:

```bash
$ sudo groupadd docker
$ sudo usermod -aG docker ${USER}
$ su - ${USER}
```

#### Como mudar a senha do su

```bash
$ sudo -i
$ passwd
```
