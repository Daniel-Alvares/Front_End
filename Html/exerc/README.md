# Resumo das Tags <html>

## Histórico HTML

### Desde os primeiros dias da World Wide Web, existem muitas versões do HTML:

Ano       |  Versão
--------|------------------------------
Year 	| Version
1989 	| Tim Berners-Lee invented www
1991 	| Tim Berners-Lee invented HTML
1993 	| Dave Raggett drafted HTML+
1995 	| HTML Working Group defined HTML 2.0
1997 	| W3C Recommendation: HTML 3.2
1999 	| W3C Recommendation: HTML 4.01
2000 	| W3C Recommendation: XHTML 1.0
2008 	| WHATWG HTML5 First Public Draft
2012 	| WHATWG HTML5 Living Standard
2014 	| W3C Recommendation: HTML5
2016 	| W3C Candidate Recommendation: HTML 5.1
2017 	| W3C Recommendation: HTML5.1 2nd Edition
2017 	| W3C Recommendation: HTML5.2


## Estrutura

![Estrutura](Estrutura.png)



Tags   | Funcionalidade
--------- | -----------------------
!DOCTYPE | declaração define que este documento é um documento HTML5
html | elemento é o elemento raiz de uma página HTML
head | elemento contém meta informações sobre a página HTML
title | elemento especifica um título para a página HTML (que é mostrada na barra de título do navegador ou na guia da página)
body | elemento define o corpo do documento e é um contêiner para todo o conteúdo visível, como títulos, parágrafos, imagens, hiperlinks, tabelas, listas, etc.
h1 - h6	| elemento define um cabeçalho com diversos tamanhos começando pelo maior h1
p	| elemento define um parágrafo
< kbd> | Define entrada de texto como comando de teclado.



## Tags de comentário HTML

Você pode adicionar comentários à sua fonte HTML usando a seguinte sintaxe: < br >
<-!-- Write your comments here --> 


## Tags de Link e seus Atributos

Links HTML - O atributo de destino

Tags   | Funcionalidade
--------- | ---------
a | Os links HTML são definidos com a tag < a>.

Por padrão, a página vinculada será exibida na janela atual do navegador. Para alterar isso, você deve especificar outro destino para o link.

O target atributo especifica onde abrir o documento vinculado.

**O target atributo pode ter um dos seguintes valores:**

    _self- Padrão. Abre o documento na mesma janela / guia em que foi clicado
    _blank - Abre o documento em uma nova janela ou guia
    _parent - Abre o documento no quadro pai
    _top - Abre o documento no corpo inteiro da janela


## Atributos
blockquote cite="https://www.w3schools.com/html/html_attributes.asp"
	  p Todos os elementos HTML podem ter atributos
    O href atributo de **a** especifica o URL da página para a qual o link vai
    O src atributo de **img** especifica o caminho para a imagem a ser exibida
    Os widthe height atributos de imgfornecer informações de tamanho para imagens
    O alt atributo de **img** fornece um texto alternativo para uma imagem
    O style atributo é usado para adicionar estilos a um elemento, como cor, fonte, tamanho e mais
    O lang atributo da **htm** tag declara o idioma da página da Web
    O titlea tributo define algumas informações extras sobre um elemento.
</blockquote>
    
## Exibição em HTML

Tags   | Funcionalidade
-------- | ---------------
 p | This is a paragraph. p
 **p** |This is another paragraph.< /p > 
< hr > | tag define uma quebra temática em uma página HTML e é mais frequentemente exibida como uma regra horizontal.
< br > | elemento HTML define uma quebra de linha.
< pre > | elemento HTML define o texto pré-formatado.


## Elementos de formatação HTML

### Os elementos de formatação foram projetados para exibir tipos especiais de texto:

   * < b > - Texto em negrito
   * < strong > - texto importante
   * < i > - texto em itálico
   * < em > - Texto enfatizado
   * < mark > - Texto marcado
   * < small > - Texto menor
   * < del > - Texto excluído
   * < ins > - texto inserido
   * < sub > - Texto subscrito
   * < sup > - Texto sobrescrito

## Elementos de cotação e citação HTML

Tag 	| Funcionalidade
------ |-------------------
< abbr > 	|tag HTML define uma abreviação ou acrônimo, como "HTML", "CSS", "Mr.", "Dr.".
< address > | tag HTML define as informações de contato do autor.
< bdo > 	| tag HTML é usada para substituir a direção do texto atual:
< blockquote > |	elemento HTML define uma seção que é citada de outra fonte.
< cite > 	| tag HTML define o título de um trabalho criativo.
< q > 	| tag HTML define uma citação curta.

## Sintaxe de imagens HTML

* A < img > tag HTML é usada para incorporar uma imagem em uma página da web.

* A < img > tag possui dois atributos obrigatórios:

  -  src - especifica o caminho para a imagem
  -  alt - Especifica um texto alternativo para a imagem

___________________________________________________________________________

 ## Tags de imagem HTML

Tag 	| Description
--------| ------------------
< img > 	|Defines an image
< map > 	|Defines an image map
< area >  	|Defines a clickable area inside an image map
< picture > 	|Defines a container for multiple image resources

**Exemplo**

< img src="imagem.jpg" alt="Descrição da imagem" > 

**Formatos comuns de imagem**
______________________________________________________________________________

Aqui estão os tipos de arquivos de imagem mais comuns, suportados em todos os navegadores (Chrome, Edge, Firefox, Safari, Opera):

Abbreviation 	|File Format 	|File Extension
---------------|--------------|---------------------
APNG 	| Animated Portable Network Graphics 	|.apng
GIF 	| Graphics Interchange Format 	| .gif
ICO 	| Microsoft Icon 	| .ico, .cur
JPEG 	| Joint Photographic Expert Group image 	| .jpg, .jpeg, .jfif, .pjpeg, .pjp
PNG 	| Portable Network Graphics 	|.png
SVG 	| Scalable Vector Graphics 	| .svg

## Elemento <picture> HTML

O < picture >elemento HTML oferece aos desenvolvedores da Web mais flexibilidade na especificação de recursos de imagem.

O < picture >elemento contém um ou mais < source >elementos, cada um referente a imagens diferentes por meio do srcset atributo Dessa forma, o navegador pode escolher a imagem que melhor se ajusta à exibição e / ou dispositivo atual.

Cada < source > elemento possui um mediaatributo que define quando a imagem é a mais adequada.

**Exemplo**

Mostre imagens diferentes para diferentes tamanhos de tela:

  < picture >
    < source media="(min-width: 650px)" srcset="img_food.jpg" >
    < source media="(min-width: 465px)" srcset="img_car.jpg" >
    < img src="img_girl.jpg" >
  < /picture > 

## Tabelas HTML

As tabelas HTML permitem que os desenvolvedores da Web organizem dados em linhas e colunas.

**Definir uma tabela HTML**

A < table >tag define uma tabela HTML.

Cada linha da tabela é definida com uma < tr >tag. Cada cabeçalho da tabela é definido com uma < th >tag. Cada dados / célula da tabela é definido com uma < td >tag.

Por padrão, o texto nos < th > elementos está em negrito e centralizado.

Por padrão, o texto nos < td > elementos é regular e alinhado à esquerda.

***Exemplo***

< table style="width:100%" >
  < tr >
    < th >Name< /th >
    < th colspan="2">Telephone< /th >
  < /tr >
  < tr >
    < td > Bill Gates < /td >
    < td > 55577854 < /td >
    < td > 55577855 < /td >
  < /tr >
< /table > 

## Listas HTML

As listas HTML permitem que os desenvolvedores da Web agrupem um conjunto de itens relacionados nas listas.

### Tags da lista HTML
Tag   | Description
------| ---------------
< ul > |Defines an unordered list
< ol > |Defines an ordered list
< li > |Defines a list item
< dl > |Defines a description list
< dt > |Defines a term in a description list
< dd > | Describes the term in a description list.

##Bloco HTML e elementos embutidos

Todo elemento HTML possui um valor de exibição padrão, dependendo do tipo de elemento que é.

Existem dois valores de exibição: bloco e embutido.

**Aqui estão os elementos no nível do bloco em HTML:**

Elementos em nível de bloco

Um elemento no nível do bloco sempre inicia em uma nova linha e ocupa toda a largura disponível (se estende para a esquerda e direita, tanto quanto possível).

* < endereço >
* < artigo >
* < aparte >
* < blockquote >
* < tela >
* < dd >
* < div >
* < dl >
* < dt >
* < fieldset >
* < figcaption >
* < figura >
* < rodapé >
* < formulário >
* < h1 > - < h6 >
* < cabeçalho >
* < hr >
* < li >
* < principal >
* < nav >
* < noscript >
* < ol >
* < p >
* < pre >
* < seção >
* < tabela >
* < tfoot >
* < ul >
* < video >


**Aqui estão os elementos embutidos no HTML:**

Elementos Inline

Um elemento embutido não inicia em uma nova linha e ocupa apenas a largura necessária.

* < Uma >
* < abbr >
* < acrônimo >
* < b >
* < bdo >
* < grande >
* < Br >
* < botão >
* < citar >
* < código >
* < dfn >
* < em >
* < i >
* < img >
* < entrada >
* < kbd >
* < label >
* < mapa >
* < objeto >
* < saída >
* < q >
* < samp >
* < script >
* < selecione >
* < pequeno >
* < span >
* < forte >
* < sub >
* < sup >
* < área de texto >
* < hora >
* < tt >
* < var >

##JavaScript em HTML

A tag HTML < script >

A < script >tag é usada para definir um script do lado do cliente (JavaScript).

O < script >elemento contém instruções de script ou aponta para um arquivo de script externo por meio do srcatributo

Os usos comuns para JavaScript são manipulação de imagem, validação de formulário e alterações dinâmicas de conteúdo.

###Tags de script HTML

Tag  |  Description
------|-------------
< script > | Defines a client-side script
< noscript > | Defines an alternate content for users that do not support client-side scripts

## O elemento HTML <meta>

O < meta >elemento é usado para especificar qual conjunto de caracteres é usado, descrição da página, palavras-chave, autor e outros metadados.

Os metadados são usados ​​pelos navegadores (como exibir conteúdo), pelos mecanismos de pesquisa (palavras-chave) e outros serviços da web.

- **Defina o conjunto de caracteres usado:**

* < meta charset="UTF-8">
* < meta name="description" content="Free Web tutorials">
* < meta name="keywords" content="HTML, CSS, XML, JavaScript">
* < meta name="author" content="John Doe">
* < meta http-equiv="refresh" content="30">
* < meta name="viewport" content="width=device-width, initial-scale=1.0">

##Elementos semânticos em HTML

**Por que elementos semânticos?**

De acordo com o W3C: "Uma Web semântica permite que os dados sejam compartilhados e reutilizados em aplicativos, empresas e comunidades".

Abaixo está uma lista alfabética de alguns dos elementos semânticos em HTML.

Os links vão para a nossa Referência HTML completa.

Tag  | Description
------|-----------------
< article>  | Defines an article
< aside>   |Defines content aside from the page content
< details>  | Defines additional details that the user can view or hide
< figcaption> | Defines a caption for a <figure> element
< figure>  | Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
< footer>  | Defines a footer for a document or section
< header>  | Specifies a header for a document or section
< main>  | Specifies the main content of a document
< mark>  | Defines marked/highlighted text
< nav>   | Defines navigation links
< section>  | Defines a section in a document
< summary>  | Defines a visible heading for a <details> element
< time> | Defines a date/time