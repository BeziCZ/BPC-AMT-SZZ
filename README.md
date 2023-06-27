# Státnicové otázky BPC-AMT
Tento repozitář a jeho funkce je založena na repozitáři s otázkami ke státní závěrečné zkoušce od oboru Informační bezpečnost na FEKT VUT. Jejich původní repozitář najdete zde: [MPC-IBE-SZZ](https://github.com/VUT-FEKT-IBE/MPC-IBE-SZZ).

Státnicové předměty pro rok 2022/23 jsou následující

- [BPC-MVE](#BPC-MVE) Měření v elektrotechnice
- [BPC-LOS](#BPC-LOS) Logické obvody a systémy
- [BPC-MIC](#BPC-MIC) Mikrokontroléry a vestavěné systémy
- [BPC-PPA](#BPC-PPA) Prostředky průmyslové automatizace
- [BPC-RR1](#BPC-RR1) Regulace a řízení 1
- [BPC-RR2](#BPC-RR2) Regulace a řízení 2
- [BPC-SNI](#BPC-SNI) Snímače
- [BPC-UIN](#BPC-UIN) Umělá inteligence
- [BPC-PRP](#BPC-PRP) Robotika a počítačové vidění

## Seznam předmětů a jejich otázek

### BPC-MVE

- [x] Chyby měření (rozdělení, výpočet, chyby metody, chyby měřicích přístrojů). Nejistoty měření - typy, výpočet nejistoty A, B, kombinovaná a rozšířená nejistota. Nejistoty nepřímých měření.
- [x] Analogově-číslicové převodníky pro měřicí techniku – rozdělení, princip základní typů AD převodníků, vlastnosti, použití. 
- [x] Měření napětí a proudu. Změna rozsahů voltmetrů a ampérmetrů. Rušení u měřicích přístrojů.
- [x] Měření výkonu v jednofázové a třífázové soustavě. Wattmetry – princip, typy, vlastnosti.
- [x] Číslicové osciloskopy – princip, vlastnosti, jejich příslušenství.
- [x] Měření frekvence, časového intervalu a fáze. Univerzální čítač – princip, vlastnosti.
- [x] Měření pasivních el. veličin (R,L,C,Z) – metody s přímým údajem, principy mostových metod.
- [x] Měření magnetických veličin. Snímače magnetických veličin (princip základních magnetických převodníků – měřicí cívka, Hallova sonda). Měření parametrů feromagnetik (hysterezní smyčka, ztráty) pomocí osciloskopu.

### BPC-LOS

- [x] Logická funkce, její vyjádření pomocí tabulky, algebraického výrazu a map. Úplný součtový a součinový tvar algebraického vyjádření logické funkce. Metody a principy minimalizace logických funkcí. Úprava logické funkce pro realizaci pomocí členů NAND a NOR.
- [x] Kombinační logické obvody: binární dekodér, multiplexor, demultiplexor, kodér, prioritní kodér, číslicový komparátor, binární sčítačka a odčítačka. Druhý doplněk. Logické obvody s třístavovým výstupem a s otevřeným kolektorem. Připojování zařízení na sběrnici.
- [x] Přechodné děje v kombinačních logických obvodech, hazardní stavy (souběhový, dynamický a statický hazard), metody detekce a řešení statického hazardu ve dvoustupňové struktuře NAND-NAND, konsensus, řešení hazardu pomocí sekvenčních obvodů.
- [x] Rozdíl mezi kombinačním a sekvenčním logickým obvodem. Klopné obvody: RS, D, JK, T, hladinové, hranové a master-slave, pravdivostní tabulka, pojem metastabilita v sekvenčních logických obvodech.
- [x] Sekvenční logické obvody: posuvný registr, posuvné registry se zpětnou vazbou (kruhový čítač, Johnsonův čítač, lineární čítač - LFSR), asynchronní a synchronní čítače, popis jejich funkce pomocí jazyka HDL. Vysvětlete pojmy HDL jazyka: souběžný a sekvenční příkaz, okamžité a odložené přiřazení.
- [x] Konečné stavové automaty: Obecný (Huffmanův) model sekvenčního logického obvodu, přechodová funkce, výstupní funkce, budicí funkce. Mealyho, Mooreho a autonomní automat. Popis konečného automatu pomocí stavového diagramu, tabulky přechodů a tabulky výstupů. Návrhová tabulka (budicí funkce KO).

### BPC-MIC

- [x] Von Neumannovy principy, blokové schéma Von Neumannova počítače. Rozdíl mezi Von Neumannovou, harvardskou a modifikovanou harvardskou architekturou.
Procesory CISC a RISC. Rozdíl mezi obvodovým a mikroprogramovým řadičem. Řetězové zpracování instrukcí (pipelining), skokový a datový konflikt.
Jak se liší a pro jaké typy úloh je určen mikroprocesor pro všeobecné použití, mikrokontrolér, signálový procesor a signálový kontrolér (DSC), SoC (System on a Chip), ASIC.
- [x] Rozdíl mezi izolovanými a paměťově mapovanými periferiemi. Způsoby obsluhy V/V: aktivní čekání, přerušení, DMA.
Přerušení: řadič přerušení, činnost procesoru při zahájení obsluhy přerušení a návratu z přerušení, tabulka vektorů přerušení. Asynchronní a synchronní přerušení. Maskovatelné, nemaskovatelné a pseudomaskovatelné přerušení. Vnořené přerušení. RESET, činnost procesoru po RESETu.
- [x] Princip a vlastnosti pamětí ROM, EEPROM, FLASH. Rozdíl mezi paměťmi NOR FLASH a NAND FLASH. Princip pamětí MRAM a FeRAM.
- [x]  Princip a vlastnosti statických pamětí RAM (SRAM) a dynamických pamětí RAM (DRAM), synchronní paměti DRAM (SDRAM).
Připojování paralelních pamětí SRAM, FLASH ke sběrnicím mikroprocesoru. Adresový dekodér.
Hierarchie paměti, paměti cache, specializované paměti cache.
- [x] Pojem logická a fyzická adresa, ochrana paměti, memory management unit (MMU). Stránkování (princip, transformace logické adresy na fyzickou, stránkovací tabulka). Virtuální adresový prostor. Zrychlení překladu adres pomocí Translation Look-aside Buffer (TLB).

### BPC-PPA

- [x] Úrovně řízení výroby a jejich funkce. Zařazení komponent do jednotlivých vrstev a možnosti jejich propojení. Způsoby řízení výroby (centralizované a distribuované). Toky dat (informací) v systému a jejich popis. Vlastnosti a možnosti nadřazených výrobních systémů (MES, ERP).
- [x] Standardní rozhraní průmyslových signálů - typy, obvodové provedení, vlastnosti a použití. Logika digitálních signálů. Zpracování analogové veličiny. Standardizace a destandardizace. Senzory - popis, typy a jejich použití. Možnosti zapojení snímačů do systému.
- [x] Průmyslové pohony (elektrické, pneumatické) - typy, vlastnosti a způsoby řízení. Zapojení průmyslových pohonů do systému.
- [x] Řídicí členy (PLC, DCS, průmyslová PC, průmyslové regulátory, vestavné systémy, HMI aj.) – vlastnosti a použití. Typy provedení komponentů. Možnosti jejich programování (parametrizace, reprezentace veličin, struktura projektu, struktura programu, stavový automat). Postup programování technologických procesů.
- [x] Průmyslové komunikační sítě (sběrnice a protokoly) – dělení, vlastnosti a použití. Referenční model ISO/OSI. Způsoby komunikace. Průmyslový Ethernet. Bezdrátový přenos dat v průmyslovém prostředí.
- [x] Spolehlivost a bezpečnost průmyslových zařízení a systémů. Metody vyhodnocení spolehlivosti. Komponenty a metody zajišťující funkční bezpečnost průmyslových strojů a zařízení. Aspekty kybernetické bezpečnosti. Kybernetické útoky a metody jejich zmírnění.
- [x] Systémy reálného času – vlastnosti a použití v průmyslové automatizaci. Pojmy determinismus, včasnost a jitter. Metody zajištění determinismu.

### BPC-RR1

- [x] Definice ovládání, řízení a regulace (řízení bez a se zpětnou vazbou), výhody a nevýhody. Základní veličiny a přenosy. Rozdělení řízení podle různých kritérií. PID regulátory, základní složky a vlastnosti. Statická analýza zpětnovazebních obvodů. Standardní přenosy ve zpětnovazebním řízení, charakteristický polynom. Věta o počáteční a konečné hodnotě, požadavky na ustálené hodnoty. 
- [x] Standardní struktury regulačních obvodů. Stabilita obvodů se zpětnou vazbou. Frekvenční charakteristiky v komplexní rovině, Nyquistovo kritérium stability, jeho zjednodušená verze a řešení v logaritmických souřadnicích, použití algebraických kritérií.
- [x] Analýza dynamických vlastností zpětnovazebních obvodů. Metoda geometrického místa kořenů. Zásoba stability v amplitudě, ve fázi a v modulu. Integrální kritéria kvality regulace, praktická kritéria.
- [x] Návrh PID regulátorů různými metodami (metoda standardních tvarů frekvenčních charakteristik, metoda optimálního modulu, metoda Zieglera-Nicholse, metoda standardních tvarů charakteristického polynomu, metoda požadovaného rozložení pólů uzavřeného obvodu).
- [x] PSD regulátory, základní složky a vlastnosti. Aproximace vzorkovače s tvarovačem, diskretizace PID regulátoru. Rozvětvené regulační obvody. Obvod s pomocnou regulovanou veličinou, s pomocnou akční veličinou, s měřením poruchy, s modelem regulované soustavy (kompenzace dopravního zpoždění). Vícerozměrové řídicí systémy. 

### BPC-RR2

- [x] Základní nelinearity a popis nelineárních systémů (popis statických a dynamických nelineárních systémů, vliv parazitních nelinearit na průběh regulačního děje).
- [x] Ustálené chování nelineárních dynamických systémů (rovnovážné stavy, mezní cyklus, metoda harmonické rovnováhy, stabilita mezního cyklu).
- [x] Stabilita nelineárních systémů (definice, metody vyšetření, věty o nestabilitě,stabilita uzavřené regulační smyčky).
- [x] Reléová regulace (on-off regulátory, řízení v klouzavém režimu).
- [x] Linearizace nelineárních dynamických systémů (rozvoj do Taylorovy řady, exaktní zpětnovazební linearizace).

### BPC-SNI

- [x] Měření polohy - principy odporové, indukčnostní, kapacitní  
- [x] Měření polohy - principy optické, magnetické, ultrazvukové 
- [x] Měření vibrací, rychlosti, zrychlení, akcelerometry, snímače úhlové rychlosti 
- [x] Tenzometry, snímače síly, hmotnosti, momentu a tlaku 
- [x] Měření průtoku, základní principy objemových, rychlostních a hmotnostních průtokoměrů
- [x] Kontaktní snímače teploty (dilatační, odporové, termoelektrické)
- [x] Měření záření (tepelné a kvantové snímače IR záření, snímače ionizujícího záření)
- [x] Chemické snímače

### BPC-UIN

- [x] Umělá inteligence (UI) - definice, úzká UI, obecná UI, superinteligence, strojové učení.
- [x] Umělé neuronové sítě - paradigmata, perceptron, algoritmus učení Backpropagation, Kohonenova samoorganizační mapa, konvoluční neuronová síť.
- [x] Expertní systémy (ES) - definice, architektura, teoretické zdroje pro realizaci ES, tvorba a ladění báze znalostí, průběh konzultace.
- [x] Počítačové vidění - předzpracování obrazu, segmentace obrazu, popis a klasifikace obrazu. 

### BPC-PRP

- [x] Kinematický model diferenciálně řízeného podvozku mobilního robotu (schéma, veličiny, matematický popis řízení, výhody a nevýhody oproti jiným typům).
- [x] Pohony robotů (přehled, vlastnosti, momentové rovnice, požadavky na robotické aplikace, víceosá NC interpolace, rampy, S-křivka).
- [x] Systém ROS - popis, platformy, komunikace uvnitř systému, node, message, topic, možnosti reálného nasazení
- [x] Zpětnovazební regulace pozice mobilního robotu při sledování trajektorie (nákres, regulační schéma, popis veličin v procesu, popis parazitních vlivů ovlivňujících kvalitu regulace v důsledku implementace do reálného stroje).
