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

## Zdjęcia
### Program w języku CFC
![program](https://github.com/user-attachments/assets/1f06620b-9ef0-4034-a2fc-9e48e1b16e23)
### Panel operatorski okienko numer 1
![Pabel operatorski okienko 1](https://github.com/user-attachments/assets/323a13e8-4886-4798-8346-3633ff723e12)
### Panel operatorski okienko numer 2
![Panel operatorski numer 2](https://github.com/user-attachments/assets/2cffffee-8f2a-444b-b9b0-b06875c80348)

 ### Wady
Główną wadą tego projektu jest to, że nie odwzorowuje on w pełni rzeczywistości. Nie została zaimplementowana obróbka danych z czujników – wartości należy wprowadzać ręcznie.
Sygnały z czujników są jedynie symulowane poprzez naciśnięcie przycisków.

Niestety, nie mam możliwości stworzenia programu gotowego do wgrania na sterownik, ponieważ nie dysponuję odpowiednim sprzętem.
