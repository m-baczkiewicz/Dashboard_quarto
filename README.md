# Dashboard_quarto
Kursy walut

Projekt "Kursy walut" to interaktywny dashboard stworzony w R, który prezentuje aktualne dane na temat kursów walut oraz cen złota. Dane są pobierane z API Narodowego Banku Polskiego (NBP). Dashboard umożliwia wizualizację danych w postaci wykresów oraz tabel, co ułatwia analizę i porównanie kursów walut.

#Wymagane pakiety
 - library(httr)
 - library(jsonlite)
 - library(ggplot2)
 - library(dplyr)
 - library(DT)
 - library(RColorBrewer)
 - library(gridExtra)
 - library(grid)

#Struktura projektu:
Projekt jest zorganizowany w formie dashboardu z następującymi sekcjami:

1: Waluty
W tej sekcji znajdują się wizualizacje i dane dotyczące najpopularniejszych walut oraz cen złota.

2: Najpopularniejsze waluty
W tej sekcji znajdują się wykresy najpopularniejszych walut na podstawie danych z NBP.

3: Tabela z wszystkimi walutami
Wyświetlenie tabeli z kursami wszystkich walut.

4: Wartości w formie boxów
Wyświetlenie aktualnej wartości złota i EUR w formie boxów.

5: Ostatnie notowania EUR i złota
Wykresy przedstawiające ostatnie 10 notowań kursów EUR i cen złota.

6: Kurs sprzedaży i kupna EUR
Wykres przedstawiający kurs sprzedaży i kupna EUR z ostatnich 10 notowań.

Projekt "Kursy walut" to narzędzie umożliwiające interaktywną analizę kursów walut i cen złota na podstawie danych z API NBP. Dzięki przejrzystym wizualizacjom i tabelom, użytkownik może łatwo śledzić zmiany na rynku walutowym.


# Link do filmu promującego projekt

https://uam-my.sharepoint.com/:v:/g/personal/micbac2_st_amu_edu_pl/EWK2zuUcNdpLiI-O2Q1J5ZEB33mvYN512U1G0wCAoj77gw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&email=jakub.nowosad%40amu.edu.pl&e=884kbE
