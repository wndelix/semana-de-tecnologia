```css
/* Configurações gerais */
body {
    font-family: Arial, sans-serif;
    font-size: 16px;
    color: #333333;
    background-color: #f0f0f0;
    margin: 0;
}

/* Cabeçalho */
#cabecalho {
    background-color: #163a5f;
    color: white;
    padding: 30px;
    margin-bottom: 20px;
    text-align: center;
}

#cabecalho h1 {
    font-size: 36px;
    letter-spacing: 2px;
}

#cabecalho p {
    font-size: 16px;
    line-height: 1.6;
}

/* Menu de navegação */
nav {
    background-color: #2874a6;
    padding: 15px;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    text-align: center;
}

nav li {
    display: inline-block;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: #ffcc00;
}

/* Seções principais */
section {
    background-color: white;
    padding: 20px;
    margin: 20px;
    border: 2px solid #cccccc;
}

section h2 {
    color: #163a5f;
    font-size: 24px;
}

section p {
    font-size: 16px;
    line-height: 1.6;
}

/* Textos da seção Sobre */
#sobre p {
    text-align: justify;
}

/* Imagem */
#sobre img {
    width: 400px;
    height: 250px;
    border: 3px solid #163a5f;
    object-fit: cover;
}

/* Tabela */
table {
    width: 100%;
    border-collapse: collapse;
}

th,
td {
    border: 1px solid #333333;
    padding: 12px;
    text-align: left;
}

th {
    background-color: #2874a6;
    color: white;
}

td {
    background-color: #f9f9f9;
}

/* Classe comum das caixas de atividades */
.atividade {
    width: 300px;
    height: 180px;
    padding: 20px;
    margin: 15px;
    border: 3px solid;
}

/* Títulos das atividades */
.atividade h3 {
    font-size: 20px;
    font-weight: bold;
}

/* Caixa 1: azul-claro, borda azul-escura e cantos retos */
.caixa-azul {
    background-color: lightblue;
    border-color: #00008b;
    border-radius: 0;
}

/* Caixa 2: verde-claro, borda verde e cantos arredondados */
.caixa-verde {
    background-color: #c8f7c5;
    border-color: green;
    border-radius: 15px;
}

/* Caixa 3: vermelho-claro, borda roxa de 5px */
.caixa-vermelha {
    background-color: #f5b7b1;
    border: 5px solid purple;
    border-radius: 30px;
    border-top-left-radius: 0px;
}

/* Links das atividades */
.atividade a {
    color: #163a5f;
    font-weight: bold;
}

/* Efeito ao passar o mouse nos links das atividades */
.atividade a:hover {
    color: rgb(220, 20, 60);
}

/* Rodapé */
footer {
    background-color: #163a5f;
    color: white;
    padding: 20px;
    text-align: center;
}

footer p {
    line-height: 1.6;
}
```
