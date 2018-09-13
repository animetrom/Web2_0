![capa web](https://user-images.githubusercontent.com/6373438/45364322-3dc51d80-b5b0-11e8-8941-d65c3b551917.png)

![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg) [![GitHub issues](https://img.shields.io/github/issues/adrianoleitedasilva/CSharp.svg)](https://github.com/adrianoleitedasilva/CSharp/issues) [![GitHub forks](https://img.shields.io/github/forks/adrianoleitedasilva/CSharp.svg)](https://github.com/adrianoleitedasilva/CSharp/network)  [![GitHub stars](https://img.shields.io/github/stars/adrianoleitedasilva/CSharp.svg)](https://github.com/adrianoleitedasilva/CSharp/stargazers) [![GitHub license](https://img.shields.io/github/license/adrianoleitedasilva/CSharp.svg)](https://github.com/adrianoleitedasilva/CSharp/blob/master/LICENSE) [![Twitter](https://img.shields.io/twitter/url/https/github.com/adrianoleitedasilva/CSharp.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fadrianoleitedasilva%2FCSharp)

Aqui vão todas as informações/conteúdos sobre HTML, CSS, JavaScript, PHP e Bootstrap. 

# Introdução

#### O que é HTML?
HTML é uma das linguagens que utilizamos para desenvolver websites. O acrônimo HTML vem do inglês e significa Hypertext Markup Language ou em português Linguagem de Marcação de Hipertexto.

O HTML é a liguagem base da internet. Foi criada para ser de fácil entendimento por seres humanos e também por máquinas, como por exemplo o Google ou outros sistemas que percorrem a internet capturando informação.

#### O que é CSS?
O Cascading Style Sheets (CSS) é uma "folha de estilo" composta por “camadas” e utilizada para definir a apresentação (aparência) em páginas da internet que adotam para o seu desenvolvimento linguagens de marcação (como XML, HTML e XHTML). O CSS define como serão exibidos os elementos contidos no código de uma página da internet e sua maior vantagem é efetuar a separação entre o formato e o conteúdo de um documento.

#### O que é JavaScript?
A primeira coisa que você precisa saber: JavaScript não tem nada a ver com Java. Java é uma linguagem server-side, como PHP, Ruby, Python e tantas outras. A única coisa parecida entre eles é o nome. ;-)

Sabendo disso, quero que saiba que JavaScript é uma linguagem de programação client-side. Ela é utilizada para controlar o HTML e o CSS para manipular comportamentos na página. Me pergunte agora: "Como assim comportamento?". Agora eu respondo: um comportamento comum, por exemplo, é um submenu. Sabe quando você passa o mouse em um ítem do menu, e aparece um submenu com vários outros ítens? Pois é. A obrigação de fazer aparecer esse submenu é do JavaScript. O submenu estava escondido, e quando passamos o mouse no ítem, o submenu aparece. Todo esse comportamento quem vai executar é o JavaScript.

#### O que é PHP?
O PHP (um acrônimo recursivo para PHP: Hypertext Preprocessor) é uma linguagem de script open source de uso geral, muito utilizada, e especialmente adequada para o desenvolvimento web e que pode ser embutida dentro do HTML.

Em vez de muitos comandos para mostrar HTML (como acontece com C ou Perl), as páginas PHP contém HTML em código mesclado que faz "alguma coisa" (neste caso, mostra "Olá, eu sou um script PHP!"). O código PHP é delimitado pelas instruções de processamento (tags) de início e fim <?php e ?> que permitem que você entre e saia do "modo PHP".

#### O que é Bootstrap?
Se você é um desenvolvedor de páginas web, sabe o quão árduo era começar um site do zero toda vez que se pegava um novo projeto para fazer. Era (no passado)! Isto, porque está disponível, desde 2011, o Bootstrap. Trata-se de um framework front-end que veio para facilitar e agilizar o trabalho, oferecendo padrões para HTML, JavaScript e CSS.

# Primeiros passos com o HTML

#### Tags 
TAGS são rótulos usados para informar ao navegador como  deve ser apresentado o site. Ou seja, quando começo a escrever HTML  estou escrevendo tags que serão interpretadas pelo navegador, produzindo assim o visual do seu site.

#### A sintaxe das Tags
Todas as TAGS possuem o mesmo formato, ou seja, possuem um padrão de codificação que deve ser seguido pelos desenvolvedores web. As TAGS começam com um sinal de “<” e terminam com um sinal de “>”. A principal diferença entre elas é que a <strong>tag de fechamento precisa de uma barra para finalizar a marcação.</strong>
```
<body> -> Tag de abertura, inicia a marcação do código

</body> -> Tag de fechamento, finaliza com uma barra a marcação do código
```

#### Estrutura Básica de uma página
```html
<html>

<head>
	<title>Minha primeira página</title>
</head>
<body>

<h1>Minha primeira página</h1>
<p>Aqui vai um texto qualquer...</p>

</body>
</html>
```

#### Adicionando a chamada do arquivo CSS
```html
<head>
	<title>Minha primeira página</title>

	<link href="estilo.css" type="text/css" rel="stylesheet" />
</head>
```

#### Explicando a estrutura básica
```html
<html> <!-- INDICA QUE O ARQUIVO É HTML -->

<head> <!-- INDICA O INÍCIO DO CABEÇALHO DO DOCUMENTO -->
	<title>Minha primeira página</title> <!-- AQUI VAI O TÍTULO DA PÁGINA -->
</head> <!-- INDICA O FIM DO CABEÇALHO DO DOCUMENTO -->
<body> <!-- INDICA O INÍCIO DO CONTEÚDO DO SITE -->

<h1>Minha primeira página</h1>
<p>Aqui vai um texto qualquer...</p>

</body> <!-- INDICA FIM DO CONTEÚDO DO SITE -->
</html> <!-- INDICA O FIM DO DOCUMENTO -->
```

# Primeiros passos com o CSS
O CSS é um complemento para o HTMl, com ele conseguimos dar um visual único para o nosso site.
```css
* {
	background: #313131;
	font-family: 'Raleway', sans-serif;
	text-decoration: none;
	text: #FFF;
	margin: 0 auto;
}

```

# Primeiros passos com o JavaScript



# Primeiros passos com o Bootstrap


#### Estrutura básica das pastas do Bootstrap
```
bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap.min.css.map
│   ├── bootstrap-theme.css
│   ├── bootstrap-theme.css.map
│   ├── bootstrap-theme.min.css
│   └── bootstrap-theme.min.css.map
├── js/
│   ├── bootstrap.js
│   └── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2
``` 
### Informações importantes
##### <strong>NOTA</strong> - Eu costumo trabalhar com o CSS <strong>minificado</strong> do CSS, no caso, bootstrap.min.css
##### <strong>NOTA 02</strong> - Eu utilizo uma estrutura de pasta um pouco diferente, dentro da pasta do meu projeto eu crio uma pasta chamada assets e dentro dela jogo todos os arquivos do Bootstrap, como você pode ver abaixo:

```
assets/
├── css/
│	└── bootstrap.min.css
├── js/
│	├── bootstrap.js
│	└── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2
```

# Primeiros passos com o PHP

#### O que vamos precisar para trabalhar com o PHP

* Xampp/Mampp/Wampp
* Sublime Text ou Bloco de Notas



