# 🗺️ Landing Page: Rotas do Interior Paranaense

## 💻 Sobre o Projeto

Este projeto é uma Landing Page responsiva desenvolvida em HTML5 e CSS3, focada nas diversas rotas turísticas do Interior do Paraná. O objetivo principal foi aplicar os conhecimentos de semântica, navegabilidade e interatividade para cumprir todos os requisitos do desafio.

## ✨ Destaques e Conformidade com Requisitos

O projeto foi construído em estrita conformidade com as especificações técnicas:

### 1. Estrutura e Semântica

* **Tags Semânticas:** Uso correto das tags **`<main>`**, **`<nav>`**, **`<section>`**, **`<article>`** e **`<footer>`**.
* **Seções Mínimas:** A página possui mais de três seções (contém `#destinos`, `#tripme`, `#advice` e `#meetus`).
* **Banner (1.1, 1.2, 1.3):** O banner está no **`<main>`**, utiliza a imagem de fundo (Cataratas/Mapa do Paraná) e possui texto com *overlay* (`<h1>` e `<p>`).
* **Justificação de Texto:** O texto dos parágrafos em bloco está justificado (`text-align: justify;`).

### 2. Navegação e IDs

* **Navegação Fixa:** A barra de navegação está **fixada no topo** (`position: sticky` ou `fixed`), facilitando a usabilidade e o acesso ao link **"Início"** a qualquer momento.
* **Navegação Interna (2.1, 2.2):** Toda a navegação é feita por âncoras internas (`<a href="#id">`), garantindo que a página seja carregada **sempre na mesma aba** (não utiliza `target="_blank"`).
* **Uso de IDs (2):** Todas as seções possuem IDs específicos que são chamados corretamente na navegação.

### 3. Interatividade (Hover e Transition)

* **Mudança de Aparência (3.1):** Todos os elementos interativos (links da `nav`, botões, cards) **mudam de aparência** ao receberem o foco do mouse (`:hover`).
* **Transição Suave (3.2):** Foi utilizado o `transition` no CSS para suavizar as mudanças de cor e o movimento dos cards de destino (`transform: translateY`), adicionando um "ar da graça" visual.

---

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estrutura e Semântica
* **CSS3:** Estilização, Responsividade (Flexbox) e Efeitos Visuais.

