---
layout: page
title: OSI Model
---

# Livet er lidt nemmere med en OSI-Model

## Min anbefaling

Jeg har gennem årene erfaret, at det er langt nemmere at forstå, designe og fejlfinde et netværk, når man bruger OSI-modellen som reference. Derfor anbefaler jeg, at du downloader eller bruger min OSI-model som skabelon og derefter placerer de teknologier, protokoller og enheder, som du selv anvender, under det lag, hvor de hører hjemme.

For eksempel kan du under Sessionslaget notere teknologier som SIP, eller andre session-baserede protokoller, som du benytter i dit miljø. Under Netværkslaget kan du tilføje IP, OSPF, BGP eller andre routingprotokoller, og under Datalinklaget kan du notere VLANs.
Når du har gennemgået alle syv lag og tilføjet de teknologier, som findes i dit eget netværk, får du et værdifuldt overblik over din infrastruktur. Dette gør det lettere at identificere afhængigheder, dokumentere miljøet og forstå, hvordan trafikken bevæger sig gennem netværket.
Næste trin er at fokusere på sikkerheden. Gennemgå hvert lag i OSI-modellen og vurder, om det er korrekt konfigureret, tilstrækkeligt beskyttet og følger gældende best practice.

Ved at arbejde systematisk lag for lag bliver det nemmere at opbygge et stabilt, veldokumenteret og sikkert netværk. Samtidig reducerer du risikoen for at overse teknologier, services eller sikkerhedsforanstaltninger, som kan have betydning for netværkets drift og sikkerhed.

Derfor er livet bare lidt nemmere med en OSI-model.

**Bemærk:** Efterhånden som dit netværk vokser, vil din OSI-model sandsynligvis blive fyldt med teknologier, protokoller og services. På det tidspunkt kan det være en fordel at lave en separat OSI-model for hver type udstyr eller service, f.eks. en switch, router, firewall, webserver eller mailserver.

Når du når dertil, behøver du ikke nødvendigvis at fortsætte med at indsætte alle de teknologier og protokoller, du anvender. Forhåbentlig har du på det tidspunkt opbygget en så god forståelse af OSI-modellen, at du blot kan gennemgå den lag for lag og fokusere på design, drift, fejlfinding, sikkerhed og best practice.

-- Ali

<figure>
    <a href="/assets/images/osimodel.png" target="_blank">
        <img src="/assets/images/osimodel.png" alt="OSI-modellen" class="osi-model-image">
    </a>
    <figcaption>Figur 1: OSI-modellens syv lag.</figcaption>
</figure>
