# Atrakcyjne i spokojne miejsca pod Warszawą (2026)

🌐 **Strona:** https://mkcin.github.io/warsaw-forest-towns/
📦 **Repozytorium:** https://github.com/mkcin/warsaw-forest-towns

Statyczna strona z analizą 20 miejscowości pod Warszawą pod kątem:

- **spokoju i zieleni** wokół działki,
- **dojazdu do Śródmieścia** komunikacją publiczną (KM / SKM / WKD / autobus),
- **infrastruktury** (szkoły, przedszkola, szpital, sklepy),
- **cen działek i domów** (stan: październik 2026).

Strona zawiera interaktywną mapę satelitarną, sortowalny ranking z filtrami, karty miejsc,
wykresy cen oraz sekcję dla rodzin z małymi dziećmi.

## Oferty domów

Sekcja **Oferty** jest generowana automatycznie: `offers.js` zawiera pobrane oferty
z Otodomu, Morizonu i Gratki, ocenione według jawnych kryteriów (cena ≤ 1,40 mln zł,
powierzchnia ≥ 90 m², lokalizacja w analizowanych miejscowościach). Plik zawiera
`meta.version` i `meta.generated_at`, które strona pokazuje w nagłówku sekcji.

Ponowne uruchomienie odświeża `offers.js`; `index.html` nie wymaga zmian.

## Uruchomienie

Wersja online: https://mkcin.github.io/warsaw-forest-towns/

Lokalnie: otwórz `index.html` w przeglądarce. Mapa (Leaflet + Esri World Imagery) wymaga internetu.

## Źródła danych

- Ceny działek: Działkopedia (Rejestr Cen Nieruchomości GUGiK + aktywne oferty), X 2026
- Ceny domów: Otodom, Tabelaofert.pl (średnie ofertowe), X 2026
- Czasy dojazdu: rozkłady KM / SKM / WKD oraz opracowania rynkowe
- Ceny i raporty rynkowe: Elandom, NZP, RynekPierwotny

## Zastrzeżenie

Analiza poglądowa. Oceny 1–10 są autorskie i wynikają z wag podanych na stronie.
Przed zakupem działki należy sprawdzić MPZP/plan ogólny, media, geologię i księgę wieczystą.
