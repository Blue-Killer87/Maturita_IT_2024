## Business Intelligence
  - Komplex procesů aplikací a technologií ICT.
  - Podporuje analytické a plánovací činnosti podniku. 
  - Abychom získali lepší pochopení chování na trhu a obchodních souvislostí.
  - Postaveny na principu multidimenzionality.

## PSC – soubor nástrojů, které měří výkonnost podniku pomocí 4 perspektiv:
1.	Finance a finanční ukazatele
2.	Interní proces
3.	Zákazníci
4.	Učení a růst

## Datawarehouse – Datový sklad 
- Integrovaný v rámci celého podniku či podnikatelských skupin
-	Subjektově orientovaný (data rozdělena podle typu, ne podle vlastních aplikací). 
-	Je stálý, nejčastější koncepce je read-only. 
-	Žádná data vevnitř nevznikají – pouze se ukládají.
-	Data jsou načítána z produkčních databází, či jiných externích zdrojů a existují po celou životnost datawarehousu. 
-	Integrovaný v rámci celého podniku, read-only
### CRM – customer relationship management
- Maximalizace loajality zákazníků 
### SCM – supply chain management
-	Řízení řetězce dodávek
### EAI – enterprise application integration
-	Integrační systém technologií a služeb, které vytvářejí soubor prostředků umožňující integraci systémů a aplikací v rámci organizace – middleware
### ERP – enterprise resource planning
-	Informační systém, který integruje a automatizuje velké množství procesů související s produkčními procesy projektu
-	Výroba, logistika, distribuce, správa majetku, prodej, fakturace účetnictví atd.
### ODS – operation data storage
-	Obsahuje data z celé historie
### DSA – data staging area
-	Dočasné úložiště dat
-	Připravená aktuální data ze zdrojových systémů pro rychlý a efektivní výběr dat
-	Slouží k prvotnímu ukládání netransformovaných dat
### eB – elektronické bankovnictví
### ETL – extraction transformation and loading
-	Datová pumpa
-	Extrakce dat z vnějších datových systémů
-	Uložení do cílových bází dat
### DMA – data market
-	Datové tržiště
-	Problémově orientovaný decentralizovaný datový sklad
-	Určen pro omezený okruh uživatelů... Takto realizovaný přenos dat lze virtuální i reálně zpoplatnit
## Účastníci komunikace IS 
-	B2B – business to business – komunikace podnikatele s podnikatelem, 
např. objednávka materiálu 
-	B2C – business to customer – komunikace podnikatele se zákazníkem, 
např. vystavení faktury 
-	C2B – customer to business – komunikace zákazníka s podnikatelem,
např. odeslání objednávky 
-	C2C – customer to customer – zákazník se zákazníkem,
např. výměna souborů 
-	C2G – customer to government – komunikace zákazníka se státní správou
např. zdravotní pojištěni
-	B2G – business to government – komunikace podnikatele se státní správou
např. daňové přiznaní
-	B2A – business to administration – komunikace podnikatele se správou
např. jízdní příkaz
-	eBusiness – elektronické obchodování všeobecně

Systémy na podporu plánování: APS, SCM

Systémy na podporu dílčích činností podniku: PR



## Testování softwaru
**Podle znalosti kódu:**
- Whitebox – pokud jsou testy na základě vlastnosti kódu, např. Unity test
- Blackbox – na software se koukáme jako by se jednalo o černou skříňku, známe jenom reakce, na základě konkrétních vstupů sledujeme jen konkrétní výstupu
- Graybox – částečná znalost kódu
  
**Podle způsobu realizace testů:**
- Automatické – často prováděné pomocí skriptů (např. Python), Cílem ověřit opakující se scénáře, za pomoci krátkých programů
- Manuální – testy prováděné přímo testerem, podle testovací případů (test case)
- Exploratory – provádějí testeři bez scénáře

**Podle dimenzí kvality:**
- Vychází z normy ISO/IEC 25010:2011
- Funkčnost – správné chování funkcí systémů, jak je definování funkční specifikací
-	Výkon – zde systém není pomalý

**Podle kompatibility:**
- Kombinace s jiným HW a SW.

**Podle použitelnosti:**
- Zda se chová, jak se chovat má.

**Podle spolehlivosti:**
- Chová se za všech okolností stejně, zvláště po přetížení.

**Podle bezpečnosti:**
- Zda jsou oddělené přístupové role. Zda se nedá do systému dostat bez hesla. Skrytý admin API atd.

**Podle udržitelnosti:**
- Zdali se dá systém upgradovat, měnění částí, modularita

**Podle přenositelnosti:**
- Dimenze podle kvality

## Fáze testování
**Unit test**
- Dělá se jako první, obvykle programátoři, ověřuje se tzv. unita (jednotka)
- Nejčastěji automatizované

**Modul test**
- Stále testují programátoři, většinou větší projekty, testování modulů, pluginů atd.

**Integrační test**
- Testuju integraci kódu, řeší programátoři

**Funkční test**
- Zkoumá se, co systém dělá

**Smoke test**
- rychlý a jednoduchý test, zjišťujeme, zda jsou všechny části implementovány

**Sanity test** 
- cílem je zjistit, zda navrhovaná funkce funguje zhruba podle očekávání

**Regres test**
- Provedení funkčních a nefunkčních testů pro zjištění, zda dříve vyvinutý a testovaný SW po změně stále funguje. Pozoruje chování samotných uživatelů, čímž může odhalit chyby, které zůstaly vývojářům skryty

**Systémové testy** 
– nejvyšší, cílem ověřit zde systém funguje jako celek

**Akceptační test**
– realizovány na straně zákazníka. Ověřuje, že produkt splňuje očekávané funkce a kvalitu.

## Cloudové pojmy
- Multitenancy – Systém zvládne více uživatelů na jednou (Tenanti mají v systému svoje vlastní data a svoje vlastní nastavení), škálovatelnost a plasticita systému
- Pay as you go – „Zaplať za to, co spotřebuješ“
- Up to date – věci jsou hned pro všechny aktuální

## Typy cloudových úložišť
- Veřejný cloud – SLA, multitenance
- Privátní cloud – veškeré prostředky tohoto nasazení jsou dirigovány a používány pouze jedním uživatelem nebo zákazníkem. HW a SW běží na dirigované privátní sítí a zároveň na HW nikdy neběží služby od jiného zákazníka. Výhoda – bezpečnost
- Hybridní cloud – spojuje výhody veřejného a privátního cloudu, případně spojení veřejného cloudu s jinou místní infrastrukturou
- Multicloud – využívá více různých cloudů. Hybridní má privátní složku, multicloud ji taky může mít, ale spíš využívá jiné cloudy, to je rozdíl. Výhoda – když mě nějaký cloud nasere, tak ho prostě vyhodím.
- Komunitní cloud – model, kdy je infrastruktura cloudu sdílena mezi několik organizací, tyto organizace může spojovat třeba bezpečnostní politika nebo stejný obor zájmů.

## Podnikové procesy
- Soubory strukturovaných aktivit nebo úloh, které vytvářejí a dodávají hodnotu zákazníkům, nebo dosahují podnikových cílů. Dělíme na interní a externí

## Základní typy
-	Hlavní procesy (core procesy) – zásadní pro dosažení podnikových cílů a poskytují přidanou hodnotu zákazníkům (výroba, marketing, prodej, dodávky atd.),
-	Podpůrné procesy (support process) – podporují hlavní procesy (IT, služba, lidské zdroje, účetnictví)
-	Řídící procesy (procesy spojené s řízením a správou organizace jako jsou plánování, rozpočtování, změna managementu a strategická rozhodování)

## Charakteristiky efektivních podnikových procesů
-	Jasné cíle – jasně definovaný účel a cíl
-	Optimalizace a efektivita
-	Flexibilita a adaptabilita
-	Měřitelnost a sledovatelnost
-	Integrace a koordinace

## Význam podnikových procesů
-	Zvýšení efektivita
-	Zlepšení kvality
-	Zákaznická spokojenost
-	Inovace a růst
-	Modelování podnikových procesů – technika používaná k vizualizaci, analýze a ke zlepšení modelu práce
-	Vizualizace procesů
-	Standardizace jazyka a symbolů
-	BPMN – bussiness process model notation, UML
-	Analýza a identifikace problémů
-	Zlepšení a optimalizace
-	Komunikace a implementace
