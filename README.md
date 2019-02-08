# Tableau-JS-API
Outcome of Back2School week at [The Dataschool](https://www.thedataschool.co.uk/) for *Eliott & David*.

## What is it not for and what is it for:
1.	Things you don’t need Tableau JS API for:  
  i.e. using [this Marginal Tax calculator](https://public.tableau.com/profile/davidsm#!/vizhome/MarginalTaxRateSimulator/MarginalRate) a couple of ways of embedding it:  
    1.	Embed in the Dataschool blog (just use iframe and the link found in the share button). [Example here, Page is only available for those signed in to the DS Blog](https://www.thedataschool.co.uk/david-sanchez/23394/).    
    1. Embed in your own page/blog (just use the embed code inside an HTML box). [Example in David's blog](https://dsmdaviz.com/2019/01/marginal-tax-rate-simulator/).  
    Or [this one](Example_01-direct%20embed.html) for a standalone page.  
    
1.	Things you need Tableau JS API for:  
    1.	Embed in your page and do anything with it (beyond the Viz itself):  
        1.	[Autoupdate](https://dsmdavid.github.io/Tableau-JS-API/Example_03-API%20embed%20autorefresh.html).  
            A Dashboard with a time (NOW() calculation in Tableau) that refreshes every X seconds. See example by Christophel Russell in the resources section below).
        1.	Pass multiple filters. (No examples yet)
        1.	Have a [two way communication](https://dsmdavid.github.io/Tableau-JS-API/Example_07-%20With_box_interaction%20in%20Dashboard.html) (interact with the Viz, take that data into the page, evaluate it and feed it back to the Viz --in this particular example, the Viz is in autorefresh by default every 10 seconds. A counter on top helps keeping track of the time left. Interacting with the boxes in the Dashboard allows fetching that value (in seconds) and change both the counter on top as well as send it back to the Viz and change the refresh time).
        1.	[Drive alarms in the webpage based on the data](https://dsmdaviz.com/criticalshipments/)  You'll need to log in to TIL tableauserver to see the dashboard (and run the workflows here to update the datasource from [not warning](https://github.com/dsmdavid/Tableau-JS-API/blob/master/RefreshDatasource_Warning.yxmd) to [warning](https://github.com/dsmdavid/Tableau-JS-API/blob/master/RefreshDatasource_Warning.yxmd)). The basic idea is a dashboard, hosted on a company's server, needs to be constantly on monitoring some critical measure. Whenever a critical value comes in, action needs to be immediate, so the webpage will launch an alert to get the attention).
            This is what [it should look video](https://www.youtube.com/watch?v=Sv14MNzBVhc).  
            ![screenshot](https://dsmdaviz.com/wp-content/uploads/2019/02/screenshot.png)   



## Resources:
1. Tableau's [official API reference](https://onlinehelp.tableau.com/current/api/js_api/en-us/JavaScriptAPI/js_api_ref.htm).   
1. Tableau's Github on [JS API](https://github.com/tableau/js-api-samples) and [Videos](https://github.com/tableau/js-api-samples/tree/master/Videos).  
1. Christopher Russell's example and original workbook on [autorefresh](http://russellchristopher.me/youdidwhat/autoload.html).    
1. Tableau's interactive [tutorial](https://onlinehelp.tableau.com/samples/en-us/js_api/tutorial.htm).    
1. [Tamas Foldi's](https://databoss.starschema.net/?s=javascript) many examples.