# Dzień 6

## Materiały

1. https://www.w3schools.com/css/
2. https://www.w3schools.com/cssref/css_selectors.asp
3. https://www.w3schools.com/css/css_intro.asp
4. https://www.w3schools.com/css/css_syntax.asp
5. https://www.w3schools.com/css/css_selectors.asp
6. https://www.w3schools.com/css/css_howto.asp
7. https://www.w3schools.com/css/css_colors.asp
8. https://www.w3schools.com/css/css_background.asp
9. https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files

## Treść zadania


OK, w poprzednich dniach udało nam się zaimplementować strukturę HTML. Teraz pora, żeby nasza pierwszy design HTML zaczął ładnie wyglądać. Tym samym, dzisiaj zaczynamy przygodę z CSS  :)

1. Na początku musimy dodać nowy plik, w którym będziemy umieszczać nasz kod css.
Sposobów na dodanie pliku css jest kilka, my przedstawimy Ci dwie opcje
- Jeśli wolisz iść prostszą drogą* to w folderze w którym aktualnie pracujesz (czyli ten sam w którym masz plik index.html) utwórz po prostu nowy plik. Przypominamy, że aby dodać nowy plik w Twoim VSC wykonaj następujące kroki:
w sidebarze po lewej stronie powinnaś zobaczyć swój folder, a tuż obok niego małe ikonki, jedna z nich (ta najbardziej po lewej)
kliknij na nią
dodaj nowy plik, pamiętaj, że tym razem musi mieć rozszerzenie .css Nazwa może być również dowolna, ale najczęściej używaną nazwą jest index.css
- Trudniejsza droga  - polecamy, abyś przeczytała sobie te materiały, które wyjaśnią Ci jaką strukturę powinien mieć Twój folder. https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files
2.Jeśli:
- w punkcie 1 wybrałaś prostszą drogę zrób tak: wklej poniższy kod w tagu head, a więc pomiędzy <head> </head> do swojego pliku HTML
`<link href="./style.css" rel="stylesheet" type="text/css">`
Kropka przed nazwą pliku oznacza, że znajduje się on w tym samym folderze, w którym masz plik index.html
- w punkcie 2 wybrałaś trudniejszą drogę to zauważ, że ścieżka w href musi identyfikować Twój plik, a więc jeśli plik index.css znajduje się u Ciebie folderze /styles* to wówczas link powinien wyglądać tak
`<link href="styles/style.css" rel="stylesheet" type="text/css">`

Uff, udało nam się dodać plik, teraz zweryfikujmy, czy działa :) W materiałach znajdziesz https://www.w3schools.com/css/  Spróbuj dodać kolor: `blue` do wszystkich paragrafów na stronie Aby dowiedzieć się jak ostylować elementy HTML przeczytaj te materiały: https://www.w3schools.com/cssref/css_selectors.asp Nie martw się, nie musisz zapamiętywać wszystkiego, znajdź po prostu ten fragment, który podpowie Ci jak ostylować na stronie wszystkie elementy określonego typu - czyli w naszym przypadku p..
Jeśli czujesz się nieco przytłoczona ilością materiałów - poniżej drobna ściągawka :)
3. Aby dodać kolor to wszystkich paragrafów na naszej stronie musimy do naszego pliku css dodać poniższy kod:

p  {
color: blue
}

4. Dla chętnych: Spróbuj pobawić się CSSem na podstawie poniższych materiałów. Na przykład spraw, aby wszystkie elementy listy były zielone, a nasz biały box miał teraz żółty kolor tła. Udało Ci się? 

