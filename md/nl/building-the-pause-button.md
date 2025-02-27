

---
title: De Pauzeknop Bouwen
description: Hoe zou een AI-pauze eruitzien? Hoe voorkom je daadwerkelijk dat een superintelligente AI wordt gecreëerd?
---
Als we de creatie van een superintelligente AI toestaan, riskeren we [ieder leven op aarde](/xrisk).
Wanneer we over een pauze spreken, hebben we het over [het implementeren van een internationaal verbod op de creatie van een superintelligente AI](/proposal).
Sommigen beweren dat het te vroeg is om op de pauzeknop te drukken (we [hebben geen tijd te verliezen](/urgency)), maar de meeste experts lijken het erover eens te zijn dat het goed zou zijn om even te pauzeren als de ontwikkelingen te snel gaan.
Maar op dit moment _hebben we geen pauzeknop_.
Dus moeten we beginnen met nadenken over hoe dit zou werken en hoe we het kunnen implementeren.

Gelukkig is het bouwen van een superintelligente AI moeilijk en vereist het veel middelen.

## Inhoud {#contents}

## De Wedloop: waarom we internationale samenwerking nodig hebben {#the-race-why-we-need-international-cooperation}

We verwachten niet dat een enkel land in staat zal zijn om een pauze te implementeren.
De economische prikkels zijn te sterk en het vertragen van de AI-ontwikkeling zou een land in een economisch en geopolitiek nadeel brengen.
De kosten van onderinvestering in veiligheid worden wereldwijd verdeeld, terwijl de voordelen van versnelling lokaal zijn.
Dit speltheoretische probleem wordt soms "Moloch" of een "wedloop naar de bodem" genoemd.

De enige uitweg is een _internationale overeenkomst_.
Daarom zijn we zo geobsedeerd door [topconferenties](/summit): dit zijn de evenementen waar wereldwijde besluitvormers bijeenkomen en werken aan een wereldwijde oplossing.
Of tenminste, dat is wat we willen dat ze doen.
Tot nu toe hebben alle AI-veiligheidstopconferenties niet geleid tot zinvolle regulering.
Het is aan jou en mij om [hen te overtuigen](/action).

## Rekenkrachtbeheer {#compute-governance}

Om een grensverleggende LLM (zoals GPT-4) te trainen, heb je veel zeer gespecialiseerde en dure hardware nodig.
GPT-4 werd getraind op 25.000 Nvidia A100 GPU's, die elk $10.000 kosten.
Hoewel er innovaties zijn die efficiëntere training mogelijk maken, is de trend dat AI-modellen steeds groter en groter worden.

De schaal van moderne AI-trainingsvereisten is enorm.
Microsoft kondigde onlangs een plan aan om [een kerncentrale te bouwen](https://www.theverge.com/2024/9/20/24249770/microsoft-three-mile-island-nuclear-power-plant-deal-ai-data-centers) voor zijn AI-energiebehoeften.
Gelukkig voor ons betekent dit dat AI-trainingsruns moeilijk te verbergen zijn, althans in de nabije toekomst.

Door de AI-chipketen te controleren en te monitoren, kunnen overheden of andere regelgevende instanties ervoor zorgen dat niemand een gevaarlijke AI-trainingsrun start.
Laten we dieper ingaan op de verschillende knelpunten in deze toeleveringsketen.

### Knelpunten in de chipketen {#choke-points-in-the-chip-supply-chain}

Het is moeilijk om de complexiteit en onderlinge afhankelijkheid van de AI-chipketen te overdrijven.
Het bestaat uit verschillende zeer gespecialiseerde bedrijven, waarvan sommige de enige in de wereld zijn die bepaalde componenten kunnen produceren.
Dit is goed nieuws voor governance.
Via de hardware kunnen we de trainingsruns reguleren.
Laten we een duik nemen in de verschillende knelpunten in de AI-chipketen.

#### Siliciumwafers: Shin-Etsu, Sumco, Siltronic {#silicon-wafers-shin-etsu-sumco-siltronic}

#### Lithografie: ASML & SMEE {#lithography-asml--smee}

Alle moderne chips worden gemaakt met behulp van lithografiemachines: enorme machines die $200 miljoen kosten en licht op een siliciumwafer projecteren.
Dit lithografiaproces is een van de meest complexe en dure onderdelen van het chipproductieproces.
Top-tier AI-chips worden allemaal gemaakt met behulp van EUV-lithografie, en ASML is het enige bedrijf dat deze machines maakt.
Dit Nederlandse bedrijf is een van de belangrijkste potentiële knelpunten voor AI-governance.
Deze machines zijn buitengewoon complex en vereisen veel expertise om te bouwen en te onderhouden.
Opmerkelijk is dat ze [afstandsbedieningen](https://www.businessinsider.com/asml-tsmc-semiconductor-chip-equipment-kill-switch-china-invade-taiwan-2024-5) hebben (voornamelijk voor het geval Taiwan wordt binnengevallen), dus in sommige belangrijke opzichten is de pauzeknop al ingebouwd.

De Nederlandse regering heeft strenge exportcontroles ingesteld voor hun EUV-lithografiemachines, waarvoor exportvergunningen vereist zijn.
Deze exportcontroles zijn voornamelijk ingesteld om China's chipambities te vertragen.
De [VS, Japan en Nederland](https://apnews.com/article/technology-district-of-columbia-netherlands-china-business-6801d6c5f65b0bc1df6186e2e89a6f7d) hebben een (niet-openbare) overeenkomst om chip- en lithografie-exporten naar China te beperken.

Het Chinese bedrijf SMEE probeert bij te blijven, maar is niet in staat om zijn eigen EUV-machines te maken.
Hun DUV-machines zijn [nog steeds vast op 28nm](https://www.scmp.com/tech/big-tech/article/3278235/chinese-chip-making-shows-progress-new-euv-patent-domestic-lithography-champion), wat generaties achter ASML's 5nm EUV-proces ligt, laat staan ASML's toekomstige 2nm-machines.
Dus SMEE is niet in staat om moderne AI-chips te produceren.

Met andere woorden: ASML is een fundamenteel knelpunt in de AI-chipketen.

#### Optiek: Zeiss {#optics-zeiss}

ASML's EUV-machines gebruiken spiegels en lenzen gemaakt door het Duitse bedrijf Zeiss.
In 2016 kocht ASML [een belang van 25%](https://optics.org/news/7/11/11) in Zeiss, en de twee bedrijven hebben een zeer nauwe relatie.
Het is waarschijnlijk dat geen enkel ander bedrijf deze optiek kan produceren.

#### Photoresist {#photoresist}

De photoresist is een chemisch product dat wordt gebruikt om patronen in de siliciumwafer te etsen.
Japanse bedrijven zijn dominant in dit veld.

De belangrijkste bedrijven in dit veld zijn:

- JSR (Japan)
- Shin-Etsu (Japan)
- Tokyo Ohka Kogyo (Japan)
- DuPont (VS)

#### Interconnect & Packaging: ASE {#interconnect--packaging-ase}

Wanneer een chip-die een fab verlaat, moet deze worden "verpakt".
ASE is waarschijnlijk het grootste interconnect-bedrijf voor AI-chips.

#### Fabricage: TSMC, Samsung en SMIC {#fabrication-tsmc-samsung-amd-smic}

Het bouwen van een "fab" (een chipfabriek) is verbazingwekkend moeilijk: het heeft een nultolerantie voor stofdeeltjes, vereist de duurste hightech-apparatuur en heeft een zeer complexe toeleveringsketen.
Een moderne fab kost ongeveer 10 tot 20 miljard dollar om te produceren.

De Taiwan Semiconductor Manufacturing Company is verantwoordelijk voor [ongeveer 90%](https://www.fool.com/investing/2025/02/03/meet-the-monster-stock-that-continues-to-crush-the/) van de moderne AI-chips, die allemaal chips zijn gemaakt met een precisie van 7nm of beter.
Samsung is het enige andere bedrijf dat moderne AI-chips kan produceren.

Maar het Chinese SMIC haalt snel in - ze hebben al een [functioneel 7nm-proces](https://wccftech.com/smic-to-limit-huawei-to-7nm-chips-until-2026-reducing-advancement/).
Vanwege de exportcontroles van de VS/Nederland kan SMIC geen ASML EUV-machines kopen en zijn ze nu ook beperkt in het kopen van oudere DUV-machines.
In juni 2024 liet een [rapport](https://evertiq.com/news/55926) zien dat SMIC 5nm-chips kan produceren met behulp van DUV-hardware,
en nu in staat is om 7nm AI-chips te produceren (ongeveer drie jaar achter het 4nm-proces dat ASML's EUV-machines kunnen produceren), maar SMIC's lithografie wordt geplaagd door lage opbrengsten.

#### Geheugenfabricage: Micron, SK Hynix {#memory-fabrication-micron-sk-hynix}

AI-chips vereisen veel HBMs (High Bandwidth Memory), wat de meest geavanceerde geheugentype is.
Slechts een paar bedrijven kunnen ze produceren.

#### AI-chipontwerp: Nvidia, AMD, Intel, Google, Apple {#ai-chip-design-nvidia-amd-intel-google-apple}

De beroemdste bedrijfsnamen op deze pagina zijn allemaal chipontwerpers.
En er zijn nieuwe bedrijven, zoals Cerebras en Groq, die chips specifiek voor AI ontwerpen.
Opmerkelijk is dat sommige van deze bedrijven relatief verouderde processen gebruiken om hun chips te produceren, zoals Groq die 14nm gebruikte, wat een potentieel knelpunt is voor governance.

### On-Chip Governance {#on-chip-governance}

- Het artikel ["Secure, Governable Chips"](https://www.cnas.org/publications/reports/secure-governable-chips) stelt een nieuwe aanpak voor AI-governance voor.
- Chips kunnen reageren op berichten van vertrouwde servers om [te bewijzen dat ze zich binnen een bepaalde afstand van een vertrouwde locatie bevinden](https://www.lesswrong.com/posts/uSSPuttae5GHfsNQL/ai-compute-governance-verifying-ai-chip-location). Dit kan nauwkeurig zijn tot op tientallen kilometers.

### Verificatiemethoden - het voorkomen van grote trainingsruns {#verification-methods---preventing-large-training-runs}

Nu we verschillende knelpunten in de chipketen hebben geïdentificeerd, kunnen we beginnen met nadenken over hoe we grote trainingsruns kunnen voorkomen.
Deze eerder genoemde actoren kunnen worden onder druk gezet (door overheden) om ervoor te zorgen dat hun producten niet worden gebruikt voor gevaarlijke AI-trainingsruns.

Maar hoe kan dit worden geverifieerd?

Het artikel ["Verification methods for international AI agreements"](https://arxiv.org/abs/2408.16074) noemt verschillende opties:

1. **Remote Sensing**: Gebruikt satelliet- en infraroodbeeldvorming om datacenters te detecteren door visuele en thermische handtekeningen. Zeer haalbaar, maar beperkt door camouflage of ondergrondse faciliteiten.
2. **Whistleblowers**: Vertrouwt op insiders die non-conformiteit melden, gestimuleerd door juridische en financiële bescherming. Haalbaar, maar afhankelijk van toegang en bereidheid van insiders om te onthullen.
3. **Energiebewaking**: Volgt energieverbruik om grote AI-operaties te identificeren, haalbaar als patronen duidelijk zijn. Haalbaarheid varieert; gegevens kunnen worden verhuld door andere activiteiten met hoog energieverbruik.
4. **Douanegegevensanalyse**: Bewaakt import/export van AI-hardware voor afwijkingen. Haalbaar, vooral voor import, hoewel landen met binnenlandse productie detectie kunnen vermijden.
5. **Financiële inlichtingen**: Observeert grote of ongebruikelijke transacties gerelateerd aan AI-hardware-aankopen. Haalbaar als financiële privacy en bankwetten toestaan, vaak het beste in combinatie met andere methoden.
6. **Datacenterinspecties**: Fysieke locatie-inspecties om naleving van hardwarelimieten en beveiligingsprotocollen te verifiëren. Effectief als het gastland inspecties toestaat; invasief en middelenintensief.
7. **Halfgeleiderproductiefaciliteitinspecties**: Verifieert chipproductieconformiteit door inspectie van faciliteiten met relevante hardware. Haalbaar, maar vereist aanzienlijke middelen en toestemming van het gastland.
8. **AI-ontwikkelaarinspecties**: Beoordeelt faciliteiten voor geautoriseerde code, veiligheidsprotocollen en AI-evaluatierapporten. Effectief, maar zeer invasief, vereist gespecialiseerde expertise en landelijke samenwerking.
9. **Chiplocatiebewaking**: Volgt AI-chipbewegingen om hun inzet te monitoren. Haalbaar met internationale overeenkomsten, maar omzeilbaar door locatiegegevens uit te schakelen of te vervalsen.
10. **Chipgebaseerde rapportage**: Integreert rapportagemechanismen in chips om te waarschuwen als ze buiten geautoriseerde limieten worden gebruikt. Haalbaar, maar uitdagend, vereist internationale normen en hardwareontwikkeling; te omzeilen door firmware te wijzigen.

Elke methode heeft zijn sterke en zwakke punten, vaak vereist complementaire benaderingen of internationale samenwerking voor effectieve implementatie.

Andere voorgestelde methoden zijn:

1. **[flexHEGs](https://yoshuabengio.org/wp-content/uploads/2024/09/FlexHEG-Interim-Report_2024.pdf)**: Een nieuw type chip dat kan worden geprogrammeerd om zichzelf te vernietigen wanneer bepaalde voorwaarden worden voldaan.

Een internationale instelling kan worden opgericht om deze verificatiemethoden te monitoren en de pauze af te dwingen.

## Softwarebeheer {#software-governance}

Fysieke chips zijn onze primaire focus, maar we willen misschien ook de _software_ reguleren die wordt gebruikt om AI-modellen te trainen en uit te voeren.
Het is heel goed mogelijk dat de grootste rekenclusters voldoende kracht hebben om een catastrofaal gevaarlijk model te trainen, maar ze missen nog steeds de software.
Laten we dieper ingaan op de soorten software-innovaties die we kunnen onderscheiden.

### Software-innovaties {#software-innovations}

Ten eerste zijn er _trainings_innovaties.
De Transformer-architectuur, bijvoorbeeld, stelde AI-modellen in staat om veel capabeler te zijn, tegen een veel lagere prijs.
Het op Transformer gebaseerde ALBERT-model [overtrof](https://arxiv.org/pdf/2308.04950) het BERT-model, zelfs met 18x minder parameters.
In de toekomst kunnen we nog efficiëntere architecturen zien.
Er zijn ook innovaties in de gegevens die aan een model worden gevoerd.

Naast trainingsverbeteringen hebben we verschillende _runtime_-verbeteringen gezien.
Chain-of-thought, graph-of-thought en andere technieken kunnen drastische verbeteringen opleveren in de prestaties van AI-modellen.
Tools als AutoGPT kunnen eenvoudige chatbots omzetten in volledig autonome agenten die het web browsen, e-mails sturen en andere taken uitvoeren.
OpenAI's o1-model maakt grotere redeneercapaciteiten mogelijk door het model meer tijd te geven om na te denken over een antwoord voordat het wordt gegeven.

### Software reguleren {#regulating-software}

De softwarekant van AI is moeilijker te controleren dan de hardwarekant.
Software is slechts informatie - het kan gemakkelijk worden gekopieerd en verspreid.
Toch hebben we eerder informatie verboden.
Kinderporno, bijvoorbeeld, is illegaal om te maken, illegaal om te verspreiden en illegaal om te bezitten.
Dezelfde handhavingsmechanismen kunnen worden gebruikt om gevaarlijke AI-software te reguleren.