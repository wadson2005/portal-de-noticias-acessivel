# Trabalho de Acessibilidade Web - Programação Para a Internet I

Este repositório contém o trabalho da disciplina de Programação Para a Internet I, do curso de Análise e Desenvolvimento de Sistemas do Instituto Federal do Piauí (IFPI), ministrada pelo professor Ely.

O projeto foi dividido em duas etapas principais, com o objetivo de estudar e aplicar na prática os conceitos de acessibilidade web, seguindo as diretrizes da WCAG 2.1.

---

## 📂 Etapa 1: Análise de Acessibilidade

Nesta etapa, foi realizado um estudo sobre a acessibilidade de três sites institucionais brasileiros. O objetivo foi identificar pontos fortes, fracos e sugerir melhorias técnicas.

A análise foi conduzida utilizando navegação via teclado e o leitor de tela NVDA.

**Sites Analisados:**
* Instituto Federal do Piauí (IFPI)
* Universidade Federal do Piauí (UFPI)
* Portal de Notícias G1

O documento completo com a avaliação detalhada de cada site pode ser encontrado no arquivo `ANALISE_COMPLETA.pdf` neste repositório.

---

## 💻 Etapa 2: Construção de Página Acessível

A segunda etapa consistiu na construção de uma página de notícias simples, onde os princípios de acessibilidade foram aplicados desde a concepção.

O resultado é o arquivo `index.html` e sua folha de estilos `style.css`.

**Principais Recursos de Acessibilidade Implementados:**

* **HTML Semântico:** A estrutura da página utiliza tags como `<header>`, `<nav>`, `<main>`, `<aside>` e `<footer>` para criar marcos de navegação claros para leitores de tela.
* **Foco Visível:** Todos os elementos interativos (links, botões, inputs) possuem um destaque visual claro (`outline`) quando recebem foco pelo teclado, utilizando a pseudo-classe `:focus-visible`.
* **Skip Link:** Um link "Pular para o conteúdo principal" é o primeiro item focável, permitindo que usuários de teclado ignorem o menu e cheguem diretamente ao conteúdo principal.
* **Conteúdo para Leitores de Tela:** Foi utilizada a técnica da classe `.sr-only` para fornecer contexto adicional em links ambíguos, como "Leia mais", sem poluir a interface visual.
* **Contraste e Rótulos:** O projeto utiliza cores com bom contraste e todos os campos de formulário possuem rótulos (`<label>`) associados corretamente.

---

### Como visualizar o projeto

1.  Clone este repositório para a sua máquina local.
2.  Abra o arquivo `index.html` em qualquer navegador moderno.
3.  Para testar a acessibilidade, navegue pela página utilizando apenas a tecla **Tab** e/ou um leitor de tela como o NVDA.

### Tecnologias Utilizadas

* HTML5
* CSS3
* NVDA