# BPC-IBE-SZZ

Kliknutím **[zde](https://github.com/jedla97/BPC-IBE-SZZ/releases/latest)** se dostanete k nejnovějším verzím otázek.

---

Otázky a odpovědi k státní závěrečné zkoušce (SZZ) oboru Informační bezpečnost na FEKT VUT.

Používáme LaTeX šablonu [FEKT.tex](https://github.com/Czechbol/FEKT.tex) od [Czechbol](https://github.com/Czechbol).

Každá aktualizace spouští automatický build všech předmětových otázek, nejnovější verze je vždy dostupná jako release (od [kamen-u-cesty](https://github.com/kamen-u-cesty)). Aby se tento build zbytečně nepouštěl i ve všech fork repozitářích, je Actions třeba v jejich nastavení vypnout (Settings > Actions > Disable Actions).

---

## Teorie informační bezpečnosti

### BPC-AKR

- [x] Prvočísla – popište způsob generování a uveďte příklad pravděpodobnostního testu a skutečného testu.
- [x] Teorie čísel, algebraické struktury – popište účel a způsob výpočtu Eulerovy funkce. Popište požadavky na grupu a způsob generování grupy pro algoritmy založené na problému DL.
- [x] Modulární aritmetika – popište algoritmus Square and Multiply a Čínskou větu o zbytcích.
- [x] Symetrická kryptografie – proudové šifry, synchronní a asynchronní proudové šifry.
- [x] Blokové šifry - Product Ciphers, konstrukce, Feistelova síť, DES, AES, základní módy blokových šifer.
- [x] Asymetrické algoritmy - RSA, Diffie-Hellman, ECDH systém a jejich využití pro digitální podpis.
- [x] Hašovací funkce - vlastnosti, princip, použití, kolize, odolnost proti kolizím, příklady.
- [x] PKI - certifikát X.509 struktura, certifikační autorita základní části, časová razítka, autorita časových razítek.
- [x] Generování náhodných čísel - kryptografické generátory, požadavky, použití, princip, testování generátorů.
- [x] Bezpečnostní architektura RM OSI - služby bezpečnosti, mechanizmy bezpečnosti, útoky na bezpečnost, příklady implementace bezpečnostních mechanizmů v jednotlivých vrstvách. 

### BPC-IC2

- [x] Definujte a vysvětlete základní pojmy (aktiva, hrozba, ochrana, bezpečnost, zranitelnost, riziko, incident a dopad).
- [x] Bezpečná konfigurace přepínače a směrovače (základní postupy konfigurace, bezpečnostní funkce, útoky, Port Security, port Fast, hardening).
- [x] Problematika logování, hlavní cíle a rozdělení (definice logu, základní kategorie, formát, obsah logu, struktura záznamu, ochrana logů).
- [x] Definice operací nutných k aplikaci automatické analýzy logů (blokové schéma včetně popisu funkce jednotlivých bloků). Jakým způsobem je realizován blok korelace při detekci známých a neznámých událostí.
- [x] Detekce nepříznivých událostí na základě signatur a anomálií, systémy IDS/IPS (vzájemný vztah, efektivita a ladění, umístění, základní architektura, zástupci, referenční model).
- [ ] Dělení penetračních testů (dle znalosti, způsobu realizace a cíle), metodologie testování (pět kroků testování). Penetrační testování webových aplikací (OWASP, průzkum prostředí, závěreční report).
- [x] DoS/DDoS útoky (princip, rozdělení, popis základních útoků, SYN Flood, HTTP Flood, DNS reflection, Ping of Death, Slowloris). Zátěžové testování (typy testů, nejznámější nástroje).
- [x] Netechnické typy útoků, sociální inženýrství, phising (používané techniky), útoky MitM (ARP spoofing, DNS spoofing, SSL strip, SSL sniff).
- [x] Protokoly IPsec a TLS (princip, umístění TCP/IP, průběh komunikace, autentizace, utajení a integrita dat).
- [x] Zabezpečení 802.11 (WPA2, používaná kryptografická primitiva, klíčové hospodářství, popis 4Way Handshake, testování bezpečnosti).

### BPC-KOM

- [x] Technika sítí a protokolů - komunikační modely, způsob přenosu informace, základní struktura sítí, typy sítí, architektura komunikace systémů.
- [x] Základní popis referenčního modelu ISO/OSI a srovnání s TCP/IP.
- [x] Základní popis síťového modelu TCP/IP a srovnání s ISO/OSI.
- [x] Principy komunikačních technik - vícenásobné využití cest, zajištění obousměrné komunikace.
- [x] Fyzická vrstva přenosových systémů - přenosová média, analogové a digitální modulace, klíčovací techniky, princip digitalizace řečového signálu.
- [x] Spojová vrstva přenosových systémů - podvrstvy, rámce spojové vrstvy, adresace, metody zajištění spolehlivého přenosu.
- [x] Síťová vrstva přenosových systémů - spínání paketů, služby síťové vrstvy, IPv4 adresy, techniky směrování, IPv4 datagram.
- [x] Síťová vrstva přenosových systémů - tunelování paketů, ARP, NAT, ICMPv4, IPv6.
- [x] Transportní vrstva přenosových systémů - služby transportní vrstvy, UDP protokol, TCP protokol.
- [x] Aplikační vrstva přenosových systémů - DHCP protokol, DNS systém, přenos souborů, webové protokoly, elektronická pošta.

### BPC-TIN

- [x] Správa paměti, statické přidělování paměti, dynamické pěidelování paměti, garbage collector, reprezentace informace v paměti
- [x] Jazyk UML a objektově orientovaný návrh - dědicnost, generalizace, asociace 1:n, n:1, n:n, agregace a kompozice.
- [x] Třídy složitosti pamětové a časové. Notace Theta. Notace Omega. Notace velké-O. Asymptotický popis složitosti algoritmu. Posouzení složitosti algoritmů. 
- [x] Posouzení složitosti algoritmu vyhledávání. Srovnání lineárních a nelineárních struktur. Vztah časové a paměťové složitosti. 
- [x] Abstraktní datový typ (ADT). ADT lineární seznam. ADT cyklický seznam. Operace vkládání, mazání a vyhledávání prvku v ADT lineární seznam. ADT zásobník, ADT fronta.
- [x] Abstraktní datový typ strom. Abstraktní datový typ binární strom. Úplný binární strom. Abstraktní datový typ binární vyhledávací strom (operace vložení, odstranení, smazání uzlu stromu). Průchody stromy in-order, pre-order, post-order.
- [x] Problematika nevyvážených stromů. Vyvažování stromů AVL - rotace: jednoduchá levá, jednoduchá pravá, dvojitá levá, dvojitá pravá. Red-Black stromy. 
- [x] Posouzení z pohledu časové a paměťové složitosti. ADT hashovací tabulky. Rešení kolizí hashovacích tabulek. Srovnání výkonnosti binárních vyhledávacích stromu a hashovacích tabulek.
- [x] Jednoduché a pokročilejší řadící techniky a jejich srovnání. Stabilita řadícího algoritmu. Bubble sort. Insertion sort. Selection sort. Shell sort. Merge sort. Heap sort. Quick sort.
- [x] Grafy, formální definice. Vyhledávání v grafech. Algoritmus BFS (prohledávání do šírky). Reprezentace BFS v paměti. Algoritmus DFS (prohledávání do hloubky). 
- [x] Omezené prohledávání do hloubky (DLS). Iterativní prohledávání do šířky (IDLS), Dijkstrův algoritmus (Uniform Cost Search), A*
- [x] Evlouční algoritmy. Genetické algoritmy, genetické programování. Pojmy populace, mutace, krížení, chromozom. Princip evolučních algoritmů.
- [x] Parallel computing and architectures, processes, threads and their synchroization. Dead lock.


## Informační bezpečnost v praxi: Informatika

### BPC-DAK

- [ ] Teorie informace: Statické a dynamické vlastnosti zdroje informace, zdrojové kódování, statické a dynamické vlastnosti přizpůsobeného zdroje.
- [ ] Systémy přenosu informace: Kapacita diskrétního kanálu bez a s poruchami, kapacita spojitého kanálu, Shannonův vztah a jeho popis, kapacita kanálu a přenosová rychlost, výkon a výkonová spektrální hustota, jednotky.
- [ ] Přenos dat: Základní pojmy. Modulační a přenosová rychlost, jednotky. Provozní charakteristiky datových spojů. Systém přenosu dat: Struktura, rozhraní, normalizace.
- [ ] Kódování snižující nadbytečnost: Prefixové kódy. Kraftova nerovnost-McMillanova věta. Huffmanův kód. Příklady kódů pro snížení nadbytečnosti. Bezztrátová a ztrátová komprese dat.
- [ ] Protichybové kódování: Vznik chyby a její modelování. Druhy chyb. Základní koncepce protichybového kódování. Třídění protichybových kódů. Hammingova vzdálenost a váha. Zabezpečovací schopnost kódu.
- [ ] Protichybové blokové kódy: Třídění blokových kódů, způsoby zadávání blokových kódů, zabezpečení, detekce a oprava chyb. Příklady protichybových blokových kódů. Cyklické kódy: Zadávání, zabezpečení, detekce a oprava chyb. Příklady protichybových cyklických kódů.
- [ ] Stromové kódy: Třídění, popis stromového kódu grafy a diagramy, Konvoluční kódy, popis, způsoby zadávání konvolučních kódů, dekódování konvolučních kódů, Viterbiho algoritmus. Turbo kódy: Metody modifikace kódů, sériově a paralelně zřetězené kódy, prokládání, násobné kódy a turbo kódy, dekódování turbo kódů.
- [ ] Protichybové kódové systémy (PKS): Třídění, popis PKS s FEC a PKS s ARQ, příklady ARQ metod a jejich srovnání. Propustnost a efektivní informační rychlost.
- [ ] Modemy: Struktura a vysvětlení významu jednotlivých bloků, Měniče v základním a v přeloženém pásmu, Linkové kódy, Klíčování, Modulace s jednou a více nosnými, protichybové zabezpečení modulačního procesu, skrambler, ekvalizér, duplexní provoz.
- [ ] Základy šifrování: Popis kryptografického systému, pravidla kryptografie, základní šifrovací postupy, symetrické a asymetrické kryptosystémy, příklady.

### BPC-HWS

- [ ] Dílčí kroky procesu směrování uvnitř směrovače.
- [ ] Směrovací protokol Distance-Vector, směrovací protokol RIP
- [ ] Směrovací protokoly Link-State, směrovací protokol OSPF.
- [ ] Základní funkční bloky mechanismů pro zajištění kvality služeb.
- [ ] Způsob využití základních typů rámců technologie WiFi. Účel a dílčí kroky jednotlivých fází připojení klienta do sítě WLAN (skenování, autentizace, asociace, stav připojení, odpojení, roaming).
- [ ] Deterministické a náhodné přístupové metody využívané v sítích WLAN.
- [ ] Vlastnosti základních algoritmů výběru buněk (PIM, iRRM, SLIP, DRRM).
- [ ] Vlastnosti a struktura přepínače se sdíleným mediem a se sdílenou pamětí.
- [ ] Struktura spojovacích polí s prostorovým dělením kanálu (křížový přepínač, plně propojená struktura, Banyan).
- [ ] Výhody a nevýhody architektur pro přepojovací uzly využívající: vstupní vyrovnávací paměti, výstupní vyrovnávací paměti, sdílenou paměť, a virtuální výstupní fronty. 

### BPC-MDS

- [ ] Jaké jsou základní měřitelné parametry kvality služeb v multimediálních sítích? Popište, jakým způsobem se zajišťuje kvalita služeb prostřednictvím integrovaných (Intserv) a diferencovaných (Diffserv) služeb, diskutujte hlavní rozdíly. K čemu slouží QoE?
- [ ] Popište výhody a nevýhody multicastového přenosu. Popište modely mulsticastu ASM, SSM, jejich rozdíly a funkci protokolu protokol IGMP.
- [ ] Popište protokoly RTP a RTCP – k čemu protokoly slouží, jaké informace poskytují, kdy a proč se používají.
- [ ] Popište protokol SDP – k čemu protokol slouží, jaké informace poskytuje, kdy a proč se používá.
- [ ] Popište rozdíly mezi progresivním stahováním, streamováním a adaptivním streamováním. Popište standardy MPEG DASH, HLS a RTSP
- [ ] Popište komunikaci prostřednictvím rodiny protokolů H.323, vyjmenujte čtyři základní prvky sítě H.323, popište jejich funkce. Jaké protokoly se v rámci komunikace H.323 používají pro signalizaci hovoru, kompresi AV dat a přenos AV dat.
- [ ] Popište komunikaci prostřednictvím protokolu SIP, žádosti a odpovědi definované v doporučení RFC3261, prvky sítě SIP a základní schéma spojení bod-bod, bod-proxy server-bod.
- [ ] Webinar, Webcast, Videokonference, teleprezence – popište základní rozdíly (výhody/nevýhody), využívané protokoly, standardní i proprietární).
- [ ] Komprese statických obrazových dat dle standardů JPEG - základní schéma, popis jednotlivých bloků - jejich funkce.
- [ ] Komprese pohyblivých obrazových dat dle standardů MPEG - základní schéma, popis jednotlivých bloků - jejich funkce, oblast použití kodeků. 

### BPC-SOS

- [x] Struktura OS – systémové jádro, monilitický systém, architektura klient-server, virtuální stroje
- [x] Procesy – uživatelský kontext, kontext jádra, vlákna
- [x] Činnost procesů – stavy činnosti, rozšířený stavový model běhu procesů
- [x] Plánování procesů – okamžiky rozhodnutí, plánovací algoritmy, systém priorit
- [x] Synchronizace procesů – souběh, vzájemné vyloučení, uvíznutí procesů
- [x] Správa paměti – vyměňování procesů, virtuální paměť pomocí stránkování a segmentace
- [x] Využití paměti – přidělování paměti procesům, algoritmy přesunu stránek do odkládacího prostoru
- [x] Souborové systémy – organizace dat na paměťovém úložišti, metody ukládání datových bloků
- [x] Konzistence dat – data a metadata, žurnálovací souborové systémy
- [x] Síťová část OS – stavy soketů při komunikaci, síťová systémová volání, procesy síťových služeb

### BPC-ZSY

- [x] Systémy PZS (Architektura PZS. Prvky PZS. Typy systémů PZS podle komunikace. Dvojitě vyvážená smyčka.)
- [x] Předmětové a překážkové detektory PZS (Typy detektorů z hlediska vícevrstvé ochrany. Typy předmětových detektorů – účel a jejich fyzikální princip. Typy překážkových detektorů – účel a jejich fyzikální princip. V rámci odpovědi vysvětlit i fungování piezoelektrického snímače, akcelerometru a tenzometru.)
- [x] Objemové a hraniční detektory PZS (Typy objemových detektorů – účel a jejich fyzikální princip. Typy hraničních detektorů – účel a jejich fyzikální princip. V rámci odpovědi vysvětlit i fungování pyroelektrického snímače.)
- [x] Dohledové videosystémy (Účel. Základní prvky. Schéma hybridního a digitálního systému. Architektura kamery. Kalkulace záběru. Techniky zpracování signálu - integrace snímků, BLC, WDR a HLC).
- [x] Systémy EPS a hlásiče EPS (Účel. Architektura. Základní prvky. Schéma a princip fungování smyčkového a sběrnicového systému. Bodové hlásiče a jejich fyzikální principy. Lineární hlásiče a jejich fyzikální principy. Prostorové hlásiče a jejich fyzikální principy.)
- [x] Systémy EKV (Účel, prvky a architektura systému EKV. Typy autentizace – princip a vlastnosti. Karty s magnetickým páskem – princip a vlastnosti. Bezkontaktní karty podle ISO 14443 – princip a vlastnosti.)
- [x] Biometrické systémy EKV (Architektura a správa biometrického systému EKV. Autentizace otisky prstů, cévním řečištěm prstu a dlaně, obličejem a duhovkou – principy a vlastnosti.)
- [x] Systémy na ochranu zboží (Účel a klasifikace. Kabelové systémy – princip a vlastnosti. AM systémy – princip a vlastnosti. RF systémy – princip a vlastnosti.)
- [x] Elektronické platební systémy (Účel. Typy a jejich charakteristika. Vysvětlit protokol TLS. Vysvětlit nespřažený platební protokol.) 
- [x] Ochrany digitálních děl (Účel a klasifikace ochran.Vzdálené DRM ochrany – typy, principy a vlastnosti.Lokální DRM ochrany – typy, principy a vlastnosti.)


## Informační bezpečnost v praxi: Právo

### BPC-KKR

- [ ] Vzájemný vztah pojmů kyberkriminalita, kybernetická bezpečnost a kybernetická obrana.
- [ ] Prameny práva (národní, evropské i mezinárodní) obsahují hmotněprávní a procesněprávní úpravy kyberkriminality.
- [ ] Úmluva o kyberkriminalitě a směrnice o útocích na informační systémy (obsah úpravy a vztah k české právní úpravě)
- [ ] Postupy a kriteria při kvalifikaci trestné činnosti (vč. problematiky kvalifikované a privilegované skutkové podstaty)
- [ ] Kategorizace kyberkriminality (včetně příkladů trestné činnosti v jednotlivých kategoriích).
- [ ] Kyberkriminalita v užším smyslu slova (příklady trestné činnosti a kvalifikace dle zvláštní části TZ).
- [ ] Elektronické důkazy a jejich specifika v trestním řízení.
- [ ] Procesní nástroje pro zajišťování elektronických důkazů.
- [ ] Specializované útvary OČTŘ ve vztahu ke kyberkriminalitě.
- [ ] Mezinárodní spolupráce v oblasti kyberkriminality.

### BPC-PNA

- [ ] Formální prameny práva
- [ ] Typologie čaských právních předpisů
- [ ] Právotvorný proces
- [ ] Pojem a struktura právní normy
- [ ] Interpretační metody
- [ ] Subjekty práv a povinností
- [ ] Právní vztahy
- [ ] Proces autoritativní aplikace práva
- [ ] Subjektivní a objektivní odpovědnost
- [ ] Formy zavinění

### BPC-SPR

- [x] Software jako předmět právní ochrany - srovnání ochrany autorskoprávní a patentové ochrany
- [x] Autorství software - autor, spoluautor, kolektivní dílo, souborné dílo, odvozené dílo, otázka autorství umělé inteligence
- [x] Osobnostní a majetková práva autora software - obsah, doba trvání, vyčerpání práv
- [x] Omezení rozsahu práv autora k software - dekompilace, reverzní inženýrství a další
- [x] Ochrana neliterárních složek software - ochrana funkcionality; ochrana datových, grafických uživatelských a aplikačních programových rozhraní)
- [x] Software jako zaměstnanecké dílo, školní dílo, kolektivní dílo a dílo na objednávku
- [x] Právní ochrana databází - pojem, způsoby ochrany, obsah a rozdíly
- [x] Smlouvy a software - licenční smlouva, smlouva o dílo a SLA - pojem, strany, obsah, forma a proces uzavírání
- [x] Veřejné licence a software, free a open source software
- [x] Autorskoprávní a trestněprávní prostředky ochrany software - účel, nároky, tresty a realizace

### BPC-UP2A

- [x] Veřejnoprávní ochrana autorského práva
- [x] Elektronický podpis a elektronická pečeť – právní úprava a druhy
- [x] Datové schránky – právní úprava a praxe používání
- [x] Provozní a lokalizační údaje a jejich využití v trestním řízení
- [x] Právní úprava kybernetické bezpečnosti v CR - základní principy
- [x] Ochrana osobních údajů – vymezení osob a základní principy zpracování osobních údajů
- [x] Povinnosti správce a zpracovatele osobních údajů
- [x] Práva subjektu údajů ve vztahu ke správci a zpracovateli
- [x] Informace veřejného sektoru – pojem, česká a evropská právní úprava
- [x] Otevřená data – pojem a právní úprava
