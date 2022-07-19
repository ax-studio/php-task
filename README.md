# php

## Wykres tygodnia 

Celem zadania jest stworzenie REST API używając frameworka [Laravel](https://laravel.com/), które będzie serwować wykresy liniowe w formie obrazków, bazując na danych z ostatnich 7 dni.

### Endpointy

Zwraca wykres liniowy na którym prezentowany jest tygodniowy rozkład temperatury z ostatnich 7 dni.
Przyjmuje paramerty:
 - `city` - miasto dla którego wyświetli się temperatura, domyślnie `Gdańsk`
```
/weekly?city={CITY_NAME},currency={CURRENCY}
```

Zwraca wykres liniowy na którym prezentowany jest dzienny kurs średni zdefiniowanej waluty z ostatnich 7 dni.
Przyjmuje paramerty:
 - `currency` - waluta, której będzie wyświetlony kurs, domyślnie `Euro`
```
/weekly/currency?city={CITY_NAME},currency={CURRENCY}
```

Zwraca wykres liniowy na którym prezentowana jest temperatura oraz dzienny kurs średni zdefiniowanej waluty z ostatnich 7 dni.
Przyjmuje paramerty:
 - `city` - miasto dla którego wyświetli się temperatura, domyślnie `Gdańsk`
 - `currency` - waluta, której będzie wyświetlony kurs, domyślnie `Euro`
```
/weekly/weather?city={CITY_NAME},currency={CURRENCY}
```

### Źródła danych

- Źródło danych pogodowych https://openweathermap.org/history
- Źródło danych kursów walut http://api.nbp.pl/
- API rysujące wykresy https://documentation.image-charts.com/line-charts/

### Rozwiązanie

- Za każdy endpoint przyznawane jest 5 punktów.
- Jakość wykonania (kod, testy, dokumentacja) to kolejne 5 punktów.

Link do repozytorium z rozwiązaniem proszę przesłać na [kontakt@axstudio.pl](mailto:kontakt@axstudio.pl)


