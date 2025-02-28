﻿# PROJEKT: HIPERTEKST I HIPERMEDIA (HIH)

Projekt stworzony w ramach przedmiotu **Hipertekst i Hipermedia** na Politechnice Gdańskiej, kierunek Informatyka. Temat projektu: **Moje hobby**.

## Spis treści
- [Opis projektu](#opis-projektu)
- [Funkcjonalności](#funkcjonalności)
- [Wymagania technologiczne](#wymagania-technologiczne)
- [Uruchomienie projektu](#uruchomienie-projektu)
- [Autorzy](#autorzy)
- [Licencja](#licencja)

---

## Opis projektu
Strona internetowa przedstawiająca moje hobby. Projekt jest zgodny ze standardami HTML5 i spełnia wymagania responsywności, walidacji oraz poprawności składniowej.

Główne elementy projektu to:
- Strona w formacie HTML.
- Dokument XML opisujący dane zgodne z tematem projektu.
- Pliki walidacji: XML Schema (XSD) i DTD.

---

## Funkcjonalności
### Etap 1: HTML
- Zgodność z HTML5 i CSS3.
- Responsywność:
  - Obsługa minimum dwóch różnych wielkości ekranu.
  - Wykorzystanie `viewport`, `@media`, `viewport-width`.
- Walidacja HTML i CSS.
- Elementy strony:
  - Nagłówek, menu, stopka, główna treść (semantyczne znaczniki: `<header>`, `<nav>`, `<footer>`, `<figure>`).
- Multimedialne elementy:
  - Galeria zdjęć z miniaturkami i podglądem.
  - Prosta grafika SVG.
  - Animacje CSS3 z klatkami kluczowymi i efektami przejścia.
- Interaktywne elementy:
  - Tabela z danymi.
  - Odsyłacze do zewnętrznych stron oraz miejsc na stronie.
  - Formularz ankiety zawierający minimum 7 pól.

### Etap 2: XML
- Plik XML przechowujący dane o hobby, hierarchia minimum 4 poziomy.
- Atrybuty i elementy zorganizowane zgodnie z zasadami składni XML.
- Elementy:
  - Minimum 12 różnych nazw elementów.
  - Zdjęcia i linki do powiązanych zasobów.

### Etap 3: XML Schema
- Walidacja pliku XML za pomocą XSD.
- Różnorodne definicje typów złożonych i prostych.
- Ograniczenia na elementy i atrybuty (np. długość, wartości, wzorce).
- Elementy list, unii oraz wyprowadzenia typów.

### Etap 4: DTD
- Walidacja pliku XML za pomocą DTD.
- Deklaracje elementów, atrybutów, encji parametrycznych.

---

## Wymagania technologiczne
- **HTML5 i CSS3** – tworzenie i stylizacja strony.
- **XML, XSD, DTD** – struktura i walidacja danych.
- **Edytor tekstu** – Visual Studio Code lub dowolny inny edytor.
- **Walidatory online**:
  - HTML: [validator.w3.org](https://validator.w3.org/).
  - CSS: [jigsaw.w3.org/css-validator](http://jigsaw.w3.org/css-validator/).

---

## Uruchomienie projektu
### 1. Sklonuj repozytorium:
```bash
git clone https://github.com/polevczyc/projekt-hih.git
```
### 2. Otwórz plik `index.html` w przeglądarce.

## Autorzy
Jakub Polewczyk **192562**

## Licencja
Projekt udostępniany na licencji MIT. Szczegóły w pliku [LICENSE](LICENSE)

### Uwagi:
Wszelkie pytania i zgłoszenia błędów proszę kierować na adres email: [jakpol9822@gmail.com](mailto:jakpol9822@gmail.com)
