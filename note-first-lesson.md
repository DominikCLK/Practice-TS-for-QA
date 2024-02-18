# Wstęp

Główną różnicą między TypeScript a JavaScript to statyczne typowanie. Oznacza to, że musisz określić typy danych zmiennych i argumentów funkcji. Kompilator TypeScriptu sprawdza te typy przed uruchomieniem programu i ostrzega przed potencjalnymi błędami. Dzięki temu łatwiej uniknąć wielu błędów. TypeScript oferuje również dodatkowe funkcje, takie jak interfejsy, klasy, moduły i wiele innych

Najważniejsze cechy, przemawiające za wyborem języka TypeScript:

- Rozszerzenie JavaScript
> Oznacza, że ​​wszystkie poprawne programy napisane w JavaScript są również poprawnymi programami TypeScript.

- Statyczne typowanie
> W TypeScript deklarujemy typy zmiennych, argumentów funkcji, zwracanych wartości itp. Dzięki temu kompilator TypeScript może wykrywać błędy typowania i ostrzegać nas przed potencjalnymi problemami już na etapie pisania kodu.

- Nowe funkcje
> TypeScript wprowadza wiele nowych funkcji i składni, które nie są obecne w JavaScript. Przykłady to interfejsy, klasa abstrakcyjna, typy wyliczeniowe, typy generyczne, destrukturyzacja, przestrzenie nazw (namespaces) itp. Te funkcje ułatwiają rozwijanie bardziej złożonych aplikacji.

- Kompatybilność z JavaScript
> Istnieje pełna kompatybilność wsteczna z istniejącym kodem JavaScript. Można stopniowo wprowadzać TypeScript do istniejących projektów JavaScript i stopniowo dodawać statyczne typowanie tam, gdzie to konieczne.

- Kompilacja do JavaScript
> Kod napisany w TypeScript często musi zostać skompilowany do kodu JavaScript przed uruchomieniem w przeglądarce lub środowisku Node.js. Kompilacja odbywa się za pomocą tzw. kompilatora TypeScript, który przetwarza kod TypeScript na równoważny kod JavaScript.
Inną opcją jest narzędzie ts-node, która pozwala nam uruchamiać pliki TypeScript bez potrzeby dodatkowej ich kompilacji przed uruchomieniem. Ten sposób jest często wykorzystywany przy pisaniu skryptów i testów automatycznych.

- Rozwinięta społeczność i narzędzia
> TypeScript ma duże wsparcie społeczności programistycznej i jest aktywnie rozwijany. Istnieje wiele narzędzi, frameworków i bibliotek, które są specjalnie opracowane dla TypeScript, co ułatwia tworzenie aplikacji w tym języku.

## TypeScript przez testera może być wykorzystywany do:

- Pisania skryptów
- Tworzenia frameworków do testów automatycznych
> Wiele nowoczesnych narzędzi, jak Playwright, Cypress, Webdriver.io, wspierają ten język. Dzięki temu można w oparciu o TypeScript budować kompleksowe rozwiązania do testów UI oraz REST API.


TIP: Po co się kompiluje TS do JS?
Przeglądarki nie rozumieją języka TypeScript, a jedynie kod JavaScript. Dlatego kod TypeScript musi zostać skompilowany do JavaScript😉 W testach automatycznych nie jest potrzebna kompilacja. Wiele narzędzi “w locie” tłumaczy sobie język TS na JS.

źródło: https://jaktestowac.pl/lesson/ts1s01l02/
