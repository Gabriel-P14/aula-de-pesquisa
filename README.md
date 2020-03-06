#CSS

###Conceito;
CSS é chamado de linguagem Cascading Style Sheet e é usado para estilizar elementos escritos em uma linguagem de marcação como HTML. O CSS separa o conteúdo da representação visual do site. Pense na decoração da sua página. Utilizando o CSS, é possível alterar o texto e o fundo, a fonte e o espaçamento entre os gráficos. Também pode criar tabelas, usar configurações de layouts, ajustar imagens para suas telas e assim por diante.

###Aplicações;
O CSS é uma ferramenta muito potente que permite criar diversas funcionalidades ao usar JavaScript ou outra linguagem mais pesada. Se usado com moderação, o CSS pode viabilizar uma ótima experiência para o desenvolvedor e usuários das páginas da web.

###Seletores CSS
Todos os elementos HTML podem conter meta informações, que são os atributos. Você pode trabalhar com CSS, para realizar seleções baseadas nesses atributos, desde sua presença ou valores.
E[ATTR]

Podemos selecionar o elemento que possui um determinado atributo.
E[ATTR=”VALOR”]

Outra possibilidade é selecionar o atributo com um valor especifico.
E[ATTR$=”VALOR”]

###Colocando referências css em páginas;
Método 1: Arquivos externo css
Este é o método que apresenta maior versatilidade. Um arquivo externo CSS pode ser ligado a quantas páginas desejarmos, desta forma deixando a manutenção de um site muito mais fácil. Para este método, utilizamos o elemento link, da seguinte forma: <link href="css/arquivo.css" rel="stylesheet">

Método 2: Tag style
Com este método, aplicamos estilos apenas na página onde as regras CSS estão inseridas. Para isso, utiliza-se a tag style dentro da tag head. Exemplo:<style>
    p {
        color: red;
    }
</style>

No exemplo acima, os estilos definifos aplicarão a cor vermelha para todos os parágrafos do documento HTML em questão. Todos os elementos style devem ficar dentro do elemento head de uma página.
Método 3: Atributo style
Esse é o método que deve ser menos utilizado, por ir contra a divisão de um página em 3 camadas, como vimos anteriormente. Utilizando o atributo style, podemos aplicar estilos a um elemento específico. Exemplo:

<p style="color: red;">Texto</p>

No exemplo acima, aplicamos a cor vermelha apenas para o parágrafo em questão (existem maneiras melhores de se selecionar apenas um elemento ou grupo de elementos para aplicação de estilos). Esse método é chamado de “inline styles” (ou estilos em linha) por estarem localizados junto com o código HTML. Ele tem precedência de aplicação sobre todos os outros.

Porém, seu uso não é recomendado, pois mistura o código CSS com o HTML e dificulta a manutenção do site, além de ir contra ideia de separação da página em camadas. Portanto, o seu uso esporádico deve ser feito com cuidado e bom senso.

###Refêrencia CSS externo;
Provavelmente a maneira mais conveniente de adicionar CSS ao seu site, é vinculá-lo a um arquivo .css externo. Dessa forma, quaisquer alterações feitas em um arquivo CSS externo serão refletidas em seu site globalmente. Uma referência a um arquivo CSS externo é colocada na seção <head> da página:

<head>
<link rel="stylesheet" type="text/css" href="style.css" />
</head>
Enquanto o style.css contém todas as regras de estilo. Por exemplo:

.xleftcol {
float: left;
width: 33%;
background:#809900;
}
.xmiddlecol {
float: left;
width: 34%;
background:#eff2df;
}
Vantagens de CSS Externo:

Tamanho menor de páginas HTML e estrutura mais limpa.
Velocidade de carregamento mais rápida.
O mesmo arquivo .css pode ser usado em várias páginas.
Desvantagens de CSS Externo:

Até que o CSS externo seja carregado, a página pode não ser processada corretamente.
## Frameworks mais usados CSS;
###Bootstrap;
O Bootstrap é um framework desenvolvido pelo Twitter, que traz consigo características bem definidas de inicialização rápida, ou seja, possuem estilos predefinidos (prontos). Com a utilização do Bootstrap é possível a criação de sites responsivos, que são aqueles que se adaptam ao tamanho da tela que estará sendo utilizada pelo usuário.
###PureCss;
O Pure é um CSS (Cascading Style Sheet) desenvolvido pelo YAHOO. Ele vai te ajudar no processo de desenvolvimento de sites mais velozes, bonitos e responsivos.

Além de um tamanho muito pequeno, chegando a 4 KB, ele é muito experiente em termos de espaço.
O Pure possui um design responsivo incorporado, de forma que o site criado se redesenha de acordo com o tamanho do dispositivo. O Pure possui uma grade de fluido móvel de 12 colunas que suporta classes responsivas para telas pequenas, grandes e médias.

As classes puras são criadas de forma que o site possa caber em qualquer tamanho de tela, sendo totalmente compatíveis com PC, tablets e dispositivos móveis.
###Foundation;
O Pure possui um design responsivo incorporado, de forma que o site criado se redesenha de acordo com o tamanho do dispositivo. O Pure possui uma grade de fluido móvel de 12 colunas que suporta classes responsivas para telas pequenas, grandes e médias.

As classes puras são criadas de forma que o site possa caber em qualquer tamanho de tela, sendo totalmente compatíveis com PC, tablets e dispositivos móveis.
