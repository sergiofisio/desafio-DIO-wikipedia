# Desafio DIO: Recriando a Wikipedia 🚀

Este repositório contém a minha solução para o desafio do Módulo 3 - Trilha HTML da DIO, com o objetivo de recriar uma página da Wikipedia com um layout aprimorado, focando na **estrutura semântica** e **acessibilidade**.

---

## 🎯 Objetivo do Desafio

O desafio proposto pela DIO visou capacitar os desenvolvedores a:

* Construir uma estrutura de site robusta e bem organizada utilizando HTML.

* Aplicar tags HTML semânticas para dar significado ao conteúdo e melhorar a compreensão por parte dos navegadores e tecnologias assistivas.

* Implementar princípios de acessibilidade para garantir que o site seja utilizável por todas as pessoas, incluindo aquelas com deficiência.

---

## ✨ Funcionalidades e Aprendizados

Neste projeto, recriei uma página inspirada na Wikipedia, abordando o tema da **Galáxia de Andrômeda**. Durante o desenvolvimento, foquei em:

* **Estrutura Semântica:** Utilização de tags como `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>` e `<footer>` para organizar o conteúdo de forma lógica e significativa.

* **Hierarquia de Títulos:** Uso correto de `<h1>` a `<h6>` para estruturar o artigo e facilitar a navegação.

* **Listas e Parágrafos:** Emprego de `<p>`, `<ul>`, `<ol>` e `<li>` para apresentar o texto e as informações de forma clara.

* **Tags de Formatação de Texto:** Aplicação de `<strong>`, `<i>`, `<u>`, `<mark>`, `<sub>`, `<sup>` e `<blockquote>` para enriquecer o conteúdo textual.

* **Novas Tags (Pesquisadas):**

    * `<abbr>`: Para abreviações, com o atributo `title` para fornecer a descrição completa.

    * `<del>`: Para indicar texto que foi deletado ou alterado.

    * `<font>`: Incluída para fins de exercício, com a **ressalva importante** de que é uma tag **obsoleta (deprecated)** e seu uso para estilização deve ser evitado em HTML moderno, preferindo-se o CSS.

* **Links e Acessibilidade:** Uso de `<a>` com `target="_blank"` e `rel="noopener noreferrer"` para links externos, e foco na descrição clara para leitores de tela.

* **CSS Básico:** Estilização utilizando um arquivo `style.css` para tornar a página mais apresentável e simular o visual da Wikipedia, incluindo:

    * Layout responsivo simples (não totalmente otimizado para mobile, mas com estrutura flexível).

    * Cores e tipografia que remetem à enciclopédia online.

    * Estilos para as novas tags implementadas.

* **Acessibilidade (com NVDA):** Testes realizados com o leitor de tela NVDA para garantir que a navegação e a leitura do conteúdo fossem claras e intuitivas para usuários com deficiência visual. Isso incluiu o uso de `label` para campos de formulário (com `sr-only` para esconder visualmente, mas manter acessível).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**

* **CSS3**

---

## 🚀 Como Executar o Projeto

Para visualizar esta página em seu navegador e testar sua acessibilidade:

1.  **Clone o repositório** ou baixe os arquivos diretamente.

2.  Certifique-se de que a estrutura de arquivos esteja correta:

    ```
    .
    ├── index.html
    └── css/
        └── style.css

    ```

3.  Abra o arquivo `index.html` em seu navegador web preferido (Chrome, Firefox, Edge, etc.).

4.  (Opcional) Para testar a acessibilidade, baixe e instale o **NVDA** (NonVisual Desktop Access) e, com a página aberta, inicie o NVDA. Explore a página usando as teclas de navegação do teclado.

---

## 👨‍💻 Autor

[Seu Nome/GitHub Username]
[Link para o seu perfil no GitHub ou LinkedIn, se desejar]

---