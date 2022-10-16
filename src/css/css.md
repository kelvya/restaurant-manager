## LENGTH CSS

### PX
>Medida angular
![](/images/recursosHTML/images/vision_angle.jpg)

### cm, in, mm

Mapeados para pixels
>1cm == 37.8px <br/>
1mm == 0.1cm == 3.78px <br/>
1in == 96px

### em
> 1em == 16px == 12pt <br/>
> font-size: 14px <br/>
> div > font-size: 1.2em <br/>
> div > div > div (font-size) <br/>
> 1° = 16.8px > 2° = 12.16px > 3° = 24.192px

### rem
> Base no root (html)

### pt (print)
> 1pt = 1/72 polegadas

### pc (print)
> 1pc == 12pt

### %
> img width=50% relativo ao elemento que ela está contida<br/>
> > heigth (atenção com %)

### vh, vw

view port heigth e view port width

A janela de navegação do navegador na sua largura e na sua altura

>1vh == 1% da altura da janela de visualização<br/>
>1vw == 1% da largura da janela de visualização<br/> 

### vmax, vmin
![](/images/recursosHTML/images/svg/vcompare.svg)

## TEXT
> color (names, hexa, rgb, hsl, gradient)[]

> ALIGN

    - tesxt-align [x]
    - text-align-last [x]
    - direction [x]
    - vertical-align [x]

> DECORATION

    - line [x]
    - color [x]
    - style [x]
    - thickness [x]
    - decoration [x]

> SPACING

    - text-indent [x]
    - letter-spacing [x]
    - line-height [x]
    - word-spacing [x]
    - white-spacing [x]

> TRANSFORM

    - uppercase [x]
    - lowercase [x]
    - capitalize [x]
  
## SELETORES

### Simples
- Nomes, ids e classes

###Combinações
- Relação entre elementos
- Adjacente (+), Descendente ( )
- Seletor filho (>), Seletor vizinho (~)

### Pseudo Elements
- Partes de um elemento
- 
::first-letter
::marker

### Pseudo Class
- Estado de um elemento
  
:hover
:checked
:active

### Atributos
- Atributos e valores de um elemento
  
>input[type=text]

### Prefixo dos Browsers
- webkit [-webkit] chrome, safari, opera+
- moz [-moz] firefox
- o [-o] opera-
- ms [-ms]internet explorer, edge

## Fontes

>Com Serifa

<p style="font-size:30px; font-family: 'times new roman'">Lorem Ipsum</p>

- Georgia
- Garamond

>Sem Serifa (sans-serif)
<p style="font-size:30px; font-family: 'Arial'">Lorem Ipsum</p>

- Verdana
- Helvética

>monoespaçadas (letras com a mesma largura fixa)
- Courier new
- Lucida Console

>Cursivas (imitam a escrita humana)
- Lucida Handwriting
- Brush Script MT

>Fantasia
- Copperplate
- Papyrus

## Box Model

>widht / height

>max-widht / min-widht

>min-height / max-height

>margin: 0 0 0 0 (top right buttom left)

>padding: 0 0 0 0 (top right buttom left)

>border-widht: 0 0 0 0 (top right buttom left)

>border-radius: 0 0 0 0 (top right buttom left)

### Variações
>margin: 0 (todos os lados)

>margin: 0 0 (top / buttom)

<p>Base</p>
<div style="border: outset 13px #fff; width:50%; margin: 30px auto">
    <div style="min-width: 300px; border: 4px solid #fff; border-radius: 12px 0 12px 0; text-align: rigth; margin: 10px auto; padding: 0 10px 0 0;">Lorem Ipsum</div>
</div>
<p>Base</p>

## POSITION

<div style="
border: solid 2px red;
min-width: 200px;
position: relative;
heigth: 250px;
margin: 30px auto">
    <div style="
    border: solid 1px #fff;
    widht: 80%;
    height: 200px;
    margin: 30px auto">
        <div style="
        width:40%;
        border: 1px solid #fff;
        text-align: right;
        position: absolute;
        background-color: #fff;
        top: 0;
        color; #000;
        padding: 0 10px 0 0;
        ">Lorem Ipsum</div>
    </div>
</div>

## BootStrap

É um recurso (framework), que pode ser adicionado ao documento HTML, facilitando o uso das classes e implementações usadas na interface.
>Extra Small
- (< 576px = 100%)
  
>Small - sm
- (> 576px = 540px)

>Medium - md
- (> 768px = 720px)

>Large - lg
- (> 992px = 960px)

>Extra Large
- (>1200px = 1440px)

>XX Large
- (>1440px = 1320px)
## Responsive Design - Responsividade
>mobile (portrait - retrato)
- 320px
- 375px
- 414px

>Mobile (landscape - paisagem)
- 568px
- 667px
- 736px
- 812px

>Tablet (portrait - retrato)
- 768px
- 834px

>Tablet (landscape - paisagem)
- 1024px
- 1112px

>Laptop
- 1366px
- 1440px

>Desktop
- 1680px
- 1920px
- 2048px

### Fluid Grids

Linhas e colunas que se ajustam mediante a largura da janela de visualização, breakpoints

### Breakpoints

As especificações (pontos de tamanho de tela que serão especificados no css e que estão sempre associados à janela de visualização[@media])

### Flexible Image

Verificar sempre o redimensionamento das imagens que é feito em porcentagem.

### Media Querie

São especificações CSS que contém as informações necessárias para a resposta, sobre a janela de visualização.

### Viewport

```
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```
### Overflow

Elementos de tela que estão fora do layout ou parcialmente fora do layout.

### Fixed Size

Utilizam pixels como larguras ou alturas.

O pixel não é responsivo

### Responsive Size

Utilizam medidas com rem ou porcentagem.

### Mobile First

Tecnica de layout que analisa primeiro telas menores para depois pensar em telas mais largas.
Não ignora telas maiores, mas inicia a técnica pelo mobile.

### Hamburguer Menu
Ícone que, ao pressionado, expande uma lista com a barra de navegação (abordagem dropdow).

## Box Sizing

>widht - Padding + Width + Border

>Height = Padding + Height = Border
```
<div style="
box-sizing: border-box;
text-align:center;
width:200px;
background-color: orange;
border:none">
    Lorem Ipsum
</div>
<hr/>
<div style="
box-sizing: border-box;
text-align:center;
width:200px;
border:3px solid #fff">
    Lorem Ipsum
</div>
<hr/>
<div style="
box-sizing: border-box;
text-align:center;
width:200px;
padding: 3px;   
border:2px solid #fff">
    Lorem Ipsum
</div>
```
<div style="
box-sizing: border-box;
text-align:center;
width:200px;
background-color: orange;
border:none">
    Lorem Ipsum
</div>
<hr/>
<div style="
box-sizing: border-box;
text-align:center;
width:200px;
border:3px solid #fff">
    Lorem Ipsum
</div>
<hr/>
<div style="
box-sizing: border-box;
text-align:center;
width:200px;
padding: 3px;   
border:2px solid #fff">
    Lorem Ipsum
</div>

```
*{
    box-sizing: border-box;
}
```
## DropDow Menu

<style>
    .drop-bt{
        background-color: #4caf50;
        color: #fff;
        border: none;
        padding: 14px;
        cursor: pointer;
        width: 100%;
    }
.drop-bt:hover + div, .drop-content:hover{
    display:block;
}

.drop{
    position: relative; 
    display: inline-block;
    margin:50px 0;
    min-width:160px;
}
.drop-content{
    display:none;
    position: absolute;
    min-width: 160px;
    box-shadow: 8px 16px 0 rgba (0,0,0,0.2);
    background-color: #f9f9f9;
}
.drop-content a{
    display:block;
    background-color:#eee;
}
drop-content a:hover{
    background-color: #fff;
    text-decoration: none;
}

</style>
<div class="drop">
    <button class="drop-bt">Menu DropDow</button>
    <div class="drop-content">
        <a href="#">Link 1</a>
        <a href="#">Link 2</a>
        <a href="#">Link 3</a>
    </div>
</div>
<br>
<br>
<br>
<br>

## Paginação

<style>
    .pag a{
        padding:0.5rem 1rem;
        color: #fff;
        display: inline-block;
    }
    .active{
        background: #f44336;
    }
    .active:hover{
        background-color: #fff;
        color:#000;
    }
</style>
<div class="pag">
    <a href="#">&laquo</a>
    <a href="#">1</a>
    <a href="#">2</a>
    <a class="active" href="#">3</a>
    <a href="#">4</a>
    <a href="#">5</a>
    <a href="#">6</a>
    <a href="#">&raquo</a>
</div>
## FLOAT
```
<div>
    <img style="" src="images/baked.jpg" width="60%"/>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Id voluptates dolores autem quos nulla illum pariatur magnam.
    </p>
</div>
```

<div>
    <img style="float:left;padding:0 12px 0 0" src="images/../../../images/recursosHTML/images/baked-salmon-garnished-with-asparagus-and-tomatoes-with-herbs.jpg" width="60%"/>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Id voluptates dolores autem quos nulla illum pariatur magnam.
    </p>
</div>
<hr/>
<div>
    <img style="float:right;padding:0 0 0 12px" src="images/../../../images/recursosHTML/images/baked-salmon-garnished-with-asparagus-and-tomatoes-with-herbs.jpg" width="60%"/>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Id voluptates dolores autem quos nulla illum pariatur magnam.
    </p>
</div>
<hr/>
<div>
    <buttom style="float:left; padding: 2%">
        Lorem Ipsum
    </buttom>
    <buttom style="float:right; padding: 2%">
        Lorem Ipsum
    </buttom>
</div>
<hr/>
<div style="clear: both">
    <buttom style="float:left; padding: 2%">
        Lorem Ipsum
    </buttom>
    <buttom style="float:left; padding: 2%">
        Lorem Ipsum
    </buttom>
</div>

<div style="clear: both">
    <buttom style="float:left; padding: 2%">
        Lorem Ipsum
    </buttom>
    <buttom style="float:left; padding: 2%">
        Lorem Ipsum
    </buttom>
</div>

terminar...
continuar na aula 40


