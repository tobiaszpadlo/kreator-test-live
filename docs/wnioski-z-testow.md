# Wnioski z testów — Kreator formularzy v1

**Przykład na danych fikcyjnych.** Uczestnicy, obserwacje i wypowiedzi poniżej są wymyślone. Raport pokazuje, jak zapisać wyniki po przeprowadzeniu testów z użytkownikami.

Przykładowa próba obejmuje trzy osoby, które okazjonalnie przygotowują ankiety. Każda zaczyna od listy formularzy po odświeżeniu strony i wykonuje trzy zadania z [planu testu](plan-testu.md). Wszystkie trzy osoby tworzą formularz i otwierają go po zapisie. Dwie samodzielnie zmieniają typ istniejącego pytania w dodatkowej próbie.

## Obserwacje

| Obszar | Przykładowa obserwacja |
| --- | --- |
| Utworzenie formularza | 3/3 osoby od razu wybierają „+ Nowy formularz”, nadają mu nazwę i dodają pytanie tekstowe oraz pytanie jednokrotnego wyboru. |
| Edycja treści i usuwanie | 3/3 osoby zmieniają treść pytania o częstotliwość i usuwają zbędne pole przed drugim podglądem. |
| Zmiana rodzaju odpowiedzi | Plan sprawdza zmianę typu, ale trzy główne zadania jej nie wymagają. W dodatkowym zadaniu („Zmień pytanie o częstotliwość tak, żeby odpowiedzi wybierało się z rozwijanej listy”) 2/3 osoby używają pola „Rodzaj odpowiedzi”. T3 najpierw szuka tej funkcji w panelu „Dodaj pytanie” i potrzebuje wskazówki. |
| Możliwe odpowiedzi | 3/3 osoby zastępują domyślne „Opcja 1” i „Opcja 2” własnymi odpowiedziami. T2 chwilę szuka miejsca do wpisania trzeciej, po czym wybiera „+ Dodaj odpowiedź”. |
| Podgląd | 3/3 osoby otwierają podgląd, rozpoznają w nim widok odbiorcy i wracają do edycji. T2 zatrzymuje się przy przycisku „Sprawdź zakończenie” i pyta, co się stanie po kliknięciu. |
| Zapis i ponowne otwarcie | 3/3 osoby zapisują formularz, znajdują go na liście po nazwie i otwierają go podczas tej samej próby. Po otwarciu widzą zmienione pytanie i odpowiedzi. |

Przykładowa wypowiedź T3 o zmianie typu: „Myślałem, że muszę dodać pytanie od nowa”. Przykładowa uwaga T1 dotycząca treści ankiety: zamiast „Rzadziej” uczestnik wolałby odpowiedź „Raz w miesiącu lub rzadziej”.

## Interpretacja wyników

- **Tworzenie formularza i edycja treści** mają potwierdzenie w przykładowej próbie. Zmiana typu istniejącego pytania ma częściowe potwierdzenie. Panel dodawania pytań może odciągać uwagę od ustawień na karcie pytania.
- **Konfiguracja odpowiedzi i rozpoznanie podglądu** mają potwierdzenie w tej próbie. Zawahania wskazują dwa miejsca do ponownego sprawdzenia — dodawanie kolejnej opcji i znaczenie przycisku na końcu podglądu.
- **Zapis w ramach jednej próby** spełnia przykładowe kryterium technologiczne. Udostępnianie, zbieranie odpowiedzi i trwałość zapisu po odświeżeniu pozostają poza zakresem testu.

## Pomysły do kolejnej iteracji

1. Uwydatnić możliwość zmiany rodzaju odpowiedzi na karcie istniejącego pytania. W kolejnym teście uwzględnić osobne zadanie zmiany typu i zanotować, czy uczestnik osiągnął cel samodzielnie oraz czy zachował treść pytania i opcje.
2. Sprawdzić, czy nazwa „Przetestuj wysłanie” lepiej oddaje działanie przycisku „Sprawdź zakończenie” w podglądzie.
