# Eventself
#### Applicatie voor het vak Programmeerproject | Menno Lont (11061200)


## Probleemstelling
Er vinden een hoop evenementen plaats op een dag, zoveel dat het moeilijk is om te bepalen wat leuk is voor jou en haalbaar. Een van de meest gebruikte eventmanagers op het moment is Facebook, maar Facebook laat vooral evenementen zien waar je vrienden heen gaan. Het is alleen mogelijk om een globaal onderwerp, globale locatie en een tijd te selecteren, voor de rest wordt het overgelaten aan algoritmes.


## Oplossing
Deze applicatie zal dit probleem oplossen door de gebruiker op basis van zijn/haar preferenties een duidelijk overzicht te geven van relevante evenementen. 
De doelgroep is vooral jonge(re) mensen en/of studenten.

#### Visuale tekening
Zie doc folder

#### Features
De applicatie toont een lijst met evenementen voor een bepaalde datum/tijd. (MVP)
De evenementen die getoond worden kunnen verschillen aan de hand van aanpasbare variabelen. (MVP)
De gebruiker kan meer informatie krijgen over een evenement door erop te klikken. (MVP)
Gebruikers kunnen interesse aangeven voor een evenement, of aangeven dat ze gaan.
Gebruikers kunnen een overzicht zien van evenementen waar ze interesse voor hebben/ waar ze heen gaan.
De evenementen kunnen worden getoond op een kaart. (MVP)


## Voorbereidingen

#### Data
Facebook maakt het mogelijk om evenementen te exporteren om ze in een agenda te kunnen zetten. Hier ga ik gebruik van maken om een lijst evenementen te maken waarmee ik kan werken. Klik op "Geplande evenementen" rechtsonder op de pagina:
https://www.facebook.com/events/calendar/

#### Externe libraries
Maps SDK voor het gebruik van Google Maps in de app. 
https://developers.google.com/maps/documentation/android-sdk/utility

#### Soortgelijke applicaties
Facebook heeft een evenementplanner. Hierbij kan je een stad, datum en onderwerp kiezen. Het gaat op een soortgelijke manier, waardes kiezen voor deze variabelen resulteert in een lijst van relevante evenementen. De nadruk ligt op waar vrienden ook naartoe gaan. Ik denk niet dat het gaat lukken om de lijst op basis van interesses van vrienden te sorteren, maar het filteren van evenementen kan zeker.

Facebook heeft ook al iets soortgelijks geïmplementeerd aan wat ik wil doen, Facebook Local. De reacties op deze app zijn verdeeld. De focus ligt hier écht op de kaart waardoor de evenementen minder gemakkelijk te vinden en sorteren zijn voor de gebruikers. Het implementeren van de evenementen op de kaart moet lukken.

#### Moeilijke onderdelen
Het moeilijkste deel lijkt mij het implementeren van de kaart die de evenementen laat zien. Dit heb ik nog niet eerder gedaan dus dat zal wel uitdagend worden. Desalniettemin gebruiken veel apps Google Maps dus ik ga er vanuit dat het moet lukken.
