# Tableau-JS-API

1.	Things you don’t need Tableau JS API for:  
  i.e. using [this Marginal Tax calculator](https://public.tableau.com/profile/davidsm#!/vizhome/MarginalTaxRateSimulator/MarginalRate) a couple of ways of embedding it:  
    1.	Embed in the Dataschool blog (just use iframe and the link found in the share button). [Example here, Page is only available for those signed in to the DS Blog](https://www.thedataschool.co.uk/david-sanchez/23394/).    
    1. Embed in your own page/blog (just use the embed code inside an HTML box). [Example in David's blog](https://dsmdaviz.com/2019/01/marginal-tax-rate-simulator/).      
1.	Things you need Tableau JS API for:  
    1.	Embed in your page and do anything with it (beyond the Viz itself):  
        1.	Autoupdate.  
        1.	Pass multiple filters.  
        1.	Drive alarms in the webpage based on the data.  
        1.	Have a two way communication (interact with the Viz, take that data into the page, evaluate it and feed it back to the Viz).
