<p align="center">
  <img src="logo.png" alt="ZmiennikPrawny" width="96" height="96">
</p>

<h1 align="center">zmiennikprawny.pl</h1>

<p align="center">
  Strona główna <b>ZmiennikPrawnego</b> – aplikacji do śledzenia nowych aktów prawnych z Dziennika Ustaw RP.
</p>

<p align="center">
  <a href="https://zmiennikprawny.pl"><b>Strona</b></a> ·
  <a href="https://zmiennikprawny.vercel.app"><b>Aplikacja</b></a> ·
  <a href="https://github.com/piowerb/ZmiennikPrawny"><b>Kod aplikacji</b></a>
</p>

<p align="center">
  <a href="https://zmiennikprawny.pl"><img alt="Status strony" src="https://img.shields.io/website?url=https%3A%2F%2Fzmiennikprawny.pl&label=zmiennikprawny.pl&up_message=online&down_message=offline&style=flat-square"></a>
  <img alt="GitHub Pages" src="https://img.shields.io/badge/hosting-GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
  <img alt="CSS" src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <br>
  <img alt="Dane: API Sejmu RP" src="https://img.shields.io/badge/dane-API_Sejmu_RP_(ELI)-005130?style=flat-square">
  <img alt="Bez ciasteczek" src="https://img.shields.io/badge/ciasteczka-brak-005130?style=flat-square">
  <img alt="Ostatni commit" src="https://img.shields.io/github/last-commit/piowerb/zmiennikprawny.pl?style=flat-square&label=ostatnia%20zmiana">
  <img alt="Licencja" src="https://img.shields.io/badge/licencja-wszelkie%20prawa%20zastrze%C5%BCone-lightgrey?style=flat-square">
</p>

<p align="center">
  <img src="docs/screenshot-desktop.png" alt="Strona zmiennikprawny.pl na komputerze" width="100%">
</p>

<p align="center">
  <img src="docs/screenshot-mobile-1.png" alt="Strona na telefonie – nagłówek" width="260">
  &nbsp;&nbsp;
  <img src="docs/screenshot-mobile-2.png" alt="Strona na telefonie – funkcje" width="260">
</p>

---

## 📋 O projekcie

ZmiennikPrawny pokazuje nowe ustawy, rozporządzenia i obwieszczenia zaraz po publikacji w Dzienniku Ustaw. Dane pochodzą z oficjalnego API Sejmu RP (ELI). Aplikacja jest darmowa i nie wymaga zakładania konta.

To repozytorium zawiera tylko stronę informacyjną. Sama aplikacja (React + TypeScript, hostowana na Vercel) jest w repozytorium [piowerb/ZmiennikPrawny](https://github.com/piowerb/ZmiennikPrawny).

## ℹ️ Co jest na stronie

- **Podgląd aplikacji na żywo** – ramka w nagłówku pobiera 3 najnowsze akty z API Sejmu; gdy API nie odpowie, pokazuje przykładowe pozycje
- **§ 1–5** – funkcje, jak to działa, dla kogo, plany rozwoju i FAQ, numerowane jak paragrafy w ustawie
- **Responsywność** – pełne dopasowanie do telefonów, w tym iPhone'ów z notchem (safe areas)
- **SEO** – dane strukturalne (WebSite, WebApplication, FAQPage), Open Graph, `sitemap.xml`, `robots.txt`
- **Prywatność** – zero ciasteczek, zero analityki, zero zewnętrznych skryptów

## 🛠 Technologia

| | |
|---|---|
| Strona | jeden statyczny plik `index.html` z wbudowanym CSS i JS |
| Biblioteki | brak – czysty HTML, CSS i JavaScript |
| Czcionki | systemowe (bez Google Fonts, więc bez przesyłania danych do Google) |
| Hosting | GitHub Pages z własną domeną (`CNAME`) |
| Dane | [API Sejmu RP – ELI](https://api.sejm.gov.pl/eli_pl.html) |

## 📁 Struktura

```
index.html            strona główna
logo.png              logo
favicon-48.png        ikona karty przeglądarki
apple-touch-icon.png  ikona na ekran główny iPhone'a
og-image.png          obrazek do podglądu linku w social media
robots.txt            ustawienia dla wyszukiwarek
sitemap.xml           mapa strony
CNAME                 domena zmiennikprawny.pl
docs/                 zrzuty ekranu do tego README
```

## ⚖️ Zastrzeżenie

ZmiennikPrawny nie jest serwisem Sejmu RP ani Rządowego Centrum Legislacji. Informacje mają charakter pomocniczy i nie stanowią porady prawnej. Wiążące są wyłącznie teksty aktów opublikowane w Dzienniku Ustaw RP.

## 📄 Licencja

Wszelkie prawa zastrzeżone. Kod i projekt strony można przeglądać w celach poglądowych. Kopiowanie i wykorzystywanie ich we własnych projektach wymaga zgody autora.

---

<p align="center">
  Autor: Piotr Werbowy (<a href="https://github.com/piowerb">@piowerb</a>) · <a href="mailto:kontakt@zmiennikprawny.pl">kontakt@zmiennikprawny.pl</a>
  <br>
  <b>ZmiennikPrawny – bądź na bieżąco z prawem</b> ⚖️
</p>
