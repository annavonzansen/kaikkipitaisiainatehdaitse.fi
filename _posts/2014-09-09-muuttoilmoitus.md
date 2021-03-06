---
title: Muuttoilmoitus
description: Miten muuttoilmoituksen pitäisi toimia
author: Ville Korhonen
---

# {{ page.title }}
 > {{ page.description }}

Ah, onnea, uusi asunto, uudet naapurit, uusi elämä. Ja sitten... muuttoilmoitus tehtävänä.

(TBD)

## Nykytilanne

 - muuttoilmoitus.fi (Posti, Maistraatti)
 - firmat saa rahaa vastaan VRK:lta päivittyneet tiedot
 - niin, rahaa vastaan ; pienillä toimijoilla ei välttämättä mahdollisuutta tähän (erityisesti yhdistykset ym.)
 - ja, sieltä VRK:lta ne tiedot saa sitten rahaa vastaan ihan kuka tahansa
 - muille pitäisi muistaa tehdä jokaiseen oma muuttoilmo (ne N yhdistystä yms.)


## "Jos minä saisin päättää"

 - ilmainen palvelu, jos henkilö on ko. organisaatiolle sallinut omien tietojensa haun
 - "vähän kuin kännykkäsovellusten tai facebookin permissionit", kansalainen voi itse valita, mitä tietoja jakaa ja kenen kanssa, vai pitääkö kaiken vain omana + viranomaisten tietona
 - firmat voivat ostaa laajempia dumppeja kuin oma asiakasrekisteri, mutta tästä VRK perisi maksun (kuten nyt), henkilö voi kuitenkin ilmoittaa, että omia tietoja ei tälläiseen saa sisällyttää
 - eli: kun liityn jäseneksi yhdistykseen Y, liittymisprosessin yhteydessä minut kierrätetään VRK:n sivujen kautta, jossa sanon, että "jep, kertokaa tälle yhdistykselle jos muutan, ja niille voi antaa tiedot: kotikunta, sähköpostiosoite"
 - tietojen tallettaminen siten, että viranomainen ei (suoraa) näe, mihin yhdistyksiin ym. kuulun
 - mutta mahdollisuus kertoa viranomaisille, että olen jäsen X, Y, Z, ja näitä tietoja voisi käyttää esim. avustusjutuissa? (eli erilaisten julkisten tukien käyttöä seuratessa, ie. näkisi jotain jäsenmääriin liittyvää dataa?)
 - vois toimia siten, että vrk.fi/hallitsetietojani > voin luoda "tokenin", jolla on jotain oikeuksia ("hae postiosoite, hae puhelinnumero"), jonka voin antaa kenelle tahansa > tokenin haltija voi hakea ko. tietoja ihan milloin tahansa ; ja voin revokoida tokenin + pystyn tägäämään niitä miten itse tahdon ("tämän annoin Mikolle", "tätä käyttää työnantajani", "suosikkiyhdistykseni jäsenrekisteri") > voin pitää viranomaisilta salassa, että kenelle tietoja viedään, mutta homma hoituisi muuten automatisoidummin kuin nyt
 - samaan paikkaan historiatiedot: ketkä ovat hakeneet minun tietoni ja milloin?
 - tokeneille expiroitumispäivä: "tämä yritys saa noutaa tietojani 2 vuoden ajan, mutta sitten joutuvat pyytämään uuden luvan"
 - mahdollisuus rekisteröidä omiin tietoihin useita osoitteita ("lomaosoite", "kotiosoite", "joku muu"), ja voin valita näistä, mitä tietoja annan esimerkiksi tilaamalleni sanomalehdelle ("toimittakaa lomaosoitteeseni")
 - tärkein: vain yksi paikka, johon muutos tarvitsee tehdä


## Lisää mahdollisuuksia
 - jos palvelu haluaa vahvasti tunnistaa käyttäjänsä (estää häiriköinnin yms.), voisi olla tunnistatamakayttaja.vrk.fi, joka tunnistaa käyttäjän, ja palauttaa palvelulle uniikin ID:n, jonka avulla palvelu ei tiedä, että kuka käyttäjä on, mutta yhteistyössä VRK:n kanssa on mahdollista selvittää henkilöllisyys esim. väärinkäyttötapauksessa
 - tällöin voit pysyä anonyyminä, mutta vahvasti tunnistautuneena...
 - estettävä kuitenkin viranomaistietokanta, josta näkee kaikki käyttäjän sidokset
