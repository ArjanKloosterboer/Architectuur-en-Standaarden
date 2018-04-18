# Begrippenlijst
Naar aanleiding van een verzoek vanuit de Regiegroep Gegevens- en Berichtenstandaarden is deze begrippenlijst van de meest voorkomende begrippen die in de huidige beweging van ‘Samen organiseren en Common ground actueel zijn opgesteld.

Aan een ieder die hieraan bij kan dragen het verzoek om waar nodig aan te vullen of aan te passen zodat dit overzicht actueel blijft en aansluit bij de behoefte van de doelgroep(en).

## API
Een application programming interface (API) is een verzameling definities op basis waarvan een computerprogramma kan communiceren met een ander programma of onderdeel (meestal in de vorm van bibliotheken). Vaak vormen API's de scheiding tussen verschillende lagen van abstractie, zodat applicaties op een hoog niveau van abstractie kunnen werken en het minder abstracte werk uitbesteden aan andere programma's. Hierdoor hoeft bijvoorbeeld een tekenprogramma niet te weten hoe het de printer moet aansturen, maar roept het daarvoor een gespecialiseerd stuk software aan in een bibliotheek, via een afdruk-API.

bron: https://nl.wikipedia.org/wiki/Application_programming_interface 

Wanneer we spreken over "API's", als alternatief op of vervanging van StUF Soap "services", bedoelen we kleine, scherp gedefinieerde, voor een businessbehoefte doelmatige en voor consumers van de API/service eenvoudig te begrijpen en eenvoudig te implementeren services. Waar StUF services (en de StUF standaard) meer ontworpen zijn met het oog op hergebruik voor providers van services, worden API's ontworpen op eenvoud van gebruik.

## Bronsystemen
Een Bronsysteem is het systeem waaruit een gegeven afkomstig is. Voor elk soort gegeven moet er voor een gemeente één bron zijn. Er zijn bronnen voor landelijke basisgegevens en voor gemeentelijke kerngegeven. Bronsystemen kunnen buitengemeentelijk zijn zoals basisregistraties, of binnengemeentelijk. Voor gegevens die binnengemeentelijk worden vastgelegd, maar ook tussen gemeenten beschikbaar moeten zijn, kunnen landelijke voorzieningen dienen als gedelegeerde bron voor de buitengemeentelijke gegevens.

## Conceptueel informatiemodel
Modellering van de werkelijkheid binnen het beschouwde domein, v.w.b. informatie daarvan, onafhankelijk van ontwerp van en implementatie in systemen. Het geeft een zo getrouw mogelijke beschrijving van die werkelijkheid en is in natuurlijke taal geformuleerd. 
Een dergelijk model definieert het ‘wat’: welke ‘concepten’ (‘dingen’)  worden onderscheiden (in de beschouwde werkelijkheid), wat betekenen zij, hoe verhouden ze zich tot elkaar en welke informatie (eigenschappen) is daarvan relevant. Het dient als taal waarmee domeinexperts kunnen communiceren met informatie-analisten en verschaft een eenduidige interpretatie van die werkelijkheid ten behoeve van deze communicatie. Een conceptueel informatiemodel wordt dan ook opgesteld voor gebruik door mensen, zodat ‘de business’ en de ICT-specialisten elkaar gaan begrijpen.

bron: Meta-informatiemodel (MIM); Kadaster, VNG Realisatie & Geonovum, 2017
Synoniem(en): Semantisch informatiemodel (SIM); Informatiemodel

## Entiteittype
In een Semantisch Informatiemodel (SIM) worden gegevens en hun relaties beschreven. Groepen samenhangende gegevens met eigenschappen van een in de werkelijkheid bestaand object, noemen we een objecttype. Het gaat om de structuur en relaties, niet om concrete instances van het objecttype. Dus bijvoorbeeld om een "ingeschreven natuurlijk persoon", niet om de persoon "Jan de Vries" (elke overeenkomst van deze voorbeeldnaam met een werkelijk bestaand persoon berust op louter toeval).
Wanneer een objecttype wordt vertaald naar een structuur in een bericht, noemen we dit een entiteittype. Een entiteittype is dus vertaling van een objecttype naar de structuur waarin deze kan worden opgenomen in een bericht voor gegevensuitwisseling in een API of service.

## Gegevensmodel
Synoniem van: Logisch informatiemodel

## Informatiemodel
Synoniem van: Conceptueel informatiemodel

## JSON
JSON of JavaScript Object Notation, is een gestandaardiseerd gegevensformaat. JSON maakt gebruik van voor de mens leesbare tekst in de vorm van data-objecten die bestaan uit een of meer attributen met bijbehorende waarden. Het wordt hoofdzakelijk gebruikt voor uitwisseling van data tussen server en webapplicatie, als een alternatief voor xml.

bron: https://nl.wikipedia.org/wiki/JSON 

## Logisch informatiemodel
Beschrijft hoe de, in het conceptueel informatiemodel onderscheiden, concepten gebruikt worden bij de interactie tussen systemen en hun gebruikers en tussen systemen onderling. Anders gezegd, een model van de representatie van informatie over de werkelijkheid in digitale registraties en in de uitwisseling daartussen. 
Het gaat hierbij, in tegenstelling tot een conceptueel informatiemodel, dus veel meer om het ‘hoe’. Het slaat de brug tussen werkelijkheid en systemen maar beschrijft nog niet de implementatie in die systemen. Een dergelijk model wordt in een formele taal beschreven en wordt waar mogelijk gegenereerd vanuit het conceptueel model. Het logisch informatiemodel wordt opgesteld voor ICT-interoperabiliteit, voor gebruik door met name de ontwerpers, bouwers en beheerders van ICT-voorzieningen.

bron: Meta-informatiemodel (MIM); Kadaster, VNG Realisatie & Geonovum, 2017
Synoniem(en): Gegevensmodel
Specialisatie(s): Uitwisselings gegevensmodel (UGM)

## NLX
NLX is an open source inter-organisational system facilitating federated authentication, secure connecting and protocolling in a large-scale, dynamic API landscape.

bron: https://github.com/VNG-Realisatie/nlx

## Resources
Onder Resources wordt in deze contect verstaan Web Resources. Een Web Resource wordt gebruikt om te verwijzen naar target van uniform resource identifier (URI). Met een URI wordt een gegeven geidentificeerd wat gebruikt kan worden in bijvoorbeeld gegevensuitwisseling.

bron: https://en.wikipedia.org/wiki/Web_resource

## REST
Representational state transfer (REST) is een software-architectuur voor gedistribueerde mediasystemen zoals het wereldwijde web.

bron: https://nl.wikipedia.org/wiki/Representational_state_transfer 

Representational state transfer (REST) is een software architectuurstijl die bestaat uit een set afgestemde architecturele constraints die toegepast zijn op componenten, koppelingen en gegevens elementen, binnen een gedistribueerd hypermedia systeem. REST negeert details zoals de implementatie van componenten en protocol syntax en concentreert zich op de rol van componenten, de constraints op de interactie van die componenten met andere componenten en de interpretatie van de belangrijke data elementen.

bron: https://api2cart.com/api-technology/rest-dummies-short-intro-representational-state-transfer/

REST beschrijft 6 beperkingen (constraints) op de architectuur van gegevensuitwisseling:
* Uniform Interface
* Stateless
* Cacheable
* Client-Server
* Layered System
* Code on Demand (optional)

bron: http://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm

## RESTful API
Een RESTful API is een application program interface (API) die gebruik maakt van de HTTP requests GET, PUT, POST and DELETE om data te verwerken.

bron: http://searchmicroservices.techtarget.com/definition/RESTful-API 

## Semantisch informatiemodel (SIM)
Synoniem van: Conceptueel informatiemodel

## Technisch datamodel
Specificeert de structuur en eigenschappen van de technologie waarin de informatie wordt vastgelegd of uitgewisseld. Dit is sterk afhankelijk van de gebruikte opslagtechnologie zoals een specifieke database of de servicetechnologie zoals XML, GML, SOAP, REST, (Geo)JSON, LinkedData e.d. Het kan tevens informatie bevatten over de manier waarop berichten ‘verpakt’ worden, het (internet)protocol en de logistiek van het berichtenverkeer. De technische specificaties worden over het algemeen zoveel als mogelijk gegenereerd uit het logisch informatiemodel. Deze specificaties worden opgesteld voor ‘machines’, te gebruiken door software-ontwikkelaars.

Synoniemen: Technisch gegevensmodel; Fysiek datamodel; Fysiek gegevensmodel
bron: Meta-informatiemodel (MIM); Kadaster, VNG Realisatie & Geonovum, 2017

## Uitwisselings gegevensModel (UGM)
Specialisatie van: Logisch informatiemodel
In een Uitwisselingsgegevensmodel (UGM) worden de gegevens en relaties zoals deze in een conceptueel informatiemodel zijn beschreven geoptimaliseerd voor gegevensuitwisseling. Normaliter zal een gegeven in het UGM gelijk zijn aan hetzelfde gegeven in het bijbehorende SIM. Qua enkelvoudige gegevens (elementen) vinden onder andere de volgende optimalisaties plaats: 

* namen met spaties worden geconverteerd naar camelCase, 
* formaten worden formeel gespecificeerd door middel van "patterns".  

Indien noodzakelijk kunnen qua samengestelde gegevens (entiteittypen) en relaties de volgende optimalisaties worden uitgevoerd:

* samenvoegen van entiteittypen,
* platslaan van relaties.

Een Uitwisselingsgegevensmodel bestaat uit entiteittypen, eigenschappen (elementen) daarvan/daarin en relaties tussen entiteittypen. Het uitwisselingsgegevensmodel wordt gemodelleerd in [UML](https://nl.wikipedia.org/wiki/Unified_Modeling_Language).

De structuren van entiteittypen zoals beschreven in het UGM vormen de basis voor de berichten zoals die beschreven staan in het Berichtstructuurmodel (BSM). We hanteren een pas-toe-of-leg-uit principe op het volgen van de UGM entiteittypestructuren in berichten voor services en API's. Daarbij mag in een bericht wel worden gedefinieerd dat slechts een deel (van de elementen en relaties) van een entiteittype in een bericht wordt opgenomen.

## BerichtStructuurModel (BSM)
Een bericht in een koppelvlakstandaard wordt gemodelleerd in een Bericht Structuur Model (BSM). Het BSM is een UML klassediagram waarmee de structuur van een specifiek bericht wordt vastgelegd. Op basis van het BSM kunnen de technische specificaties van berichten (xsd's of open API specificatie) worden gegenereerd.

In een BerichtStructuurModel worden berichten vormgegeven op basis van een UitwisselingsGegevensModel. Alle onderdelen uit een UGM kunnen worden hergebruitk in een BSM. In een BerichtStructuurmodel worden alleen die onderdelen van het UGM opgenomen die daadwerkelijk worden gebruikt in het bericht. Dat betekent dat er vaak gebruik zal worden gemaakt van een deel van de attributen van een entiteit en ook mogelijk een deel van de relaties wordt gebruikt. Ook de enumeratiewaarden van een Enumeratie kunnen bepekrt worden (niet veranderd).

Een BSM beschrijft de berichtstructuren onafhankelijk van een eventueel te gebruiken formaat of uitwisselstandaard (StUF soap/xml of REST/JSON API). Voorbeelden zijn vraag- en antwoordbericht of een kennisgevingsbericht. Vanuit een BSM kan eenzelfde bericht in verschillende formaten gegenereerd worden.

## Koppelvlakstandaard
In een koppelvlak wordt zo specifiek en doelgericht mogelijk vastgelegd hoe een koppelvlak moet werken. Dit bevat ten minste de koppelvlakarchitectuur, berichtinteracties, functionele- en technische berichtdefinities (berichtschema’s). In een koppelvlakstandaard worden modellen en afspraken uit de bovenliggende niveaus van standaardisatie gebruikt op basis van een specifieke businessbehoefte aan gegevensuitwisseling. Een koppelvlakstandaard wordt gebruikt voor het daadwerkelijk implementeren van services/API’s.

## Gegevensuitwisseltechnieken
We ontwikkelen, gebruiken en beheren standaarden die o.a. de technische aspecten van gegevensuitwisseling beschrijven. Deze standaarden worden koppelvlakoverstijgend beschreven en beheerd. 
De beschrijving van een gegevensuitwisseltechniek kan betrekking hebben op protocolbindingen (zoals http, soap) of op de opbouw en afhandeling van berichten voor verschillende interactiepatronen. Deze standaarden beschrijven niet de gegevens in berichten, maar beschrijven op welke manier gegevens in berichten worden opgenomen, hoe berichten eruit zien om een bepaald resultaat bij de ontvanger van het bericht te kunnen verwachten, hoe ontvangen berichten geïnterpreteerd moeten worden, hoe ontvangst en verwerking worden bevestigd, hoe fouten worden teruggemeld, naamgevingsconventies, enz.

We onderscheiden op dit moment twee gescheiden technische onderlagen, hoewel we ons niet hiertoe zullen limiteren: 
* StUF (SOAP/XML)
* (RESTful) API (http(s), JSON)
