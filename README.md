# 🚀 RACK+ Frontend E2E Tests

Este repositório contém a implementação do front-end (HTML, CSS e JavaScript) das páginas de Login e Homepage do sistema RACK+, juntamente com uma suíte de testes automatizados End-to-End (E2E) utilizando Cypress.

O projeto RACK+ foi originalmente desenvolvido em um projeto anterior no SENAI, com foco na construção da interface. Neste repositório, a aplicação foi reutilizada e adaptada com o objetivo de aplicar práticas de Quality Assurance (QA), por meio da criação de testes automatizados para validação da interface e da experiência do usuário.

🔗 **Repositório:**
https://github.com/CaioGomes26/rackplus-frontend-e2e-tests

---

## 📌 Sobre o Projeto

Este projeto valida a interface do sistema RACK+ através de testes automatizados, cobrindo:

* ✔️ Validação de elementos visuais (UI)
* ✔️ Fluxos funcionais (login, navegação, interações)
* ✔️ Responsividade (desktop e mobile)

---

##  Objetivo

Aplicar práticas de **Quality Assurance (QA)** em aplicações front-end, utilizando testes E2E para garantir:

* Confiabilidade da interface
* Boa experiência do usuário (UX)
* Prevenção de regressões

---

##  Cobertura de Testes (Cypress)

###  Login (`login.cy.js`)

* Fluxo de autenticação (sucesso e falha)
* Validação de campos obrigatórios
* Feedback visual (mensagens de erro e animações)
* Interações (mostrar/ocultar senha)
* Testes de responsividade

###  Homepage (`homepage.cy.js`)

* Navegação entre menus (desktop e mobile)
* Validação de layout responsivo
* Verificação de elementos visuais (cards, cores e status)
* Integridade de links, ícones e imagens

### OBS
* A página não foi testada pois se assemelha a de Login, contudo, fora enviada em conjunto no projeto apenas para apresentação da interface.

---

##  Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript
* Bootstrap 5
* Cypress

---

##  Pré-requisitos

Antes de iniciar, você precisa ter instalado:

* Node.js (v12 ou superior)
* VS Code (recomendado)
* Extensão Live Server
* Cypress (instalado no projeto)

---

##  Instalação

```bash
# Clonar repositório
git clone https://github.com/CaioGomes26/rackplus-frontend-e2e-tests.git

# Acessar pasta
cd rackplus-frontend-e2e-tests

# Instalar dependências
npm install
```

---

##  Executando o Projeto

Inicie o servidor local com o Live Server:

* Abra o projeto no VS Code
* Clique com o botão direito no arquivo de login
* Selecione **"Open with Live Server"**
* Certifique-se de que está rodando em:

```
http://127.0.0.1:5500/
```

---

##  Executando os Testes

###  Modo Interativo

```bash
npx cypress open
```

###  Modo Headless

```bash
npx cypress run
```

###  Resultados

* Vídeos: `cypress/videos/`
* Screenshots: `cypress/screenshots/`

---

## 💡 Observação

Caso a aplicação esteja rodando em outra porta, ajuste a URL base nos arquivos de teste (`.cy.js`).

---

## 👨‍💻 Autor

**Caio Gomes de Oliveira**

Projeto desenvolvido como parte da formação em desenvolvimento front-end no SENAI, com foco em testes automatizados e qualidade de software.
