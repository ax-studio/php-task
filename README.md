# php

## Wykres tygodnia 

Celem zadania jest stworzenie REST API używając frameworka [Laravel](https://laravel.com/), które będzie serwować wykresy liniowe w formie obrazków, bazując na danych z ostatnich 7 dni.

### Endpointy

Zwraca wykres liniowy na którym prezentowany jest dzienny kurs średni zdefiniowanej waluty z ostatnich 7 dni.
Przyjmuje paramerty:
 - `currency` - waluta, która będzie prezentowana, domyślnie `Euro`
```
/weekly/currency/{CURRENCY}
```

Zwraca wykres liniowy na którym prezentowana są dzienne kury średnie zdefiniowanych walut z ostatnich 7 dni.
Przyjmuje paramerty:
 - `currencies` - waluty, które będa prezentowane, domyślnie `Euro`
```
/weekly/?currencies={CURRENCY1}:{CURRENCY2}
```

### Źródła danych

- Źródło danych kursów walut http://api.nbp.pl/
- API rysujące wykresy https://documentation.image-charts.com/line-charts/

### Rozwiązanie

- Za każdy endpoint przyznawane jest 5 punktów.
- Jakość wykonania (kod, testy, dokumentacja) to kolejne 5 punktów.

Link do repozytorium z rozwiązaniem proszę przesłać na [kontakt@axstudio.pl](mailto:kontakt@axstudio.pl)


