# Istraživanje i optimizacija minimalnog nezavisnog dominantnog skupa u grafovima

## Opis
Ovaj projekat istražuje i optimizuje problem **minimalnog nezavisnog dominantnog skupa (MNDS)** u grafovima koristeći različite metode, uključujući:

- Gruba sila (BRUT)
- Genetski algoritam (GA)
- Optimizaciju kolonijom mrava (ACO)
- Varijantnu pretragu susedstva (VNS)

## Metode
1. **Gruba sila**: Pronađite sve moguće skupove čvorova i izaberite onaj s najmanjim brojem čvorova koji zadovoljava uslove nezavisnosti i dominacije.
   
2. **Genetski algoritam**: Koristi prirodne principe selekcije, krosing-over i mutaciju za pronalaženje približnih rešenja.

3. **Optimizacija kolonijom mrava**: Imitira ponašanje mrava kako bi pronašao optimalne puteve do rešenja.

4. **Varijantna pretraga susedstva**: Koristi lokalnu pretragu i nasumično menjanje rešenja kako bi se poboljšala rešenja kroz iteracije.

## Rezultati
- **ACO** je pokazao 100% stopu uspešnosti.
- **VNS** je postigao najbolju ravnotežu između brzine i uspešnosti.
- **GA** i **ACO** su fleksibilne metode pogodne za različite tipove grafova.

## Preporuke za budući rad
Istražiti druge heurističke metode i kombinacije za dalja poboljšanja u performansama i tačnosti rešenja.

## Kako pokrenuti
1. Klonirajte repozitorijum.
2. Instalirajte potrebne biblioteke.
3. Pokrenite skripte za testiranje svake metode.
