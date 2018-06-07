# brshinyapps
Gallery of Shiny Apps developed by brazilian R users.

# To contribute
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
