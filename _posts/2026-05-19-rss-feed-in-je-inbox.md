---
layout: "post"
title: "Vinger aan de pols"
subtitle: ": Nieuwtjes van deze site direct in je INBOX met RSS:"
active: "journal"
date: "2026-05-19"
category:
    - gebruikersland
    - zelfdoen
tags:
    - hulp

image:
  feature: bpc00003.jpg
header-img: "img/postcover/bpc00003.jpg"
comments: "false"

---

<section>
    <h3 style="color: #a10202;; font-weight: bold;">: VRACHT:</h3>
    <ol style="color: ivory;">
        <li><a href="#C1">~0: <b style="color: #c5975f;"> BEGIN</b>:</a></li>
        <li><a href="#C2">~PID-1: <b style="color: #c5975f;"> RSS-FEED</b>:</a></li>
        <li><a href="#C3">~PID-2: <b style="color: #c5975f;"> RSS-APPLICATIES</b>:</a></li>
        <li><a href="#C4">~PID-3: <b style="color: #c5975f;"> EMAIL-CLIENTS</b>:</a></li>
        <li><a href="#C5">~PID-4: <b style="color: #c5975f;"> KDE-DESKTOP-PLASMOIDS</b>:</a></li>
        <li><a href="#C6">~PID-5: <b style="color: #c5975f;"> VINGER AAN DE POLS</b>:</a></li>
        <li><a href="#C7">~PID-6: <b style="color: #c5975f;"> HELP</b>:</a></li>
        <li><a href="#C99">~PId-9: <b style="color: #c5975f;"> VOETNOTEN</b>:</a></li>
    </ol>
    <br />
    <br />
    <h2 class="arthead" id="C1">: BEGIN:</h2>
</section>

Wat een plaat, niet waar? Wat er allemaal staat? Neem eens een kijkje hier, en zie hoe feeds tot een overzicht leiden, de plaatjes zijn klikbaar, zodat je op je site terecht komt.

<div class="plaatje-rij" style="display: grid; padding: 10px;">
    <div style="border: 1px solid black; padding: 10px; font-size: 30px; text-align: center;">
        <a href="https://worldmonitor.app/"><img src="/assets/img/world-monitor-01.png" alt="world-monitor-app"></a>
    </div>
    <div style="border: 1px solid black; padding: 10px; font-size: 30px; text-align: center;">
        <a href="https://world-monitor.com/"><img src="/assets/img/world-monitor-02.png" alt="w.m.com"></a>
    </div>
</div>

Let wel, de input is voornamelijk MSN, en dus kunnen de uitkomsten behoorlijk afwijken van wat er werkelijk plaatsvind.

En met deze disclaimer:
> Enjoy de feeds! [niet de feds ....feeds]

Maar is de vinger aan de pols van de wereld? Nee. Dat is slechts de buitenkant. voor een echte vinger aan de pols, zou je ff elders je licht moeten opsteken. Het neemt niet weg dat er een ander middel is om een wat rustiger en gecontroleerd overzicht te krijgen.

Je kunt natuurlijk gewoon geregeld deze site bezoeken om nieuwtjes na te vorsen. Uiteraard zijn we daar dankbaar voor. Echter, hoe zou je het vinden om de nieuwtjes gewoon in de inbox van je email-client te ontvangen? Wanneer we dan toch een leercurve hebben met een Linux distro, laten we dan wat handigs ermee doen, toch?




<br>
<h2 id="C2" class="arthead">: RSS-Feed:</h2>
<br>

Veel sites hebben een RSS feed. Dat wil zeggen, zodra er nieuwstjes zijn krijg jij de kop ervan te zien. Je kan dus lekker koppen snellen, en indien er iets tussen zit dat je aantrekt, dan kan je de file openen die erbij hoort. Feitleijk lees je dan slechts dat deel van een site, dat jij interessant vindt, zonder:
> hoe bent u hier gekomen, waar gaat u naar toe, hoe interacteert u met onze website, en heeft u ook zin de nieuwste Big Pharma gepatenteerde pil tegen estrogeen gevulde marsmannetjes met toxische adem.

Denk eens aan de mogelijkheden:
+ Video kanalen op Rumble, Odysee, Youtube,
+ Blog-websites als deze, substack, en anderen
+ Telegram kanalen
+ Kranten

Je kan dus heel gericht, chirugisch een eigen verzameling opbouwen van informatie stromen waardoor je op de hoogte blijft van het nieuws. En zeker wanneer je met technische zaken zoals met IT bezig bent, kan het handig zijn te weten wat er speelt.

Je stelt zelf in wat je wilt zien, wat je wilt behouden en wat je naar het digitale niemandsland verwijst.

Het zou er zo uit kunnen zien:
<div class="plaatje-rij" syle="display: grid; padding: 10px;">
    <div style="border: 1px solid black; padding: 10px; font-size: 30px; text-align: center;">
        <img src="/assets/img/rss-feed-1.jpg" alt="rss-feed-app">
    </div>
    <div style="border: 1px solid black; padding: 10px; font-size: 30px; text-align: center;">
        <img src="/assets/img/rss-feed-3.jpg" alt="rss-feed-inbox">
    </div>
    <div style="display: block; border: 1px solid black; padding: 10px; font-size: 30px; margins:auto; width=75%">
        <img src="/assets/img/rss-feed-2.png" alt="rss-feed-desktop-plamoid">
    </div>
 </div>

De eerste is een apparte applicatie. De tweede laat ziet hoe het er uit zou kunnen zien in de email-client, en de derde is een desktop-plasmoid (KDE-PLASMA).
Je hebt uiteraard ook web-email providers die RSS-feed tonen zoals Murena.io (google vervanger) maar dit soort oplossingen vallen even buiten de beschouwing. De reden is eenvoudig:

> Alles in eigen hand houden, zonder onnodige afhankelijkheid van derden.

<br>
<h2 id="C3" class="arthead">: RSS-APPLICATIES:</h2>
<br>

Ik heb er 3 gekozen uit vele. Het hangt er bijvoorbeeld vanaf welke desktop je hebt. Gebruik je KDE-Plasma, dan zijn er andere mogelijkheden (eyecandy) en gebruik je een GTK-desktop [XFCE, MATE, etc] dan kan je beter die gebruiken welke voor die desktop bedoeld zijn. Dit heeft te maken met hoe de RSS readers gebouwd zijn. Je kan elke RSS gebruiken, echter, je krijgt dan wel de dependencies die bij QT of GTK horen erbij.

Voor Linux zijn er diverse:
+ Akregator [KDE Desktop]
+ Liferea [Linux Feed Reader]
+ RSSGuard [KDE Desktop]

### stap-1: Installeren

Twee methoden zijn er:
1. via de MX Packetinstalleerder;
2. via de CLI.

De MX Pakketinstalleerder heeft diverse tabs. De eerste is populaire paketten. Zou je aldaar RSS in het zoekveld plaatsen en opzoeken, dan zie je: Newsboat. Dan krijg je een tekst-gebaseerde RSS reader. Leuk indien je dat eens wilt uitproberen.

Je kan ook de 2e tab gebruiken: `Enabled Repos`
Zoek je op de genoemde 3 dan vind je ze ook.
1. zet een vinkje links van de applicatie van je keuze.
2. klik op installeren
3. Vul je sudo wachtwoord in.
4. Laat het installatie process voltooien en klik `Close`.
5. Sluit de MX Pakketinstalleerder.

Ben je wat avontuurlijker aangelegd, en heb je dunne vingers, probeer de installatie eens via de CLI:
1. `CTRL + ALT + T` om de konsole te openen
2. Er zijn nu 3 mogelijkheden:
    + `sudo apt install Akregator` + `ENTER`
    + `sudo apt install Liferea` + `ENTER`
    + `sudo apt install RSSGuard` + `ENTER`
3. vul je sudo wachtwoord in + `ENTER`
4. Laat het installatie process voltooien
5. Sluit de CLI met de opdracht: `exit` + `ENTER`

Persoonlijk, ben ik een fan van Akgregator, omdat de andere moeilijker doen dan deze. Akgregator is intuitiever, en heeft zeer uitgebreide mogelijkheden om duizenden bronnen en duizenden artikelen te bewaren. En het integreert goed in de KDE omgeving.

<div style="display:block; margin:auto; width: 65%">
    <img src="/assets/img/rss-feed-3.png" alt="akregator">
</div>


<br>
<h2 id="C4" class="arthead">: EMAIL-CLIENTS:</h2>
<br>

Ik bedoel hier niet je web-email account mee. Een `Email-client` is een applicatie die draait op je Linux-box. Het maakt verbinding met je email-account (IMAP of POP3), en haalt de mail binnen zodat je die op je gemak in een voor jouw aantrekkelijk formaat kunt lezen. Email en RSS-Feeds zijn in wezen dezelfde soort berichten, dus één applicatie gebruiken voor 2 doeleinden lijkt heel logisch, omdat het alle informatie op 1 plek heeft. Daarnaast kan het onderdeel zijn van je eigen workflow, omdat dit kan samenwerken met je adresboek en je kalender.

Een paar voorbeelden uit de GUI groep:
- Thunderbird -> Betterbird
- Evolution
- Kmail
- Claws Mail

Claws mails is hier een buitenbeentje. Dit komt omdat het weliswaar een GUI heeft, maar zich concentreert op pure tekst, en niet op `html`. HTML is een taal waarmee webpagina's worden geschreven. Dit is technisch gezien een stuk veiliger, omdat het geen injectie toestaat van script talen zoals JAVASCRIPT en andere talen. Wanneer je dan een html pagina wilt zien, met alle mooie opmaak, dan is er een special viewer: `Dilo` - viewer of een aparte `PDF`-viewer. Claws mails is modulair opgezet, dus je zult zelf een behoorlijke dosis kennis dienen mee te nemen en een hoop werk moeten verzetten om het goed in te richten.

Echter, je krijgt dan wel een emailclient die slechts dat heeft wat je nodig hebt, lichtgewicht is, en bijzonder krachtig.

Uiteraard kan je een RSS feed inrichten in Betterbird, een fork van Thunderbird, omdat de eerste zich scherper bewust is van privacy en veiligheid.


<br>
<h2 id="C5" class="arthead">: RSS-FEED-LINKS:</h2>
<br>

Nu is het zaak een aantal links te hebben met een RSS-feed.
Hierbij zijn twee zaken opvallend:
1. Zoeken: je kan van elke site een rss-feed zoeken. Ik laat je hieronder zien hoe je een x-account en substack kunt volgen via nitter.net:
    + basis link: https://nitter.net/{USERNAME}/rss
    + https://{name}.substack.com/feed
    + https://nypost.com/business/feed/

2. Het volgen van
    + `The White House` op X via nitter.net (frontend). De link wordt dan: https://nitter.net/WhiteHouse/rss
    + `badlands`-media: https://badlands.substack.com/feed

Had je dit in je feed gehad ... dan had je de WH berichten de wereld in zien sturen waarbij men qagg.news heeft nagedaan en postte: where we go one, we go quantum waarbij de 48ste regel een speciaal geheim teken bevat.

Gein of wat anders, bepaal je uiteraard zelf.
Dit is een goede link om eens wat rss-feeds te ontdekken: [rss-feeds-grabbelton](https://rss.feedspot.com) of kijk onder deze [startpage-search ](https://www.startpage.com/sp/search?query=rss+feeds+directory&cat=web&pl=opensearch)

<br>
<h2 id="C5" class="arthead">: VINGER AAN DE POLS:</h2>
<br>



En met deze disclaimer:
> Enjoy je feeds!

 <br>
<h2 id="C7" class="arthead">: HELP:</h2>
<br>

Mocht dit alles op een niveau zijn waarvan je zegt: daar kan ik wel wat hulp bij gebruiken, laat het me weten via de geëigenende kanalen via email, Signal of Element.

Wil je meer weten? Neem dan contact op via: <a href="mailto: praktisch-linux@tuta.com">praktisch-linux [at] tuta.com</a>.

<p>: Ivar.</p>
