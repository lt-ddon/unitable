[🇬🇧 English](README.en.md)
# Wprowadzenie
Unitable jest to tablica znaków Unicode, służąca do szybkiego wyszukiwania kodów znaków.
Stworzona jako minimalistyczne narzędzie przydatne w programowaniu koderów/dekoderów znaków.
# Sposób użycia
## UNITABLE 1
Jest to pierwsza wersja tabeli, wyświetla wszystkie bloki danego planu. Powoduje to duże obciążenie przeglądarki, dlatego zalecam używania na wydajnym sprzęcie.
Sposób użycia polega na wciśnięciu jednego z przycisków "Generuj plan" i wywołaniu funkcji wyszukiwania w przeglądarce (Ctrl+F), a następnie wpisaniu znaku bądź unikodu. Wówczas przeglądarka wyszuka znak.

Wyświetlanie tak dużej liczby znaków zużywa pamięć RAM i procesor, więc zalecam zachować ostrożność.
## UNITABLE 2
Wersja druga, dopracowana. Sposób użycia różni się zupełnie od wersji pierwszej. Znaki można wyszukiwać poprzez przeglądanie bloków używając przycisków "Poprzedni blok" i "Następny blok".
Jeśli chcesz wyszukać znak znając jego kod szesnastkowy, wpisz ją w pole obok przycisku "Znajdź kod", następnie potwierdź wciskając ten przycisk.
Jeśli chcesz wyszukać kod szesnastkowy danego znaku, wklej znak w pole obok przycisku "Znajdź znak", następnie kliknij przycisk.
## Legenda
Wyświetlane tabele pokazują bloki Unicode.
Po wyszukaniu znaku ukaże się czerwona ramka wskazująca pozycję znaku w bloku.
### B (Blok)
W lewym górnym rogu bloku znajduje się wartość "B:" oznaczająca ID bloku. Rysunek wyświetlany na górze strony przedstawia mapę bloków i ich zawartość.
### O (Offset)
W górnym wierszu nagłówkowym tabeli znajdują się wartości "O:" oznaczające pierwszą cyfrę szesnastkową unikodu.
### L (Linia)
Lewa kolumna nagłówkowa pokazuje wartości wierszy znaków. Wartości "L:" oznaczają pozostałe cyfry szesnastkowe unikodu.
