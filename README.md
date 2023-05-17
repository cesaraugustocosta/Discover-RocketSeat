# Discover-RocketSeat

## Guia Estelar HTML

### HEAD
<head></head> é a parte não visível pelo navegador, onde se faz configurações, contém informações como o título, links para o css, para o favicon.

### HEAD

Descrição
Falaremos agora sobre a tag <meta> , ela serve para definir metadados, como codificação de caracteres especiais e portabilidade para dispositivos mobiles.
Meta normalmente virá com o atributo name para especificar a meta, content para conteúdo, mas há também como o atributo charset, para caracteres especiais.

### Favicon
Favicon é uma abreviação para "favorite icon", refere-se aos ícones dos favoritos a alguns anos atrás, mas nos dias de hoje acabou ficando este termo, antigamente ele era por 16 pixeis, porém com o avanço da tecnologia isso mudou.

Para colocarmos o ícone usaremos a tag <link> com o atributo rel="icon", que seria para representar relação, no caso a tag link vai conter um ícone, depois o href para mostrar onde está o ícone.

### Meta SEO
Veremos agora das metas que são importantes para SEO(Search Engine Optimization ou motores de busca, como o google).
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
Esses já vimos anteriormente.

<meta name="author" content="Mayk Brito">
Temos também o de autor, para definir o autor da página, para possuirmos propriedade sobre a página.

<meta name="description" content="Um website para iniciantes em programação">
Este meta é usado para descrição de sites, caso você não tenha esse meta, o navegador irá procurar qualquer texto seu, mas muito melhor escolher o que você quer que apareça.

<meta name="robots" content="index, follow">
Esse meta diz para o robô do google o que queremos que ele faça, ele é responsável por colocar os resultados da busca , por exemplo. É possível dizer ao robô seguir links na página, através do follow, ou o contrário com o nofollow , ou "indexar" a página, através do index, ou no index.

### Meta Social
Descrição
Existem metadados personalizados por empresas de redes sociais, como Facebook, que criou o Open Graph, que é um tipo de metadado se quisermos colocar um tipo de conteúdo especial, caso queiramos compartilhar o link da nossa página no Facebook.

 <head>
    <!-- Open Graph: facebook -->
    <meta property="og:image" content="https://cdn-images-1.medium.com/max/92/1*TkXVfLTwsHdwpUEjGzdi9w@2x.jpeg">
    <meta property="og:description" content="Aqui vem um texto para ser mostrado ao compartilhar no facebook">
    <meta property="og:title" content="Um site da Rocketseat">

    <!-- twitter -->
    <meta name="twitter:title" content="Rocketseat">
</head>
São exemplos de metadados, que o Facebook procura na hora que compartilhamos a nossa página, como imagens, descrição, texto e outros.

O Twitter usa o atributo name diferente do Facebook que resolveu usar o property .
