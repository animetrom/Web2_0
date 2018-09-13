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
##### <strong>NOTA</strong> - Eu costumo trabalhar com a versão <strong>minificada</strong> do CSS, no caso, bootstrap.min.css
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












# Ferramentas para Baixar

#### IDEs
* [Sublime Text 3](https://www.sublimetext.com/ "Clique aqui para baixar o Sublime")
* [Visual Studio](https://blog.da2k.com.br "Clique aqui para baixar o Visual Studio Code!")

#### Complementos 
* [NodeJS](https://nodejs.org/ "Clique aqui para acessar o NodeJS")
* [Package Control(Plugins para o Sublime)](https://nodejs.org/ "Clique aqui para acessar o NodeJS")

#### Links Úteis
* [Google Fonts](https://fonts.google.com/ "Clique aqui para acessar o Google Fonts")

## EXTRA

#### Packages para Sublime
* [Emmet](https://packagecontrol.io/packages/Emmet "Clique para acessar") - Package que auxilia no 
* [AdvancedNewFile](https://packagecontrol.io/packages/AdvancedNewFile "Clique para acessar") - Como pode ser entendido pelo nome, AdvancedNewFile possibilita a criação de novos arquivos e pastas no Sublime Text. Sem necessidade de Windows ou Mac Navigator, você pode criar arquivos ou pastas em qualquer nível da pasta do seu projeto. Além de sua opção de caminho absoluto e relativo, você também pode definir a extensão padrão para arquivos recém-criados.
* [AutoFileName](https://packagecontrol.io/packages/AutoFileName "Clique para acessar") - AutoFileName é um dos principais pacotes que eu uso principalmente. Completa os nomes dos arquivos automaticamente. Geralmente, ele preenche automaticamente os nomes dos arquivos quando o cursor está entre aspas, mas alterei a configuração para que o preenchimento automático seja acionado apenas com uma combinação de teclas para evitar nomes de arquivos e variáveis ​​misturados na lista pop-up de preenchimento automático.
* [Bracket​Highlighter](https://packagecontrol.io/packages/BracketHighlighter "Clique para acessar") - É um dos meus pacotes favoritos do Sublime Text. Ele simplesmente destaca seus suportes. Quando o cursor está entre aspas, chaves, parênteses, marca o início e o fim desta parte. Ao escrever uma série matemática complicada ou funções aninhadas, este pacote ajuda você a ver em qual bloco o cursor está. Também abrange funções avançadas de seleção.
* [SideBarEnhancements](https://packagecontrol.io/packages/SideBarEnhancements "Clique para acessar") - Os comandos da Barra Lateral do Sublime Text são bastante limitados e apenas lidam com ações simples. O pacote SideBarEnhancements é um dos pacotes que devem ser instalados no Sublime Text. Ele ganha um grande número de aprimoramentos no menu de contexto da Barra Lateral. Você pode definir o comando "abrir com" para extensões específicas, como abrir arquivos de imagem com o Photoshop ou abrir seus arquivos html com diferentes navegadores e atribuir uma tecla de acesso específica a esses comandos. Suporta copiar, cortar ou mover entre arquivos e pastas sem tocar no explorador de arquivos. Também torna possível copiar o caminho do arquivo, copiar o nome do arquivo, pesquisar em uma pasta específica ou mostrar o arquivo selecionado no Windows Explorer.
* [SublimeCodeIntel](https://packagecontrol.io/packages/SublimeCodeIntel "Clique para acessar") - O pacote SublimeCodeIntel transforma seu editor de texto em IDE com todos os recursos. Você definitivamente o instalou para completar código ampliado e avançado no Sublime Text. Com uma nova versão do SublimeCodeIntel, você notará que a lógica de conclusão de código alcançou um nível mais alto de comparação com a versão anterior.
Este pacote possibilita o autocompletar cada definição de palavra no seu projeto. Ele suporta JavaScript, SCSS, Python, HTML, Ruby, Python3, XML, Sass, HTML5, Perl, CSS, Twig, Less, Node.js, TemplateToolkit e PHP pré-definidos no arquivo de configuração.
* [Alignment]() - O plugin de alinhamento ajuda a alinhar facilmente várias seleções ou seleções de várias linhas. O que isso significa é que você pode alinhar várias seleções ou linhas por meio de um delimitador como =. Basta digitar ctrl + alt + a no Windows ou cmd + ctrl + a em um Mac para alinhar sua seleção. Para alinhar: siga este tutorial para configurar os delimitadores personalizados.
* [Color Highlighter](https://packagecontrol.io/packages/Color%20Highlighter "Clique para acessar") - Ele sublinha códigos de cores hexadecimais (como #FFFFFF, rgb (255,255,255), vermelho, etc.) com sua cor real. Quando você clica naquele código, ele é preenchido com cor.
* [GitGutter](https://packagecontrol.io/packages/GitGutter "Clique para acessar") - Este plugin fornece ao seu editor um status de git ao vivo em seu projeto. Pode mostrar três estados: 1. Alterando / editando linhas com um quadrado, 2. Adicionando linhas com uma cruz verde, 3. Removendo linhas com uma seta vermelha
* [A File Icon](https://packagecontrol.io/packages/A%20File%20Icon "Clique para acessar") - 
* [LiveReload](https://packagecontrol.io/packages/LiveReload "Clique para acessar") - Reload automático das páginas
* [MaybsQuit](https://packagecontrol.io/packages/Maybs%20Quit "Clique para acessar") - O Maybs Quit permite um painel rápido para confirmar a saída do Sublime Text. Ambos cmd / ctrl + w e cmd / ctrl + q estão muito próximos um do outro no teclado e podem levar a erros. Evite deixar o texto subliminar sem querer quando estiver apenas a tentar fechar um ficheiro, utilizando o Maybs Quit!


##### Packages para o Visual Studio Code



