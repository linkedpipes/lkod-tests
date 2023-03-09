# Testovací scénáře 

## Na základě URL rozhraní poznat, co je to za rozhraní - SPARQL, DCAT-AP Dokumenty, CKAN API
- pro CKAN API napsat, že není podporované dle OFN + link
- pro ostatní napsat, jaký typ je detekován + metadata odpovídající https://ofn.gov.cz/rozhraní-katalogů-otevřených-dat/2021-01-11/#dcat-ap-dokumenty-katalog

## Validní katalog - DCAT-AP Dokumenty - JSON-LD varianta
URL: https://raw.githubusercontent.com/linkedpipes/lkod-tests/main/dcat-ap-dokumenty/validn%C3%AD/v01.jsonld

## Neplatná URL
URL: https://blalallalalal.cz

## Nedostupný CORS
URL: https://www.mvcr.cz/

## Nevalidní katalog 01 - DCAT-AP Dokumenty - JSON-LD varianta
URL: https://raw.githubusercontent.com/linkedpipes/lkod-tests/main/dcat-ap-dokumenty/nevalidní/n01.jsonld
syntax error

## Nevalidní katalog 02 - DCAT-AP Dokumenty - JSON-LD varianta
URL: https://raw.githubusercontent.com/linkedpipes/lkod-tests/main/dcat-ap-dokumenty/nevalidní/n02.jsonld
null v JSON-LD language map - JSON schema error, JSON-LD error

## Nevalidní katalog 03 - DCAT-AP Dokumenty - JSON-LD varianta
URL: https://raw.githubusercontent.com/linkedpipes/lkod-tests/main/dcat-ap-dokumenty/nevalidní/n03.jsonld
Syntakticky i json-ld validní, ale prázdný

## Nevalidní katalog 04 - DCAT-AP Dokumenty - JSON-LD varianta
URL: https://raw.githubusercontent.com/linkedpipes/lkod-tests/main/dcat-ap-dokumenty/nevalidní/n04.jsonld
chybný JSON-LD kontext - tedy RDF se nepovede načíst nebo bude prázdné

## Nevalidní katalog 05 - DCAT-AP Dokumenty - JSON-LD varianta
URL: https://raw.githubusercontent.com/linkedpipes/lkod-tests/main/dcat-ap-dokumenty/nevalidní/n05.jsonld
Katalog OK, nelze načíst datovou sadu - nevalidní URL

## Nevalidní katalog 06 - DCAT-AP Dokumenty - Turtle varianta
URL: https://raw.githubusercontent.com/linkedpipes/lkod-tests/main/dcat-ap-dokumenty/nevalidní/n06.ttl
Katalog OK, nelze načíst datovou sadu - nevalidní URL
