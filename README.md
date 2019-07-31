# Licencjat
Badanie reprezentatywności ofert pracy publikowanych na nabory.kprm.gov.pl 

Badanie zostało przeprowadzone w ramach pisania przez Autora jego pracy licencjackiej. Celem pracy była analiza ofert pracy na stanowiska w służbie cywilnej publikowanych na stronie naborów Kancelarii Prezesa Rady Ministrów poprzez stworzenie zbioru danych metodami
web-scrapingu i zastosowanie na tak stworzonym zbiorze danych modelu alokacji ukrytej Dichirleta. Rezultatem badania jest przybliżone zapotrzebowanie na pracowników wykonujących
pracę o różnym charakterze w służbie cywilnej.

Realizacja projektu odbywała się etapowo, zaś etapy stanowią poszczególne pliki .RMD . Kolejność, w jakiej tworzone były pliki jest następująca:
1A i 1B: kprm_scraping_current_final.Rmd i kprm_scraping_archive_final.Rmd  -- pobieranie danych internetowych
2: czyszczenie_danych.Rmd   -- doprowadzanie danych do stanu użytecznego
3: stopwords_stemming.Rmd -- usuwanie niepotrzebnych słów ze zbioru danych
4: wizualizacja_wstepna.Rmd -- eksploracja danych
5: lda-1.Rmd  -- zastosowanie modelu alokacji ukrytej Dirichleta
6: tfidf-lda-2.Rmd  -- drugie i finalne zastosowanie alokacji ukrytej Dirichleta (zbudowanie lepszego modelu)
7: opracowanie_wynikow.Rmd  -- analiza i tworzenie wykresów
