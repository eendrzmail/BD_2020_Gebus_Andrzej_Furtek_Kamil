## Dokumentacja projektu w pliku dokumentacja.docx
### Link do filmu znajduje się w pliku links.md

Projekt ma na celu utworzenie aplikacji do obsługi biblioteki.

Plik erd.jpeg przedstawia diagram erd bazy danych, którą zamierzam utworzyć.

Projekt zamierzam stworzyć korzystając z:
- Angular (frontend)
- PHP (backend php łączące się z oracledb i wystawiające dane na zewnątrz w formie prostego rest API)
- OracleDB 

### Założenia bazy danych:

Książka:
  - może mieć kilku autorów (tabela łącząca)
  - może mieć kilka kategorii
  - może mieć tylko jedno wydawnictwo (lub wcale)
  - może istnieć wiele egzamplarzy jednej książki

Wypożyczenia:
  - Podczas wypożyczenia do bazy zapisywane są dane takie jak:
    - wypożyczany egzemplarz
    - czytelnik
    - obsługujący pracownik
    - data wypożyczenia
  - Pracownik filii może na życzenie klienta prolongować daną książkę po jej wypożyczeniu na kolejne 7dni
  
Pracownicy:
  - każdy pracownik ma login oraz hasło którym loguje się do systemu. Po zalogowaniu może dodawać oraz edytować wypozyczenia
  
## PL/SQL

W pl/sql zamierzam zaprogramować takie rzeczy jak:
  - generowanie loginu pracownika na podstawie jego danych osobowych
  - Obliczanie daty oddania na podstawie daty wypozyczenia oraz liczby prolongacji
  - Tworzenie top książek pod względem oceny oraz roku ich wydania
  - Analiza zarobków pracownikóa (mediany,średnie)
  

