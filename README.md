# Imersão Java

Iniciativa Alura em prol do desenvolvimento de competências para o mercado de TI a partir do desenvolvimento de uma aplicação Java que consuma dados de APIs como a do IMDB. O conteúdo foi apresentado em 5 aulas, vide links abaixo. Os Códigos fontes encontram-se neste repositório. Nosso objetivo é manter o conhecimento transmitido acessível a todos.

https://www.alura.com.br/imersao-java

#Aula 1
https://www.youtube.com/watch?v=e7FJaSXwvdk

Objetivo: construir uma aplica��o do zero para consumir a API do IMDb e exibir os filmes mais populares, destacando seus p�steres e visualizando sua classifica��o... Tudo isso sem usar nenhuma biblioteca externa!

Como a API do IMDB usada durante esta aula saiu do ar, a comunidade criou endere�os alternativos de acesso aos dados, entre eles:

(https://mocki.io/v1/9a7c1ca9-29b4-4eb3-8306-1adb9d159060) criada pelo @rezendecas
(https://alura-imdb-api.herokuapp.com/movies) criada pelo Jhon Santana
(https://api.mocki.io/v2/549a5d8b) criada pelo instrutor Alexandre Aquiles
(https://alura-filmes.herokuapp.com/conteudos) criada pela instrutora Jacqueline Oliveira
(https://raw.githubusercontent.com/alexfelipe/imersao-java/json/top250.json) criada pelo instrutor Alex Felipe

Código Fonte oficial: https://github.com/alura-cursos/imersao-java/tree/aula1

#Links citados
https://www.imdb.com/chart/top/
https://imdb-api.com/api
https://code.visualstudio.com/docs/languages/java#_install-visual-studio-code-for-java
https://docs.oracle.com/en/java/javase/17/docs/api/java.net.http/java/net/http/HttpRequest.html
https://gist.github.com/alexandreaquiles/cf337d3bcb59dd790ed2b08a0a4db7a3
https://github.com/FasterXML/jackson
https://regex101.com/
https://www.alura.com.br/artigos/escrever-bom-readme
https://imdb-api.com/en/API/Top250Movies/
https://www.alura.com.br/artigos/o-que-e-json
https://www.alura.com.br/artigos/decorando-terminal-cores-emojis
https://www.alura.com.br/artigos/desenvolvendo-aplicacoes-java-vs-code

#Desafios
Consumir o endpoint de filmes mais populares da API do IMDB. Procure também, na documentação da API do IMDB, o endpoint que retorna as melhores séries e o que retorna as séries mais populares.
Usar sua criatividade para deixar a saída dos dados mais bonitinha: usar emojis com código UTF-8, mostrar a nota do filme como estrelinhas, decorar o terminal com cores, negrito e itálico usando códigos ANSI, e mais!
Colocar a chave da API do IMDB em algum lugar fora do código como um arquivo de configuração (p. ex, um arquivo .properties) ou uma variável de ambiente
Mudar o JsonParser para usar uma biblioteca de parsing de JSON como Jackson ou GSON
Desafio supremo: criar alguma maneira para você dar uma avaliação ao filme, puxando de algum arquivo de configuração OU pedindo a avaliação para o usuário digitar no terminal.

#Aula 2
https://www.youtube.com/watch?v=pZy3sijHMU8

Objetivo: criar um gerador de figurinhas explorando outras bibliotecas nativas do Java, para que possamos enviar por Whatsapp os nossos filmes preferidos!

Código Fonte oficial: https://github.com/alura-cursos/imersao-java/tree/aula2

#Links citados
https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/io/InputStream.html
https://www.alura.com.br/apostila-java-orientacao-objetos/apendice-pacote-java-io

https://api.mocki.io/v2/549a5d8b/Top250Movies
https://api.mocki.io/v2/549a5d8b/MostPopularMovies
https://api.mocki.io/v2/549a5d8b/MostPopularTVs
https://api.mocki.io/v2/549a5d8b/Top250TVs

https://docs.oracle.com/en/java/javase/17/docs/api/java.desktop/javax/imageio/package-summary.html
https://docs.oracle.com/en/java/javase/17/docs/api/java.desktop/java/awt/image/BufferedImage.html
https://docs.oracle.com/en/java/javase/17/docs/api/java.desktop/java/awt/Graphics2D.html
https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/io/InputStream.html

#Desafios
Ler a documentação da classe abstrata InputStream.
Centralizar o texto na figurinha.
Fazer um pacote no Whatsapp e/ou Telegram com as suas próprias figurinhas!
Criar diretório de saída das imagens, se ainda não existir.
Colocar outra fonte como a Comic Sans ou a Impact, a fonte usada em memes.
Colocar uma imagem de você que está fazendo esse curso sorrindo, fazendo joinha!
Colocar contorno (outline) no texto da imagem.
Tratar as imagens retornadas pela API do IMDB para pegar uma imagem maior ao invés dos thumbnails. Opções: pegar a URL da imagem e remover o trecho mostrado durante a aula ou consumir o endpoint de posters da API do IMDB (mais trabalhoso), tratando o JSON retornado.
Fazer com que o texto da figurinha seja personalizado de acordo com as classificações do IMDB.
Desafio supremo: usar alguma biblioteca de manipulação de imagens como OpenCV pra extrair imagem principal e contorná-la.

#Aula 3
https://www.youtube.com/watch?v=mOZVkNEznCE

Objetivo: pegarmos os filmes do IMDB e gerar figurinhas com os pêsteres, aproveitando para refatorar o que for possível.

Código Fonte oficial: https://github.com/alura-cursos/imersao-java/tree/aula3

#Links citados
https://www.alura.com.br/artigos/como-nao-aprender-orientacao-a-objetos-heranca
https://www.alura.com.br/artigos/como-nao-aprender-orientacao-a-objetos-heranca
https://www.alura.com.br/podcast/design-patterns-hipsters-206-a345
https://www.alura.com.br/podcast/solid-codigo-bom-e-bonito-hipsters-ponto-tech-219-a649
https://api.nasa.gov/
https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY
https://www.alura.com.br/artigos/nao-aprender-oo-getters-e-setters
https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612
https://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672
https://api.mocki.io/v2/549a5d8b/NASA-APOD
https://raw.githubusercontent.com/alura-cursos/imersao-java/api/NASA-APOD.json
https://api.mocki.io/v2/549a5d8b/NASA-APOD-JamesWebbSpaceTelescope
https://raw.githubusercontent.com/alura-cursos/imersao-java/api/NASA-APOD-JamesWebbSpaceTelescope.json
https://github.com/public-apis/public-apis

#Desafios
Transformar a classe que representa os conteúdos em um Record, disponível a partir do Java 16
Criar as suas próprias exceções e usá-las na classe que implementa o cliente HTTP
Usar recursos do Java 8 e posterior, como Streams e Lambdas, para mapear uma lista em uma outra
Criar uma Enum que une, como configurações, a URL da API e o extrator utilizado
Desafio supremo: consumir outras APIs que contém imagens, como a da Marvel, que é bem diferente.

#Aula 4
https://www.youtube.com/watch?v=srVV_6gA_Xg

#Aula 5
