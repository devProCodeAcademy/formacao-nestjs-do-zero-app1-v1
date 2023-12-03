# devProCode Academy

## Formação NestJs do Zero com TypeORM, Prisma e Swagger

Seja muito bem-vindo e bem-vinda ao curso de **Formação NestJs do Zero com TypeORM, Prisma e Swagger**. Este repositório refere-se ao projeto desenvolvido durante o curso.

## Descrição

Nesta formação você aprenderá os principais conceitos do framework NestJs desde o zero, como injeção de dependência, módulos, controllers e services, além de integrar outas ferramentas com TypeORM, Prisma e Swagger, tudo isso através da criação de APIs Restful aplicando boas práticas e requisitos exigidos pelo mercado de trabalho.

## Rodando a aplicação no seu PC

> IMPORTANTE: Se você for executar esse projeto em PC com Windows, use uma instalação Linux no seu Windows através do WSL.

Faça um clone deste repositório e instale no seu ambiente de desenvolvimento usando o seguinte comando no seu terminal (escolha um diretório apropriado):

```shell
git clone https://github.com/devProCodeAcademy/formacao-nestjs-do-zero-v1.git
```

Após clonar o conteúdo do repositório, acesse o diretório criado e execute os comandos abaixo para criar e executar os containers da aplicação e do banco de dados PostgreSQL.

```shell
# Entrar no diretório do projeto
cd formacao-nestjs-do-zero-v1

# Instalar as dependências
npm install

# Rodar o BD Postgres com o Docker Compose
docker-compose up --build

# Iniciar a aplicação
npm run start:dev
```

Após essa instalação a aplicação estará em execução no endereço `http://localhost:3000`.
