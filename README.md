# Tableau-JS-API
Outcome of Back2School week at [The Dataschool](https://www.thedataschool.co.uk/) for Eliott & David.

1.	Things you don’t need Tableau JS API for:  
  i.e. using [this Marginal Tax calculator](https://public.tableau.com/profile/davidsm#!/vizhome/MarginalTaxRateSimulator/MarginalRate) a couple of ways of embedding it:  
    1.	Embed in the Dataschool blog (just use iframe and the link found in the share button). [Example here, Page is only available for those signed in to the DS Blog](https://www.thedataschool.co.uk/david-sanchez/23394/).    
    1. Embed in your own page/blog (just use the embed code inside an HTML box). [Example in David's blog](https://dsmdaviz.com/2019/01/marginal-tax-rate-simulator/).  
    Or [this one]('Example_01-direct embed.html') for a standalone page.  
    
1.	Things you need Tableau JS API for:  
    1.	Embed in your page and do anything with it (beyond the Viz itself):  
        1.	Autoupdate.  
        1.	Pass multiple filters.  
        1.	Drive alarms in the webpage based on the data.  
        1.	Have a two way communication (interact with the Viz, take that data into the page, evaluate it and feed it back to the Viz).


## Resources:
1. Tableau's [official API reference](https://onlinehelp.tableau.com/current/api/js_api/en-us/JavaScriptAPI/js_api_ref.htm).   
1. Tableau's Github on [JS API](https://github.com/tableau/js-api-samples) and [Videos](https://github.com/tableau/js-api-samples/tree/master/Videos).  
1. Christopher Russell's example and original workbook on [autorefresh](http://russellchristopher.me/youdidwhat/autoload.html).    
1. Tableau's interactive [tutorial](https://onlinehelp.tableau.com/samples/en-us/js_api/tutorial.htm).    
1. [Tamas Foldi's](https://databoss.starschema.net/?s=javascript) many examples.