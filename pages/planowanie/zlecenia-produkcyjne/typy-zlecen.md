---
title: "Typy zleceń"
permalink: typy-zlecen.html 
---

! STRONA NIEAKTUALNA !

Przy tworzeniu zlecenia produkcyjnego mamy możliwość wyboru jednego z dwóch "Typów zleceń": z własną technologią bądź z technologią wzorcową. Dzięki temu mamy możliwość edycji technologii z poziomu każdego zlecenia.
Typ zlecenia z technologią wzorcową- przy pomocy {% include inline_image.html file="lupka.png" alt="Przycisk lupy" %} wybieramy z listy technologię, którą utworzyliśmy wcześniej ( **TECHNOLOGIE >> Technologie** ). Aby edytować taką technologię wybieramy {% include inline_image.html file="settingsIcon24.png" alt="settings" %} **Technologia** , a następnie {% include inline_image.html file="startIcon24.png" alt="Przycisk Dodaj nowe" %} **Powrót do edycji**. Tutaj można wprowadzać dowolne zmiany: zamieniać operację, zmieniać produkty, ilości, nazwy etc. Po zapisaniu zmian będą one przypisane TYLKO do tego konkretnego zlecenia produkcyjnego.  

{% include callout.html content='Przykład:  Produkujemy stołki, używając do tego konkretnej technologi. Do zakładu przychodzi jednorazowe zamówienie na 10 sz. takich stołków, jednak klient życzy sobie zastosować inne nogi niż standardowo. Produkt gotowy będzie produkowany tą samą technologią, jednak zmieni się jeden z produktów wchodzących w jego skład. Dzięki możliwości edycji można dokonać zmian na drzewie technologii podmieniając ten produkt. Nie trzeba więc zakładać nowej technologii, a zmiany będą widoczne tylko dla tego zlecenia. ' type="info" %}

  
Typ zlecenia z własną technologią - w tym wariancie tworzymy od zera nową technologię dla danego zlecenia. Technologia ta nie będzie później widoczna na liście technologii. Aby stworzyć taką technologię postępujemy analogicznie jak w pierwszym przypadku.  
  
Wpływ zmiany pola "Typ zlecenia":

- z technologią własną na technologię wzorcową - przy zapisie usuwamy dotychczas utworzoną technologię,
- z technologią wzorcową na technologię własną - utworzona przez nas struktura pozostaje taka jak dotychczas.

{% include callout.html content='Aby móc edytować technologię z poziomu zlecenia należy najpierw odblokować odpowiednie opcje w parametrach programu. Edycja technologii możliwa jest jedynie dla zlecenia będącego w stanie "Oczekujące". Po akceptacji nie ma możliwości wprowadzenia jakichkolwiek zmian.
' type="warning" %}

Aby to zrobić wybieramy **Administracja >> Parametry >> Zlecenia**, tam w zakładce "Główna" odznaczamy "Blokady", które chcemy zdjąć.
