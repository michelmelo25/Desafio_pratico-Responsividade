# 📱 Desafio Prático de Responsividade: Desktop para Mobile

## 🌟 Visão Geral do Projeto

Este repositório apresenta a **solução prática** para um desafio de desenvolvimento web focado em responsividade. O objetivo principal foi transformar três projetos web que existiam apenas na versão desktop em layouts totalmente funcionais e otimizados para dispositivos móveis.

O desafio consistiu em utilizar o código-fonte original (HTML e CSS) e adicionar as regras de estilo necessárias para a experiência mobile, seguindo layouts de referência específicos.

## 🛠️ Tecnologias e Metodologia

Todo o trabalho foi realizado utilizando **HTML e CSS puro**, reforçando a compreensão dos fundamentos do design responsivo.

- **HTML5:** Estrutura e semântica do conteúdo.
- **CSS3 (Puro):** Estilização completa.
- **Media Queries:** O recurso central utilizado para implementar os _breakpoints_ e adaptar o layout especificamente para telas menores (mobile).

> **Metodologia:** Foi adotada uma abordagem _Mobile-First_ para os novos estilos (embora o código base fosse Desktop-First), garantindo que as regras de estilo móvel fossem concisas e eficientes.

## ✨ Projetos Adaptados

Três diferentes tipos de projetos foram reestruturados para garantir a responsividade em diversos cenários de interface de usuário (UI):

| Projeto                                            | Descrição da Solução Responsiva                                                                                                                                                 |
| :------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **1. Perfil de Viagens (Travelgram)**              | Reorganização do feed, ajuste na navegação e adaptação do cabeçalho/menu para uma interface de perfil vertical, priorizando o conteúdo visual no mobile.                        |
| **2. Portal de Notícias (Tech News)**              | Otimização da legibilidade dos artigos, redefinição do _grid_ de notícias para uma coluna única (ou poucas colunas) e simplificação do cabeçalho e menu de categorias.          |
| **3. Formulário de Matrícula (Estrela do Amanhã)** | Garantia de que todos os campos de entrada, _checkboxes_ e _dropareas_ ocupem 100% da largura, com espaçamentos otimizados para toque e navegação fácil em dispositivos móveis. |

## 📂 Estrutura de Arquivos

A estrutura de arquivos original de cada projeto foi mantida, com a adição dos Media Queries nos respectivos arquivos CSS para implementar a responsividade.

```
├── Formulario-de-Matricula-Estrela-do-Amanha/
├── Tech-News/
└── Travelgram/
    ├── assets/
    ├── styles/
    │   └── *.css  (Contém as Media Queries)
    └── index.html
```

## 🖥️ Como Visualizar os Projetos

Você pode visualizar as páginas abrindo o arquivo `index.html` de cada projeto diretamente no seu navegador. Para testar a responsividade:

1.  Abra a página (ex: `Travelgram/index.html`).
2.  Abra as Ferramentas do Desenvolvedor (F12 ou `Ctrl+Shift+I`).
3.  Use o ícone **Toggle device toolbar** ($\small{\text{Ctrl+Shift+M}}$) para simular diferentes tamanhos de tela (Smartphones, Tablets, etc.).
