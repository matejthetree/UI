---
title: DI study group 9.7.2019. - klasifikacija maslina po listu
date: 2019-07-11T12:07:09.806Z
image: /images/screenshot-2019-07-10-at-11.35.00-pm.png
tags:
  - di-study-group-pula
published: true
---
## Drugo druzenje?

Drugo druzenje je iza nas. I dalje se nalazimo u velikom broju :)

### Mornaricki park 
Jedna grupa je radila na datasetu za Mornaricki Park, i ispostavilo se da klasifikacija drveca nije tako trivijalna. Zato sto u parku imamo gusti drvored, u vecini slika se nalazi vise drveca, i krosnje se znaju ispreplitati. Klasifikacija na tipu lista ili kore bi bila jednostavna, no ideja je da se iz bilo koje pozicije odrede sva stabla u slici. 
Probati cemo sa detaljnim poligonima oko stabla, no za to ce nam trebati malo vise iskustva sa NN.

## Masline

[Notebook Link](https://www.kaggle.com/matejthetree/masline-10-07?scriptVersionId=17028659)

[Dataset Link](https://www.kaggle.com/matejthetree/mk0907full)

Dobili smo listove od 5 sorta maslina. 
Uvijek smo za validacijski set odvajali stablo koje nije u trening setu, da bi izblegli overfit.
Kroz prvotne eksperimente, pokazalo se da je jedna sorta zapravo bila mjesavina vise sorti, pa smo nju za sad izbacili dok ne dobijemo nove podatke.

Sa ostale cetiri sorte smo uspijeli doci na 97% preciznosti.
To je za sada mali uzorak, no pokazuje da se moze preko lista klasificirati maslina, barem donekle.

Slijedeci su koraci pronaci vise sorti, i vise listova. I vidjeti na vecem datasetu.

Cijeli proces mozete vidjeti u notebooku na vrhu.

Ako se zelite igrati sa notebookom, kliknete na `copy & edit`. Napravite account na kaggle.com i voila. Ne zaboravite dole desno u settings ukljuciti *GPU* i *Internet*.

Notebook je iskomentiran i za pocetnike :)


## Python course

Za one koji neznaju programirati, neka prodju python course
www.learnpython.org

na discord serveru pitajte ako nesto nije jasno.

## Zakljucak

Eto od dva projekta, jedan pokazuje uspijeh. 
Za slijedeci put cekamo nove ideje iz grupe, nakon sto zavrse prva dva videa sa course.fast.ai

Vidimo se



