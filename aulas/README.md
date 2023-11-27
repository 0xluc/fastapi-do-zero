---
title: FastAPI do Zero!
description: Boas vindas ao nosso minicurso de FastAPI!
---

<script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
<lottie-player src="https://raw.githubusercontent.com/dunossauro/fastapi-do-zero/main/stuff/anim_lottie.json" background="transparent" speed="1" style="margin-left: auto; margin-right: auto;" loop autoplay></lottie-player>

# FastAPI do ZERO

> Esse material ainda está em fase de desenvolvimento. Caso encontre algum erro, ficarei extremamente feliz que você me notifique ou envie um Pull Request! [Problemas já conhecidos](https://github.com/dunossauro/fastapi-do-zero/issues)

**Construindo um Projeto com Bancos de Dados, Testes e Deploy**

Boas-vindas à sua jornada de aprendizado com o framework FastAPI! Neste curso, o foco é proporcionar um entendimento prático das habilidades essenciais para o desenvolvimento eficiente de APIs. Exploraremos temas como integração com bancos de dados e implementação de testes, oferecendo uma base sólida para quem busca trabalhar com essa ferramenta. A abordagem é direta e informativa, visando nos equipar com o conhecimento necessário para começar a criar nossos próprios projetos.

## O que é FastAPI?

FastAPI é um framework Python moderno, projetado para simplicidade, velocidade e eficiência. A combinação de alto desempenho com anotações de tipo Python facilita o desenvolvimento de APIs RESTful.

## Sobre o curso

Este curso foi desenvolvido para oferecer uma experiência prática no uso do FastAPI, uma das ferramentas mais modernas para construção de APIs. Ao longo do curso, o objetivo é que você obtenha uma compreensão das funcionalidades do FastAPI e de boas práticas associadas a ele.

O projeto central do curso será a construção de um gerenciador de tarefas (uma lista de tarefas), começando do zero. Esse projeto incluirá a implementação da autenticação do usuário e das operações CRUD completas.

Para a construção do projeto, serão utilizadas as versões mais recentes das ferramentas, disponíveis em 2023, como a versão 0.100 do FastAPI, a versão 2.0 do Pydantic, a versão 2.0 do SQLAlchemy ORM, além do Python 3.11 e do Alembic para gerenciamento de migrações.

Além da construção do projeto, o curso também incluirá a prática de testes, utilizando o pytest. Essa abordagem tem como objetivo garantir que as APIs desenvolvidas sejam não apenas funcionais, mas também robustas e confiáveis.

## O que você vai aprender?

Aqui está uma visão geral dos tópicos que vamos abordar neste curso:

1. **Configurando um ambiente de desenvolvimento para FastAPI**: Vamos começar do absoluto zero, criando e configurando nosso ambiente de desenvolvimento.

2. **Primeiros Passos com FastAPI e TDD**: Depois de configurar o ambiente, mergulharemos na estrutura básica de um projeto FastAPI e faremos uma introdução detalhada ao Test Driven Development (TDD).

3. **Modelagem de Dados com Pydantic e SQLAlchemy**: Aprenderemos a criar e manipular modelos de dados utilizando Pydantic e SQLAlchemy, dois recursos que levam a eficiência do FastAPI a um outro nível.

4. **Autenticação e Autorização em FastAPI**: Vamos construir um sistema de autenticação completo, para proteger nossas rotas e garantir que apenas usuários autenticados tenham acesso a certos dados.

5. **Testando sua Aplicação FastAPI**: Faremos uma introdução detalhada aos testes de aplicação FastAPI, utilizando as bibliotecas pytest e coverage.

6. **Dockerizando e Fazendo Deploy de sua Aplicação FastAPI**: Por fim, vamos aprender como "dockerizar" nossa aplicação FastAPI e fazer seu deploy utilizando Fly.io.

## 💰 Esse curso é gratuito?

SIM! Esse curso foi todo desenvolvido [de forma aberta](#licenca){:target="_blank"} e com a [ajuda financeira](https://apoia.se/fastapi){:target="_blank"} de pessoas incríveis. Caso você sinta vontade de contribuir, você pode me pagar um café por pix (pix.dunossauro@gmail.com) ou apoiar a [campanha recorrente de financiamento coletivo da live de python](https://apoia.se/livedepython){:target="_blank"} que é o que paga as contas aqui de casa.

## Onde o curso será disponibilizado?

Esse material está em fase de desenvolvimento e todas as aulas estarão disponíveis no meu canal do YouTube. Você pode conferir outros materiais disponíveis por lá enquanto os vídeos não saem, ou se inscrever para ser notificado quando os vídeos saírem!

[**http://youtube.com/@dunossauro**](http://youtube.com/@dunossauro){:target="_blank"}

> Aqui estará listada a playlist quando disponível!

## Pré-requisitos

Para aproveitar ao máximo este curso, é recomendado que você tenha algum conhecimento prévio de Python. Além disso, algum entendimento básico de desenvolvimento web e APIs RESTful será útil, mas não essencial, pois a abordagem deste curso é prática e centrada em um projeto concreto. Através de exemplos reais e instruções passo a passo, você terá a oportunidade de acompanhar o processo de construção de uma aplicação real. Mesmo que os conceitos de desenvolvimento web sejam novos para você, a ênfase na aplicação prática e a estrutura detalhada do curso facilitarão o entendimento e a aplicação dessas habilidades até o fim do processo.

??? info "Caso esteja iniciando seus estudos em Python!"
	Caso você ainda não se sinta uma pessoa preparada, ou caiu aqui sem saber exatamente o que esperar. Temos um pequeno curso introdutório. Destinado aos primeiros passos com python.
	![type:video](https://youtube.com/embed/yTQDbqmv8Ho)

	[:fontawesome-brands-youtube: Link direto](https://www.youtube.com/watch?v=yTQDbqmv8Ho){ .md-button }

	Também temos uma live focada em dicas para iniciar os estudos em python

    ![type:video](https://www.youtube.com/embed/HSotf1Amess)

	[:fontawesome-brands-youtube: Link direto](https://www.youtube.com/watch?v=HSotf1Amess){ .md-button }

	Ou então a leitura do livro [**Pense em python**](https://penseallen.github.io/PensePython2e/){:target="_blank"}

## Aulas

1. [Configurando o Ambiente de Desenvolvimento](/01/){:target="_blank"}
2. [Estruturando seu Projeto e Criando Rotas CRUD](/02/){:target="_blank"}
3. [Configurando Banco de Dados e Gerenciando Migrações com Alembic](/03/){:target="_blank"}
4. [Integrando Banco de Dados a API](/04/){:target="_blank"}
5. [Autenticação e Autorização](/05/){:target="_blank"}
6. [Refatorando a Estrutura do Projeto](/06/){:target="_blank"}
7. [Tornando o sistema de autenticação robusto](/07/){:target="_blank"}
9. [Criando Rotas CRUD para Tarefas](/08/){:target="_blank"}
10. [Dockerizando a aplicação](/09/){:target="_blank"}
11. [Automatizando os testes com integração contínua](/10/){:target="_blank"}
12. [Fazendo o deploy no fly.io](/11/){:target="_blank"}
13. [Despedida](/12/){:target="_blank"}

### 🦖 Quem vai ministrar essas aulas?

Prazer! Eu me chamo Eduardo. Mas as pessoas me conhecem na internet como [@dunossauro](https://dunossauro.com){:target="_blank"}.

<div class="sbs" markdown>
![Uma fotografia minha, Dunossauro, sentado em um banco com um por do sol ao fundo](assets/dunossauro.jpg){ align=left width="300" .shadow}
<div markdown>

Eu sou um programador Python muito empolgado e curioso. Toco um projeto pessoal chamado [Live de Python](https://www.youtube.com/@Dunossauro){:target="_blank"} há pouco mais de 6 anos. Onde conversamos sobre tudo e mais um pouco quando o assunto é Python.

Esse projeto que estamos desenvolvendo é um pedaço, um projeto, de um grande curso de FastAPI que estou montando. Espero que você se divirta ao máximo com a parte prática enquanto escrevo em mais detalhes todo o potencial teórico que lançarei no futuro!

[Caso queira saber mais sobre esse projeto completo](https://youtu.be/ikmFLkjxqFg){:target="_blank"}.
</div>
</div>

## 📖 Licença

Todo esse curso foi escrito e produzido por Eduardo Mendes ([@dunossauro](https://dunossauro.com/){:target="_blank"}).

Todo esse material é gratuito e está sob licença Creative Commons [BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/){:target="_blank"}. O que quer dizer que:

- Você pode copiar e reproduzir esse material em qualquer meio e em qualquer formato;
- Você pode adaptar esse material e construir outros materiais usando esse material.

Pontos de atenção:

- Você precisa dar os devidos créditos a esse material onde for usar ou adaptar;
- Você não pode usar para fins comerciais. Como vender ou usar para obter vantagens comerciais;
- Todo o material derivado desse material deve ser redistribuído com a licença [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/){:target="_blank"}.

## 🧰 Ferramentas necessárias para acompanhar o curso

1. Um editor de texto ou IDE de sua escolha. Estou usando o [GNU/Emacs](https://www.gnu.org/software/emacs/){:target="_blank"} enquanto escrevo as aulas;
2. Um terminal. Todos os exemplos do curso são executados e explicados no terminal. Você pode usar o que se sentir mais a vontade e for compatível com seu sistema operacional;
3. Ter o interpretador Python instalado em uma versão igual ou superior a `3.11`
4. Uma conta no [Github](https://github.com/){:target="_blank"}: para podermos testar com Github Actions;
5. Uma conta no [Fly.io](https://fly.io/){:target="_blank"}: ferramenta que usaremos para fazer deploy.

## 🔧 Ferramentas de apoio

Toda essa página foi feita usando as seguintes bibliotecas:

- [MkDocs](https://www.mkdocs.org/){:target="_blank"}: Para geração das páginas estáticas usando Markdown
- [Mkdocs-material](https://squidfunk.github.io/mkdocs-material/){:target="_blank"}: Tema para o MkDocs
- [pymdown-extensions](https://facelessuser.github.io/pymdown-extensions/){:target="_blank"}: Extensões para MkDocs, como emojis, diagramas e blocos estilizados de código
- [Python-Markdown](https://python-markdown.github.io/){:target="_blank"}: Extensão do Python para Markdown
- [Mkdocs-video](https://github.com/soulless-viewer/mkdocs-video){:target="_blank"}: Extensão para o MkDocs exibir os vídeos na página
- [Mermaid.js](https://mermaid-js.github.io/mermaid/){:target="_blank"}: Construção dos diagramas
- [Glaxnimate](https://glaxnimate.mattbas.org/){:target="_blank"}: Pra criar a animação no topo dessa página
- [Lottie-Player](https://github.com/LottieFiles/lottie-player){:target="_blank"}: Pra exibir a animação do Glaxnimate

Para os slides:

- [marp](https://marp.app/){:target="_blank"}: Onde preparei os slides
- [Rose-Pine](https://github.com/rainbowflesh/Rose-Pine-For-Marp){:target="_blank"}: Tema que usei no marp

### 📁 Repositório
O versionamento de tudo está sendo feito no [repositório do curso Github](https://github.com/dunossauro/fastapi-do-zero){:target="_blank"}

### 🚀 Deploy
Os deploys das páginas estáticas geradas pelo MkDocs estão sendo feitos no [Netlify](https://www.netlify.com/){:target="_blank"}

## Conclusão

Neste curso, a intenção é fornecer uma compreensão completa do framework FastAPI, utilizando-o para construir uma aplicação de gerenciamento de tarefas. O aprendizado será focado na prática, e cada conceito será acompanhado por exemplos e exercícios relevantes.

A jornada começará com a configuração do ambiente de desenvolvimento e introdução ao FastAPI. Ao longo das aulas, abordaremos tópicos como autenticação, operações CRUD, testes com pytest e deploy. A ênfase será colocada na aplicação de boas práticas e no entendimento das ferramentas e tecnologias atualizadas, incluindo as versões mais recentes do FastAPI, Pydantic, SQLAlchemy ORM, Python e Alembic.

Este conteúdo foi pensado para auxiliar na compreensão de como criar uma API eficiente e confiável, dando atenção a aspectos importantes como testes e integração com banco de dados.

## F.A.Q.

Perguntas frequentes que me fizeram durante os vídeos

- Que papel de parede é esse? [É uma foto do Liam Wong](https://www.tumblr.com/liamwong){:target="_blank"}
- Qual o tema no shell? Todo o meu tema do Gnome foi customizado com [Gradience](https://gradienceteam.github.io/){:target="_blank"} o tema é [Pretty In Purple](https://www.gnome-look.org/p/2031597){:target="_blank"}
- Qual o tema do seu editor? [Rebecca](https://github.com/vic/rebecca-theme){:target="_blank"}
