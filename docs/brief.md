# Brief prototypu: Kreator formularzy

## 1. Problem
Osoba przygotowująca ankietę o użytkowaniu oprogramowania musiała skorzystać z zewnętrznego narzędzia. Ankieta działała, ale edycja formularza była ograniczona przez mały wybór typów pól. Formularze przygotowuje nieregularnie, ilekroć zbiera dane od użytkowników.

## 2. Użytkownik
Osoba, która chce zebrać informacje od szerszego grona ludzi i w tym celu przygotowuje formularz online.

## 3. Wartość
Ta osoba może łatwo przygotować formularz z różnymi typami pól i udostępnić go innym.

## 4. Zakres
Prototyp pokazuje jedną ścieżkę osoby przygotowującej formularz w przeglądarce na komputerze.

**Ekran 1 · Lista formularzy:** widać gotowe formularze do przejrzenia oraz możliwość utworzenia nowego.
**Ekran 2 · Edycja formularza:** użytkownik dodaje, usuwa i edytuje pola. Może wybrać pole otwarte tekstowe, pole jednokrotnego wyboru, pole wielokrotnego wyboru albo listę rozwijaną z wcześniej określonymi odpowiedziami.
**Ekran 3 · Podgląd formularza:** użytkownik widzi przygotowany formularz z dodanymi polami w wybranych typach.
**Ekran 4 · Zapis i lista:** użytkownik zapisuje formularz, wraca do listy i może go z niej ponownie otworzyć podczas tej samej próby.

**Dane w prototypie:** formularz: pola (typ: otwarte tekstowe, jednokrotny wybór, wielokrotny wybór, lista rozwijana; odpowiedzi określone wcześniej dla listy rozwijanej). Fikcyjne formularze na liście mają te same pola.

**Poza prototypem:** zbieranie odpowiedzi od osób wypełniających formularze, udostępnianie formularza innym oraz zachowanie zapisanych formularzy po ponownym otwarciu pliku HTML.

## 5. Co testujemy
**Założenie o użyteczności:** użytkownik bez podpowiedzi utworzy formularz i zrozumie, jak edytować istniejące pola. Nie potwierdzi się, jeśli podczas testu z 2–3 osobami testerzy nie będą wiedzieć, jak utworzyć formularz lub edytować pola.
**Założenie o technologii:** pojedynczy plik HTML pokaże tworzenie, podgląd, zapis i ponowne otwarcie formularza z listy podczas jednej próby na danych fikcyjnych. Nie potwierdzi się, jeśli po zapisaniu nie będzie można otworzyć formularza z listy.

## Pytania do specyfikacji
_Nie dotyczą prototypu. Agent budujący prototyp ich nie rozstrzyga._
- Jak docelowo zbierać odpowiedzi z udostępnionych formularzy? → decyduję ja
