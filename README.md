<h1 align="center">
   🚀 NLW Heat - Node
</h1>
<p align="center">🚀 Projeto desenvolvido na NLW Heat, é uma aplicação para o DoWhile onde as pessoas poderão compartilhar as espectativas sobre a DoWhile!</p>

<div align="center">
  
  ![license](https://img.shields.io/static/v1?label=license&message=MIT&color=5f09a2&style=for-the-badge)
  ![node](https://img.shields.io/static/v1?label=code&message=node.js&color=5f09a2&style=for-the-badge&logo=node.js)<space><space>
  
</div>

<p align="center">
	<a href="#tecnologias">Tecnologias</a> • 
	<a href="#pré-requisitos">Pré-requisitos</a>  •
	<a href="#rodando">Rodando</a>
</p>
  
<h3 align="center"> 
	🚧  NLW Heat 🚀 Backend concluido 🎉
</h4>

---
## **Tecnologias**

As seguintes ferramentas foram usadas na construção do projeto:

- [Axios](https://axios-http.com/)
- [Express](https://expressjs.com/)
- [JSON Web Token](https://jwt.io/)
- [Prisma](https://www.prisma.io/)
- [TypeScript](https://www.typescriptlang.org/)
  
## **Pré-requisitos**

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disso é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)
Além disso na pasta raiz do projeto você deve criar um arquivo .env com as seguintes informações GITHUB_CLIENT_SECRET, GITHUB_CLIENT_ID e JWT_SECRET. Sendo os 2 primeiros você consegue gerar no próprio github nesse [link](https://github.com/settings/developers), o terceiro deve ser um código hash qualquer que você pode gerar a partir desse [link](https://www.md5hashgenerator.com/).
  
## **Rodando** o Back End (servidor)

```bash
# Clone este repositório
$ git clone https://github.com/gsebold027/NLW_Heat.git
# Acesse a pasta do projeto no terminal/cmd
$ cd NLW_Heat
# Instale as dependências (com o yarn ou npm)
$ yarn
# Executa as migrations do Prisma
$ yarn prisma migrate dev
# Execute a aplicação em modo de desenvolvimento
$ yarn dev
# O servidor inciará na porta:4000 - acesse <http://localhost:4000>
```

---
Projeto realizado por Gustavo Sebold, durante o Evento NLW Heat promovido pela [Rocketseat](https://www.rocketseat.com.br/)
