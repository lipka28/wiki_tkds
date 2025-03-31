# Vybavení a nosnost ==todo: rework==

<img src="/assets/sep_line.png"/>

<img src="/assets/Adventure_gear.png"/>

<img src="/assets/sep_line.png"/>

## Nosnost a skladnost

Nosnost postavy udává, kolik výbavy a jiných předmětů může mít postava v jednu chvíli u sebe. Výbava postavy se umisťuje do tak zvaných *Slotů* v *inventáři*.

- **Inventář:** Je abstraktní pojem pro umístění předmětů postavy. V logice hry postava uchovává své předměty různě na svém těle. Například na opasku, v kapsách či přivázané na zádech.
- **Sloty:** Sloty jsou nejen abstrakcí pro váhu předmětu ale i jeho prostorovou náročnost. Pro lepší představu, 1 slot reprezentuje předmět, kterým lze efektivně manipulovat v jedné ruce. 2 sloty pak předmět do dvou ruk a tak dále. Lehké a drobné předměty jsou pak označovány *L*. Do 1 slotu se vejdou *5 lehkých* předmětů. Váha lehkých předmětů se počítá vždy jen za každý celý slot, který dohromady obsadí.
- **Nosnost:** Nosnost postavy odpovídá její dovednosti *Zdatnost*.
- **Překročení nosnosti:** Nosnost postavy lze překročit až na dvojnásobek. Avšak hybnost postavy, která tak učiní, je zredukována na polovinu a obdrží Postih na všechny své hody na Zdatnost a Zručnost, a také všechny ověření dovednosti proti Zdatnosti či Zručnosti přetíženého, probíhají s Bonusem.

## Peníze a bohatství

Ve hře lze rozlišovat libovolné množství měn a platidel. Nejběžnějšími platidly jsou však *Groše*, *Šilinky* a *Mizny*. Groše jsou zlaté mince a hodnotou odpovídají 10-ti šilinkům. Šilinky jsou stříbrné mince a hodnotou odpovídají 10-ti miznám. Mizny jsou pak z mědi.

- **Peníze a skladnost:** I když trochu nereálné, peníze nezabírají v inventářích postav žádné místo. Nosit všechny peníze u sebe se však nedoporučuje. Jelikož by mohli skončit v rukou šikovného bandity či kapsáře. 
- **Prodej předmětů:** Poklady získané na dobrodružství se prodávají za svou plnou cenu (nepoškozené). Běžné předměty se pak prodávají za polovinu. Poškozené běžné předměty jsou neprodejné.
- **Nákup předmětů:** Při tvorbě postavy je níže popsaná výbava dostupná za uváděné ceny. Při hře samotné se však dostupnost i cena předmětů může lišit v závislosti na tom, kde se postavy zrovna nachází.

## Zbroje a štíty

Zbroje zvyšují obranu nositele a tím snižují šanci na jeho zásah. Obrana zbroje nahrazuje přirozenou obranu nositele. Sundávání a oblékání libovolné zbroje trvá *1 scénu*.

- **Přirozená obrana:** Je obranná hodnota založená čistě na schopnostech jedince, bez zbroje či štítu. Přirozená obrana hráčských postav je závislá na jejich povolání.

### Typy zbrojí:

- **Oblečení** - Plní funkci běžného oblečení lze v něm spát.
- **Lehká** - Flexibilní, lze v ní i spát.
- **Střední** - Hlučná (postih na plížení), nedá se v ní spát.
- **Těžká** - Hlučná (postih na plížení), těžká (postih na plavání a šplhání), nedá se v ní spát.
- **Štít** - Poskytuje další bonus do Obrany jedince a lze jej použít jako improvizovanou příruční zbraň. Použití jako zbraň však vyruší bonus k obraně štítu do začátku tvého příštího tahu.

| ZBROJE                          |   TYP   | Obrana | Pož. Zdatnost | Sloty | CENA  |
| :------------------------------ | :-----: | :----: | :-----------: | :---: | :---: |
| Okované či polstrované oblečení |  Lehká  |   11   |       -       |   1   | 10 ši |
| Kožená zbroj                    |  Lehká  |   12   |      11       |   1   | 20 ši |
| Okovaná kožená zbroj            | Střední |   13   |      12       |   2   | 30 ši |
| Šupinová zbroj                  | Střední |   14   |      12       |   2   | 40 ši |
| Šupinová zbroj s kyrysem        |  Těžká  |   15   |      13       |   3   | 80 ši |
| Půl plát s kyrysem              |  Těžká  |   16   |      14       |   3   | 16 gr |
| Plná plátová zbroj              |  Těžká  |   17   |      14       |   4   | 30 gr |
| Štít                            |  Štít   |   +2   |      12       |   2   | 15 ši |

**Pož. Zdatnost:** Potřebná výše *Zdatnosti* pro nošení zbroje.

<img src="/assets/sep_line.png"/>

### Zbroje mimořádné kvality

Magické zbroje či ty vykované extrémně zručnými kováři. Jsou považovány za mimořádné zbroje. Takové zbroje poskytují o 1 bod více obrany, než jejich běžné verze (Platí i pro štíty). 

## Zbraně

Hlavní dělení zraní je podle toho, zda se jedná o zbraně na blízku nebo na dálku. Druhým nejvýznamnějším dělením je způsob jakým je zbraň držena. 

- **Obouruční:** Obouruční zbraně je, pro efektivní využití, třeba držet v obou rukách. Na obouruční zbraně (převážně ty na blízku) může být uvalovány postihy za použití ve stísněných prostorách.
- **Jednoruční:** Jednoruční zbraně lze efektivně používat jen jednou rukou. Lze ji efektivně kombinovat se štítem nebo druhou zbraní. Pokud druhá zbraň není příruční, obě tyto zbraně útočí s *Postihem*.
- **Příruční:** Příruční zbraně lze efektivně používat jednou rukou a lze je kombinovat s jinými jednoručními zbraněmi či štítem. 
- **Přirozená zbraň:** Je speciální kategorie zbraně, která je většinou součástí těla daného stvoření (např. zuby, drápy). Pokud není psáno jinak, přirozenou zbraň nelze považovat za součást předchozích kategorií. 

### Vlastnosti zbraní

Většina zbraní má nějaké speciální vlastnosti či využití. Ve hře se vyskytují následující vlastnosti zbraní:

- **Brutální (Brut):** Každou kostku na které padne 1 při hodu na poškození touhle zbraní. Lze 1x přehodit.
- **Černý prach (ČP):** Zbraň využívá střelný prach a její údržba je tedy složitější. Setká-li se  taková zbraň s vodou (nebo podobným materiálem). Stává se nepoužitelnou dokud nevysušena a očištěna (10 minut) vhodnými nástroji. Na druhou stranu při setkání s plameny může (většinou její munice) explodovat či způsobit jiné zranění.
- **Dlouhá (Dl):** Dosah útoků na blízku stvoření z touto zbraní je delší o 1. Neplatí u stvoření velikosti 1/4 nebo menší.
- **Dostřel X (D X):** Zbraň má dostřel X metrů. Zbraní lze dostřelit i na dvojnásobnou vzdálenost, ale s postihem.
- **Hozená X (H X):** Zbraní jde hodit na vzdálenost X metrů. Při útokům hodem se ověřuje Zdatnost pokud zbraň není také Obratná. Zbraň lze hodit i na vzdálenost O 5 metrů větší avšak s Postihem.
- **Křesadlová zbraň (Kř):** Křesadlové zbraně jsou extrémně smrtelné ale velmi nespolehlivé. Pro zbraně s touhle vlastností platí následující pravidla:
    - S touhle zbraní se na zásah hází s *Postihem*.
    - Přebíjení zbraně vyžaduje 4 akce na místo 1. (Lze kombinovat Akci a obětování hybnosti jako 2 akce v jednom kole)
    - Pokud při hodu na zásah touhle zbraní padne na kostce hodnota 5 nebo níže, zbraň selže a zasekne se. Před dalším použitím musí být vyčištěna vhodnými nástroji.

- **Nabíjecí (N):** Zbraň potřebuje před každým použitím přebít. Zbraň lze přebít použitím Akce nebo veškeré své hybnosti v daném tahu (je-li tvá hybnost aspoň 2).
- **Obratná (Obr):** Při útoku tohle zbraní si útočník může vybrat zda chce k ověření na zásah použít Zdatnost nebo Zručnost.
- **Průrazná (P):** Poskytuje bonus k zásahu proti nepřátelům ve zbroji nebo se štítem. Alternativně poskytuje ten samý bonus proti všem monstrům jejichž Obrana je 14 nebo více.
- **Rozmach (Roz):** Při úspěšném zabití touhle zbraní. Lze útok 1x opakovat do dalšího cíle v dosahu. Nový cíl však nesmí být více jak 1 metr vzdálený od zabitého.
- **Speciální (Sp):** Zbraň má unikátní vlastnost. Podívej se do popisku zbraně pro více informací.
- **Verzatilní (V):** Zbraň se dá efektivně použít jako jednoruční a i jako obouruční. V případě obouručního použití zvedni kostku poškození o 1 stupeň (např. 1k6 -> 1k8).

### Zbraně na blízku

| Název             | Cena  | Sloty | Držení     | Poškození | Požadavky   | Vlastnosti  |
| ----------------- | ----- | ----- | ---------- | --------- | ----------- | ----------- |
| Hůl               | 1 mi  | 2     | Obouruční  | 1k4       | -           | Obr, Sp     |
| Krátké kopí       | 1 ši  | L     | Jednoruční | 1k4       | -           | H 10        |
| Nůž               | 1 ši  | L     | Příruční   | 1k4       | -           | H 5, Obr    |
| Sekyrka           | 1 ši  | L     | Příruční   | 1k4       | -           | H 5         |
| Boxer             | 2 ši  | L     | Příruční   | 1k4       | -           | Obr         |
| Kopí              | 2 ši  | 1     | Jednoruční | 1k4       | -           | Dl, H 5, V  |
| Palice            | 3 ši  | 1     | Příruční   | 1k6       | -           | -           |
| Bič               | 5 ši  | 1     | Příruční   | 1k4       | Zručnost 12 | Dl, Obr, Sp |
| Palcát            | 5 ši  | 1     | Jednoruční | 1k6       | -           | V           |
| Main-gauche       | 6 ši  | 1     | Příruční   | 1k4       | Zručnost 12 | Obr, Sp     |
| Krátký meč        | 10 ši | 1     | Příruční   | 1k6       | -           | Obr         |
| Píka              | 10 ši | 2     | Obouruční  | 1k8       | Zdatnost 12 | Dl          |
| Řemdich           | 15 ši | 1     | Jednoruční | 1k6       | Zdatnost 12 | Brut, P     |
| Zahnutý meč       | 15 ši | 1     | Jednoruční | 1k6       | Zručnost 12 | Obr, V      |
| Rapír             | 18 ši | 1     | Jednoruční | 1k8       | Zručnost 13 | Obr         |
| Dlouhý meč        | 20 ši | 2     | Jednoruční | 1k8       | Zdatnost 12 | V           |
| Válečná sekyra    | 30 ši | 2     | Jednoruční | 1k8       | Zdatnost 13 | Roz, V      |
| Válečné kladivo   | 30 ši | 2     | Jednoruční | 1k8       | Zdatnost 13 | Brut, P, V  |
| Obouruční kladivo | 10 gr | 3     | Obouruční  | 1k12      | Zdatnost 14 | Brut, P     |
| Obouruční meč     | 10 gr | 3     | Obouruční  | 2k6       | Zdatnost 13 | -           |
| Obouruční sekera  | 10 gr | 3     | Obouruční  | 1k12      | Zdatnost 13 | Roz         |

### Zbraně na dálku

| Název           | Cena  | Sloty | Držení     | Poškození | Požadavky                 | Vlastnosti            |
| --------------- | ----- | ----- | ---------- | --------- | ------------------------- | --------------------- |
| Prak            | 5 mi  | 1     | Jednoruční | 1k4       | -                         | D 15, Sp              |
| Krátký luk      | 10 ši | 1     | Obouruční  | 1k6       | Zručnost 12               | D 20                  |
| Dalekonosný luk | 15 ši | 2     | Obouruční  | 1k8       | Zdatnost 12 a Zručnost 12 | D 60, Sp              |
| Granát          | 20 ši | L     | Jednoruční | Speciální | -                         | ČP, H 10, Sp          |
| Příruční kuše   | 25 ši | 1     | Příruční   | 1k6       | Zručnost 11               | D 10, N               |
| Kuše            | 30 ši | 2     | Obouruční  | 1k8       | -                         | D 20, N               |
| Bambitka        | 50 ši | 1     | Příruční   | 2k6       | Zručnost 11               | Brut, ČP, D 5, Kř, P  |
| Těžká kuše      | 60 ši | 2     | Obouruční  | 1k10      | Zdatnost 12               | Brut, D 30, N, P      |
| Houfnice        | 10 gr | 2     | Obouruční  | Speciální | Zručnost 12               | Brut, ČP, Kř, (P), Sp |
| Mušketa         | 12 gr | 2     | Obouruční  | 2k6       | Zručnost 12               | Brut, ČP, D 20, Kř, P |

### Munice

Používání většiny střelných zbraní vyžaduje specifickou munici. Munici lze koupit včetně kontejneru, který zabírá 1 slot v inventáři, a nebo po kusech pro doplnění chybějící munice. 

| Název                              | Použití |   Používané pro    | Sloty | Cena (Cena za 1 ks) |
| :--------------------------------- | :-----: | :----------------: | :---: | :-----------------: |
| Kazeta šipek do kuše               |   20    |        Kuše        |   1   |     2 ši (1 mi)     |
| Roh broků a černého prachu         |    5    |      Houfnice      |   1   |    10 ši (2 ši)     |
| Toulec s šípy do luku              |   20    |        Luky        |   1   |     2 ši (1 mi)     |
| Váček kulek a roh s černým prachem |   10    | Bambitky a muškety |   1   |    20 ši (2 ši)     |

**Nesplnění požadavků u zbraní:** Pokud postava nesplňuje požadavky zbraně, je zbraň v jejích rukou považována za improvizovanou zbraň působící 1k6 poškození (pokud poškození zbraně samotné není nižší). Navíc nemůže využívat vlastností dané zbraně.

#### Popisky a speciální schopnosti

**Bambitka:** Malá jednoraná palná zbraň s dřevěnou rukojetí a ocelovou hlavní, často s mosaznými nebo železnými prvky a křesadlovým mechanizmem. 

**Bič:** Dlouhý pramen spletený z kožených řemenů nebo surové kůže, zakončený někdy olověnými či ocelovými kuličkami. Rukojeť bývá dřevěná a ovinutá kůží. 

- *Speciální:* Pokud při útoku touto zbraní byla použita Zručnost a výsledek hodu na zásah překonal jak obranu tak Zručnost soupeře. Může si útoční vybrat, že způsobí jen poloviční poškození a zachytí část těla soupeře.

**Boxer:** Kovový nástavec na prsty, vyrobený z bronzu, železa nebo oceli.

**Dalekonosný luk:** Konstrukce z tisu, jilmu nebo kompozitních materiálů kombinujících dřevo, rohovinu a šlachy. Tětiva je spletená z konopí nebo zvířecích šlach.

- *Speciální:* Vzhledem ke své velikost, je dalekonosný luk celkem problematický pro střelbu na blízké vzdálenosti. Na nepřátele do 5-ti metrů se útočí s postihem.

**Dlouhý meč:** Ocelová dvoubřitá čepel, rukojeť potažená kůží nebo drátěným opletem, zakončená kovovou hlavicí.

**Granát:** Kovová nádoba naplněná střelným prachem a střepinami, uzavřená doutnákem. 

- *Speciální:* Použití této zbraně vyžaduje oheň pro zapálení doutnáku. Při útoku touhle zbraní se neháže na zásah. Na místo toho si útočník vybere místo v dosahu. Následuje hod štěstí útočníka. Při úspěchu granát exploduje při dopadu, v opačném případě se odkutálí *1k4* metry náhodným směrem (nebo dle povrchu) a až pak exploduje. Výbuch granátu udělí *1k6* poškození všem v 5-ti metrové oblasti do které dopadl (centrované na granátu). Všichni zasažení musí také uspět v hodu štěstí jinak obdrží extra *1k6* poškození.

**Houfnice:** Krátká, masivní bronzová nebo železná rozevřená hlaveň zasazená do dřevěné lafety. 

- *Speciální:* Při výstřelu z této zbraně vyber prostor o velikosti 5 metrů, který není od tebe vzdálen více jak 1 metr a hoď si na zásah (čistě pro určení zaseknutí zbraně). Všechny subjekty v této oblasti obdrží *1k6* poškození a musí podstoupit hod štěstí. Pokud neuspějí obdrží extra 1k6 poškození. Alternativně lze touhle zbraní zaútočit na 1 cíl do vzdálenosti 2 metry. Zbraň pak efektivně funguje jako mušketa, včetně jejích vlastností (mimo dostřelu).

**Hůl:** Pevný kus jasanového, dubového nebo mahagonového dřeva, někdy s kovovými okovy na koncích. 

- *Speciální 1:* Pokud při útoku touto zbraní byla použita Zručnost a výsledek hodu na zásah překonal jak obranu tak Zručnost soupeře. Může si útoční vybrat, že způsobí jen poloviční poškození a shodí soupeře na zem.
- *Speciální 2:* Pokud při útoku touto zbraní byla použita Zdatnost a výsledek hodu na zásah překonal jak obranu tak Zdatnost soupeře. Může si útoční vybrat, že způsobí jen poloviční poškození a odstrčí nepřítele o 2 metry libovolným směrem.

**Kopí:** Dřevěné ratiště (dub, jasan) zakončené ocelovým nebo železným hrotem, někdy s háčky nebo výčnělky.

**Krátké kopí:** Lehčí a kompaktnější verze kopí s kovaným hrotem z kalené oceli.

**Krátký luk:** Menší než dalekonosný luk, vyrobený z břízy či jasanu, s rohovými výztuhami.

**Krátký meč:** Středně dlouhá čepel z kvalitní oceli, rukojeť potažená kůží nebo látkou, jednoduchá kovová záštita.

**Kuše:** Tělo z dubového či ořechového dřeva s ocelovým lučištěm a mechanickým spoušťovým mechanismem.

**Main-gauche:** Krátká dýka s pevnou kovovou záštitou, čepel z vyleštěné oceli, rukojeť ze dřeva nebo rohoviny.

- *Speciální:* Používání této zbraně zvedá obranu proti útokům na blízku nositele o 1 (Nezávisle na tom, zda je použita při boji dvěma zbraněmi.) 

**Mušketa:** Dlouhá ocelová hlaveň zasazená do pažby z třešňového nebo ořechového dřeva. Mechanismus bývá křesadlový nebo doutnákový.

**Nůž:** Krátká čepel z tvrzené oceli, rukojeť z rohoviny, dřeva nebo kosti. Některé varianty mají zoubkované ostří.

**Obouruční kladivo:** Masivní železná hlavice upevněná na dlouhé rukojeti z tvrdého dřeva, často omotané koženými pruhy.

**Obouruční meč:** Těžká a dlouhá ocelová čepel, často s hlubokou drážkou. Rukojeť s dřevěným jádrem potaženým kůží.

**Obouruční sekera:** Dvoubřitá sekera s těžkou ocelovou hlavou a ratištěm z tvrdého dřeva vyztuženého kovovými objímkami.

**Palcát:** Železná nebo bronzová hlavice s výstupky nebo hroty, upevněná na dřevěné nebo celokovové rukojeti.

**Palice:** Těžká dřevěná či kovová zbraň, často s železnými obručemi nebo výstupky.

**Píka:** Velmi dlouhá dřevěná ratiště s ocelovým hrotem, někdy s háčky na lámání kopí nepřátel.

**Prak:** Kožená kapsa připevněná na dva prameny tkaných šlach či lněného provazu. 

- *Speciální:* Munice do praku je v podstatě neomezená kdekoliv, kde je přístup ke kamení, suti či jinému podobnému materiálu. Alternativně se do praku dá nabít malý předmět (jako lektvar či granát) a hodit jej tak na větší vzdálenost.

**Příruční kuše:** Malá verze kuše s kratším lučištěm z pružné oceli a jednoduchým spoušťovým mechanismem.

**Rapír:** Dlouhá a tenká čepel z lehké oceli s košíkovým jílcem pro ochranu ruky.

**Řemdich:** Železná koule s ostrými hroty, připevněná k rukojeti pomocí kovového řetězu.

**Sekyrka:** Malá jednobřitá ocelová sekera s dřevěnou násadou, někdy s protizávažím na druhé straně.

**Těžká kuše:** Robustní kuše s kovovými výztuhami, silným lučištěm a složitým napínacím mechanismem.

**Válečná sekyra:** Jednobřitá nebo dvoubřitá sekera s dlouhou rukojetí, hlavice z uhlíkové oceli.

**Válečné kladivo:** Kovová hlavice s hrotem na jedné straně a kladivovou plochou na druhé, rukojeť ze dřeva nebo kovu.

**Zahnutý meč:** Čepel se zakřivením z uhlíkové oceli, rukojeť omotaná hedvábím nebo kůží pro lepší úchop.

### Zbraně mimořádné kvality

Stejně jako u zbrojí, existují i zbraně mimořádné kvality. Takové zbraně vždy poskytují bonus k hodu na zásah, pro který jsou použity.

<img src="/assets/sep_line.png"/>

## Výbava dobrodruha

Níže uvedená výbava a ceny, jsou hráčům dostupné pouze při tvorbě postavy. Ceny a dostupnost předmětů, během hry samotné se mohou výrazně lišit.

| PŘEDMĚT                                                      | Sloty |   CENA   |
| ------------------------------------------------------------ | :---: | :------: |
| Alchymistické nástroje (10 použití)                          |   1   |  30 ši   |
| Cestovní výbava                                              |   2   |  10 ši   |
| Čistící sada na křesadlové zbraně (10 použití)               |   1   |  20 ši   |
| Dalekohled                                                   |   1   |  20 ši   |
| Dřevěná tyč - 2 metry                                        |   2   |   3 mi   |
| Dřevěný kůl                                                  |   L   |   1 mi   |
| Hák                                                          |   1   |   2 ši   |
| Horolezecké náčiní                                           |   2   |  10 ši   |
| Hrnek                                                        |   1   |   3 mi   |
| Hudební nástroj - Ruční                                      |   1   |  10 ši   |
| Hudební nástroj - Velký                                      |   2   |  50 ši   |
| Kladívko                                                     |   1   |   3 ši   |
| Koňské sedlo a otěže                                         |   4   |  40 ši   |
| Kovový hřeb                                                  |   L   |   5 mi   |
| Křesadlo                                                     |   1   |   2 ši   |
| Křída                                                        |   L   |   1 mi   |
| Lahvička oleje                                               |   L   |   3 ši   |
| Lahvička s korkovou zátkou                                   |   L   |   5 mi   |
| Lucerna                                                      |   1   |  10 ši   |
| Lupa                                                         |   L   |  30 ši   |
| Maskovací sada (10 použití)                                  |   2   |  25 ši   |
| Motouz (20 metrů)                                            |   1   |   2 mi   |
| Mýdlo                                                        |   L   |   2 mi   |
| Nástroj (Krumpáč, Pila, Kladivo, Lopata, Páčidlo, Prut na ryby atd...) | 1 - 2 |   3 ši   |
| Oblečení - Běžné                                             |   1   | - (1 ši) |
| Oblečení - Pro dobrodruha                                    |   1   | - (1 ši) |
| Oblečení - Společenské                                       |   2   |  20 ši   |
| Oblečení - Módní společenské                                 |   2   |  50 gr   |
| Oblečení - Zimní                                             |   2   |   5 ši   |
| Pochodeň                                                     |   L   |   2 mi   |
| Polní lékárnička (10 použití)                                |   2   |  40 ši   |
| Pouta                                                        |   1   |   8 ši   |
| Provaz (10 metrů)                                            |   1   |   3 ši   |
| Psací potřeby (10 použití)                                   |   2   |  10 ši   |
| Pytel kovových ježků                                         |   L   |   5 ši   |
| Řetěz (2 metry)                                              |   1   |   5 ši   |
| Svíčka                                                       |   L   |   3 mi   |
| Truhla se zámkem (dřevěná, malá)                             |   1   |   3 ši   |
| Truhla se zámkem (dřevěná, velká)                            |  5+   |  10 ši   |
| Víno (1 litr, obyčejné)                                      |   1   |   1 ši   |
| Víno (1 litr, Kvalitní)                                      |   1   |  15 ši   |
| Visací zámek s klíčem                                        |   1   |   6 ši   |
| Zápalky (10 použití)                                         |   1   |   8 ši   |
| Zásoby                                                       |   1   |   2 ši   |
| Zásoby pro zvíře                                             |   1   |   1 ši   |
| Zlodějské náčiní (10 použití)                                |   2   |  25 ši   |
| Zrcátko                                                      |   1   |   5 ši   |
| Zvoneček                                                     |   1   |   1 ši   |
| A další... (Řekni si PJ co potřebuješ)                       |  ??   |    ??    |

asd

#### Popisky

asd

<img src="/assets/sep_line.png"/>

## Zvěř a povozy

**Nosnost tažných zvířat:** Tažná zvěř může dosáhnout až dvojnásobku své psané nosnosti. Avšak při překročení psané nosnosti se jejich hybnost sníží na polovinu.

<img src="/assets/sep_line.png"/>

### Pes

Domestikované plemeno vybírané především pro svou inteligenci a stopovací schopnosti.

**Lvl:** 1; **HP:** 6; **OČ:** 12; **ToHIT:** +1;  **Hybnost:** 18; **Z.Hody:** *Z:*15 / *T:*14 / *M:* 16; **Morálka:** 10

**Útoky:** 1x Kousnutí *1k6*

**Speciální schopnosti:**

- *Stopování:* Poskytuje bonus *+4* ke stopování.
- *Na příkaz:* Trénovaný, aby útočil na příkaz majitele.

**Cena:** 20 st

<img src="/assets/sep_line.png"/>

### Mula

Tvrdohlavý kříženec koně a osla.

**Lvl:** 2; **HP:** 8; **OČ:** 12; **ToHIT:** +1;  **Hybnost:** 12; **Z.Hod:** *Z:*14 / *T:*16 / *M:* 16; **Morálka:** 9

**Útoky:** 1x Kopanec *1k4* nebo 1x Kousnutí *1k3*

**Speciální schopnosti:**

- *Lhostejný:* Nechá se zavést téměř kamkoli, dokonce i do podzemí. 
- *Defenzivní:* Může zaútočit pokud ohrožen, nemůže však být vycvičena k boji.
- *Nosnost:* Lze vybavit 4-mi malými nebo 2-mi velkými sedlovými brašnami.

**Cena:** 30 st

<img src="/assets/sep_line.png"/>

### Kůň

Lehce stavěný kůň určený pro rychlou jízdu.

**Lvl:** 2; **HP:** 8; **OČ:** 12; **ToHIT:** +1;  **Hybnost:** 24; **Z.Hod:** *Z:*14 / *T:*15 / *M:* 16; **Morálka:** 7

**Útoky:** 2x Kopanec *1k4*

**Speciální schopnosti:**

- *Bojácný:* Pokud je napaden musí ověřit morálku. Při neúspěchu uteče.
- *Nosnost:* Lze vybavit 2-mi malými nebo 1 velkou sedlovou brašnou.

**Cena:** 75 st

<img src="/assets/sep_line.png"/>

### Kárka

Dvoukolá kárka s velkou kapacitou.

**SP:** 2; **OČ:** 10; **Max hybnost:** 4, **Minimum zvířat:** 2 muly nebo 1 kůň.

**Speciální schopnosti:**

- *Max nosnost:* (20) 40 Slotů (v závorce nosnost s minimem zvířat) 
- *Obtížný terén:* Tento typ vozidla muže cestovat pouze po udržovaných cestách.

**Cena:** 100 st

<img src="/assets/sep_line.png"/>

### Povoz

Čtyřkolový otevřený vůz

**SP:** 4; **OČ:** 10; **Max hybnost:** 4, **Minimum zvířat:** 4 muly nebo 2 koně.

**Speciální schopnosti:**

- *Max nosnost:* (80) 160 Slotů (v závorce nosnost s minimem zvířat) 
- *Obtížný terén:* Tento typ vozidla muže cestovat pouze po udržovaných cestách.

**Cena:** 200 st

!!! note "SP: Životy struktur"
	Struktury nelze poškodit běžnými zbraněmi (meče, luky, sekery atd..). Avšak velká stvoření, kouzla a obléhací zbraně je poškodit mohou. Za každých *5 poškození*, které útokem způsobí obléhací zbraň, kouzlo nebo velká nestvůra. *Obdrží struktura 1 bod poškození*. Pokud by měla struktura podstoupit záchranný hod, automaticky selže.

<img src="/assets/sep_line.png"/>

## Nájemná pomoc

asd

<img src="/assets/sep_line.png"/>
