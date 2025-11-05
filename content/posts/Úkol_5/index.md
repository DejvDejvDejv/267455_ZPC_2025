+++
date = '2025-09-22T14:39:09+02:00'
draft = false
title = 'Úkol č.5'
menu = "main"
weight=6
featured = true
+++

### Zapojení arduina
<!--more-->
Pro zapojení v tomto miniprojektu jsem si zvolil práci s **Ultrazvukovým měřičem vzdálenosti HC-SR04**. Chtěl jsem si zkusit zapojení s touto komponentou, jelikož ji budu využívat ve svém semestrálním projektu. Vymyslel jsem si zapojení, u kterého při zaznamenání vzdálenosti **menší než 50 mm** se spustí sekvence diod. Pro sekvenci jsem zvolil SOS vyťukané v Morseově abecedě. Zelená dioda signalizuje čárku a červená dioda pomlčku. 

Nejdříve jsem zapojoval diody. U těch jsem již věděl, jak s nimi pracovat ze cvičení. Ze cvičení jsem měl i potřebné **rezistory, diody, drátky a samozřejmě arduino**. Pro tento miniprojekt jsem potřeboval navíc pouze samotný měřič, což byla komponenta, se kterou jsem dříve nepracoval. Ze začátku jsem si moc nevěděl rady se zapojením **Trig** a **Echo**. Na internetu jsem však našel potřebný plánek rozložení, takže se zapojením ve finále nebyly větší komplikace. Výsledné zapojení je vidět ve videu.

Větší komplikace byly s kódem. S tím jsem si sám nevěděl moc rady. Vzal jsem tedy na pomoc **ChatGPT**, který mi poměrně dost pomohl s napsáním kódu. Následovaly pouze menší úpravy kódu, jako bylo třeba definování pinů či upravování délek blikání. 

{{< youtube mYJrw-qpDmM >}}
