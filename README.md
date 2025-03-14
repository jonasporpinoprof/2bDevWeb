#index.HTML
### **1. Estrutura Geral**
- O código segue o padrão **HTML5** (`<!DOCTYPE html>`).
- O idioma do documento é definido como **português do Brasil** (`lang="pt-br"`).

### **2. `<head>` (Cabeçalho)**
- Define a codificação de caracteres como **UTF-8** para suportar acentos e caracteres especiais.
- Define o título da página como **"Luizinho"**.
- Importa um arquivo de estilos CSS externo chamado **"style.css"**.

### **3. `<body>` (Corpo da Página)**
#### **3.1 Cabeçalho (`<header>`)**
- Contém um menu de navegação (`<nav class="menu">`).
- O menu inclui uma lista não ordenada (`<ul>`) com três itens de menu:
  - **Página Inicial**
  - **Conteúdo**
  - **Contato**

#### **3.2 Conteúdo Principal (`<main>`)**
- **Título principal (`<h1>`)**: "Meu primeiro Site".
- **Imagem (`<img>` dentro de `<div class="foto">`)**:
  - A imagem **"nice.png"** será exibida com o texto alternativo "gato" caso a imagem não carregue.
- **Subtítulos**:
  - `<h2>`: "Estudando HTML".
  - `<h3>`: "Utilizando as TAGs".
- **Parágrafos (`<p>`)**:
  - Três frases famosas do personagem **Chapolin Colorado**, cada uma com classes e IDs diferentes:
    - `"Se aproveitam de minha nobreza."` (classe `n1`).
    - `"Não contavam com a minha astúcia."` (ID `n2`).
    - `"Ninguém tem paciência comigo!"` (classe `n1`).
---

#stily.css
---
Este código CSS define o estilo visual do site descrito anteriormente. Aqui está uma explicação detalhada dos estilos aplicados:
---

### **1. Reset de Estilos Globais (`* {}`)**
- Remove margens (`margin: 0;`) e preenchimentos (`padding: 0;`) padrão de todos os elementos para evitar espaçamentos indesejados.
- Usa `box-sizing: border-box;` para garantir que `padding` e `border` não aumentem o tamanho dos elementos.

---

### **2. Estilização Geral do `body`**
- Define a **cor do texto** como **rosa** (`color: pink;`).
- Define a **cor de fundo** como **marrom** (`background-color: brown;`).
- Aplica a **fonte padrão** **Arial** ou, caso não esteja disponível, uma **fonte sans-serif**.

---

### **3. Estilos do Menu de Navegação (`nav` e `.menu`)**
#### **3.1 Estrutura do Menu**
- O menu (`nav`) usa **`display: flex;`** para alinhar os itens horizontalmente.
- **`justify-content: center;`** alinha os itens ao centro da tela.
- **`margin-top: 20px;`** adiciona um espaçamento no topo.

#### **3.2 Lista do Menu (`.menu ul`)**
- Remove os estilos padrão de lista (`list-style-type: none;`).
- Usa `display: flex;` para alinhar os itens horizontalmente.

#### **3.3 Itens da Lista (`.menu li`)**
- Adiciona **espaçamento lateral** entre os itens do menu (`margin: 0 10px;`).

#### **3.4 Links do Menu (`.menu a`)**
- Define um **fundo roxo claro** (`background-color: rgb(186, 129, 239);`).
- Define a **cor do texto como branco** (`color: white;`).
- Remove o **sublinhado** (`text-decoration: none;`).
- Adiciona **preenchimento interno** (`padding: 10px 20px;`) para criar um efeito de "botão".
- Adiciona **bordas arredondadas** (`border-radius: 5px;`).
- Aplica uma **transição suave** (`transition`) nos efeitos de hover.

#### **3.5 Efeito `hover` no Menu (`.menu a:hover`)**
- **Muda a cor do fundo** para um tom mais escuro de roxo (`rgb(134, 94, 179);`).
- Aplica um **efeito de escala (`scale(1.1)`)**, aumentando o tamanho do botão ao passar o mouse.

---

### **4. Estilização da Imagem (`.foto` e `img`)**
- `.foto`:
  - Usa `display: block;` para garantir que o elemento seja tratado como bloco.
  - **Centraliza a imagem** (`margin: auto;`).
  - Define um **tamanho fixo** de **200x200 pixels** (`width: 200px; height: 200px;`).

- `img`:
  - **Ocupa 100% do espaço disponível** dentro do `.foto` (`width: 100%; height: 100%;`).
  - Adiciona **bordas arredondadas** (`border-radius: 10px;`).

---

### **5. Estilos Adicionais**
- **`main {}`**
  - **Centraliza o texto** (`text-align: center;`).
  - Adiciona um **espaçamento superior** de `40px`.
---
