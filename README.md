A economia do chimarrão
=========

Um relatório automatizado com análise exploratória de dados do chimarrão (erva-mate), uma cultura regional do sul do Brasil.


Como funciona?
-----------------

Para gerar o relatório (um arquivo `HTML`), basta "knitar" o arquivo **index.Rmd**, que é um documento do tipo R Markdown.

Será efetuada a coleta, tratamento e exibição dos dados de forma automatizada, que ficarão disponíveis no arquivo **index.html** gerado.

```r
rmarkdown::render("index.Rmd")
```


Autor
------

[Fernando da Silva](fernando@gecefurg.com.br)

