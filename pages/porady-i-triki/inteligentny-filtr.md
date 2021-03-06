---
title: "Inteligentny filtr"
permalink: inteligentny-filtr.html
---
 Inteligentny filtr w qcadoo pozwala na szybkie i wygodne wyszukiwanie interesujących nas pozycji. Dzięki tej funkcji nie musimy wertować stron z poszczególnymi nazwami, wystarczy wpisać interesujące nas wyrażenie w pole filtru i zostanie ono odnalezione. 

Filtrować możemy nie tylko nazwy i numery, lecz także daty. Ten rodzaj filtrowania umożliwia nam wyszukiwanie dat na dwa sposoby:

1. Wyszukiwanie konkretnej daty, nawet z dokładnością do godziny. Pożądany format daty to: RRRR-MM-DD gg:mm:ss. Aby filtr zadziałał, wymagane jest tylko wpisanie roku. Można więc pominąć np. miesiąc, dzień i czas. Przykładowo: możemy użyć filtru wpisując tylko rok „2013”, albo dzień: „2013-01” itd.  
  
2. Wyszukiwanie daty wcześniejszej (\<) lub późniejszej (\>) od interesującego nas terminu.Przykładowo: na liście zleceń chcemy wyszukać te, które zostały rozpoczęte po 1 maja 2013 r. Wystarczy wtedy wpisać w oknie filtru: „\>2013-05-01” i otrzymamy wówczas interesującą nas listę zleceń.

Do filtrowania wartości można również wykorzystać następujące znaczniki:

1. "%" - znacznik ten wyszuka wszystkie pozycje, które mają wprowadzone jakikolwiek ciąg znaków w danej kolumnie. Można go łączyć z tektstem np. wyszukując nazwę produktu, możemy go wprowadzić w środek tekstu.

2. "_" - podłoga działa w podobny sposób jak "%", z taką różnicą, że zastępuje on pojedynczy znak.

3. Isnull - wyraz ten wyszuka pozycje, które w danej kolumnie nie mają wpisanej wartości.

4. "[nazwa_produktu]" - Domyślnie filtr wyszukuje wszystko co w danej wartości znajdzie, jeśli poszukiwany jest tylko dany wyraz, musimy umieścić ciąg znaków w "[]". 
