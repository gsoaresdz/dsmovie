<h1 align="center">DSMovie</h1>

## Sobre o projeto
DSMovie é uma aplicação web responsiva, desenvolvida com Java e Spring no backend e React no frontend. O aplicativo foi desenvolvido durante o evento 'Semana Spring React', promovido pela DevSuperior - Escola de Programação.

A aplicação consiste em uma página que exibe uma lista paginada de filmes e outra página que contém um formulário para a avaliação de um filme. Na lista paginada, cada filme apresenta uma nota de avaliação, calculada pela média das notas atribuídas pelos usuários. Já na página de avaliação, há campos para que o usuário informe seu e-mail e a nota que deseja atribuir ao filme selecionado.

## Layout
![1](https://github.com/gsoaresdz/dsmovie/assets/69989654/9bb33d3c-cb56-4b0d-a226-351ace8590ad)

![Avaliação](https://github.com/gsoaresdz/dsmovie/assets/69989654/49b1d818-604b-47f0-9761-d4653c4c129c)

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
- Spring boot
- HTML
- CSS
- JavaScript
- TypeScript
- ReactJS
- Bootstrap
- Maven
- PostgreSQL
- H2
- PgAdmin
- Git / GitHub

## Como executar o projeto

### Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/gsoaresdz/dsmovie

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

### Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/gsoaresdz/dsmovie

# entrar na pasta do projeto front end web
cd frontend

# instalar dependências
yarn install

# executar o projeto
yarn start
```
