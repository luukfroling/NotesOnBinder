# Aantekeningen op de late donderdagavond

Het lijkt erop dat thebe alleen bestanden van github kan halen: 
![thebeGithub](./images/thebeGithub.png)
Proberen om vanaf laptop bestanden van github te halen als test. 


## probleem: binder blijft laden

Binder zegt dat hij blijft laden zonder dat er iets gebeurd. Dit gaat oneindig door

## 1 opnieuw beginnen

Ik heb alles qua github uit de _config.yml gehaald. Binder laad nu locaal binnen 3 seconde maar github pages werkt niet meer.

## 2 github desktop goed opzetten met github pages

github desktop goed opgezet zodat github pages sneller werkt

## 3 Zonder "repository: " in _config

Nogsteeds niks in _config.yml, laadtijd eerste keer vrij hoog maar hij laad wel -> foto om het demonstratieeffect voor te zijn
![demonstratie](./images/demonstratieeffect.png)

## 4 (note) Bestaande instanties

Let bij het testen op f12 of er een nieuwe instantie of een al bestaande instantie is gebruikt 
![instantie](./images/isready.png)

## 5 (note) Thebe werkt alleen met github

Het lijkt erop dat thebe alleen bestanden van github kan halen: 
![thebeGithub](./images/thebeGithub.png)
Dit komt uit de build-logs van het dictaat. De bestanden zullen dus zozo op github geplaatst moeten worden.
De vraag is of alle bestanden van het boek mee moeten verhuizen of alleen de notebooks waar je toegang tot krijgt.

## 6 (note) max aantal users bereikt

Maximum aantal users op jupyterbook site; omdat de live code launch het niet bleef doen even op de website getest
![binderUsers](./images/binder_max.png)
Het lijkt erop dat binder zozo niet zo goed werkt op het moment (2/11/2023 9:32)

## 7 kapot na toevoegen repository

Na het toevoegen van deze code gaat het weer kapot, met de head error.
![eerste_error](./images/url.png)

## 8 oplossing voor 7

Dit lost de error op: deze laad gedurende 10 seconde zonder de opgeslagen versie te gebruiken ( note 4)
![head](./images/head.png)