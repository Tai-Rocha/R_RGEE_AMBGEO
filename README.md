# Ementa do curso Dados geoespaciais na linguagem R

### Resumo
O curso oferecerá os principais conceitos teóricos e práticos  para manipulação e visualização de dados geoespaciais usando linguagem R. Serão abordados os seguintes temas:

### Conteúdo
1. Introdução a linguagem R 
1.1 Porquê o R ? Breve hitórico, vantagens e desvantagens 
1.2 Instalação do R e  Rstudio IDE
1.2.1 Windows
1.2.2 Linux
1.2.3 Mac
1.3 Rstudio 
1.3.1 Entendo a interface 
1.3.2 Instalação dos pacotes R 
1.4  A importância de se trabalhar com a estrututa de “Projetos” 

2. Dados geoespaciais no R 
2.1 Dados vetoriais e dados matriciais. raster, sf/sp e rgdal : principais pacotes R do ecossistema geoespacial.  Importando e exportando dados os geoespaciais.
2.2 Operações básicas (joins, buffer, extração de valores, média, somas etc.)
2.3 Pacotes para vizualização de dados: tmap e ggplot
2.2 Pacotes R para download de dados geoespaciais

3. Rgee: um pacote R para acessar o GEE 
3.1 Pre requisitos e instalção
3.2 Entendendo a sintaxe o rgee* (mostrar o que se pode fazer, o que se tem disponível de operação para cada classe de objetos)
3.3 Operações básicas 

Estudos de casos usando o rgee (1h e 30 min)
4.1 Análise exploratória de dados ambientais
4.2 Estatísticas básicas para áreas de interesse 
4.3 [MapBiomas](https://mapbiomas.org/) no Rgee
4.5 Dados geoespaciais de ocorrência de espécies


5. Off topic, porém, não menos importante:  Onde e como buscar ajuda?
5.1 Google 
5.2 Github 
5.3 Stackoverflow

### Metodologia

Todas as aulas serão gravadas usando scripts R no Rstudio e alguns sites. 

Divisão deos vídeos:

00:00 - 33:56 (Video_1, Script_1_install.R)- Introdução a linguagem R , IDE Rstudio (interface) e instalações

00:00 - 10:17 (Video_2, Script_1_install.R) - Funcionalidade projetos do Rstudio

00:00 - 60:01 (Video_3, Scripts_2_vetores.R)- Dados geoespaciais na linguagem R: introdução a dados vetoriais, principais pacotes e tipos de objetos vetoriais

00:00 - 60:47 (Video_4, Scripts_2_vetores.R)- Dados geoespaciais na linguagem R: Operações com vetores

00:00 - 120:26 (video_5, Scripts_3_matriz.R)- Dados geoespaciais na linguagem R: introdução a dados matriciais, principais pacotes, tipos de objetos matriciais e operações com matrizes

00:00 - 37:00 (video_6, Script_4_rgee.R)- Introdução ao Google Earth Engine no R com pacote rgee, instalações, sintaxe do rgee e comandos básicos

00:00 - 120:18 (video_7, Scrip_5_Estudos_de_caso.R)- Estudos de casos: análises geoespaciais usando os pacotes e conceitos das aulas anteriores em exemplos mais complexos

00:00 - 07:00 (video_8)- Off topic: Onde e como pedir ajuda na comunidade R


### Referências 

[Geocomputation with R](https://geocompr.robinlovelace.net/)

[Análises Ecológicas no R](https://analises-ecologicas.netlify.app/index.html)

[Ciência de Dados em R](https://livro.curso-r.com/index.html)

[Análise Espacial com R](https://www.dropbox.com/s/blgtp2bmpdghol7/AnaliseEspacialComR.pdf?dl=0)

[Documentação GEE](https://developers.google.com/earth-engine) 

Aybar, C., Wu, Q., Bautista, L., Yali, R., & Barja, A. (2020). rgee: An R package for interacting with Google Earth Engine. Journal of Open Source Software, 5(51), 2272.

[Introdução ao rgee](https://cran.r-project.org/web/packages/rgee/vignettes/rgee01.html)

[Repositório rgee](https://github.com/r-spatial/rgee)

[rgeeExtra](https://r-earthengine.com/rgeeExtra/), extensão para o rgee 


[Slides](https://tai-rocha.github.io/R_RGEE_AMBGEO.github.io/) do curso de Dados geoespaciais na linguagem R. 



