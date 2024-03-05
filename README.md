# documenta-o_css

/* ==========================================================================
   Estilos para o Projeto XYZ
   ========================================================================== */

/* Reset de Estilos */
/* Utilizamos um reset para garantir uma base consistente em todos os navegadores */
html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section,
summary,
time,
mark,
audio,
video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}

/* Acessibilidade */
/* Certifique-se de que o contraste de cor entre texto e fundo é suficiente para usuários com deficiência visual */
body {
    color: #333;
    background-color: #fff;
}

a {
    color: #007bff; /* azul */
}

a:hover {
    color: #0056b3; /* azul escuro */
}

/* Use tamanhos de fonte e espaçamento adequados para facilitar a leitura */
p,
ul,
ol {
    font-size: 16px;
    line-height: 1.5;
}

/* Desempenho */
/* Minimize o número de seletores aninhados para reduzir a complexidade e melhorar o desempenho de renderização */
.header {
    background-color: #f7f7f7;
    padding: 10px;
}

.header .logo {
    max-width: 150px;
}

/* Em vez disso, utilize seletores diretos sempre que possível */
.header-logo {
    max-width: 150px;
}

/* Combine regras CSS similares para reduzir o tamanho do arquivo */
.button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    font-size: 16px;
}

.button:hover {
    background-color: #0056b3;
}

/* Em vez disso, combine regras CSS similares */
.button {
    display: inline-block;
    padding: 10px 20px;
    font-size: 16px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
}

/* Remova estilos não utilizados para reduzir o tamanho do arquivo */
/* Estilos que não estão sendo usados no site atualmente */
.unused-style {
    /* Propriedades não utilizadas */
}

/* ==========================================================================
   Fim dos Estilos
   ========================================================================== */
