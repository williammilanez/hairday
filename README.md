<p align="center">
  <img alt="Logo HairDay" src="./src/assets/images/logo.png" width="250px" />
</p>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=1D4ED8&labelColor=0F172A">
  <img src="https://img.shields.io/badge/status-active-success" alt="Status: active">
  <img src="https://img.shields.io/github/last-commit/williammilanez/hairday" alt="Last commit">
  <img src="https://img.shields.io/github/languages/top/williammilanez/hairday" alt="Top language">
</p>

---

<p align="center">
  <img alt="Projeto" src="./src/assets/images/project-cover.png" width="75%">
</p>

## 💻 Projeto

A **Plataforma de Agendamento HairDay** é uma aplicação web voltada para o **gerenciamento de horários de corte de cabelo em barbearias**, permitindo criar, visualizar e cancelar agendamentos de forma simples, rápida e organizada.<br>
O projeto foi desenvolvido com foco em **arquitetura modular**, **boas práticas de JavaScript**, separação de responsabilidades e integração com uma **API simulada** utilizando `json-server`.<br>
É totalmente **responsivo** e funcional nas versões **Desktop** e **Mobile**.

### Funcionalidades principais:

- Criação de agendamentos com nome do cliente, data e horário.
- Listagem de agendamentos filtrados por dia.
- Cancelamento de agendamentos em tempo real.
- Bloqueio automático de horários já ocupados.
- Validação de datas e horários passados.
- Atualização dinâmica da interface sem recarregar a página.
- Arquitetura em camadas (`services`, `modules` e `utils`)

---

## 🚀 Tecnologias

Desenvolvido com:

- **HTML5**
- **CSS3**
- **JavaScript (ES Modules)**
- **Day.js**
- **Webpack**
- **Babel**
- **json-server**

---

## 🔖 Layout

Visualize o layout do projeto:

<p align="center">
  <img alt="Preview do projeto" src="./src/assets/images/project-preview.png" width="75%">
</p>

- Horários organizados por **Manhã**, **Tarde** e **Noite**.<br>
- Destaque visual para horários disponíveis e indisponíveis.<br>
- Lista de agendamentos do dia.<br>
- Ícone de cancelamento com confirmação do usuário.

---

## 📝 Como Abrir o Projeto

1. Clone ou baixe o repositório.
2. No terminal, instale as dependências do projeto: `npm install`.
3. Inicie a API simulada (json-server): `npm run server`.
   - A API ficará disponível em: http://localhost:3333.
4. Inicie o ambiente de desenvolvimento: `npm run dev`.
   - A aplicação será aberta em: http://localhost:3000.

## 📝 Como Usar o Projeto

1. Selecione uma data.
2. Escolha um horário disponível.
3. Informe o nome do cliente.
4. Confirme o agendamento.
5. Para cancelar, clique no ícone “X” na linha do agendamento desejado.

---

## 📚 Aprendizados Aplicados

- Arquitetura modular em JavaScript.
- Separação de responsabilidades (UI, Services e Lógica).
- Consumo de API REST com `fetch`.
- Manipulação de datas com Day.js.
- Controle de estado baseado em backend.
- Uso do `json-server` como API simulada.
- Configuração de ambiente com Webpack.
- Organização de código para escalabilidade.

---

## 👨‍💻 Autor

Desenvolvido por **Rocketseat**<br>.
Adaptado e implementado por **William Milanez**<br>.
📍 Formação de Full-Stack – _Plataforma de Agendamento_.

---

## 📄 Licença

Este projeto está sob a licença **MIT**.<br>
Este projeto é de uso educacional e livre para fins de estudo e prática pessoal.

---
