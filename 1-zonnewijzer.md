In deze workshop gaan we aan de slag met de gegevens uit de [Zonnewijzer](https://www.arcgis.com/apps/webappviewer/index.html?id=3b6236d6aa6349699a9165b0d64b6299). De Zonnewijzer is een webapplicatie in de cloud. De gegevens komen echter uit de database van het Geo-team. De Zonnewijzer vraagt de gegevens op met behulp van een web API. Met de [ArcGIS REST API](https://developers.arcgis.com/rest/), om precies te zijn.    

De ArcGIS REST API is niet alleen geschikt voor het tonen van gegevens in een kaartviewer. Je kunt de API ook gebruiken om de ruwe gegevens op te vragen, selecties te maken of statistieken te berekenen. Zo kun je de gegevens eenvoudig hergebruiken in JavaScript code, Power BI, R of Tableau.   

Voor een overzicht van alle gegevens die Zuid-Holland aanbiedt via de ArcGIS REST API, raadpleeg je de [services directory](https://geoservices.zuid-holland.nl/arcgis/rest/services).    

In de oefeningen beperken we ons tot de Zonnewijzer service:    
https://geoservices.zuid-holland.nl/arcgis/rest/services/Ruimte/Zonnewijzer/FeatureServer   

Als je bovenstaande link volgt, zie je dat de Zonnewijzer service meer dan twintig kaartlagen ontsluit. 