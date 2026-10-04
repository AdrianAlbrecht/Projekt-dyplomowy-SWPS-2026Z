# Projekt dyplomowy — spotkanie 05
## Domknięcie projektu: kompletność dokumentacji i przygotowanie do oddania

---

## Cel spotkania

To ostatni regularny milestone przed finalnym oddaniem projektu.

Na tym etapie nie skupiamy się już na wymyślaniu kolejnych funkcjonalności.

Najważniejsze pytania brzmią:

1. Czy wytwór jest wystarczająco kompletny?
2. Czy jego opis odpowiada temu, co rzeczywiście powstało?
3. Czy wszystkie najważniejsze decyzje projektowe zostały uzasadnione?
4. Czy dokumentacja pozwala zrozumieć wytwór bez analizowania kodu?
5. Czy materiały są gotowe do wykorzystania w pracy dyplomowej?
6. Czy czegoś istotnego jeszcze brakuje?
7. Co trafia do głównej treści pracy, a co do załączników?

Po tym spotkaniu projekt powinien być już przede wszystkim:

> **poprawiany, uzupełniany i porządkowany, a nie projektowany od początku.**

---

# 1. Co powinno już istnieć?

Na tym etapie powinny istnieć:

- wytwór zbliżony do wersji finalnej,
- opis genezy i celu,
- opis odbiorców,
- opis założeń projektowych,
- opis technologii,
- uzasadnienie najważniejszych decyzji,
- opis funkcjonalności,
- opis logiki działania,
- opis procesu realizacji,
- ograniczenia,
- możliwości dalszego rozwoju,
- materiały dokumentujące wytwór.

Jeżeli któregoś z tych elementów nadal nie ma, należy go uzupełnić przed finalnym oddaniem.

---

# 2. Najpierw sprawdź spójność

Przed dopracowywaniem tekstu należy sprawdzić, czy:

```text
PROBLEM
  ↓
INSIGHT
  ↓
POTRZEBA
  ↓
CEL
  ↓
FUNKCJONALNOŚCI
  ↓
TECHNOLOGIA
  ↓
GOTOWY WYTWÓR
```

tworzą jedną logiczną całość.

Jeżeli w trakcie realizacji projekt się zmienił, opis również musi zostać zaktualizowany.

Nie może pozostać sytuacja, w której:

> w pracy opisany jest jeden projekt, a faktycznie powstało coś innego.

---

# 3. Sprawdź zgodność briefu z finalnym wytworem

Wróć do briefu projektowego.

Dla każdego elementu odpowiedz:

| Element | Czy nadal aktualny? | Czy znajduje odzwierciedlenie w wytworze? |
|---|:---:|:---:|
| Problem | ✅ / ❌ | ✅ / ❌ |
| Odbiorca | ✅ / ❌ | ✅ / ❌ |
| Insight | ✅ / ❌ | ✅ / ❌ |
| Cel | ✅ / ❌ | ✅ / ❌ |
| Główne funkcjonalności | ✅ / ❌ | ✅ / ❌ |
| Zakres | ✅ / ❌ | ✅ / ❌ |

Jeżeli coś się zmieniło, nie oznacza to automatycznie problemu.

Trzeba jednak odpowiedzieć:

> **dlaczego?**

---

# 4. Finalny zakres wytworu

Przygotuj ostateczną listę funkcjonalności.

## Funkcjonalności zrealizowane

| Funkcjonalność | Status | Znaczenie dla projektu |
|---|:---:|---|
| ... | ✅ | ... |
| ... | ✅ | ... |
| ... | ✅ | ... |

---

## Funkcjonalności częściowo zrealizowane

| Funkcjonalność | Czego brakuje? | Czy wpływa to na główny cel? |
|---|---|---|
| ... | ... | ... |
| ... | ... | ... |

---

## Funkcjonalności niezrealizowane

| Funkcjonalność | Dlaczego nie została wykonana? |
|---|---|
| ... | ... |
| ... | ... |

Element niezrealizowany nie musi automatycznie oznaczać błędu.

Może zostać:

- usunięty z zakresu,
- opisany jako ograniczenie,
- przeniesiony do dalszego rozwoju.

---

# 5. Nie dodawaj funkcji tylko dlatego, że został czas

Na końcu projektu często pojawia się pokusa:

> „Dodam jeszcze jedną rzecz.”

Jeżeli funkcjonalność nie wynika z celu projektu, może jedynie:

- zwiększyć ryzyko błędów,
- utrudnić dokumentację,
- zaburzyć spójność projektu,
- zabrać czas potrzebny na poprawienie opisu.

Na tym etapie zwykle lepiej:

> **doprowadzić istniejące elementy do porządku niż dodawać nowe.**

---

# 6. Kompletność dokumentacji

Dokumentacja powinna umożliwić osobie oceniającej zrozumienie:

- co powstało,
- jak działa,
- jak wygląda,
- jak zostało wykonane,
- jakie decyzje podjęto,
- jakie są jego ograniczenia.

Nie powinna wymagać:

- uruchamiania środowiska programistycznego,
- czytania całego kodu,
- odtwarzania historii zmian,
- domyślania się, jak działa produkt.

---

# 7. Główna treść pracy a załączniki

Nie wszystko musi znaleźć się bezpośrednio w rozdziale opisującym wytwór.

Warto rozdzielić:

## Główna treść pracy

Powinna zawierać przede wszystkim:

- genezę wytworu,
- jego cel,
- odbiorców,
- założenia projektowe,
- uzasadnienie decyzji,
- opis technologii,
- opis funkcjonalności,
- logikę działania,
- najważniejsze ilustracje,
- proces realizacji,
- ograniczenia,
- dalszy rozwój.

---

## Załączniki

Mogą zawierać materiały bardziej szczegółowe, np.:

- kod źródłowy,
- prompty,
- pełne scenariusze rozmów,
- dodatkowe screenshoty,
- makiety,
- pliki konfiguracyjne,
- dodatkowe schematy,
- pliki wynikowe,
- nagrania,
- instrukcje uruchomienia,
- inne materiały potrzebne do dokumentacji projektu.

---

# 8. Nie przenoś całego opisu do załącznika

Załącznik nie powinien zastępować właściwego opisu.

Czytelnik głównej części pracy powinien zrozumieć wytwór bez konieczności czytania wszystkiego, co znajduje się w załącznikach.

Załączniki mają:

> **uzupełniać dokumentację, a nie zastępować narrację.**

---

# 9. Kod źródłowy

Jeżeli wytwór zawiera kod, można go dołączyć jako:

- repozytorium,
- archiwum,
- załącznik,
- inny uzgodniony sposób.

Nie ma potrzeby umieszczania wielu stron kodu w głównej treści pracy.

Jeżeli fragment kodu jest szczególnie istotny dla zrozumienia projektu, można go pokazać.

Powinien jednak mieć konkretny cel.

---

# 10. Co warto udokumentować kodem?

Fragment kodu może mieć sens, jeżeli pokazuje np.:

- istotny mechanizm,
- nietypową logikę,
- realizację ważnej funkcjonalności,
- sposób wykorzystania modelu,
- ważny element przetwarzania danych.

Nie ma sensu wstawianie kodu tylko po to, żeby pokazać:

> „że projekt został zaprogramowany”.

---

# 11. Prompty

Jeżeli projekt wykorzystuje modele generatywne i istotnym elementem działania są prompty, należy je zachować.

W zależności od projektu można umieścić:

- najważniejsze prompty w głównym opisie,
- pełny zestaw promptów w załączniku.

W opisie warto wyjaśnić:

- do czego prompt służy,
- jakie zachowanie ma wywołać,
- jaki rodzaj danych otrzymuje model,
- jak wykorzystywana jest odpowiedź.

---

# 12. Scenariusz chatbota

Jeżeli projektem jest chatbot, dokumentacja może obejmować:

- główną logikę rozmowy,
- kolejne etapy,
- możliwe odpowiedzi użytkownika,
- reakcje systemu,
- mechanizm zakończenia procesu.

Nie trzeba wklejać całej rozmowy do głównego rozdziału.

Pełny scenariusz może znaleźć się w załączniku.

---

# 13. Prototypy i makiety

Jeżeli wytworem jest prototyp:

warto zachować:

- plik źródłowy,
- eksport do PDF,
- link do prototypu,
- najważniejsze screenshoty,
- opis głównego workflow.

Jeżeli rozwiązanie wymaga interakcji, dobrze jest również przygotować sposób pokazania jej działania.

---

# 14. Nagranie działania

W niektórych projektach przydatne może być krótkie nagranie pokazujące działanie.

Szczególnie jeżeli:

- projekt wymaga konkretnego środowiska,
- dostęp do aplikacji może później wygasnąć,
- wykorzystano usługę zewnętrzną,
- interakcję trudno przedstawić statycznymi zrzutami ekranu.

Nagranie nie zastępuje opisu w pracy.

Stanowi dodatkowy element dokumentacji.

---

# 15. Link nie jest dokumentacją

Nie wystarczy napisać:

> „Aplikacja dostępna jest pod adresem...”

Link może:

- przestać działać,
- wymagać logowania,
- wygasnąć,
- prowadzić do zmienionej wersji.

Dlatego kluczowe elementy wytworu należy również **udokumentować w samej pracy lub załącznikach**.

---

# 16. Screenshoty — wybór finalny

Przejrzyj wykonane screenshoty.

Zostaw przede wszystkim te, które pokazują:

1. rozpoczęcie interakcji,
2. najważniejsze funkcjonalności,
3. kluczowe etapy workflow,
4. rezultat działania,
5. elementy istotne z punktu widzenia problemu pracy.

Nie trzeba pokazywać wszystkich ekranów.

---

# 17. Czy screenshot jest czytelny?

Sprawdź:

- czy nie jest zbyt mały,
- czy najważniejszy element jest widoczny,
- czy nie zawiera przypadkowych danych,
- czy jest aktualny,
- czy odpowiada finalnej wersji,
- czy ma sensowny podpis.

---

# 18. Dane wrażliwe i przypadkowe dane

Przed wykonaniem finalnych screenshotów sprawdź, czy nie znajdują się na nich:

- prawdziwe dane osób,
- adresy e-mail,
- tokeny API,
- klucze dostępu,
- dane logowania,
- prywatne rozmowy,
- inne informacje, które nie powinny znaleźć się w pracy.

Do prezentacji można wykorzystać dane demonstracyjne.

---

# 19. Finalny opis technologii

Sprawdź, czy opis technologii nie jest wyłącznie listą:

> Python, Django, HTML, CSS, PostgreSQL, OpenAI API.

Lista nie wyjaśnia projektu.

Dla najważniejszych elementów powinno być wiadomo:

| Technologia | Do czego? | Dlaczego? |
|---|---|---|
| ... | ... | ... |
| ... | ... | ... |

---

# 20. Finalny opis funkcjonalności

Dla każdej głównej funkcjonalności powinno być wiadomo:

1. co robi,
2. jak użytkownik z niej korzysta,
3. jaką pełni rolę,
4. dlaczego znajduje się w projekcie.

---

## Przykład

Nie:

> Aplikacja posiada pasek postępu.

Lepiej:

> W górnej części interfejsu zastosowano pasek postępu informujący użytkownika o aktualnym etapie procesu. Element ten umożliwia ocenę liczby pozostałych kroków i został wprowadzony w celu zwiększenia czytelności wieloetapowej interakcji.

---

# 21. Finalny opis procesu realizacji

Sprawdź, czy proces pokazuje:

- od czego rozpoczęto,
- jakie były najważniejsze etapy,
- jakie istotne zmiany wprowadzono,
- jak projekt doszedł do obecnej wersji.

Nie musi pokazywać każdego kroku technicznego.

---

# 22. Finalne ograniczenia

Ograniczenia powinny dotyczyć rzeczywistej wersji wytworu.

Przykładowo:

- brak określonej funkcjonalności,
- ograniczona platforma,
- ograniczony zakres testów,
- zależność od zewnętrznej usługi,
- brak wersji mobilnej,
- ograniczenie technologiczne,
- brak trwałego przechowywania danych,
- ograniczona personalizacja.

---

# 23. Dalszy rozwój

Dalszy rozwój powinien być realistyczny.

Nie musi oznaczać:

> „w przyszłości aplikacja będzie posiadała wszystko”.

Lepiej wskazać 2–5 konkretnych kierunków.

Przykład:

1. dodanie systemu kont użytkowników,
2. przeprowadzenie testów użyteczności,
3. rozbudowanie mechanizmu personalizacji,
4. stworzenie wersji mobilnej,
5. przeprowadzenie badania skuteczności rozwiązania.

---

# 24. Samoocena przed oddaniem

Przed finalnym oddaniem oceń własny projekt według dokładnie tych samych obszarów, według których będzie oceniany.

---

# 25. Kryterium 1 — Gotowy wytwór

### Sprawdź:

- [ ] wytwór istnieje,
- [ ] można go zaprezentować,
- [ ] realizuje główny cel,
- [ ] główny workflow jest kompletny,
- [ ] najważniejsze funkcjonalności działają lub są przedstawione zgodnie z ustalonym zakresem,
- [ ] projekt nie jest wyłącznie koncepcją.

Zadaj sobie pytanie:

> **Czy osoba oglądająca projekt może zobaczyć, co faktycznie zostało wykonane?**

---

# 26. Kryterium 2 — Osadzenie w kontekście

### Sprawdź:

- [ ] wiadomo, z jakiego problemu wynika projekt,
- [ ] wiadomo, dla kogo powstał,
- [ ] istnieje związek z częścią psychologiczną,
- [ ] wyniki / teoria prowadzą do konkretnych założeń,
- [ ] funkcjonalności odpowiadają na zidentyfikowane potrzeby.

Zadaj sobie pytanie:

> **Czy czytelnik rozumie, dlaczego ten wytwór znajduje się właśnie w tej pracy dyplomowej?**

---

# 27. Kryterium 3 — Uzasadnienie decyzji projektowych

### Sprawdź:

- [ ] uzasadniona jest forma wytworu,
- [ ] uzasadnione są najważniejsze funkcjonalności,
- [ ] uzasadniony jest wybór technologii,
- [ ] opisano istotne zmiany podczas realizacji,
- [ ] wiadomo, dlaczego projekt ma właśnie taki zakres.

Zadaj sobie pytanie:

> **Czy opisuję tylko „co zrobiłem”, czy również „dlaczego zrobiłem to właśnie tak”?**

---

# 28. Kryterium 4 — Merytoryczność opisu

### Sprawdź:

- [ ] tekst jest logiczny,
- [ ] kolejne części wynikają z siebie,
- [ ] terminologia jest spójna,
- [ ] opis jest zrozumiały dla osoby spoza projektu,
- [ ] nie ma zbędnych szczegółów technicznych,
- [ ] nie brakuje ważnych informacji,
- [ ] ilustracje są opisane.

Zadaj sobie pytanie:

> **Czy można zrozumieć projekt, czytając samą pracę?**

---

# 29. Kryterium 5 — Kompletność dokumentacji

### Sprawdź:

- [ ] pokazano cały istotny wytwór,
- [ ] istnieją odpowiednie screenshoty / zdjęcia / materiały,
- [ ] udokumentowano główny workflow,
- [ ] dołączono potrzebne pliki,
- [ ] kod lub repozytorium jest dostępne, jeśli dotyczy,
- [ ] prompty / scenariusze / makiety są dostępne, jeśli są istotne,
- [ ] materiały pozwalają zrozumieć efekt końcowy.

Zadaj sobie pytanie:

> **Czy osoba oceniająca ma wszystko, czego potrzebuje do zapoznania się z projektem?**

---

# 30. Test osoby z zewnątrz

Dobrym testem kompletności jest pokazanie opisu osobie, która:

- nie uczestniczyła w projekcie,
- nie zna kodu,
- nie była na konsultacjach.

Po przeczytaniu powinna potrafić odpowiedzieć:

> Co powstało?

> Dlaczego?

> Dla kogo?

> Jak działa?

> Jak zostało wykonane?

> Jakie ma ograniczenia?

Jeżeli nie potrafi — coś trzeba doprecyzować.

---

# 31. Finalny pakiet do oddania

Przed wysłaniem materiałów przygotuj całość w uporządkowanej formie.

Przykładowo:

```text
projekt/
│
├── opis_wytworu.pdf / docx
│
├── README.md
│
├── screenshots/
│   ├── 01_start.png
│   ├── 02_funkcjonalnosc.png
│   └── 03_wynik.png
│
├── prototyp/
│
├── kod/
│
├── prompty/
│
├── scenariusze/
│
└── inne_materialy/
```

Nie każdy projekt będzie potrzebował wszystkich tych folderów.

Struktura powinna być dostosowana do rodzaju wytworu.

---

# 32. README projektu

Jeżeli przekazywany jest folder, repozytorium lub archiwum, warto przygotować krótki `README.md`.

Powinien zawierać:

## Nazwa projektu

> ...

## Krótki opis

> ...

## Zawartość

> ...

## Jak obejrzeć / uruchomić wytwór?

> ...

## Link do wersji online

> ...

## Najważniejsze pliki

> ...

Nie trzeba przygotowywać rozbudowanej dokumentacji instalacyjnej, jeżeli nie jest potrzebna.

---

# 33. Sprawdź materiały przed wysłaniem

Przed wysłaniem:

- otwórz wszystkie pliki,
- sprawdź linki,
- sprawdź dostęp do repozytorium,
- sprawdź prototyp,
- sprawdź nagrania,
- sprawdź format plików,
- sprawdź, czy nie brakuje załączników.

Nie wysyłaj materiałów, których samodzielnie wcześniej nie sprawdzono.

---

# 34. Linki i uprawnienia

Jeżeli przekazujesz:

- Google Drive,
- Figma,
- GitHub,
- aplikację online,
- inny serwis,

sprawdź uprawnienia dostępu.

Projekt, którego nie można otworzyć z powodu braku uprawnień, jest praktycznie niedostępny do oceny.

---

# 35. Stabilność finalnej wersji

Jeżeli wytwór działa na zewnętrznej platformie, warto zachować również:

- screenshoty,
- eksport,
- kopię lokalną,
- nagranie,
- inną formę archiwizacji.

Nie należy opierać całej dokumentacji wyłącznie na tym, że:

> „link powinien działać”.

---

# 36. Czego NIE robić tuż przed oddaniem?

Nie:

- przepisuj całego projektu od nowa,
- zmieniaj technologii bez bardzo dobrego powodu,
- dodawaj kilkunastu nowych funkcji,
- usuwaj działających elementów tylko dlatego, że można je zrobić „ładniej”,
- zostawiaj dokumentacji na ostatni dzień.

Priorytetem jest:

```text
KOMPLETNOŚĆ
     ↓
SPÓJNOŚĆ
     ↓
CZYTELNOŚĆ
     ↓
POPRAWKI
     ↓
DODATKI
```

---

# 37. Karta projektu — spotkanie 05

Na konsultację przygotuj możliwie kompletną wersję projektu.

---

## Wytwór

**Aktualny status:**

> ...

**Co jeszcze wymaga wykonania?**

> ...

---

## Opis

- [ ] geneza,
- [ ] cel,
- [ ] odbiorca,
- [ ] założenia,
- [ ] technologie,
- [ ] funkcjonalności,
- [ ] logika działania,
- [ ] proces realizacji,
- [ ] ograniczenia,
- [ ] dalszy rozwój.

---

## Dokumentacja

- [ ] screenshoty,
- [ ] zdjęcia,
- [ ] link do aplikacji,
- [ ] prototyp,
- [ ] repozytorium,
- [ ] kod źródłowy,
- [ ] prompty,
- [ ] scenariusze,
- [ ] nagrania,
- [ ] inne materiały.

Zaznacz wyłącznie elementy dotyczące Twojego projektu.

---

## Co znajduje się w głównej części pracy?

> ...

---

## Co znajduje się w załącznikach?

> ...

---

## Brakujące elementy

1. ...
2. ...
3. ...

---

## Najważniejsze rzeczy do poprawienia przed oddaniem

1. ...
2. ...
3. ...

---

# 38. Milestone 05

Po tym etapie powinny istnieć:

- [ ] wytwór zbliżony do wersji finalnej,
- [ ] kompletny roboczy opis wytworu,
- [ ] pełny zestaw materiałów dokumentacyjnych,
- [ ] komplet screenshotów lub innych ilustracji,
- [ ] finalna lista funkcjonalności,
- [ ] finalne uzasadnienie technologii,
- [ ] opis ograniczeń,
- [ ] opis dalszego rozwoju,
- [ ] materiały przeznaczone do załączników,
- [ ] lista ostatnich poprawek.

Po spotkaniu powinno być jasne:

> **co dokładnie trzeba poprawić przed finalnym oddaniem i nie powinno już być żadnych fundamentalnych pytań dotyczących koncepcji projektu.**

---

# 39. Finalne oddanie

Komplet materiałów należy przekazać:

# **do 14.01.2027**

Termin ten przypada tydzień przed ostatnimi zajęciami.

Do oddania należy przekazać:

1. **gotowy wytwór,**
2. **opis wytworu przeznaczony do pracy dyplomowej,**
3. **kompletną dokumentację,**
4. **wszystkie materiały potrzebne do zapoznania się z projektem.**

> **Materiały przekazane po 14.01.2027 nie będą sprawdzane w terminie podstawowym.**

Ostatnie zajęcia odbywają się:

# **21.01.2027**

i są przeznaczone na:

- finalną konsultację,
- omówienie dostarczonych materiałów,
- ocenę projektu.

Ostatnie spotkanie **nie jest terminem na oddawanie projektu**.

---

# 40. Ostatnia checklista przed wysłaniem

## Wytwór

- [ ] istnieje,
- [ ] jest dostępny,
- [ ] można go zaprezentować,
- [ ] realizuje główny cel.

## Kontekst

- [ ] wiadomo, z czego wynika,
- [ ] wiadomo, dla kogo powstał,
- [ ] jest powiązany z psychologiczną częścią pracy.

## Decyzje projektowe

- [ ] wiadomo, dlaczego wybrano taką formę,
- [ ] wiadomo, dlaczego wybrano takie funkcjonalności,
- [ ] wiadomo, dlaczego wybrano takie technologie.

## Opis

- [ ] jest logiczny,
- [ ] jest spójny,
- [ ] jest zrozumiały,
- [ ] opisuje cały wytwór.

## Dokumentacja

- [ ] pokazuje działanie,
- [ ] zawiera potrzebne ilustracje,
- [ ] zawiera odpowiednie załączniki,
- [ ] wszystkie linki działają,
- [ ] wszystkie pliki można otworzyć.

---

# 41. Najważniejsza zasada na koniec

Finalny projekt powinien pozwalać prześledzić pełną drogę:

```text
PROBLEM PSYCHOLOGICZNY
        ↓
WNIOSKI / INSIGHT
        ↓
POTRZEBA UŻYTKOWNIKA
        ↓
BRIEF PROJEKTOWY
        ↓
DECYZJE PROJEKTOWE
        ↓
FUNKCJONALNOŚCI
        ↓
TECHNOLOGIA
        ↓
WYTWÓR
        ↓
DOKUMENTACJA
```

Jeżeli wszystkie te elementy są ze sobą spójne i zostały jasno opisane, projekt jest gotowy do finalnego oddania.