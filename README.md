![cover]

# project1-Quick-Hack-Prototype

De opdrachtgever is de OBA. Voor deze opdracht kregen we een grote dataset en hier mochten we zelf weten wat ermee moesten doen.

## Het idee
Mijn eerste twee concepten hadden te maken met film. Ik wou dat je oude film posters kon zoeken en dat je kan zien waar in Amsterdam de film toen der tijd speelde. De informatie hiervoor was veel te beperkt. De externe dataset die ik gevonden had was niet toegankelijk voor publiek gebruik zonder toestemmming, dus ik sloeg het idee over. Mijn tweede idee was dat je Nederlandse film directors kon zien en door middel van IMDB kan je alle informatie vinden van de desbetreffende director. Helaas was de informatie te beperkt, dus ik liet dit idee ook gaan. Mijn uiteindelijke idee is een memory game. De gebruiker kan d.m.v zoekwoorden zelf zijn eigen kaarten kiezen. 
Deze kaarten worden in het spel gegooid en het spel kan beginnen. Als het spel voltooid is dan zal er een section geopend worden waar de plaatjes te zien valt plus wat de plaatjes inhouden met bijbehorende tekst.

## Hoe werkt het technisch
De game heeft twee modes. De gebruiker kan zelf zoeken naar plaatjes OF de gebruiker gebruikt de standaard kaarten die ik zelf in een array heb gezet. Er bestaan per mode 3 arrays. De woorden staan twee keer in een array en door middel van een randomizer en een concat gooit hij beiden arrays in 1 array en husselt de inhoudt. Dit zorgt ervoor dat de kaarten willekeurig op het bord komen te staan. De kaarten worden gematched door middel van het checken van ID's. Als 2 id's matchen met elkaar dan moet hij het plaatje laten zien en deze blijven zichtbaar op het bord. Als de ID's niet matchen dan zal de plaatjes terug gezet worden in kaartjes.

Zowel als de plaatjes gematched zijn als niet dan zal er een geluidje worden afgespeeld. Als het spel is uitgespeeld dan zal er een overwinningsdeuntje worden afgespeeld en er zal een nieuwe sectie worden geopend.

## Bugs 
* Klikken op de afbeelding zelf verwijderd het plaatje.

## Link prototype
https://desleyaalderink.github.io/OBA-Amsterdam/

[cover]: preview.png
