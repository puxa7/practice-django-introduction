> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s9e01-django-introduction` (dotyczy [mentee](https://devmentor.pl/mentoring-javascript/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#03` Django: Wprowadzenie

1. W folderze swojej aplikacji utwórz katalog `templates/first_app/`.
2. Stwórz szablon `info.html`, w którym wyświetlisz wartości zmiennych `author` i `year` w odpowiednich miejscach nagłówka i paragrafu.
3. W widoku przekaż do szablonu dane: `author` ustaw na „Anna Nowak”, a `year` na aktualny rok (np. za pomocą `datetime.now().year`).
4. Skonfiguruj routing tak, aby widok był dostępny pod adresem `/info/`.
5. Otwórz w przeglądarce adres http://127.0.0.1:8000/info/ i sprawdź, czy wyświetla się strona z napisem:
   
   Autor: Anna Nowak  
   Rok: [bieżący rok]

**Wskazówka:**
Zadbaj o poprawną strukturę katalogów dla szablonów — Django domyślnie przeszukuje folder `templates` wewnątrz aplikacji.


&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-django-introduction)*

> :arrow_left: [*poprzednie zadanie*](./../02) | [*następne zadanie*](./../04) :arrow_right:
