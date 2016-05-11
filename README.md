## Project Argus - ESNO impact on US Agriculture
---------------------------------

###1. Description

***Increase in Agriculture***
**First major improvement** - 1950-1970 (average output of 1.5) Due to improvement in fertilizers, pesticides, herbicides, machinery.
**Second major improvement** - 1980-2000 (average output of 2) Due to better genetics, preferred selection of qualities in seeds, automation in machinery, irrigation technologies
Output has been stagnant from last decade or so around 2.5. Next level of optimization in agri economy can come from data analytics.

***Weather***
Weather has started to play very major role in agri productivity and it threats the future. Global warming, increased frequency of natural calamities related to weather, floods, long draughts, warmer summers and cold winters.
Analysis over long duration of period required to find correlation between weather patterns, agri productivity, agri inputs, secondary factors like (fertilizers, pesticides, herbicides, irrigation, soil quality, seed variety), and social factors like profitability, subsidies, labor and capital required.

###2. Technology Stack Used

    Hybrid Add - IONIC Framework
    Graph DB - Neo4j
    NoSql DB - Mongo
    WebServer - Node Express
    UI Framework - Twitter Bootstrap
    Deployment - Cloud Foundry
    Hosting - IBM Blumix
    Visualization - High Charts
   
   
###3. Developer APIs

    GET /api/getcropdata
    Request Parameters: 
    crop: Crop Name
    Response: JSON String
     
    Example
    Request: /api/getcropdata?crop=cotton
    Response: {"items":[{"_id":"573191df978bccae5a2b194c","year":1866,"crop":"cotton","region":"albama","acres harvested":977000,"acres planted":"","production":264000,"yield":0.054432,"":""},{"_id":"573191df978bccae5a2b194d","year":1866,"crop":"cotton","region":"texas","acres harvested":490000,"acres planted":"","production":172320000,"yield":0.14742,"":""}]}
















