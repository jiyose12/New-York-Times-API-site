# New-York-Times-API-site

# Descrição

Um projeto para a disciplina de Javascript que consiste em criar um site usando a API do New York Times [Site da API][nytapi]
 
# Objetivo

Desde 1851 o jornal americano New York Times vem guardando conteúdos de notícias e informações. Este projeto tem a finalidade de disponibilizar por meio de um site os diversos assuntos usando a NYT API. Assim, de forma rápida e facil, o usuário busca pela paralvra chave e os Artigos são dispostos na tela.

# Inspiração

Inspirado nos grandes jornais e principalmente no Jornalismo online. Que recorre a técnicas diferentes do jornalismo tradicional impresso.Logo, a velocidade das informações em tempo real para todos aqueles que gostam de estarem bem informados. Portanto, à internet é o melhor meio para transmissão dessas informações que irão satisfazer,seus bons leitores.

O website que não so traz informações revelantes mas também possui o design relembrando os antigos jornais é o do [The Washington Post][TheWashingtonPost]. A Inspiração do design do projeto provém deste site.

# Protótipos

As notícias recentes serão dispostas como mostrada na figura abaixo.

![print0][foto0]

Haverá um campo de pesquisa no topo da página e ao lado colocaremos um filtro de busca para caso o leitor queira especificar mais ainda as notícias apresentadas

![print1][foto1]

# Recursos da API  

Existem várias APIs que o New York Times oferece, por exemplo de Artigos, Livros, Comentários, Análises de Filmes etc. Neste projeto usaremos apenas de Artigos.

Os parâmetros de busca são as ferramentas essenciais da API. Com eles podemos pesquisar as informações por:

q= 

fq=

begin_date

end_date

sort

Há outros parâmetros, porém apenas serão usados no projeto os citados acima.

![print2][foto2]

Os elementos a serem captados pela API serão: o titulo da noticia, o snippet, o link da noticia, data da noticia e a imagem (caso haja)
Um exemplo do resultado seria:

![print3][foto3]

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [nytapi]: <https://developer.nytimes.com/>
   [foto0]: <Inspiracao01.jpg>
   [foto1]: <Prototipo01.png>
   [foto2]: <RecursoAPI01.jpg>
   [foto3]: <RecursoAPI02.jpg>
   [TheWashingtonPost]: <https://www.washingtonpost.com/>