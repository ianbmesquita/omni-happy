<h1 align="center">
    <img alt="Happy" src=".github/banner-happy.png" />
</h1>

<p align="center">
  <a href="#bookmark-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#wrench-ferramentas-utilizadas">Ferramentas Utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#boom-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :bookmark: Sobre

O **Happy** é uma aplicação Web desenvolvida pensando na possibilidade de permitir a facilitação de visitas a orfanatos cadastrados para realização de doações à crianças.

Essa aplicação foi realizada durante a **Next Level Week 3** da [Rocketseat](https://rocketseat.com.br/).

## :rocket: Tecnologias

<p float="left">
  <img alt="Node.js" src=".github/node.svg" />
  <img alt="TypeScript" src=".github/typescript.svg" hspace="10" />
</p>

-  [Node.js](https://nodejs.org/en/)
-  [TypeScript](https://www.typescriptlang.org/)

## :wrench: Ferramentas Utilizadas

- **cors** - Pacote responsável por fornecer um middleware de conexão com o Express para habilitar CORS(Compartilhamento de recursos de origem cruzada).
- **express** - Biblioteca responsável pela criação de servidor HTTP para disponibilização de APIs.
- **express-async-errors** - Hack para o async/await que captura erros de requisição.
- **multer** - Dependência responsável por pelo upload de arquivos.
- **sqlite3** - Dependência responsável por fazer a conexão entre o servidor e o banco de dados SQLITE.
- **typeorm** - Dependência responsável por fazer o data mapper ORM.
- **yup** - Dependência responsável por lidar com conversões e validações de dados.

## :boom: Como Executar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado.
  - É **necessário** ter um gerenciador de pacotes seja o **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.
  - É **necessário** ter um **browser** instalado.

1. Faça um clone do repositório:

```sh
  $ git clone https://github.com/ianbmesquita/omni-happy.git
```

2. Executando a Aplicação:

```sh
  # Acessando o diretório da aplicação.
  $ cd omni-happy/server

  # Instalando as dependências do projeto.
  $ yarn # ou npm install

  # Inicializando o servidor ReactJS.
  $ yarn dev:server # ou npm dev:server	

  # Criando o banco de dados usando migration do TypeORM.
  $ yarn typeorm migration:run # ou npm typeorm migration:run	

  # Caso ocorra algum erro, desfazer o banco de dados usando migration do TypeORM.
  $ yarn typeorm migration:revert # ou npm typeorm migration:revert	
```

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---
<sup>Projeto desenvolvido com a tutoria de [Diego Fernandes](https://github.com/diego3g), da [Rocketseat](rocketseat.com.br).</sup>