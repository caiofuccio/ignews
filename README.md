<p align="center">
	<img alt="GitHub language count" src="https://img.shields.io/github/languages/count/caiofuccio/ignews">
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/caiofuccio/ignews">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/caiofuccio/ignews">
  <img alt="status" src="https://img.shields.io/badge/status-finished-success">
  <a href="https://github.com/caiofuccio">
	  <img alt="Feito por Caio Fuccio" src="https://img.shields.io/badge/feito%20por-Caio%20Fuccio-9cf">
	<a/>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
</p>
<br/>

<h1  align="center">
  <img alt="ig.news" src="./public/images/logo.svg" width="250px">
</h1>
<br/>

<p align="center">
 <a href="#-sobre">Sobre</a> •
 <a href="#%EF%B8%8F-features">Features</a> •
 <a href="#%EF%B8%8F-layout">Layout</a> • 
 <a href="#-como-executar">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-autor">Autor</a> •
 <a href="#%EF%B8%8F-licença">Licença</a>
</p>
<br/>

<h4 align="center"> 
	🎊   Finalizado   🎊
</h4>
<br/>

---

## 💻 Sobre

O ig.news é uma aplicação web que agrupa notícias e postagens de blogs com novidades sobre a ferramenta React para desenvolvimento web. Para ter acesso às notícias é necessário que o usuário se cadastre com uma conta do GitHub e faça uma assinatura mensal no valor de USD $9,90 utilizando um cartão de crédito.

Essa aplicação é um dos desafio proposto pela RocketSeat na trilha de React do bootcamp Ignite de 2021.

<br/>

---

## ⚙️ Features

Página Home:

- [x] Cadastro e autenticação do usuário usando uma conta do GitHub
- [x] Inscrição do usuário usando a plataforma de pagamentos Stripe
- [x] Redirecionamento para a página de cadastro caso um usuário não logado tente fazer uma assinatura.
- [x] Redirecionamento para a página de posts caso um assinante tente fazer uma nova assinatura.

Página Posts:

- [x] Lista todos os posts publicados com título e primeiro parágrafo.
- [x] Caso o usuário não esteja logado e clique em um post ele é redirecionado para a home.
- [x] Caso o usuário esteja logado e não seja assinante, ele é redirecionado para a página de preview da matéria, que mostra os três primeiros parágrafos e um botão para inscrição.
- [x] Caso o usuário esteja logado e seja assinante, ele tem acesso completo ao post.

<br/>

---

## 🖼️ Layout

<strong>Página Home</strong>
<img alt="Página Home" src="assets/home.png">

<strong>Página de Posts</strong>
<img alt="Página de Posts" src="assets/posts.png">

<strong>Página completa do post</strong>
<img alt="Página completa do post" src="assets/post-complete.png">

<strong>Página preview do post</strong>
<img alt="Página preview do post" src="assets/post-preview.png">

<br/>

---

## 🧰 Como executar

## Pré requisitos

Antes de começar, você vai precisar criar uma conta, caso ainda não possua nos três serviços abaixo, utilizados na construção dessa aplicação:

- FaunaDB: banco de dados usado para armazenar os dados dos usuários cadastrados e das assinaturas. É otimizado para aplicações serverless.
- Stripe: plataforma de pagamento que permite os usuários fazerem sua assinatura usando um cartão de crédito.
- Prismic CMS: painel de administração onde serão escritos os posts. Eles são carregados na aplicação via API.

<br/>

    # Clone o repositório
    $ git clone git@github.com:caiofuccio/ignews.git

    # Instale as dependências
    $ yarn

    # Execute a aplicação em modo de desenvolvimento
    $ yarn dev

    # A aplicação será aberta na porta:3000 - acesse https://localhost:3000

<br/>

---

## 🚀 Tecnologias

As seguintes ferramentas de programação foram usadas na construção do projeto:

<img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img alt="CSS3" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>
<br/>
<img alt="JavaScript" src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img alt="TypeScript" src="https://img.shields.io/badge/typescript%20-%23007ACC.svg?&style=for-the-badge&logo=typescript&logoColor=white"/>
<br/>
<img alt="React" src="https://img.shields.io/badge/react%20-%2320232a.svg?&style=for-the-badge&logo=react&logoColor=%2361DAFB"/> <img alt="Next JS" src="https://img.shields.io/badge/nextjs-%23000000.svg?&style=for-the-badge&logo=next.js&logoColor=white"/>
<br/>
<img alt="SASS" src="https://img.shields.io/badge/SASS-hotpink.svg?&style=for-the-badge&logo=SASS&logoColor=white"/>
<br/>
<br/>

Usamos também as seguintes ferramentas de terceiros:

<img alt="Fauna DB" src="https://redmonk.com/rstephens/files/2020/10/Fauna-logo-blue.png" width=80px style="background:white; padding:5px 9px"> <br/>
<img alt="Stripe" src="https://shields.io/badge/stripe-white?logo=stripe&style=for-the-badge"> <br/>
<img alt="Prismic" src="https://shields.io/badge/prismic-9cf?logo=prismic&style=for-the-badge">

<br/>

---

## 👨‍💻 Autor

<p align="center">
	<img width="120px" alt="Caio Fuccio" src="https://avatars.githubusercontent.com/u/62528140?s=460&u=f323d1d9a12ba8b63b9d2bdff4502f29f6a68416&v=4"/>
	<br/>
	<strong>Caio Fuccio</strong>
	<br/>
	<sub> Front-End Developer | ReactJS - JAMStack</sub>
	<br/>
	<br/>
	<a href="https://www.linkedin.com/in/caiofuccio/">
		<img alt="Linkedin badge" src="https://img.shields.io/badge/-Caio%20Fuccio-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/caiofuccio/">
	</a>
	<a href="mailto:caio@gmail.com">
		<img alt="Linkedin badge" src="https://img.shields.io/badge/-caio.fuccio@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:caio.fuccio@gmail.com">
	</a>
</p>

<br/>

---

## ⚖️ Licença

Este projeto está sob a licença MIT.

Acesse o arquivo de [LICENSE](./LICENSE) para mais informações.
