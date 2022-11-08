# CHESS RATINGS

## Popis

Soutìžní hráèi šachu mají pøiøazený urèitý rating (skóre) vystihující jejich dovednost v šachové høe -- èím vyšší rating, tím lepší hráè. Ratingy se oficiálnì pøepoèítávají jednou za mìsíc na základì her, které hráè v pøedchozím mìsíci odehrál.

## Soubory

Každý soubor je seznam ratingù platných k 1. dnu daného mìsíce, tj. pøepoètený podle výsledkù za pøedchozí mìsíc. Význam jednotlivých sloupcù:

* ID Number: ID hráèe v databázi, mìlo by být pro hráèe stálé
* Name: jméno hráèe (mùže se mìnit, ale ne moc èasto)
* Fed: zemì, v níž je hráè registrován (tzv. federace)
* Sex: pohlaví hráèe
* Tit: nejvyšší dosažený titul hráèe (napø. GM=velmistr, IM=mezinárodní mistr atd.)
* WTit: nejvyšší dosažený titul v ženské kategorii (ženy mají speciální tituly, napø. WGM=ženská velmistrynì, mohou ale získávat i obecné, tj. "mužské" tituly jako IM)
* OTit: tituly v nehráèských kategoriích, napø. mezinárodní rozhodèí, trenér apod.
* FOA: rating èi jiný popis dovedností v kategorii hraní online (FIDE online arena)
* Rat: hodnota ratingu
* Gms: poèet her odehraných v pøedchozím období
* K: tzv. koeficient rozvoje, udává nastavenou rychlost zmìny ratingu pøi pøepoètu, základní hodnoty jsou 10, 20 a 40
* B-day: rok narození
* Flag: pøíznak speciálního režimu (napø. i=inactive=hráè neodehrál za poslední rok žádnou hru)
* Year, Mon: rok a mìsíc, k nìmuž raating platí