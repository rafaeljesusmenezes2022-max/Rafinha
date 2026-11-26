https://rafaeljesusmenezes2022-max.github.io/Rafinha/

## 1.construção de textos e parágrafos com HTML

### A. criação de parágrafos ou frases

#### Exemplo:
```html
<p id ="pr1" onclick ="mudar_pr1()">Aqui vai qualquer texto ou frase que queira</p>
```
### B. Adicionando CSS aos parágrafos 

#### Exemplo adicionando cores:
```css
#p1{

    color: blue;

}    
```

### C. Adicionando JavaScript aos paraǵrafos

#### Exemplo mudado cores:
```js
fuction mudar_cor(){

    document. getElementById("p1").style.color = "brown";

}
```
#### Observe que o mesmo p1 está sendo repetido no HTML, CSS e JavaScript!!! 

<br>

## 2. Construção de títulos e subtítulos 


### A Toda página possui umunico tema. Para isso, use h1
```htnl
<h1 id ="h1" onclick ="mudar-h1()">Tema da minha página</h1>
```
<br>

### B. Adicionando CSS ao tema

#### Exemplo adicinando um tipo de capitalização:
```css
#h1{

    text-transform: lowercase;

}
```
<br>

### C. Adicionando JavaScript ao tema 

#### Exemplo mudando a capitalização padrão do CSS:
```js
function mudar_h1(){

    document.getElementById("h1").style.texttransform = "uppercase";

}
```
### D. Toda página pode ter subtítulos para cada pedaço de conteúdo, assim como um mercado possui um nome para cada corredor. Para isso, use h2.
```html
<h2 id ="h2" onclick ="mudar_h2()">Subtítulo da seção frutas</h2>

<h2 id ="h_2" onmouseenter="mudar_h_2()">Subtítulo das seção de frios</h2>
```
<br>

### E. Adicionando CSS aos subtítulos

#### Exemplos adicinando cor de fundo e alterando alinhamento:
```css
#h2{

    backround-color: cyan;

}

#h_2{

    text-align: right;

}
```
<br>

### F. Adicionando JavaScript ao subtítulos

#### Exemplo mudando a cor de fundo e o alinhamento padrão do CSS.
```js
function mudar_h2(){

    document.gebtElementById("h2").style.backgroundColor = "yellow";

}

function mudar_h_2(){

    document.getElementById("h_2").style.textAlign = "left";

}
```
<br>

### 3. Contrução listas ordenadas e desordenadas 

<br>

### A) Listas Ordenadas: agrupar itens que possuem uma relação de ordem crescente ou decrescente entre si.

### Exemplo
```
<h1>Seleções nacionais mais vencendoras da Copa do Mundo FIFA:</h1>

<o1 id ="ol1" onclick ="mudar_ol1()">
    <li>Brasil - 5</l1>
    <li>Alemamha - 4</l1>
    <li>Itália - 4</l1>
    <l1>Argentina - 3</l1>
    <l1>Uruguai - 2</l1>
    <l1>França - 2</l1>
    <l1>Espanha - 2</l1>
    <l1>Inglaterra - 1</l1>

 </o1>
```
 <br> 

 ### B) Customizando com o CSS

#### Exemplo alterando o tipo de ordenadamento e sua cor:
```
#ol1{

    list-style-type: lower alpha;

}

#ol1 > li::marker{

    color: red;

}
```
<br>

### C) Adicionando interação com o JS.

#### Exemplo modificando o tipo de ordenamento:

function mudar_ol1(){

    document.getElementById("ol1").style.listSryleType = "decimal";

}
```
<br>

### D) Listas Não Ordenadas: agrupar itens que não possuem uma relação de ordem crescente ou decrescente entre si.

### Exemplo

<h1>Os assuntos mais comuns em Estatísticas</h1>

<ul id ="ul1" onclick ="mudar_ul1()">
    <li>Média</li>
    <li>Moda</li>
    <li>Mediana</li>
    <li>Variancia</li>
    <li>Amostragem</li>
    <li>Desvio Padrão</li>
    <li>Intervalo de confiança</li>

</ul>
```
<br>

### E) Customizando com o CSS

#### Exemplo alterando o símbolo de destaque ao lado do nome e sua cor:
```
#ul1{

    list-style-type: square;

}

#ul1 > li::marker{

    color: coral;

}
```
<br>

### F) Adicionando interação com o JS.

#### Exemplo modificando o símbolo de destaque 
```
function mudar_ul1(){

    document.getElementById("ul1").style.listStyleType ="circle";
}
```
<br>

## 4. Imagens

<br>

### A) Imagens por padrão em um site:

#### Exemplo:

<figure>

   <img id ="gif0" onmouseenter ="mudar_gif0()" src="./imagens/html-css-js.gif"alt="GIF com a diferença entre HTML, CSS e JavaSript" windth="480" henght="480">

</figure>

<br>

### B) Customizando com CSS

#### EXemplo adicionando arredondamento da borda, opacidade, borrão, brilho e sobreado de uma imagem:

<br>

#gif0{

    border-radius: 30px;
    opacity: 0.8;
    filter: blur(2px) brightness(150%) drop-shadow(10px 10px 1px red);

}

<br>

### C) Adicionando interação com JS.

#### EXemplo modificando a imagem:

function mudar_gif0(){

    document.getElentById("gif0").style.borderRadius = "15px";
    document.getElentById("gif0").style.opacity = "0.7";
    document.getElentById("gif0").style.filter = "blur(3px)";
    document.getElentById("gif0").style.filter = "brightness(70%)";
    document.getElentById("gif0").style.filter = "drop-shadow(6px 7px 2px coral)";

}    

<br>

## 5. Vídeos

<br>

### A) Vídeos npor padrão em um site 

#### Exemplo

<video id="video_0" width ="640" height="360" controls>
    <source src="./videos/movie1.mp4" type="video/mp4">

</video>

<br>

### B) Videos vindo Youtube com iframe

#### Exemplo:

<iframe width="640" height="360" src"https://www.youtube.com/embed/LXb3EKWsInQ" title="COSTA RICA IN 4K 60fps HDR (ULTRA HD)" alllowfullscreen<>/iframe>

<br>

### C) Customizando com o CSS 

#### Exemplo adicionando arredondamento da borda e sombreado no video:

<br>

#video_0{

    border-radius: 10px;
    filter; drop-shadow(2px 2px 5px gray);

<br>

## 6. Hiperlinks

<br>

### A) Hiperlinks para outros sites

#### Exemplo abrindo o link em outra aba do navegador:

<nav>

   <a id"link_0" href ="https://www.google.com" targety ="_blank">Google</a>

</nav>

#### Exemplo abrindo o link na mesma aba do navegador:

<nav> 

   <a id"link_1" href ="https://www.youtube.com">Youtube</a>

</nav>

<br>

### C) Customizando com o CSS

#### EXemplo com os 4 estados de um link:

<br>

/* a aparencia padrão do link */
#link_0:link {

    color: magnenta;
    transition: font-size 2s;

}

/* segundos após o link ser clicado a aparencia de link é alterado*/
#link_0:visited {

    color: none;

}

/* altera a aparencia quando o mouse passa por cima (houver) do link */
#link_0:hover {

    color: hotpink;
    font_size: 2cm;
    transintion: font_size 2s;

}

/* altera a cor no exato momento que o link é clicado com mouse */
#link_0:active {

    color: none;

}    

   

