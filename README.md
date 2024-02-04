<h1 align="center">DSMovie</h1>

## Sobre o projeto
DSMovie é uma aplicação web responsiva, desenvolvida com Java e Spring no backend e React no frontend. O aplicativo foi desenvolvido durante o evento 'Semana Spring React', promovido pela DevSuperior - Escola de Programação.

A aplicação consiste em uma página que exibe uma lista paginada de filmes e outra página que contém um formulário para a avaliação de um filme. Na lista paginada, cada filme apresenta uma nota de avaliação, calculada pela média das notas atribuídas pelos usuários. Já na página de avaliação, há campos para que o usuário informe seu e-mail e a nota que deseja atribuir ao filme selecionado.

## Layout web
![Listagem](https://github.com/dennisferreira1/assets/blob/main/dsmovie/img/desktop-listagem.png)

![Avaliação](https://github.com/dennisferreira1/assets/blob/main/dsmovie/img/desktop-avaliacao.png)

## Layout mobile
![Listagem](https://github.com/dennisferreira1/assets/blob/main/dsmovie/img/mobile-listagem.png)

![Avaliação](https://github.com/dennisferreira1/assets/blob/main/dsmovie/img/mobile-avaliacao.png)

## Recursos
- Listar filmes
- Avaliar filme

## Modelo conceitual
![Modelo Conceitual](https://github.com/dennisferreira1/assets/blob/main/dsmovie/img/modelo-conceitual.png)

## Competências / Técnicas
### Backend
- Criar e configurar o projeto com Spring
- Configurar o  banco de dados
- Mapeamento ORM
- Desenvolvimento em camadas
- REST API
- Configurar perfis de projeto
### Frontend
- Criar e configurar o projeto com React
- Componentes
- Props
- Estado
- Rotas
- Navegação
### Integração frontend e backend
- Axios

## Tecnologias e ferramentas utilizadas
- Java
- Spring
- HTML
- CSS
- JS
- TypeScript
- ReactJS
- Bootstrap
- Maven
- Postgresql
- H2
- PgAdmin
- Flyway
- Git / GitHub

## Como executar o projeto

### Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/dennisferreira1/projeto-dsmovie

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

### Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/dennisferreira1/projeto-dsmovie

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```
