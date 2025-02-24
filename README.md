# Linia do rozlewania żywicy do pojemników
Przedstawiony projekt został zrealizowany w ramach przedmiotu Systemy PLC.

### Oprogramowanie
- Codesys V3.5 SP 17 PATCH 3

### Język
- CFC

### Funkcje
Na panelu operatorskim znajdują się pola do wpisywania wartości, takie jak:
- odległość od ścianki pojemnika do otworu, przez który nalewana jest ciecz
- ilość cieczy do dozowania
Dostępne są również przyciski:
- START
- STOP
- Usuń awarię
- przycisk imitujący działanie czujnika
System sprawdza występowanie błędów:
- w sytuacjach awaryjnych program automatycznie wyłącza wszystkie procesy i sygnalizuje awarię za pomocą lampki ostrzegawczej

Więcej informacji na temat funkcji można znaleźć w dokumentacji.

 ### Wady
Główną wadą tego projektu jest to, że nie odwzorowuje on w pełni rzeczywistości. Nie została zaimplementowana obróbka danych z czujników – wartości należy wprowadzać ręcznie.
Sygnały z czujników są jedynie symulowane poprzez naciśnięcie przycisków.

Niestety, nie mam możliwości stworzenia programu gotowego do wgrania na sterownik, ponieważ nie dysponuję odpowiednim sprzętem.
