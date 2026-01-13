# ✈️ Flex Turismos

> Uma Landing Page moderna e responsiva desenvolvida para consolidar conhecimentos em CSS Flexbox e HTML Semântico.

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-green) ![License](https://img.shields.io/badge/License-MIT-blue) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

---

## 🖼️ Preview

![Screenshot do Projeto](img/0-main.png)

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido como parte de um desafio prático do **Bootcamp Full Stack da DIO (Digital Innovation One)**.

O objetivo principal não foi apenas entregar uma página visualmente agradável, mas sim **dominar a lógica do CSS Flexbox**, abandonando técnicas antigas de posicionamento (como `float`) e abraçando padrões modernos de layout.

### O que eu quis resolver?

1.  **Alinhamento:** Como centralizar e distribuir elementos sem "gambiarras".
2.  **Estrutura:** Criar um layout de colunas e linhas fluido.
3.  **Semântica:** Garantir que o HTML seja acessível e bem estruturado.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico:** Uso correto de tags como `<header>`, `<nav>`, `<section>` e `<footer>` para melhor SEO e acessibilidade.
- **CSS3 Moderno:**
  - **Flexbox:** O coração do layout.
  - **CSS Variables:** Para gerenciamento centralizado de cores (`:root`).

---

## 📂 Estrutura do Projeto

O site é uma _One Page_ dividida nas seguintes seções:

| Seção              | Descrição Técnica                                                                       |
| :----------------- | :-------------------------------------------------------------------------------------- |
| **🏠 Header**      | Navegação horizontal com logo e menu, alinhados via `justify-content: space-between`.   |
| **✨ Home (Hero)** | Destaque principal utilizando `flex-direction` para alinhar texto e imagem lado a lado. |
| **👥 Quem Somos**  | Texto descritivo e imagem, focando em tipografia e espaçamento (`line-height`).         |
| **🛠️ Serviços**    | Cards informativos organizados em linha com `gap` para espaçamento uniforme.            |
| **💲 Planos**      | Estrutura de preços alinhada verticalmente, utilizando bordas e listas estilizadas.     |
| **🦶 Footer**      | Rodapé simples com créditos, alinhado com Flexbox.                                      |

---

## 🧠 Aprendizados e Conceitos Aplicados

Durante o desenvolvimento, foquei em aplicar as melhores práticas de **Clean Code** no CSS. Abaixo, alguns dos desafios superados:

### 1. O poder do `gap` vs `margin`

Aprendi que para separar elementos flexíveis, a propriedade `gap` é muito mais eficiente e limpa do que aplicar margens individuais em cada elemento filho.

```css
.container-planos {
  display: flex;
  gap: 50px; /* Cria um espaço perfeito entre os planos */
}
```
