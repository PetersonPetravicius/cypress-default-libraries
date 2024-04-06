# Biblioteca padrão Cypress para Estudo

Este projeto contem a biblioteca de testes padrão cypress para estudo e implementação de novas verificações.

## 🚀 Começando 🚀 

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte **[Implantação](https://github.com/PetersonPetravicius/cypressDefaultStudies)** para saber como implantar o projeto.

### 📋 Pré-requisitos 📋


+ [NodeJS v20.12.1 ++](https://nodejs.org/en/download) 

+ [GitBash 2.44.0 ++](https://git-scm.com/downloads)

+ IDE [VScode](https://code.visualstudio.com/download)

```

Realizar a instalação dos programas antes de dar inicio ao clone do projeto.

```

### 🔧 Instalação 🔧

Ao atender os pré-requisitos, é necesario configurar o [gitBash](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git).

```

Seguir o artigo de configuração GITBASH.

```

Feito isto, você está apto a realizar o [Clone](https://www.dio.me/articles/comando-git-conheca-o-git-clone-como-nunca) do projeto

```

Seguir o artigo detalhado para realizar o Clone deste projeto em sua maquina local.

```

🏆Se chegou até aqui, então o projeto ja está disponivel para analise e execução dos testes no seu local.🏆 

## ⚙️ Executando os testes ⚙️ 

Para execução dos testes devemos executar no terminal do VS Code ou gitbash a inicialização do node e a instalação do Cypress
```

Passo 01: No terminal VS Code ou GitBash (na pasta principal do projeto) rodar o comando
'npm init --yes'
Passo 02: Após execução do comando PASSO 01, envie o comando 'npm install -D cypress' para a versão mais atual do cypress OU
'npm install -D cypress@12.5.0' para instalar uma versão expecifica.

Passo 03: para abrir a versão desktop do cypress que roda os testes WEB, realizar o comando no terminal: 'npx cypress open'
OU para rodar os testes sem abrir a ferramenta desktop, executar o comando 'npx cypress run'

Os Cenários de testes executaveis estão disponíveis em e2e>financesAppTest.cy.js

```

### 🔩 Analise os testes de ponta a ponta 🔩

Ao fim da execução dos testes, um pequeno report com o resumo das execuções será exibido na guia "Terminal" quando executado 'npx cypress run'.

```
====================================================================================================

  (Run Finished)


       Spec                                              Tests  Passing  Failing  Pending  Skipped
  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐
  │ √  1-getting-started/todo.cy.js             00:04        6        6        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/actions.cy.js        00:14       14       14        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/aliasing.cy.js       00:02        2        2        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/assertions.cy.j      00:04        9        9        -        -        - │
  │    s                                                                                           │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/connectors.cy.j      00:02        8        8        -        -        - │
  │    s                                                                                           │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/cookies.cy.js        00:02        7        7        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/cypress_api.cy.      00:02       10       10        -        -        - │
  │    js                                                                                          │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/files.cy.js          00:02        4        4        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/location.cy.js       00:01        3        3        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/misc.cy.js           00:03        5        5        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/navigation.cy.j      00:03        3        3        -        -        - │
  │    s                                                                                           │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/network_request      00:05        6        6        -        -        - │
  │    s.cy.js                                                                                     │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/querying.cy.js       00:02        5        5        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/spies_stubs_clo      00:04        7        7        -        -        - │
  │    cks.cy.js                                                                                   │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/storage.cy.js        00:02        5        5        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/traversal.cy.js      00:03       18       18        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/utilities.cy.js      00:03        5        5        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/viewport.cy.js       00:04        1        1        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/waiting.cy.js        00:06        2        2        -        -        - │
  ├────────────────────────────────────────────────────────────────────────────────────────────────┤
  │ √  2-advanced-examples/window.cy.js         00:01        3        3        -        -        - │
  └────────────────────────────────────────────────────────────────────────────────────────────────┘
    √  All specs passed!                        01:23      123      123        -        -        -


====================================================================================================

```

## 📦 Implantação 📦

A implantação deste projeto, pode ser realizada utilizando a ferramenta [Jenkins](https://digital.ai/pt/catalyst-blog/how-to-launch-jenkins-selenium-tests-using-the-pipeline/), tornando-o capaz de ser executado a cada nova 
subida de codigo ao repositorio e execução de pipeline.

## 🛠️ Construído com 🛠️

Neste projeto as ferramentas adotadas foram:

[IDE VScode](https://visualstudio.microsoft.com/pt-br/vs/getting-started/)

[JScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

[Cypress](https://docs.cypress.io/guides/overview/why-cypress)


## 📌 Versão 📌

O projeto se encontra em sua versão 1.0 

## ✒️ Autor ✒️

* **Peterson Petravicius** - *Analista de Qualidade* - [LinkedIn](https://www.linkedin.com/in/petersonpk/)


## 🎁 Expressões de gratidão 🎁

* Este projeto foi uma retomada de conhecimento sobre os conceitos basicos de automação WEB após receber um desafio de implementação 📢;
* Um binde 🍺;

---

```

console.log("Tchau");

```
😊