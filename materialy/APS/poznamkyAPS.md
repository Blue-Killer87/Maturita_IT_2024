**Business Intelligence**

    - Představuje komplex procesů, aplikací a technologií ICT.
    - Podporuje analytické a plánovací činnosti podniku. (V plánování pomáhá APS[Advanced Planning System] systém.)
    - Pro získání lepšího pochopení chování trhu a obchodních souvislostí
    - Postaven na principu multidimenzionality. (Pohled na realitu z různých pohledů.)

    - V systému BI mohou být zahrnuty další informační systémy a technologie ICT:
        1. ERP (Enterprise Resource Planning)
            - Řízení podnikových zdrojů
            - IS který integruje a automatizuje velké množství procesů souvisejících s produkčními činnostmi podniků (Výroba, logistika, sklady, fakturace, prodej, správa majetku...)

        2. ODS (Operational Data Storage)
            - Obsahuje data bez historie, mění se po každém nahrání.

        3. BSC (Ballance Score Card)

            - Měří 4 aspekty:
                1. Prachy (finance) a obchodní ukazatele
                2. Interní obchodní procesy
                3. Zákazníci
                4. Učení a růst

            - p.s. je to kolečko

        4. DWH (Data Warehouse)

            - Verzuje, přídá, ale nemaže
            - Data Warehouse = datový sklad, integrovaný v rámci celého podniku či podnikatelských skupin
            - Subjektově orientovaný (data jsou rozdělena podle jejich typů, né podle jejich aplikací)
            - Read-only access
            - Žádná data v DWH nevznikají, jen se tam přidávají
            - Data jsou načítána z produkčních databází či jiných externích zdrojů a existují po celou životnost DWH

        5. CRM (Custom Relationship Management)

            - Řízení vztahů se zákazníky

        6. eB (electronic Banking)
        7. SCM (Supply Chain Management)
        8. EAI (Enterprise Application Integration)

            - Integrační systém technologií a služeb, které vytváří soubor prostředků,
              umožnující integraci systémů a aplikaci v rámci organizace. (middleware)

        9. ETL (Extraction, Transoformation & Loading)

            - Datová pumpa
            - Nástroj, který tahá data z IS a ukládá je do datových skladů.
            - Extraction - Vytáhnutí dat z informačních systému (CRM, SCM, ERP)
            - Transformation - Úprava dat do požadovaného formátu.
            - Loading - Uložení dat do cílových skladů.

        10. DSA (Data Staging Area)

            - Dočasné uložiště, kde jsou připravena aktuální data ze zdrojových systémů pro rychlý a efektivní výběr dat.
            - Slouží k prvotnímu ukládání netransformovaných dat.

        11. DMA (Data Market)

            - Datové tržiště
            - Problémově orientovaný, decentralizovaný datový sklad, který je určen pro omezený okruh uživatelů. (oddělení, divize, pobočka)

        12. OLAP (Online Analytical Processing)
        13. Data mining

            - Dolování dat
            - Extrakce, získávání relevantní dat z různých datových uložišť

        14. Reporting

            - Sumarizace dat (Výstup)

        15.


Testování softwaru
    Podle znalosti kódu
        2 principy:
            - white box (opensource)
                - Pokud jsou testy psané na základu znalosti kódu 
                - Typickým příkladem je unity test
            
            - black box (proprietary)
                - Na software se díváme jakoby se jednalo o černou skřínku
                - Známe pouze reakce softwaru. Na základě konkrétních vstupů sledujeme konkrétní výstupy.

            - grey box
                - Něco vim, něco ne

            - dle způsobu realizace testů:
                - automatiovaný = dodáváme proměnné, test je skript

                - Ruční = prováděný testerem podle testovacích případů

                - exploratory test = tester testuje bez podkladu a návodu

                - podle dimenzí kvality = Podle ISO normy ISO/25010:2011    
                    - dle funkčnosti = správné chování funkcí systému podle definice funkčnosti
                    - dle výkonu
                    - dle kompatibility
                    - dle kvality
                    - dle použitelnosti
                    - dle spolehlivosti = chová se za všech okolností stejně, zvlášt po přetížení, výpadku, chybě...
                    - dle bezpečnosti
                    - dle udržitelnosti
                    - dle přenositelnosti

        Fáze Testování

            - Unit test = Dělá se jako první, většinou programátory. Základní ověření kódu a jeho funkčnosti. Testuje se tzv unita, jednota kódu.

            - Module test = Testují programátoři, větší projekty, celé pluginy, projekty.

            - Integrační test = Tvoří testeři nebo programátoři, kód je již napsaný. Ověřujeme jestli moduly pracují správně dohromady.

        - Funkční test - zkoumá se co systém Dělá

            - Smoke test = rychlý jednoduchý test, zjištuje se jestli je vše nainstalováno a Funkční. Neřeší se složitosti.
        
            - Sanity test = cílem je zjistit, zdali funkce fungují podle očekávání

            - Regresní = Provedení funčkních a nefunkčních testů pro zjištění zda dříve vyvinutý a otestovaný software po změně stále funguje

            - Test použitelnosti = Jeho princip spočívá v tom, že tato metoda pozoruje chování samotných uživatelů čímž může odhalit chyby, které zůstali vývojářům skryty

            - Systémový test = z pohledu hiearchie se jedná o nejvyšší stupeň testování (poslední test), provádí vývojový tým. Ověřuje jestli systém funguje tak jak klient chtěl (třeba podle SLA)

            - Akceptační test = Test prováděný zákazníkem, ověřuje jestli je to podle jeho požadavků

        Cloud

            - Multitenancy
                - více nájemníků, jeden systém
            - Pay as you go 
                -x;
            - Up to date 
                -
            - Práce přes Internet

        Typy cloudových uložišť 
            
            - Veřejný cloud
                - Vysoká škálovatelnost