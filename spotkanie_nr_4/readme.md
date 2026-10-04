# Projekt dyplomowy — spotkanie 04
## Jak opisać wytwór w pracy dyplomowej?

---

## Cel spotkania

Na wcześniejszych etapach:

- określiliśmy problem i odbiorcę,
- przygotowaliśmy insight i brief projektowy,
- wybraliśmy formę rozwiązania i technologię,
- rozpoczęliśmy realizację,
- przygotowaliśmy pierwszą działającą wersję wytworu,
- zaczęliśmy dokumentować proces.

Teraz przechodzimy do kolejnego ważnego elementu:

> **trzeba opisać wytwór w taki sposób, aby osoba, która nie tworzyła projektu, mogła zrozumieć jego cel, logikę, funkcjonalności i sposób powstania.**

Opis wytworu powinien stanowić fragment pracy dyplomowej.

Nie jest to:

- instrukcja obsługi,
- dokumentacja programistyczna,
- lista bibliotek,
- opis kodu linia po linii,
- historia wszystkiego, co wydarzyło się podczas realizacji.

Jest to **spójny opis rozwiązania projektowego**.

---

# 1. Co powinien zrozumieć czytelnik?

Po przeczytaniu fragmentu dotyczącego wytworu czytelnik powinien potrafić odpowiedzieć na pytania:

1. Dlaczego wytwór powstał?
2. Z czego wynika jego forma?
3. Dla kogo jest przeznaczony?
4. Jaki problem ma rozwiązywać?
5. Jak działa?
6. Jakie posiada najważniejsze funkcjonalności?
7. Jakich technologii użyto?
8. Dlaczego wybrano właśnie te technologie?
9. Jak przebiegał proces realizacji?
10. Jakie są ograniczenia obecnej wersji?
11. Jak można ją dalej rozwijać?

Jeżeli po przeczytaniu opisu nadal trzeba uruchomić aplikację albo przeczytać kod, aby zrozumieć projekt, opis jest niewystarczający.

---

# 2. Możliwa struktura fragmentu pracy

Nie istnieje jeden obowiązkowy układ dla wszystkich projektów.

W większości przypadków można jednak zastosować strukturę zbliżoną do poniższej:

```text
X. Wytwór technologiczny

X.1. Geneza i założenia projektu
X.2. Cel i odbiorcy rozwiązania
X.3. Założenia projektowe
X.4. Zastosowane technologie
X.5. Funkcjonalności wytworu
X.6. Logika działania
X.7. Proces realizacji
X.8. Ograniczenia
X.9. Możliwości dalszego rozwoju
```

Nie wszystkie projekty wymagają dokładnie tylu podrozdziałów.

Niektóre elementy można połączyć.

Przykładowo:

```text
X. Projekt i implementacja wytworu

X.1. Założenia projektowe
X.2. Technologie i sposób realizacji
X.3. Funkcjonalności i logika działania
X.4. Ograniczenia i dalszy rozwój
```

Najważniejsza jest **logika i czytelność opisu**, a nie liczba nagłówków.

---

# 3. Geneza wytworu

Ta część odpowiada na pytanie:

> **Skąd w ogóle wziął się pomysł na to rozwiązanie?**

Powinna łączyć wytwór z wcześniejszymi częściami pracy.

Może odnosić się do:

- wyników badań,
- problemu psychologicznego,
- części teoretycznej,
- potrzeb użytkowników,
- określonych mechanizmów psychologicznych.

Nie należy ponownie przepisywać całego rozdziału teoretycznego ani wyników badań.

Trzeba wybrać te elementy, które **bezpośrednio wpłynęły na projekt**.

---

## Przykład — źle

> Badanie wykazało, że istnieje korelacja pomiędzy stresem a poczuciem własnej skuteczności. Na tej podstawie stworzono aplikację.

Problem:

- nie wiadomo, dlaczego właśnie aplikacja,
- nie wiadomo, co aplikacja ma robić,
- nie wiadomo, w jaki sposób wynik badania wpłynął na projekt.

---

## Przykład — lepiej

> Wyniki badania wskazały na związek pomiędzy nasileniem stresu związanego z procesem rekrutacji a poziomem poczucia własnej skuteczności. Na tej podstawie przyjęto, że projektowane rozwiązanie powinno nie tylko przekazywać informacje dotyczące przygotowania do rekrutacji, ale również angażować użytkownika w działania wspierające poczucie sprawczości. Założenie to stało się podstawą do przygotowania interaktywnego narzędzia prowadzącego użytkownika przez kolejne etapy przygotowania do procesu rekrutacyjnego.

Tutaj widać już:

```text
wynik
↓
wniosek
↓
założenie projektowe
↓
rozwiązanie
```

---

# 4. Cel wytworu

Cel powinien być opisany konkretnie.

Unikaj zdań typu:

> Celem projektu było stworzenie aplikacji.

Stworzenie aplikacji jest **czynnością**, a nie właściwym celem.

Lepsza konstrukcja:

> Celem wytworu jest wspieranie [...] poprzez [...].

Przykład:

> Celem wytworu jest wspieranie studentów rozpoczynających poszukiwanie pierwszej pracy w przygotowaniu do procesu rekrutacji poprzez krótkie, ustrukturyzowane ćwiczenia wzmacniające poczucie własnej skuteczności.

---

# 5. Odbiorca

W opisie należy jasno określić, dla kogo powstał produkt.

Przykład:

> Narzędzie przeznaczone jest dla studentów ostatnich lat studiów oraz absolwentów rozpoczynających poszukiwanie pierwszej pracy związanej z kierunkiem kształcenia.

Warto wskazać również te cechy odbiorcy, które rzeczywiście wpłynęły na sposób projektowania rozwiązania.

---

# 6. Założenia projektowe

Założenia projektowe powinny wynikać z wcześniejszej analizy problemu.

Przykładowo:

> Na podstawie wyników badań oraz przyjętych założeń teoretycznych określono następujące główne założenia projektowe:
>
> 1. rozwiązanie powinno prowadzić użytkownika przez proces krok po kroku,
> 2. pojedyncza interakcja powinna być krótka,
> 3. użytkownik powinien wykonywać aktywne zadania,
> 4. narzędzie powinno udzielać informacji zwrotnej,
> 5. korzystanie z rozwiązania nie powinno wymagać instalowania dodatkowego oprogramowania.

Nie chodzi o tworzenie wymagań systemowych jak w dużym projekcie informatycznym.

Interesują nas przede wszystkim **założenia mające znaczenie dla celu pracy**.

---

# 7. Uzasadnienie decyzji projektowych

Jednym z ważniejszych elementów opisu jest odpowiedź na pytanie:

> **Dlaczego projekt wygląda właśnie tak?**

Nie wystarczy opisywać efektu.

---

## Słabo

> Aplikacja została podzielona na siedem etapów.

---

## Lepiej

> Proces podzielono na siedem krótkich etapów. Decyzja ta wynikała z założenia, że użytkownik powinien realizować kolejne zadania stopniowo, zamiast otrzymywać jednocześnie dużą ilość informacji.

---

## Słabo

> Zastosowano chatbot.

---

## Lepiej

> Zdecydowano się na formę chatbota ze względu na sekwencyjny charakter interwencji. Interfejs konwersacyjny umożliwia prowadzenie użytkownika przez kolejne pytania i ćwiczenia oraz prezentowanie informacji w niewielkich porcjach.

---

# 8. Opis technologii

Opis technologii powinien być **zwięzły i podporządkowany projektowi**.

Nie trzeba pisać wielostronicowej historii:

- Pythona,
- HTML,
- JavaScript,
- frameworka,
- modelu językowego.

Należy przede wszystkim wyjaśnić:

1. co zostało wykorzystane,
2. do czego,
3. dlaczego.

---

## Przykład

> Aplikację wykonano w języku Python przy użyciu biblioteki Streamlit. Narzędzie to umożliwia szybkie tworzenie interaktywnych aplikacji webowych bez konieczności przygotowywania oddzielnej warstwy frontendowej. Wybór Streamlit pozwolił skoncentrować realizację projektu na logice działania narzędzia oraz sposobie interakcji z użytkownikiem.

---

# 9. Technologia nie jest głównym bohaterem

Nie pisz:

> Python jest interpretowanym językiem programowania wysokiego poziomu stworzonym przez Guido van Rossuma...

jeżeli ta informacja nie ma znaczenia dla projektu.

Czytelnik nie potrzebuje podręcznika do Pythona.

Potrzebuje informacji:

> **dlaczego Python został wykorzystany w tym projekcie.**

---

# 10. Jeżeli wykorzystujesz AI

Opis powinien jasno określać:

- jaki model lub usługa została wykorzystana,
- do jakiego zadania,
- jakie dane otrzymuje,
- jaki rodzaj odpowiedzi zwraca,
- jak wynik jest wykorzystywany przez system.

Nie wystarczy napisać:

> W projekcie wykorzystano sztuczną inteligencję.

---

## Przykład

> Model językowy wykorzystano do klasyfikowania swobodnych wypowiedzi użytkownika do jednej z przygotowanych kategorii odpowiedzi. Wynik klasyfikacji służy następnie do wyboru kolejnego etapu scenariusza.

To znacznie bardziej wartościowa informacja niż sam fakt wykorzystania AI.

---

# 11. Opis funkcjonalności

Opis funkcjonalności powinien przedstawiać **co użytkownik może zrobić i jaką rolę pełni dany element**.

Nie musi być instrukcją obsługi.

---

## Słabo

> Na stronie znajduje się przycisk „Dalej”. Po jego kliknięciu użytkownik przechodzi dalej.

---

## Lepiej

> Interwencja została podzielona na kolejne etapy realizowane sekwencyjnie. Po zakończeniu ćwiczenia użytkownik przechodzi do następnego kroku, co pozwala zachować ustaloną kolejność procesu.

---

# 12. Opisuj funkcje w kontekście celu

Dobrze jest zachować relację:

```text
POTRZEBA
↓
ZAŁOŻENIE
↓
FUNKCJONALNOŚĆ
```

Przykład:

```text
Potrzeba:
użytkownik potrzebuje informacji o postępie

↓

Założenie:
system powinien pokazywać aktualny etap

↓

Funkcjonalność:
pasek postępu
```

W pracy można to zapisać:

> Aby użytkownik miał możliwość śledzenia aktualnego etapu procesu, w interfejsie zastosowano pasek postępu wskazujący liczbę ukończonych i pozostałych kroków.

---

# 13. Logika działania

Czytelnik powinien wiedzieć, **co dzieje się z punktu widzenia całego systemu**.

Przykład:

> Po uruchomieniu aplikacji użytkownik rozpoczyna nową sesję. System przedstawia pierwszy etap procesu oraz związane z nim ćwiczenie. Po udzieleniu odpowiedzi aplikacja zapisuje wybór i wyświetla odpowiednią informację zwrotną. Następnie użytkownik przechodzi do kolejnego etapu. Po wykonaniu wszystkich zadań generowane jest podsumowanie procesu.

Taki opis jest często bardziej wartościowy niż szczegółowy opis kodu.

---

# 14. Czy potrzebuję diagramu?

Nie ma obowiązku przygotowywania rozbudowanych diagramów technicznych.

Jeżeli prosty schemat:

```text
START
 ↓
ETAP 1
 ↓
ETAP 2
 ↓
WYNIK
```

ułatwia zrozumienie produktu — warto go zastosować.

Jeżeli diagram nie wnosi niczego ponad to, co jasno opisano tekstem, nie ma potrzeby tworzenia go wyłącznie po to, aby „był diagram”.

---

# 15. Proces realizacji

Opis procesu tworzenia wytworu nie powinien być kroniką każdego dnia pracy.

Nie pisz:

> Najpierw utworzono projekt. Następnie utworzono plik. Później dodano bibliotekę. Kolejnego dnia wykonano przycisk.

Interesują nas ważniejsze etapy.

---

## Przykład

> Realizację rozpoczęto od przygotowania podstawowego scenariusza interakcji. Następnie zaimplementowano główną ścieżkę użytkownika obejmującą trzy pierwsze etapy procesu. Po konsultacji zmodyfikowano sposób prezentowania treści, ograniczając długość pojedynczych komunikatów. W kolejnym etapie dodano mechanizm zapisywania aktualnego postępu oraz ekran podsumowania.

Taki opis pokazuje:

- kolejność pracy,
- rozwój rozwiązania,
- istotne zmiany,
- wpływ iteracji na produkt.

---

# 16. Nie dokumentuj odrzuconych pomysłów dla samego dokumentowania

Nie ma potrzeby opisywania:

- każdej testowanej biblioteki,
- każdego błędu,
- wszystkich wcześniejszych kolorów,
- każdego pomysłu, który pojawił się przez pięć minut.

Warto opisać zmianę, jeżeli **miała znaczenie dla końcowego produktu**.

---

# 17. Jak pisać o zmianach?

Przykład:

> Początkowo zakładano możliwość swobodnego wpisywania odpowiedzi przez użytkownika. Podczas realizacji zrezygnowano z tego rozwiązania na rzecz odpowiedzi wybieranych z przygotowanej listy. Pozwoliło to zachować przewidywalny przebieg scenariusza oraz ograniczyć ryzyko wygenerowania odpowiedzi niezwiązanych z celem interwencji.

To nie jest przyznanie się do błędu.

To pokazuje **świadomy proces projektowy**.

---

# 18. Zrzuty ekranu

Zrzuty ekranu są jednym z najlepszych sposobów pokazania wytworu w pracy.

Powinny jednak mieć konkretną funkcję.

Screenshot powinien:

- prezentować istotny element,
- być czytelny,
- mieć podpis,
- zostać omówiony w tekście.

---

## Źle

> Rysunek 4. Screenshot aplikacji.

---

## Lepiej

> Rysunek 4. Widok drugiego etapu interwencji zawierającego ćwiczenie identyfikacji dotychczasowych osiągnięć użytkownika.

---

# 19. Screenshot nie zastępuje opisu

Nie wystarczy:

> Interfejs przedstawiono na rysunku 5.

Należy wyjaśnić, co jest istotne.

Przykład:

> W centralnej części interfejsu prezentowane jest aktualne pytanie, natomiast pasek znajdujący się w górnej części wskazuje postęp użytkownika. Zdecydowano się na prezentowanie jednego pytania jednocześnie, aby ograniczyć ilość informacji widocznych na ekranie.

---

# 20. Nie pokazuj wszystkiego

Jeżeli aplikacja posiada:

- 20 podobnych ekranów,
- 30 komunikatów,
- 15 wariantów tego samego formularza,

nie trzeba umieszczać wszystkich w głównej treści pracy.

Wybierz elementy reprezentatywne.

Pełniejsze materiały mogą znaleźć się w dokumentacji lub załącznikach.

---

# 21. Ograniczenia

Każdy wytwór ma ograniczenia.

Opisanie ich **nie obniża wartości pracy**.

Pokazuje, że autor rozumie granice przygotowanego rozwiązania.

---

## Przykłady ograniczeń

> Aktualna wersja aplikacji nie posiada systemu trwałego zapisywania kont użytkowników.

> Model językowy może generować różne odpowiedzi dla podobnych danych wejściowych.

> Prototyp został przygotowany wyłącznie dla urządzeń o rozdzielczości typowej dla komputerów stacjonarnych.

> Badanie nie obejmowało rzeczywistego testowania skuteczności interwencji.

---

# 22. Ograniczenie a błąd

Nie pisz:

> Nie zdążyłem zrobić aplikacji mobilnej.

Lepiej:

> Aktualny zakres projektu obejmuje aplikację webową. Przygotowanie osobnej wersji mobilnej pozostawiono jako możliwy kierunek dalszego rozwoju.

Jeżeli coś zostało świadomie pozostawione poza zakresem, należy to tak przedstawić.

---

# 23. Dalszy rozwój

Dalszy rozwój powinien wynikać z rzeczywistych ograniczeń projektu.

Przykładowo:

```text
OGRANICZENIE
Brak trwałego konta użytkownika

↓

MOŻLIWY ROZWÓJ
Dodanie systemu kont i synchronizacji postępów
```

lub:

```text
OGRANICZENIE
Brak badania skuteczności narzędzia

↓

MOŻLIWY ROZWÓJ
Badanie pre-post z grupą kontrolną
```

---

# 24. Język opisu

Opis powinien mieć charakter **akademicki, ale zrozumiały**.

Nie trzeba sztucznie komplikować zdań.

---

## Zbyt potocznie

> Zrobiliśmy chatbota, który gada z użytkownikiem i daje mu ćwiczenia.

---

## Zbyt technicznie

> Event handler wywołuje callback powodujący zmianę wartości zmiennej stanu odpowiedzialnej za indeks aktualnego node'a.

---

## Lepiej

> Chatbot prowadzi użytkownika kolejno przez przygotowane etapy interwencji. Po zakończeniu każdego etapu zapisywany jest aktualny postęp, a użytkownik przechodzi do kolejnego elementu scenariusza.

---

# 25. Unikaj opisu oczywistości

Nie trzeba wyjaśniać:

> Przycisk jest elementem interfejsu umożliwiającym użytkownikowi wykonanie określonej akcji.

Opisz raczej:

> **jaką rolę ten element pełni w Twoim rozwiązaniu.**

---

# 26. Terminologia

W obrębie całego opisu używaj spójnego nazewnictwa.

Jeżeli używasz określenia:

> „etap interwencji”

nie zmieniaj później bez potrzeby na:

> „moduł”, „poziom”, „część”, „sesję”

jeżeli wszystkie te słowa opisują dokładnie to samo.

Spójne nazewnictwo bardzo poprawia czytelność pracy.

---

# 27. Opis wytworu a instrukcja obsługi

Nie pisz:

> Aby rozpocząć, użytkownik powinien kliknąć zielony przycisk znajdujący się w prawym dolnym rogu ekranu.

chyba że takie szczegóły mają znaczenie dla projektu.

Lepiej:

> Po uruchomieniu aplikacji użytkownik może rozpocząć nowy proces interwencji.

---

# 28. Opis wytworu a dokumentacja kodu

Nie opisuj kodu funkcja po funkcji.

Zamiast:

```text
Funkcja get_response() przyjmuje argument text.
Następnie wywołuje funkcję classify().
```

lepiej:

> Moduł odpowiedzialny za analizę wypowiedzi użytkownika klasyfikuje wprowadzony tekst, a uzyskany wynik jest wykorzystywany do wyboru kolejnego elementu scenariusza.

Kod źródłowy może zostać dostarczony osobno.

---

# 29. Jak sprawdzić jakość opisu?

Po napisaniu fragmentu spróbuj odpowiedzieć:

### Czy osoba nieznająca mojego projektu wie:

- dlaczego powstał?
- dla kogo powstał?
- co robi?
- jak działa?
- dlaczego wygląda właśnie tak?
- z czego został wykonany?
- jak przebiegał proces jego tworzenia?
- jakie ma ograniczenia?

Jeżeli odpowiedź na któreś z tych pytań brzmi „nie”, prawdopodobnie czegoś brakuje.

---

# 30. Roboczy szablon opisu

Możesz wykorzystać poniższą strukturę jako punkt wyjścia.

---

## X. Wytwór technologiczny

### X.1. Geneza i cel wytworu

> Na podstawie [...]
>
> Zidentyfikowano [...]
>
> Z tego względu przyjęto [...]
>
> Celem wytworu jest [...]

---

### X.2. Założenia projektowe

> Na podstawie [...] przyjęto następujące założenia [...]

Najważniejsze założenia:

1. ...
2. ...
3. ...

---

### X.3. Zastosowane technologie

> Do realizacji wytworu wykorzystano [...]
>
> Wybór [...] wynikał z [...]
>
> Technologia ta umożliwiła [...]

---

### X.4. Funkcjonalności

> Wytwór umożliwia [...]

Najważniejsze funkcjonalności:

1. ...
2. ...
3. ...

Każdą z nich należy **opisać**, a nie tylko wymienić.

---

### X.5. Logika działania

> Proces rozpoczyna się od [...]
>
> Następnie [...]
>
> W zależności od [...]
>
> Proces kończy się [...]

---

### X.6. Proces realizacji

> Realizację rozpoczęto od [...]
>
> Następnie [...]
>
> W wyniku [...]
>
> Zmieniono [...]

---

### X.7. Ograniczenia i dalszy rozwój

> Aktualna wersja rozwiązania [...]
>
> Głównym ograniczeniem jest [...]
>
> W przyszłości rozwiązanie można rozszerzyć o [...]

---

# 31. Karta projektu — spotkanie 04

Na konsultację przygotuj **roboczy fragment pracy dotyczący wytworu**.

Nie musi to być jeszcze wersja ostateczna.

Powinien jednak zawierać rzeczywistą treść, a nie wyłącznie nagłówki.

---

## Geneza

**Z czego wynika potrzeba stworzenia wytworu?**

> ...

---

## Cel

> ...

---

## Odbiorca

> ...

---

## Założenia projektowe

1. ...
2. ...
3. ...

---

## Technologie

| Technologia / narzędzie | Zastosowanie | Uzasadnienie |
|---|---|---|
| ... | ... | ... |
| ... | ... | ... |

---

## Funkcjonalności

| Funkcjonalność | Jak działa? | Dlaczego istnieje? |
|---|---|---|
| ... | ... | ... |
| ... | ... | ... |

---

## Główny workflow

```text
...
↓
...
↓
...
↓
...
```

---

## Proces realizacji

**Najważniejsze etapy:**

1. ...
2. ...
3. ...

---

## Najważniejsze zmiany podczas realizacji

| Co zmieniono? | Dlaczego? |
|---|---|
| ... | ... |
| ... | ... |

---

## Ograniczenia

1. ...
2. ...
3. ...

---

## Możliwy dalszy rozwój

1. ...
2. ...
3. ...

---

## Materiały wizualne

- [ ] ekran startowy,
- [ ] główna funkcjonalność,
- [ ] przykładowa interakcja,
- [ ] wynik / podsumowanie,
- [ ] inne istotne elementy.

---

# 32. Milestone 04

Po tym etapie powinny istnieć:

- [ ] rozwinięta wersja wytworu,
- [ ] opis genezy i celu wytworu,
- [ ] opis odbiorców,
- [ ] opis założeń projektowych,
- [ ] opis i uzasadnienie technologii,
- [ ] opis głównych funkcjonalności,
- [ ] opis logiki działania,
- [ ] rozpoczęty opis procesu realizacji,
- [ ] materiały wizualne,
- [ ] lista ograniczeń,
- [ ] propozycje dalszego rozwoju.

Najważniejszym efektem tego etapu jest sytuacja:

> **wytwór nie tylko istnieje — istnieje również jego rzeczywisty opis, który można dalej poprawiać i wykorzystać w pracy dyplomowej.**

---

# 33. Na kolejne spotkanie

Spotkanie 05 jest ostatnim regularnym milestone'em przed oddaniem projektu.

Na kolejne zajęcia należy przygotować:

1. wytwór możliwie zbliżony do wersji finalnej,
2. kompletny roboczy opis wytworu,
3. komplet materiałów dokumentacyjnych,
4. zrzuty ekranu i inne materiały wizualne,
5. materiały przeznaczone do załączników,
6. uzupełniony opis ograniczeń i dalszego rozwoju.

Na spotkaniu 05 skupimy się przede wszystkim na:

> **kompletności dokumentacji, sprawdzeniu całej historii projektu oraz przygotowaniu materiałów do finalnego oddania.**

Po spotkaniu 05 nie powinniśmy już projektować wytworu od początku ani zastanawiać się, czym właściwie ma być.

Powinniśmy poprawiać i domykać to, co już istnieje.