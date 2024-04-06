# Projeto FinancesCypress

Projeto Automação WEB utilizando o frameWork Cypress com o objetivo de validar a pagina: https://devfinance-agilizei.netlify.app/# completando o desafio de trabalhar com clicks em cima dos componentes da tela.

## 🚀 Começando 🚀 

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte **[Implantação](https://github.com/PetersonPetravicius/financialCypress)** para saber como implantar o projeto.

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


DevTools listening on ws://127.0.0.1:61338/devtools/browser/1460f876-1596-408c-b062-839e72aeda75

====================================================================================================

  (Run Starting)

  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐
  │ Cypress:        13.7.2                                                                         │
  │ Browser:        Electron 118 (headless)                                                        │
  │ Node Version:   v16.13.1 (C:\Program Files\nodejs\node.exe)                                    │
  │ Specs:          1 found (financesAppTest.cy.js)                                                │
  │ Searched:       cypress/e2e/**/*.cy.{js,jsx,ts,tsx}                                            │
  └────────────────────────────────────────────────────────────────────────────────────────────────┘


────────────────────────────────────────────────────────────────────────────────────────────────────

  Running:  financesAppTest.cy.js                                                           (1 of 1)


  Transações
    √ Cadastrar uma entrada (4818ms)
    √ Cadastrar uma saída (1082ms)
    √ Excluir uma entrada (1061ms)
    √ Excluir uma saída (1558ms)


  4 passing (10s)


  (Results)

  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐
  │ Tests:        4                                                                                │
  │ Passing:      4                                                                                │
  │ Failing:      0                                                                                │
  │ Pending:      0                                                                                │
  │ Skipped:      0                                                                                │
  │ Screenshots:  0                                                                                │
  │ Video:        false                                                                            │
  │ Duration:     10 seconds                                                                       │
  │ Spec Ran:     financesAppTest.cy.js                                                            │
  └────────────────────────────────────────────────────────────────────────────────────────────────┘


====================================================================================================

  (Run Finished)


       Spec                                              Tests  Passing  Failing  Pending  Skipped
  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐
  │ √  financesAppTest.cy.js                    00:10        4        4        -        -        - │
  └────────────────────────────────────────────────────────────────────────────────────────────────┘
    √  All specs passed!                        00:10        4        4        -        -        -


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

O projeto se encontra em sua versão 1.1 

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