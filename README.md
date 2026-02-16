# Steam-Top-50-Games-2024-2025
1️⃣ Opis projektu
Tytuł

AAA vs AA vs Indie – Trendy rynkowe na platformie Steam (2024–2025)

Opis

Projekt analizuje trendy na rynku gier komputerowych na platformie Steam w okresie od września 2024 do grudnia 2025, koncentrując się na porównaniu produkcji z segmentu AAA, AA oraz Indie.

Analiza opiera się na danych estymowanych i zagregowanych, ponieważ wydawcy nie udostępniają szczegółowych danych sprzedażowych.
W związku z tym projekt skupia się na kierunku trendów, dynamice wzrostu oraz relatywnej wydajności segmentów, a nie na dokładnych wartościach sprzedażowych.

Cel biznesowy

Celem projektu jest ocena, czy gry Indie są w stanie osiągać wyniki rynkowe porównywalne z wysokobudżetowymi produkcjami AAA oraz analiza wpływu ceny, gatunku i czasu od premiery na poziom adopcji graczy.

2️⃣ Kluczowe pytania biznesowe

Analiza odpowiada na następujące pytania:

Jak w czasie rośnie liczba graczy w segmentach AAA, AA i Indie?

Czy wyższa cena koreluje z większą liczbą właścicieli gry?

Czy gry Indie są konkurencyjne pod względem mediany liczby graczy?

Które gatunki przyciągają największą liczbę odbiorców?

Czy tryb multiplayer istotnie wpływa na poziom popularności gry?

3️⃣ Dane i założenia
Źródła danych

Publiczne statystyki platformy Steam

Ogólnodostępne estymacje branżowe

Dane przygotowane i oczyszczone manualnie

Kluczowe założenia

Liczba właścicieli gry jest wartością estymowaną, a nie oficjalną sprzedażą

Dane przedstawiają miesięczne snapshoty (stan na dany miesiąc), a nie pojedyncze zdarzenia sprzedażowe

Cena odzwierciedla cenę katalogową w danym okresie

Ta sama gra występuje wielokrotnie w różnych miesiącach

Ograniczenia

Brak dostępu do rzeczywistych danych przychodowych i kosztowych

Brak podziału regionalnego

Brak danych dotyczących retencji i odpływu graczy

Z uwagi na powyższe ograniczenia, wnioski koncentrują się na trendach relatywnych, a nie na bezwzględnych wartościach sprzedaży.

4️⃣ Model danych i granularność
Granularność

Gra × Miesiąc

Liczba właścicieli reprezentuje skumulowaną liczbę graczy w danym miesiącu

Cena jest atrybutem nieaddytywnym

Kluczowe decyzje projektowe

Zastosowano medianę zamiast sumy przy analizie liczby właścicieli i ceny

Uniknięto sumowania cen, aby zapobiec sztucznemu zawyżaniu wartości

Skupiono się na medianach w celu ograniczenia wpływu gier typu blockbuster na wyniki analizy

5️⃣ KPI i metryki
Główne KPI:

Mediana estymowanej liczby właścicieli

Mediana ceny

Mediana wzrostu od momentu premiery

Liczba właścicieli według gatunku

Dlaczego mediana?

Dane dotyczące popularności są silnie skośne

Niewielka liczba hitów znacząco zawyża średnią

Mediana lepiej reprezentuje „typową” grę w danym segmencie

6️⃣ Kluczowe wnioski

Gry AAA szybciej osiągają wysoką liczbę właścicieli, głównie dzięki skali marketingowej

Gry Indie wykazują konkurencyjny wzrost długoterminowy, mimo niższych cen

Cena nie wykazuje liniowej zależności z liczbą właścicieli

Gatunki takie jak FPS i Action RPG dominują we wszystkich segmentach produkcyjnych

Obecność trybu multiplayer zwiększa popularność gry, szczególnie w segmencie Indie

7️⃣ Wniosek biznesowy

Chociaż gry AAA dominują pod względem początkowej skali adopcji, głównie dzięki budżetom marketingowym i rozpoznawalności marki, segment Indie wykazuje istotny potencjał długoterminowy.

Gry Indie często osiągają porównywalny poziom popularności przy znacznie niższych cenach, co może wskazywać na wyższą efektywność kosztową.

Z perspektywy inwestycyjnej i dywersyfikacji portfela, segment Indie stanowi obszar o relatywnie niższym ryzyku i wysokim potencjale wzrostu — szczególnie przy odpowiednim doborze gatunku oraz modelu multiplayer.

8️⃣ Narzędzia i technologie

SQL Server – modelowanie danych i transformacje

Power BI – wizualizacja danych i budowa dashboardu

DAX – tworzenie miar i agregacji kontekstowych

9️⃣ Podgląd dashboardu

(W tym miejscu należy umieścić zrzut ekranu dashboardu.)

🔟 Dalszy rozwój projektu

Dodanie scenariuszowej estymacji przychodów

Rozszerzenie analizy o kolejne lata

Wprowadzenie modelowania retencji graczy

Porównanie danych Steam z rynkiem konsolowym
