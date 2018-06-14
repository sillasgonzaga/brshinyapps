

# brshinyapps

(Texto disponível em Português e Inglês)  
(Portuguese and English versions available)

Galeria de apps Shiny desenvolvidos por usuários brasileiros de R.

Gallery of Shiny apps developed by brazilian R users.

# Para contribuir | To contribute
Você está mais que incentivado para submeter seus apps para aparecer aqui. Por favor crie uma issue para que seu Shiny app seja incluído aqui. Ao criar sua issue, por favor forneça links para um print da tela do app e para o próprio app. Para ajudar ainda mais, use a função abaixo e cole na issue seu output:

You are encouraged to submit your apps to be shown here. Please open an issue to ask for your shiny app to be included in this README. When writing your issue, please provide urls for both a screenshot of the app and for the app itself. To be even more helpful, paste the output of the function below:

``` r
nova_submissao <- function(app_name, screenshot, app_url){
  
  html <- sprintf(
    '[<img src="%s" width="480" height="300">](%s)',
    screenshot, app_url
    )
  
  header <- sprintf("### %s", app_name)
  
  cat(paste0(
    header,
    "\n",
    html
  ))
}

# Example:
nova_submissao("meu_app",
               "https://i.imgur.com/MP2nQEJ.jpg?1",
               "https://giars.shinyapps.io/shiny-redes/")
```

# Gallery

### Olx Map Search
[<img src="https://i.imgur.com/tSzAmiJ.jpg?1" width="480" height="300">](https://sillasgonzaga.shinyapps.io/olxshiny2/)

### Pesquisas Eleitorais 2018
[<img src="https://i.imgur.com/44G4e5x.jpg?1" width="480" height="300">](http://pesqele.conre3.org.br/app/)

### Aplicação de Análise de Redes Sociais - GIARS
[<img src="https://i.imgur.com/MP2nQEJ.jpg?1" width="480" height="300">](https://giars.shinyapps.io/shiny-redes/)

### Enem e Censo das Escolas de Santa Catarina
[<img src="https://i.imgur.com/Gu4YxnM.jpg?1" width="480" height="300">](https://silvio.shinyapps.io/ENEMSC/)

### Carômetro
[<img src="https://i.imgur.com/SRSueP3.jpg?1" width="480" height="300">](https://flaviobarros.shinyapps.io/carometro/)

### Word Cloud
[<img src="https://i.imgur.com/YOWXARs.jpg?1" width="480" height="300">](https://gomesfellipe.shinyapps.io/appwordcloud/)

### appPCAkmeans
[<img src="https://i.imgur.com/XuKuIV8.jpg?1" width="480" height="300">](https://gomesfellipe.shinyapps.io/apppcakmeans/)
