## Estrutura básica do HTML

- Criado por Tim berners-Lee em 1991 o HTML 1, desde então surgiram 5 versões e o HTML se tornou base da web.

A primeira linha do documento deve ser o <!DOCTYPE html>, apesar de parecer um elemento HTML ela apenas diz ao navegador que ele está lidando com um arquivo do tipo HTML5. Os elementos HTML vem logo abaixo.

**<html>**

A tag html é a raiz do seu documento, todos os elementos HTML devem estar dentro dela. E nela nós informamos ao navegador qual é o idioma desse nosso documento, através do atributo lang, para o português brasileiro usamos pt-BR.

**<head>**

A tag head contém elementos que serão lidos pelo navegador, como os metadados - um exemplo é o charset, que é a codificação de caracteres e a mais comum é a UTF-8, o JavaScript com a tag script, o CSS através das tags style e link - veremos a diferença quando falarmos sobre CSS - e o título da página com a tag title.

**<body>**

E dentro da tag body colocamos todo o conteúdo visível ao usuário: textos, imagens, vídeos.



<h1 class="título">Título</h1>   



- Estrutura básica 

  `<!DOCTYPE html>  não é um elemento html, apenas diz ao navegador o que ta escrevendo.
      <html>   >> abrimos a tag do html.
  
          <head> >>
           inicia o head, e dentro do head temos algumas meta informações que um navegador/buscador necessita.
              <meta>
              <title></title> >> coloca o título da aba no navegador
          </head>
  
  ​        <body>
  ​            onde vai estar o conteúdo da nossa página.
  ​        </body>
  </html>
  
  
  

