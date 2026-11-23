# zmiennikprawny.pl

Strona główna **ZmiennikPrawnego**, aplikacji do śledzenia nowych aktów prawnych z Dziennika Ustaw RP.

**Strona:** https://zmiennikprawny.pl
**Aplikacja:** https://zmiennikprawny.vercel.app
**Kod aplikacji:** https://github.com/piowerb/ZmiennikPrawny

## O projekcie

ZmiennikPrawny pokazuje nowe ustawy, rozporządzenia i obwieszczenia zaraz po publikacji w Dzienniku Ustaw. Dane pochodzą z oficjalnego API Sejmu RP (ELI). Aplikacja jest darmowa i nie wymaga zakładania konta.

To repozytorium zawiera tylko stronę informacyjną. Sama aplikacja jest w osobnym repozytorium.

## Technologia

- Jeden statyczny plik HTML z CSS, bez frameworków i bez zewnętrznych bibliotek
- Brak ciasteczek i narzędzi analitycznych
- Hosting: GitHub Pages z własną domeną (plik `CNAME`)
- Ramka z podglądem aplikacji pobiera na żywo 3 najnowsze akty z API Sejmu; gdy API nie odpowie, pokazuje przykładowe pozycje

## Struktura

```
index.html            strona główna
logo.png              logo
favicon-48.png        ikona karty przeglądarki
apple-touch-icon.png  ikona na ekran główny iPhone'a
og-image.png          obrazek do podglądu linku w social media
robots.txt            ustawienia dla wyszukiwarek
sitemap.xml           mapa strony
CNAME                 domena zmiennikprawny.pl
```

## Zastrzeżenie

ZmiennikPrawny nie jest serwisem Sejmu RP ani Rządowego Centrum Legislacji. Informacje mają charakter pomocniczy i nie stanowią porady prawnej. Wiążące są wyłącznie teksty aktów opublikowane w Dzienniku Ustaw RP.

## Licencja

Wszelkie prawa zastrzeżone. Kod i projekt strony można przeglądać w celach poglądowych. Kopiowanie i wykorzystywanie ich we własnych projektach wymaga zgody autora.

Autor: [@piowerb](https://github.com/piowerb)
