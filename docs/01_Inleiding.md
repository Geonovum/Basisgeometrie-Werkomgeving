Inleiding
=========

Dit model voor het gebruiken van een basisgeometrie is een specifieke toepassing voor het koppelen van geometrie aan een informatieobject.

NEN 3610, het Basismodel geo-informatie, beschrijft een geo-object als
abstractie van een fenomeen in de werkelijkheid, dat direct of indirect is
geassocieerd met een locatie relatief ten opzichte van de aarde. Een geo-object
heeft dus als eigenschap een locatie. Deze locatie kan gerealiseerd worden
doormiddel van coordinaten met een georeferentie, een geometrie. Het fenomeen of
het object zelf heeft ook kenmerken die het object definieren.
Informatiemodellen modelleren de gezamenlijkheid van
objectkenmerken inclusief locatie en geometrie.

Er zijn situaties waarbij verschillende modellen gebruikt worden om dezelfde
objecten in de werkelijkheid te modelleren met elk een specifieke set van
kenmerken maar wel met dezelfde locatie. Het enige dat de modellen gemeenschappelijk hebben
is de geometrie van het object. Indien er behoefte is om uit het oogpunt van
voorkomen van redundantie de modellen te normaliseren vanuit het geometrie
perspectief is een centraal model voor alleen geometrie een optie.

Dit model Basisgeometrie biedt hiervoor een gestandaardiseerde oplossing. Het
model beschrijft een geometrie als een apart objecttype dat vervolgens als een
eigenschap gebruikt kan worden door een objecttype van een ander
informatiemodel. Doel is het gezamenlijk kunnen gebruiken van een geometrie of
geometriebestanden door verschillende informatiemodellen. Het objecttype
Geometrie in Basisgeometrie bevat alleen een attribuut geometrie en heeft geen
inhoudelijke attributen.
