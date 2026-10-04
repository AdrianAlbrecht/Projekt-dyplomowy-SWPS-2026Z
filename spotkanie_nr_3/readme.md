# Projekt dyplomowy — spotkanie 03
## Pierwsza wersja wytworu: prototyp, główny workflow i iteracyjne rozwijanie projektu

---

## Cel spotkania

Na poprzednich etapach określiliśmy:

- problem,
- odbiorcę,
- potrzeby użytkownika,
- insight projektowy,
- brief projektowy,
- podstawowe funkcjonalności,
- zakres projektu,
- formę rozwiązania,
- technologię lub narzędzia.

Teraz przechodzimy od planowania do **rzeczywistego wytworu**.

Na tym etapie powinno już istnieć coś, co można:

- uruchomić,
- kliknąć,
- przejść,
- obejrzeć,
- przetestować,
- albo przynajmniej zaprezentować jako konkretną reprezentację przyszłego rozwiązania.

Po tym etapie osoba studiująca powinna potrafić odpowiedzieć na pytania:

1. Jak wygląda podstawowy sposób działania mojego wytworu?
2. Jak użytkownik przechodzi przez najważniejszy proces?
3. Które funkcjonalności już istnieją?
4. Które elementy wymagają jeszcze wykonania?
5. Czy aktualna wersja nadal odpowiada na problem określony wcześniej?
6. Jakie decyzje projektowe zostały już podjęte podczas realizacji?
7. Jak dokumentować rozwój projektu, aby później móc go poprawnie opisać w pracy?

---

# 1. Od planu do działającego rozwiązania

Na tym etapie nie wystarczy już powiedzieć:

> „Chcę zrobić aplikację, która będzie...”

Powinno być możliwe pokazanie:

> **„To jest aktualna wersja mojego rozwiązania i tak działa jego najważniejszy element.”**

Nie oznacza to jeszcze gotowego projektu.

Pierwsza wersja może być:

- częściowo działającą aplikacją,
- interaktywnym prototypem,
- makietą high fidelity,
- przepływem chatbota,
- podstawową wersją strony,
- działającą jedną główną funkcjonalnością,
- demonstratorem określonego mechanizmu,
- inną formą pozwalającą realnie pokazać sposób działania rozwiązania.

---

# 2. Jak gotowy powinien być wytwór?

Nie istnieje jeden poziom prototypu właściwy dla wszystkich projektów.

Innego poziomu należy oczekiwać od:

- aplikacji internetowej,
- aplikacji mobilnej,
- chatbota,
- narzędzia wykorzystującego AI,
- prototypu UX,
- narzędzia badawczego,
- rozwiązania przygotowanego w Figma,
- rozwiązania no-code,
- projektu o charakterze eksperymentalnym.

Dlatego wymagany poziom jest ustalany **indywidualnie podczas konsultacji**.

Najważniejsze pytanie brzmi:

> **Czy aktualna wersja pozwala pokazać najważniejszą ideę i sposób działania wytworu?**

---

# 3. Low fidelity czy high fidelity?

Nie każdy projekt wymaga od razu zaawansowanej implementacji.

## Low fidelity

Prototyp low fidelity może przedstawiać:

- podstawowy układ ekranów,
- kolejność kroków,
- strukturę informacji,
- sposób przechodzenia przez proces,
- główną logikę interakcji.

Może być odpowiedni na wczesnym etapie projektowania.

Przykładowo:

- proste wireframe'y,
- schemat ekranów,
- podstawowa makieta,
- przepływ rozmowy,
- uproszczony scenariusz interakcji.

---

## High fidelity

Prototyp high fidelity powinien znacznie bardziej przypominać końcowy produkt.

Może zawierać:

- docelowy wygląd,
- realistyczne treści,
- działające przejścia,
- interakcje,
- kompletne ścieżki użytkownika,
- rzeczywiste materiały wykorzystywane w rozwiązaniu.

Jeżeli sam prototyp stanowi główny wytwór projektu, jego poziom powinien być odpowiednio wysoki, aby możliwe było pokazanie sposobu działania rozwiązania.

---

# 4. Prototyp nie oznacza „byle czego”

Słowo „prototyp” nie oznacza:

> „Nie musi działać, więc zrobię trzy ekrany.”

Zakres prototypu powinien wynikać z celu pracy.

Jeżeli istotą projektu jest np. sposób przeprowadzania użytkownika przez interwencję, trzeba pokazać tę interwencję.

Jeżeli istotą jest określony mechanizm interakcji, powinien być widoczny.

Jeżeli istotą jest wykorzystanie AI do określonego zadania, trzeba pokazać działanie tego elementu.

Nie wszystkie elementy techniczne muszą być ukończone, ale **najważniejsza idea projektu musi być możliwa do zaprezentowania**.

---

# 5. Minimalna wersja wytworu

Wróć do zakresu określonego podczas wcześniejszych spotkań.

Podstawowe pytanie brzmi:

> **Jaka jest najmniejsza wersja mojego wytworu, która rzeczywiście realizuje jego główny cel?**

Można potraktować ją jako robocze minimum projektu.

Przykład:

Projekt zakłada stworzenie chatbota wspierającego studentów podczas przygotowania do pierwszej rekrutacji.

Minimalna wersja może obejmować:

1. rozpoczęcie interakcji,
2. przedstawienie celu narzędzia,
3. przejście przez przygotowany proces,
4. wykonanie kilku ćwiczeń,
5. reakcję systemu na wybory użytkownika,
6. zakończenie procesu i podsumowanie.

Nie musi jeszcze zawierać:

- kont użytkowników,
- historii rozmów pomiędzy urządzeniami,
- rozbudowanego panelu administratora,
- systemu powiadomień,
- integracji z zewnętrznymi usługami.

---

# 6. Główny workflow

Na tym etapie trzeba umieć pokazać **główną ścieżkę użytkownika**.

Workflow odpowiada na pytanie:

> **Co dzieje się od momentu rozpoczęcia korzystania z wytworu do osiągnięcia jego podstawowego celu?**

Przykład:

```text
Użytkownik uruchamia aplikację
            ↓
Otrzymuje informację o celu narzędzia
            ↓
Rozpoczyna pierwszy etap
            ↓
Wykonuje zadanie
            ↓
System reaguje na odpowiedź
            ↓
Użytkownik przechodzi dalej
            ↓
Kończy proces
            ↓
Otrzymuje podsumowanie
```

Nie musi to być formalny diagram.

Najważniejsze jest, aby można było jednoznacznie opisać **logikę działania wytworu**.

---

# 7. Główna ścieżka najpierw

Na tym etapie skoncentruj się przede wszystkim na tzw. głównej ścieżce.

Czyli:

> **Co robi typowy użytkownik, jeżeli wszystko przebiega zgodnie z założeniami?**

Najpierw doprowadź do działania podstawowy proces.

Dopiero później zajmuj się:

- przypadkami wyjątkowymi,
- rzadkimi błędami,
- dodatkowymi ekranami,
- funkcjonalnościami pobocznymi,
- dodatkami kosmetycznymi.

---

# 8. Przykład — chatbot

Główna ścieżka może wyglądać następująco:

```text
START
  ↓
Powitanie
  ↓
Wyjaśnienie celu
  ↓
Pytanie 1
  ↓
Odpowiedź użytkownika
  ↓
Reakcja bota
  ↓
Ćwiczenie
  ↓
Podsumowanie
  ↓
Przejście do kolejnego etapu
```

Na spotkaniu powinno być już możliwe pokazanie przynajmniej części takiego procesu w rzeczywistym narzędziu.

---

# 9. Przykład — aplikacja internetowa

```text
Strona startowa
      ↓
Rozpoczęcie procesu
      ↓
Wprowadzenie danych / wybór opcji
      ↓
Przetworzenie informacji
      ↓
Wynik
      ↓
Wyjaśnienie / rekomendacja
```

Na tym etapie ważniejsze jest działanie tej ścieżki niż np. przygotowanie pięciu dodatkowych podstron.

---

# 10. Przykład — prototyp w Figma

Jeżeli wytworem jest prototyp:

```text
Ekran startowy
      ↓
Główne menu
      ↓
Wybrana funkcjonalność
      ↓
Interakcja
      ↓
Informacja zwrotna
      ↓
Zakończenie procesu
```

Sam zestaw oddzielnych ekranów nie pokazuje jeszcze sposobu działania.

Powinno być możliwe przejście przez zaprojektowaną ścieżkę.

---

# 11. Iteracyjne rozwijanie projektu

Nie zakładamy, że pierwsza wersja będzie wersją finalną.

Typowy proces wygląda następująco:

```text
POMYSŁ
  ↓
PROTOTYP
  ↓
KONSULTACJA
  ↓
POPRAWKI
  ↓
KOLEJNA WERSJA
  ↓
KONSULTACJA
  ↓
POPRAWKI
  ↓
WERSJA FINALNA
```

Zmiana projektu podczas realizacji jest czymś normalnym.

Może się okazać, że:

- pewna funkcjonalność nie jest potrzebna,
- zakres jest zbyt duży,
- wybrana technologia ma ograniczenia,
- określona interakcja jest nieczytelna,
- pewien element należy uprościć,
- potrzebna jest dodatkowa funkcjonalność.

---

# 12. Zmiana decyzji projektowej nie jest błędem

Jeżeli podczas realizacji okaże się, że wcześniejszy pomysł był niewłaściwy, można go zmienić.

Ważne jest jednak, aby potrafić później wyjaśnić **aktualne rozwiązanie**.

Przykład:

> Początkowo zakładano zastosowanie swobodnej rozmowy z modelem językowym. W trakcie realizacji ograniczono interakcję do zdefiniowanych opcji odpowiedzi, ponieważ pozwalało to lepiej kontrolować przebieg procesu i zapewniało zgodność z założonym scenariuszem interwencji.

To jest wartościowa decyzja projektowa.

---

# 13. Nie dokumentujemy wszystkich ślepych uliczek

Nie ma potrzeby zapisywania każdej:

- literówki,
- zmiany koloru,
- próby biblioteki,
- drobnej poprawki,
- technicznej pomyłki.

Dokumentuj przede wszystkim decyzje, które wpłynęły na:

- sposób działania produktu,
- funkcjonalności,
- sposób interakcji,
- zakres projektu,
- wykorzystaną technologię,
- końcowy kształt rozwiązania.

---

# 14. Zacznij dokumentację już teraz

Nie odkładaj dokumentowania projektu na koniec semestru.

Za kilka tygodni trudno będzie odtworzyć:

- dlaczego wybrano dane rozwiązanie,
- jak wyglądała wcześniejsza wersja,
- kiedy zmieniono zakres,
- jakie funkcjonalności pojawiały się kolejno,
- jak wyglądał proces tworzenia.

Dlatego od tego etapu warto regularnie zbierać materiały.

---

# 15. Co warto zachowywać?

W zależności od rodzaju projektu:

- zrzuty ekranu,
- kolejne wersje makiet,
- zdjęcia,
- schematy przepływu,
- wersje prototypu,
- linki,
- nagrania działania,
- prompty,
- scenariusze,
- pliki konfiguracyjne,
- kod źródłowy,
- ważne fragmenty konfiguracji,
- materiały użyte w projekcie.

Nie wszystko musi później znaleźć się w pracy.

Lepiej jednak mieć materiał i zdecydować później, że jest niepotrzebny, niż próbować go odtworzyć po zakończeniu projektu.

---

# 16. Zrzuty ekranu

Zrzuty ekranu będą szczególnie przydatne przy opisywaniu funkcjonalności.

Nie rób ich przypadkowo.

Dobry screenshot powinien pokazywać konkretny element, np.:

- ekran startowy,
- rozpoczęcie procesu,
- główną funkcjonalność,
- przykładową interakcję,
- wynik działania,
- podsumowanie procesu.

Jeżeli aplikacja ma 20 bardzo podobnych ekranów, nie trzeba umieszczać wszystkich.

Dokumentacja ma **wyjaśniać wytwór**, a nie stanowić album każdej możliwej sytuacji.

---

# 17. Opisuj screenshoty

W pracy nie powinno znaleźć się:

> Rysunek 4. Aplikacja.

Lepszy podpis:

> Rysunek 4. Widok drugiego etapu interwencji, w którym użytkownik wybiera sposób reakcji na sytuację rekrutacyjną.

W tekście należy również wyjaśnić, **co pokazuje ilustracja i dlaczego dany element jest istotny**.

---

# 18. Dokumentuj funkcjonalności

Od tego etapu warto prowadzić roboczą tabelę.

| Funkcjonalność | Status | Jak działa? | Materiał do dokumentacji |
|---|:---:|---|---|
| Rozpoczęcie procesu | ✅ | Użytkownik uruchamia nową sesję | Screenshot ekranu startowego |
| Etap 1 | ✅ | Użytkownik wykonuje pierwsze ćwiczenie | Screenshot |
| Etap 2 | 🟡 | Częściowo wykonany | — |
| Podsumowanie | ❌ | Jeszcze nie istnieje | — |

Możliwe statusy:

- ✅ gotowe,
- 🟡 w trakcie,
- ❌ brak.

---

# 19. Dokumentuj ważne decyzje projektowe

Prowadź również prostą tabelę decyzji.

| Decyzja | Uzasadnienie | Efekt |
|---|---|---|
| Podział procesu na etapy | Ograniczenie przeciążenia użytkownika | Użytkownik wykonuje jedno zadanie naraz |
| Aplikacja webowa | Łatwe udostępnienie | Brak konieczności instalacji |
| Brak logowania | Nie jest potrzebne do realizacji głównego celu | Mniejszy zakres projektu |
| ... | ... | ... |

Nie jest to jeszcze tekst do pracy.

To **materiał roboczy**, który ułatwi późniejsze napisanie rozdziału.

---

# 20. Opis procesu tworzenia

W pracy dyplomowej trzeba będzie później opisać również:

> **jak wytwór został wykonany.**

Nie chodzi o dziennik:

> „W poniedziałek zrobiłem menu, we wtorek poprawiłem przycisk.”

Opis powinien pokazywać raczej **logikę procesu**.

Przykład:

> W pierwszym etapie przygotowano podstawowy przepływ interakcji obejmujący rozpoczęcie sesji, realizację ćwiczenia oraz zakończenie etapu. Następnie rozszerzono rozwiązanie o kolejne scenariusze. Po przygotowaniu pierwszej wersji zmodyfikowano sposób prezentowania treści, dzieląc dłuższe komunikaty na krótsze fragmenty.

---

# 21. Opis technologii a opis kodu

Nie trzeba opisywać każdej klasy, funkcji ani pliku.

Fragment pracy:

> Aplikacja składa się z pliku `app.py`, w którym znajduje się funkcja `main()`, następnie funkcja `show_page()`, a w linii 46...

zwykle nie pomaga czytelnikowi zrozumieć wytworu.

Znacznie ważniejsze jest:

- z jakich głównych elementów składa się rozwiązanie,
- jak elementy współpracują,
- co odpowiada za najważniejsze funkcjonalności,
- jakie technologie zostały wykorzystane,
- dlaczego.

Kod może znaleźć się w załączniku, jeżeli jest potrzebny.

---

# 22. Logika działania

Warto zacząć przygotowywać prosty opis:

> **Co dzieje się po kolei?**

Przykład:

1. użytkownik uruchamia aplikację,
2. wybiera rozpoczęcie procesu,
3. system prezentuje pierwsze zadanie,
4. użytkownik udziela odpowiedzi,
5. odpowiedź jest przetwarzana,
6. system wybiera odpowiednią reakcję,
7. użytkownik przechodzi do następnego etapu,
8. po zakończeniu otrzymuje podsumowanie.

Taki opis będzie później znacznie bardziej użyteczny niż bardzo szczegółowy opis implementacji.

---

# 23. Sprawdź zgodność z briefem

Pierwsza działająca wersja jest dobrym momentem, aby wrócić do wcześniejszych założeń.

Dla każdej głównej funkcjonalności zadaj pytanie:

> **Czy nadal wiem, dlaczego ten element istnieje?**

Jeżeli odpowiedź brzmi:

> „Bo już go zrobiłem.”

to nie jest wystarczające uzasadnienie.

---

# 24. Macierz zgodności

Można przygotować prostą tabelę:

| Potrzeba / insight | Planowana funkcjonalność | Czy istnieje? | Czy realizuje założenie? |
|---|---|:---:|:---:|
| Użytkownik potrzebuje prowadzenia krok po kroku | Etapy procesu | ✅ | ✅ |
| Użytkownik potrzebuje aktywnego działania | Ćwiczenia | 🟡 | 🟡 |
| Użytkownik potrzebuje informacji o postępie | Pasek postępu | ❌ | — |

Jeżeli funkcjonalność nie ma żadnego związku z potrzebą lub celem projektu, zastanów się, czy naprawdę jest potrzebna.

---

# 25. Ograniczenia techniczne

Podczas implementacji prawdopodobnie pojawią się ograniczenia.

Przykładowo:

- platforma nie obsługuje potrzebnej funkcjonalności,
- darmowy plan ma ograniczenia,
- API jest płatne,
- model nie pozwala uzyskać stabilnych rezultatów,
- rozwiązanie działa tylko w przeglądarce,
- narzędzie nie pozwala zapisywać danych,
- implementacja pełnej funkcjonalności przekracza zakres projektu.

Takie ograniczenia nie muszą oznaczać niepowodzenia projektu.

Należy je:

1. zidentyfikować,
2. zdecydować, jak na nie reagujemy,
3. później opisać w pracy.

---

# 26. Ograniczenia produktu

Nie należy ukrywać ograniczeń rozwiązania.

Przykład:

> Aktualna wersja aplikacji nie posiada systemu kont użytkowników, dlatego dane nie są synchronizowane pomiędzy urządzeniami.

albo:

> Prototyp prezentuje pełną ścieżkę interakcji, ale nie implementuje rzeczywistego mechanizmu zapisywania danych.

To jest normalny element dokumentowania wytworu.

---

# 27. Co może zostać rozwinięte później?

Od tego etapu można prowadzić osobną listę:

## Dalszy rozwój

- ...
- ...
- ...

Ta lista nie jest obietnicą, że wszystko zostanie wykonane.

Posłuży później do napisania części dotyczącej:

- ograniczeń,
- dalszych możliwości rozwoju produktu.

---

# 28. Nie poprawiaj bez końca wyglądu

Przy ograniczonym czasie łatwo spędzić kilka godzin na:

- kolorze przycisku,
- marginesach,
- animacji,
- wyborze fontu,
- drobnych elementach wizualnych.

Jeżeli główna funkcjonalność nadal nie działa, nie jest to najlepsze wykorzystanie czasu.

Na tym etapie priorytet:

```text
1. GŁÓWNA LOGIKA
2. GŁÓWNY WORKFLOW
3. PODSTAWOWE FUNKCJONALNOŚCI
4. CZYTELNOŚĆ
5. ELEMENTY DODATKOWE
6. KOSMETYKA
```

Wyjątkiem są oczywiście projekty, w których sam wygląd lub UX stanowi istotny przedmiot projektu.

---

# 29. Karta projektu — spotkanie 03

Przygotuj poniższe informacje przed konsultacją.

---

## Aktualna wersja wytworu

**Forma:**

> ...

**Link / plik / sposób uruchomienia:**

> ...

**Co aktualnie działa?**

> ...

---

## Główny workflow

Opisz podstawową ścieżkę użytkownika:

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

## Stan funkcjonalności

| Funkcjonalność | Status | Uwagi |
|---|:---:|---|
| ... | ✅ / 🟡 / ❌ | ... |
| ... | ✅ / 🟡 / ❌ | ... |
| ... | ✅ / 🟡 / ❌ | ... |
| ... | ✅ / 🟡 / ❌ | ... |

---

## Najważniejsze decyzje od poprzedniego spotkania

| Decyzja | Dlaczego? |
|---|---|
| ... | ... |
| ... | ... |
| ... | ... |

---

## Zmiany względem briefu

**Co zostało zmienione?**

> ...

**Dlaczego?**

> ...

---

## Aktualne problemy

1. ...
2. ...
3. ...

---

## Ograniczenia

1. ...
2. ...
3. ...

---

## Materiały dokumentacyjne

Co zostało już zachowane?

- [ ] zrzuty ekranu,
- [ ] makiety,
- [ ] link do prototypu,
- [ ] kod źródłowy,
- [ ] prompty,
- [ ] scenariusze,
- [ ] nagranie,
- [ ] schemat działania,
- [ ] inne: ...

---

# 30. Milestone 03

Po trzecim etapie projektu powinny istnieć:

- [ ] pierwsza rzeczywista wersja wytworu,
- [ ] możliwy do pokazania główny workflow,
- [ ] przynajmniej część podstawowych funkcjonalności,
- [ ] aktualna lista funkcjonalności i ich status,
- [ ] udokumentowane najważniejsze decyzje projektowe,
- [ ] zidentyfikowane problemy i ograniczenia,
- [ ] pierwsze materiały dokumentacyjne,
- [ ] określony zakres pracy potrzebnej do kolejnej wersji.

Najważniejsza zmiana względem poprzedniego spotkania:

> **nie rozmawiamy już wyłącznie o pomyśle — pracujemy na istniejącym wytworze.**

---

# 31. Na kolejne spotkanie

Na spotkanie 04 należy znacząco rozwinąć wytwór.

Powinna istnieć **większość podstawowych funkcjonalności**, a projekt powinien coraz bardziej przypominać wersję końcową.

Równolegle należy rozpocząć przygotowywanie właściwego opisu do pracy dyplomowej.

Na kolejne spotkanie przygotuj:

1. rozwiniętą wersję wytworu,
2. możliwie kompletny główny workflow,
3. aktualną listę funkcjonalności,
4. dokumentację najważniejszych elementów,
5. zrzuty ekranu lub inne materiały wizualne,
6. listę wykorzystanych technologii i narzędzi,
7. roboczy opis:
   - czym jest wytwór,
   - dla kogo powstał,
   - jakie posiada funkcjonalności,
   - jak działa,
   - jak został wykonany.

Na spotkaniu 04 przejdziemy od:

> **„mam już działającą wersję projektu”**

do:

> **„potrafię w sposób logiczny i zrozumiały opisać mój wytwór w pracy dyplomowej”.**