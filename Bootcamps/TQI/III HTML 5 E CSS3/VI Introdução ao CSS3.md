# Introdução ao CSS3

## O que iremos aprender?

- O que são  seletores.
- Conceitos básicos
- Principais seletores CSS

### Requisitos

- Editor de texto
- Navegador
- Assistir as aulas de html 5.

#### História

- Após a criação do html, a necessidade de formatar página foi evidente, para isso foi criada a linguagem de estilo conhecida como CSS, em que a sintaxe é bem simples, e pode ser resumida em uma frase:
**Você cria regras de estilo para elementos ou grupo de elementos, podemos usar a âncora para exemplificar**

#### O que são seletores?

- Uma regra css é formada por um seletor ou grupo de seletores que nada mais são que elementos do html (a,p,h1,h3)
- Junto com o seletor dentro das chaves {}, há a declaração, que é formada por uma propriedade "**color**" e um valor "**blue**".
- Podemos usar também a propriedade "**font-size** e valor "**14px**"

#### ID x Classe

- Geralmente temos sites mais complexos que demandam várias regras para elementos do mesmo tipo. Para título de exemplo, nosso index do curso de html tinha vários headers, mas não queremos que o principal, tenha a mesma cor e tamanho do header da postagem.
- Ids e classes podem representar qualquer tipo de elemento, no html declaramos o id com a palavra "**id**" e a classe coma palavrea "**class**"
- Css o ID é precedido de ponto ".**header**" e a classe de hash "#**header**#
- Outra característica é que um ID só pode ser usado uma vez na página.

#### Prática -

- Na aula prática utilizamos abaixo do title no `<head>` o código `<link rel="stylesheet" href="syle.css">`que é utilizado para dizer ao navegador qual tipo de arquivo estamos adicionando com o **rel** e também par linkar o style.css com o html com o **href**.

```

#title {
    color: blue;
}

#title {
    font-size: 35px;
    font-style: italic
}

.subtitle {
    color: rgb(187, 48, 48)
}

.subtitle {
    font-size: 25px;
    font-style: oblique
}

.post_title {
    color: black
}


`.post_title {
    font-size: 16px;
    font-style: italic;
}



## Conceitos básicos

- Quando estamos fazendo um layout de um site o navegador representa cada elemento html como uma caixa retangular que chamamos de box model.
- Com o css conseguimos alterar a aparência dessa caixa.
- temos a Margem(margin)bordas(border)padding e conteúdo(content)
- **Margem** são espaçamentos entre elementos
- **Bordas** circundam o padding e conteúdo e consegue alterar a aparência delas como largura e cor.
- **Padding** espaçamento entre a borda e o conteúdo
- **Conteúdo** é o que o bloco representa, um texto imagem ou vídeo.

#### Prática

- [ ] Para enxergamos o box-model vamos adicionar cores a alguns elementos.
- Adicionamos `article class="post_2"` no `<article>` para criar a classe e estilizamos com 
`.post_2 {    background: white;    padding: 10px;    border: 3px solid #000;    margin: 30px;}`

- O mesmo fizemos com o `<header>` e criamos a classe `header class="post1"`
e estilzamos com

`.post_1 {    background: rgb(255, 255, 255);    padding: 15px;    border: #000 2px solid;    margin: 10px;}`

- Demos também cor ao `<body>` com o 

`body { background: #ccc;}`
