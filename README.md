# CSS
### Conceito;
CSS é chamado de linguagem Cascading Style Sheet e é usado para estilizar elementos escritos em uma linguagem de marcação como HTML. O CSS separa o conteúdo da representação visual do site. Pense  na decoração da sua página. Utilizando o CSS é possível alterar a cor do texto e do fundo, fonte e espaçamento entre parágrafos. Também pode criar tabelas, usar variações de layouts, ajustar imagens para suas respectivas telas e assim por diante.
### Aplicações ;
O CSS é uma ferramenta muito potente que possibilita criar diversas funcionalidades ao invés de usar JavaScript ou outra linguagem mais pesada. Se usado com moderação, CSS pode viabilizar uma ótima experiência ao desenvolvedor e usuários das páginas web.
## Seletores CSS
Seletor por tag
Este seletor básico escolhe todos os elementos que correspondem ao nome fornecido.
Sintaxe: nome-da-tag
Exemplo: input corresponderá a qualquer elemento <input>.
Seletor por classe
Este seletor básico escolhe elementos baseados no valor de seu atributo classe. Sintaxe: .nome-da-classe
Examplo: .index irá corresponder a qualquer elemento que tenha o índice de classe (provavelmente definido por um atributo class="index", ou similar).
Seletor por ID
Este seletor básico escolhe nós baseados no valor do atributo id. Deve existir apenas um elemento com o mesmo ID no mesmo documento.
Sintaxe: #nome-do-id
Exemplo: #toc irá corresponder ao elemento que possuir o id=toc (definido por um atributo id="toc", ou similar).
Seletores universais
Este seletor básico irá escolher todos os nós. Ele também existe em um namespace único e em uma variante de todo o namespace também.
Sintaxe: * ns|* *|*
Exemplo: * irá corresponder a todos os elementos do documento.
Seletores por atributo
Este seletor básico ira escolher nós baseados no valor de um de seus atributos, ou até mesmo pelo próprio atributo.
Sintaxe: [atrib] [atrib=valor] [atrib~=valor] [atrib|=valor] [atrib^=valor] [atrib$=valor] [atrib*=valor]
Exemplo: [autoplay] irá corresponder a todos os elementos que possuirem o atributo autoplay (para qualquer valor).
