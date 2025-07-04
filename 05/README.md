> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s9e01-django-introduction` (dotyczy [mentee](https://devmentor.pl/mentoring-javascript/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#05` Django: Wprowadzenie

1. Stwórz szablon HTML zawierający formularz z jednym polem tekstowym `name` i przyciskiem „Wyślij”. Formularz powinien przesyłać dane metodą POST.
2. W widoku zaimplementuj obsługę dwóch metod:
   - dla zapytania GET wyświetl formularz,
   - dla zapytania POST pobierz przesłane imię i zwróć odpowiedź w formacie:
     
     Dziękujemy, <name>!
3. Zabezpiecz formularz tokenem CSRF.
4. Skonfiguruj routing tak, aby formularz był dostępny pod adresem `/form/`.
5. Sprawdź w przeglądarce, czy formularz działa prawidłowo i zwraca komunikat po wysłaniu danych.

**Wskazówka:**
Przypomnij sobie, jak w Django sprawdzić metodę zapytania w obiekcie `request` i jak odczytać dane przesłane formularzem metodą POST.

&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-django-introduction)*

> :arrow_left: [*poprzednie zadanie*](./../04) | ~~*następne zadanie*~~ :arrow_right:
