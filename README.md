# Portfólio Pessoal — Maxsuel Bruno

*Autor:* Maxsuel Bruno Oliveira de Abreu  
*Disciplina:* Desenvolvimento Web I — IFCE Campus Maranguape (Prof. Thomaz Maia)  
*Prazo de Entrega:* 30/11/2025

---

## Descrição do projeto
Este repositório contém a página *Portfólio Pessoal* desenvolvida em *HTML* e *CSS*. O objetivo é apresentar minha página pessoal com seções semânticas, lista de projetos, tabela de habilidades e formulário de contato, aplicando conceitos aprendidos no módulo (semântica, formulários, tabelas, listas, imagens, posicionamento e Flexbox). O site foi pensado para ser claro, legível e responsivo.

---

## Demonstração / Links
- Repositório GitHub: https://github.com/MaxsuelBruno  
- Projetos citados no portfólio:
  - Projeto LiricPlay (Site de Música): https://maxsuelbruno.github.io/Projeto-Figma_DesenvolvimentoWeb/
  - Projeto Landing Page: https://maxsuelbruno.github.io/Projeto-Landing-Page_DesenvolvimentoWeb/
  - Software House Factory: https://github.com/Softy-Tab

> *Link do GitHub Pages do portfólio:* COLE_AQUI_O_LINK_DO_SEU_GITHUB_PAGES

---

## Como o projeto atende aos requisitos do PDF (checagem)

### 1. Estrutura semântica
- Utilizei <header> contendo o nome completo e a navegação principal (<nav>).
- Utilizei <main> com as seções principais: *Sobre, **Projetos, **Habilidades* e *Contato*.
- Utilizei <footer> com informações de contato (link do GitHub e ano).

### 2. Navegação
- Links internos no <nav> que levam às seções: #sobre, #projetos, #habilidades, #contato.

### 3. Seção "Sobre mim"
- Texto de apresentação dentro de <p> e títulos (<h1>, <h2>).
- Foto pessoal com <figure> e <img> (recomenda-se adicionar <figcaption> se desejar legenda).

### 4. Seção "Projetos"
- Lista de projetos usando <ul> com <a> apontando para repositórios / páginas externas.
- Galeria com imagens de exemplo dos projetos.

### 5. Seção "Habilidades"
- Tabela <table> com colunas: *Tecnologia, **Nível de Conhecimento, **Tempo de Experiência*.

### 6. Seção "Contato"
- Formulário <form> com campos obrigatórios:
  - Nome (<input type="text">)
  - E-mail (<input type="email">)
  - Assunto (<input type="text">)
  - Mensagem (<textarea>)
  - Botão de envio (<button type="submit">)

---

## Requisitos de estilo (CSS) aplicados
- style.css utiliza seletores por tag, classe e ID.
- Definição de cores, tipografia, tamanhos e pesos (font-family, font-size).
- Box model aplicado (margin, padding, border).
- Uso de posicionamento (por exemplo, header e footer com width, padding; pode-se ampliar com position: sticky se preferir).
- Uso de *Flexbox* para organizar a galeria de projetos e o layout responsivo das seções (.galeria-projetos com display: flex; flex-wrap: wrap; justify-content: center;).
- Seletores :hover aplicados em botão (button:hover) e links.
- Layout pensado para boa legibilidade e harmonia entre cores.

---

## Estrutura de pastas (conforme exigido)
```
├── index.html
├── css/
│   └── style.css
├── img/
│   ├── eu.jpg
│   ├── liricplay.png
│   ├── teladeLogin.jpg
└─ ─├── landingpage.jpg 
```
