# AGILE & SCRUM

-   [Źródło](#)
-   [Zwinna praca](#)
    -   [Różnica między Agile a Scrum?](#)
    -   [Czemu zwinna praca?](#)
    -   [Fundamentalne założenia Agile](#)
    -   [Minimalizacja ryzyka, większa innowacja](#)
    -   [Czemu akurat SCRUM a nie inna implementacja?](#)
-   [SCRUM](#run-project)
    -   [Co to SCRUM?](#run-project)
    -   [Podstawowe założenia](#run-project)
    -   [Role w projekcie](#run-project)
        -   [Właścicel Produktu (Product Owner)](#run-project)
        -   [Lider Zespołu (Scrum Master)](#run-project)
        -   [Zespół](#run-project)
    -   [Techniki](#run-project)
    -   [Wdrożenie SCRUM'a](#run-project)

## Źródło

-   Ksiązka "SCRUM" Jeff Sutherland
    -   Autor ksiązki jest tez jednym z pomysłodawców AGILE oraz SCRUM'a
    -   Zrozumienie genezy SCRUM'a
    -   Świetnie napisana, praktyczna wiedza
-   Moje doświadczenia
    -   Praca w paru firmach, różne implementacje pracy zwinnej lub całkowity brak

## Zwinna praca (Agile)

### Różnica między Agile a Scrum?

-   Agile to jest filozofia, sposób myślenia na temat wykonywnia pracy
-   Scrum to konkretna implementacja zwinnej pracy

### Czemu zwinna praca?

-   kakadowe podejście nie działa w środowisku o niskiej przewidywalności
    -   niska przewidywalność
        -   innowacja
        -   adaptacja względem potrzeb klienta
    -   hamonogram jest zbyt szybko nie aktualny
        -   wysiłek spędzony na wykresach i szczegółowym planowaniu idzie na marne
        -   oderwanie od rzeczywistości prowadzi nas w złym kierunku
    -   zbyt późne zderzenie z rzeczywistością
        -   poprawienie wykrytych błędów jest znacznie bardziej kosztowne
    -   nie odpowiedni system pracy prowadzi do porażki
        -   problemem było planowanie z góry, założenie że nic się nie zmieni
        -   nieefektywny
        -   marnotractwo
        -   depresyjny
        -   prowadzi do zlych zachowań
            -   mikrozarządzania
            -   zachowań pasywno-agresywnych
            -   nadgodzin
    -   jest to praktykowane ponieważ nie znamy innego systemu
        -   inni tak robią
        -   biznes lubi przewidywalność i wizualizacje

![gantt](https://github.com/pavelee/scrum_about_pl/blob/main/asset/gantt.png?raw=true)

### Fundamentalne założenia Agile

-   Ludzie i interakcje ponad procesy i narzędzia
-   Działające oprogramowanie ponad szczegółową dokumentacje
-   Współpracę z klientem ponad negocjacjowanie umów
-   Reagowanie na zmiany ponad realizacje założonego planu

### Minimalizacja ryzyka, większa innowacja

-   ryzyko rynkowe - czy ludzie chca tego co tworzymy?
    -   w rzeczywistości ludzie nie wiedzą, czego chcą, dopóki tego nie wypróbują
    -   jak najszybsze zderzenie się z rzeczywistością
-   ryzyko techniczne - czy rzeczywiście możemy to zrobić?
    -   Chcemy prototypowaniać tak aby szybko przedstawić różne możliwości bez ogromnych inwestycji
-   ryzyko finansowe - czy faktycznie możemy sprzedać to co stworzymy?
    -   Tworzymy coś, co jest świetne, ale nie możemy sprzedać tego za taką kwotę, by osiągnąć zysk
    -   W jaki sposób możemy przytostowo sprawdzić że klient jest gotowy za to zapłacić? Jeśli nie, to chcemy dokonać zmian

### Czemu akurat SCRUM a nie inna implementacja?

-   To tylko środek do celu a nie sam cel
-   Celem jest efektywniejsza, bardziej ekscytująca praca

### Stosowanie zasad dla zasady jest głupotą

-   Róbmy tylko to co dla nas jest korzystne

## SCRUM

### Co to SCRUM?

-   Implementacja pracy zwinnej, czyli jak w praktyce zastosować zwinne podejście
-   Autor SCRUM'a zainspirował się artykułem szukającym przyczyny efektyności zespołów. Wspomniany artykuł używał analogii w postaci graczy rugby
    -   najlepsze z nich pracowały jak rugbyści w młynie (scrum) – gdy piłka jest przekazywana w obrębie drużyny przemieszczającej się wraz z nią przez boisko
    -   samooptymalizacja, adaptacja w czasie gry
-   można się nauczyć tylko w praktyce

### Podstawowe założenia

-   cykl sprawdzania i dostosowywania (Inspect and Adapt)
    -   Co pewien czas należy przerwać pracę, sprawdzić, co zostało zrobione, i zobaczyć, czy to, co robimy, wciąż jest właściwe. I pomyśleć, jak można zrobić to lepiej.
    -   od samego początku regularne sprawdzanie kierunku (Inspect)
        -   czy robimy to co faktycznie jest potrzebne
        -   uzyskiwanie opinii na bieżąco
        -   nie ma znaczenia jak ciężko pracujemy, jeśli podążamy w złym kierunku
            -   Im szybciej dostarczymy coś naszym klientom, tym szybciej oni powiedzą nam, czy robimy rzecz, której potrzebują.
        -   Wersje demonstracyjne (prototypy)
            -   Dążenie do produktu możliwego do częstego prezentowania
    -   pytanie czy można to zrobić lepiej (Adapt)
        -   co nas przed tym powstrzymuje
            -   na początek musimy przerwać działania które nas wykańczają
            -   eksperymentowanie aby sprawdzić czy uda się osiągnąć poprawę
                -   Czy nowy stan jest lepszy od poprzedniego?
-   kierowanie się wartością
    -   Co wniesie do projektu największą wartość
        -   Szukanie odpowiedzi na pytanie czego możemy nie robić
    -   20% funkcjonalności stanowi 80% wartości
        -   dostarczyć 20% w pierwszej koleności
    -   to co wydaje wydawało się istotne na początku, w rzeczywistości takie nie musi być
        -   Zespół może dostarczyć większą wartość, robiąc coś innego
        -   Trzeba koniecznie pamiętać, że nasza kolejność zmienia się nieustannie – właściwa w jednym tygodniu nie będzie taka sama w następnym. Zmienia się nasze środowisko. Uczymy się coraz to nowych rzeczy
            -   Najważniejsze to uznać tę niepewność i zaakceptować fakt, że nasza aktualna kolejność (a co za tym idzie – wartość) jest związana z pewnym konkretnym momentem. To się zmieni. I znów. I znów.
-   Praca małymi krokami
    -   Myśląc o budowaniu czegokolwiek, nie zakładajmy, że aż do samego końca nie wytworzymy niczego wartościowego. Spróbujmy pomyśleć o planie minimum
        -   Co jest rzeczą absolutnie najmniejszą, jaką mogę zbudować, by dostarczyła jakąś wartość klientowi?
        -   Całość zasadza się na tym, że im prędzej otrzymamy rzeczywistą opinię, tym szybciej zrobimy lepszy samochód
    -   Zatem najważniejsze – nie zaczynać od gotowego projektu! Lepiej zbudować funkcjonalny prototyp i poprawić ewentualne niedoróbki
-   Minimalizacja marnotractwa
    -   Kluczem do przyśpieszenia jest pozbycie się marnotrawstwa
        -   Poprawiamy to co nas prowadzi do marnotractwa
        -   Otwartość na szukanie poprawy
    -   Reagowanie na błędy "teraz"
        -   Poźniejsza naprawa jest znacznie kosztowniejsza
    -   Unikanie absurdu
        -   Nie realne cele
        -   Brak reakcji
    -   Pozbycie się przeciążeń
        -   Nie potrzebne raporty
        -   Wypełnianie formularzy dla samego wypełniania
        -   bezsensowne spotkania
    -   Minimalizujemy marnotractwo, aczkolwiek będzie obecne. Nie istnieje perfekcyjny system pracy.
-   Transparentność
    -   Praca musi być widoczna
        -   Widoczny progress
    -   Chcemy sobie ufać nawzajem, co mamy mieć do ukrycia?
        -   Każdy ma możliwość wglądu
-   Zadowolenie z pracy
    -   Autonomia zespołu w tym jak realizują wizje
        -   Otwartość na kreatywność
        -
    -   Mierzenie wyników, nie godzin
        -   Kogo obchodzi, ile godzin pracy coś nam zajęło? Liczy się, jak szybko zostało dostarczone i czy jest wystarczającej jakości

### Role w projekcie

#### Właścicel Produktu (Product Owner)

-   Kreowanie wizji produktu
    -   Co chcemy osiągnąć?
-   Wyznaczenie priorytetów
    -   Co aktualnie wniesie największą wartość do projektu?
-   Idealne cechy
    -   Potrawi przekonać do wizji produktu
    -   Zna się na dziedzinie
    -   Upoważniony do podejmowania decyzji
    -   Pozostaje do dyspozycji zespołu, aby tłumaczyć, jakie potrzeby należy spełnić i dlaczego
    -   Odpowiedzialny za wartość

![priorytet](https://github.com/pavelee/scrum_about_pl/blob/main/asset/priorytet.png?raw=true)

#### Lider Zespołu (Scrum Master)

-   Lider służebny
    -   Wspiera zespół
        -   pomoc w jak najlepszym wykonywaniu pracy
    -   Zajmuję się tylko usuwaniem przeszkód
        -   Orientuje się co spowalnia zespół
        -   Prowadzi ku stałej poprawie
            -   Jak możemy zrobić to lepiej?

#### Zespół

-   Jedną z istotnych zasad metody Scrum jest to, że członkowie grupy samodzielnie decydują o sposobie wykonania pracy. Cele strategiczne to odpowiedzialność kierownictwa, ale podjęcie decyzji, jak je osiągnąć, jest zadaniem zespołu
-   Zespół nie może być zbyt duży
    -   Chemy aby każdy wszystko wiedział
        -   Każda kolejna osoba to kolejny kanał komunikacyjny
-   idealne cechy zespołu
    -   rozumie wizje
        -   posiadają motywacje do realizacji
    -   autonomiczny
        -   samoorganizacja
        -   samodzielne podejmowanie decyzji
    -   wskroś funkcjonalny
        -   wszystkie umiejętności potrzebne do ukończenia projektu
        -   nie chcemy tracić czasu czekając na inne zespoły, działy itp.
-   Intensywność komunikacji przyśpiesza pracę.
    -   Mapa komunikacji zespołu
    -   Im większa intensywność komunikacji im więcej każdy wie o wszystkim tym szybszy jest zespół
    -   Zasadniczo wskaźniki uzyskane przy tego typu analizie określają, w jakim stopniu każdy członek drużyny wie, co jest potrzebne do wykonania pracy jako całości

### Techniki

#### Sprint (przepieg, cykl, iteracja)

-   Podziel pracę na fragmenty, które możesz wykonać w regularnym, ustalonym, krótkim okresie
    -   Optymalnie: od jednego do czterech tygodni
    -   Istotne jest utrzymanie
    -   To jest to co nazywamy Sprintem
-   Na końcu każdego sprintu musi znaleźć się coś, co jest  gotowe. Coś, z czego można korzystać – do latania, jeżdżenia. Do czegokolwiek
-   Na początku sprintu zespół spotyka się i planuje sprint
    -   Decyduje ile pracy może wykonać w trakcie sprintu
    -   Wybiera z listy priorytetów tematy
-   Na koniec sprintu spotykamy się
    -   Analizujemy ile rzeczywiście udało się osiągnąć
        -   Pokazujemy co się udało osiągnąć
        -   Czy wzięli na swoje barki zbyt wiele i nie skończyli wszystkiego?
        -   Czy wzieli zbyt mało?
        -   Celem jest zrozumienie jak szybko pracuje grupa
-   Gdy zespół zobowiąże się do wykonania danego zadania, jest ono blokowane
    -   ingerowanie w działanie zespołu i rozpraszanie go drastycznie zmniejsza jego szybkość.

#### Road mapa i kamienie milowe (mile stone)

-   Potrzebujemy minimalnego planu
    -   Nie chcemy poświęcać zbyt dużo czasu na planownie
-   Szacujemy kiedy skończymy
    -   kamienie milowe są po to aby móc się zorientować jak szybko pracujemy
        -   Oszacowanie gdzie chcemy dość w tym kwartale, roku itp

![stozek](https://github.com/pavelee/scrum_about_pl/blob/main/asset/stozek_niepewnosci.jpeg?raw=true)

#### Rejestr Produktu (Product Backlog)

-   Zawiera wszystko co jest do zrobienia
    -   od przygotowania prototypu projektu nowej deski rozdzielczej po testowanie kierunkowskazów
-   Rejestr może mieć setki zapisów lub zawierać tylko kilka rzeczy, które należy określić na samym początku
-   Podstawowa idea rejestru jest taka, że powinien zawierać wszystko, co może zawierać produkt. Nigdy nie da się faktycznie zbudować wszystkiego, ale chcemy przecież mieć kompletne zestawienie tego, co może znaleźć się w naszej wizji produktu
-   Rejestr jest sortowany po priorytetach
    -   Tematy na górze rejestru są brane przez zespół do realizacji
    -   Najważniejsza jednak jest decyzja, co robić najpierw. Trzeba zadać sobie następujące pytania: Które elementy mają największy wpływ na biznes? Które są najważniejsze dla klienta? Które pozwalają zarobić najwięcej pieniędzy, a które najłatwiej wykonać?
    -   Trzeba zdawać sobie sprawę, że na liście jest wiele rzeczy, których nigdy nie zrealizujemy, ale priorytetem są te, które zapewniają największą wartość połączoną z najmniejszym ryzykiem

#### Historyjki (User Story)

-   Celem jest przedstawienie wizji w narracyjny sposób
    -   „Jako klient, chcę mieć możliwość przeglądania książek według gatunków, abym mógł znaleźć typ, jaki lubię”.
    -   „Jako klient, chcę wkładać książkę do koszyka, abym mógł ją kupić”.
    -   „Jako menedżer produktu, chcę mieć możliwość śledzenia zakupów klientki, abym w każdej chwili mógł zaproponować jej określone książki na podstawie jej ostatnich zakupów”.
-   Format
    -   Kto?
    -   Co?
    -   Dlaczego?
-   Nad takimi właśnie historiami zastanawia się zespół. Może dyskutować nad konkretnym sposobem ich implementacji. Są one wystarczająco szczegółowe, by można było na ich podstawie podjąć działania, choć nie wskazują jak.
-   każda gotowa historyjka musi spełniać kryteria INVEST. Musi być:
    -   Independent (niezależna) – możliwa do realizacji sama w sobie. Nie powinna być zależna od innej historyjki.
    -   Negotiable (negocjowalna) – zanim zaczniemy ją wykonywać, musimy mieć możliwość jej poprawienia. Możliwość zmiany musi być cechą wbudowaną.
    -   Valuable (wartościowa) – w rzeczywistości ma dostarczać wartości klientowi lub interesariuszowi.
    -   Estimable (możliwa do oszacowania) – musi istnieć możliwość określenia jej rozmiaru.
    -   Small (mała) – czyli taka, którą można łatwo oszacować i zaplanować. Jeżeli jest zbyt długa, trzeba ją poprawić lub podzielić na mniejsze fragmenty.
    -   Testable (sprawdzalna) – musi mieć powiązany ze sobą test, który ma przejść, aby zostać zrealizowana.
-   Dla każdej historyjki, którą się zajmujemy, powinna istnieć zarówno „definicja gotowości” (np. „Czy spełnia kryteria INVEST?”), jak i „definicja ukończenia” (np. „Jakie warunki muszą być spełnione, jakie testy trzeba zaliczyć, aby uznać pracę za zakończoną?”)

#### Planowanie sprintu

-   W metodzie Scrum ten rodzaj planowania występuje w każdym sprincie, podczas spotkania nazywanego „planowaniem sprintu”. Wszyscy się schodzą, patrzą na listę historii do wykonania i każdy mówi: „OK, co możemy osiągnąć w tym sprincie? Czy te historie są gotowe? Czy mogą być ukończone do zakończenia tego cyklu? Czy możemy potem zademonstrować je klientowi, aby dowieść ich rzeczywistej wartości?
-   Planning poker
    -   Unikanie negatywych skutków efektu "kaskady informacyjnej"
        -   Opinia innych członków zespołu wpływa na naszą własną
    -   Pomysł jest prosty. Każda osoba dostaje zestaw kart z tak interesującymi liczbami Fibonacciego – 1, 2, 3, 5, 8, 13 itd. Każdy element, który trzeba oszacować, zostaje przeniesiony na stół. Następnie każdy uczestnik wyciąga kartę, która według niego odwzorowuje właściwy nakład pracy i kładzie ją wartością do góry na stole. Wszyscy odwracają karty jednocześnie
    -   Jeżeli liczby na każdej karcie mieszczą się w zakresie trzech wyrazów ciągu Fibonacciego od siebie (mały rozrzut; powiedzmy piątka, dwie ósemki oraz trzynaście), zespół jedynie dodaje wszystkie liczby, liczy średnią (w tym przypadku 8,5) i przechodzi do następnego elementu
    -   Trzeba pamiętać, że mówimy o oszacowaniach, a nie o ścisłych harmonogramach. I to o oszacowaniach, które dotyczą małych fragmentów projektu
    -   Jeśli wartości na kartach mają rozrzut większy niż  trzy  wyrazy ciągu, to wtedy osoby z kartą najwyższą i najniższą tłumaczą swoją decyzję. Następnie rozgrywamy kolejną rundę pokera
    -   Zespół szybko kładzie nowe karty. Teraz trójka zamienia się w ósemkę, a pozostałe karty zostają bez zmian. Wyniki są wystarczająco bliskie, więc dodaje się je, uśrednia i przechodzi do następnego zadania.cel
-   Niezwykle istotne jest, że oszacowania dokonuje zespół, który faktycznie wykonuje pracę, a nie jacyś specjaliści od szacunków „idealnych”
-   Finalnie chcemy mieć zbiór tasków do wykonania
#### Retrospektywa sprintu

-   Pod koniec sprintu chcemy zrozumieć gdzie możemy uzyskać poprawę
-   Obwinianie kogokolwiek jest głupie
    -   Nie szukajmy złych ludzi, szukajmy złych systemów. Takich, które generują niewłaściwe zachowania i – w efekcie – słabą wydajność.

#### Daily

-   Pomysł polega na tym, aby drużyna szybko naradziła się, jak dojść do celu – czyli zakończenia sprintu.
-   Codzienne spotkanie zespołu
    -   Chcemy rozmawiać, intensyfikować komunikacje
    -   Jedna osoba usłyszy od drugiej, że zadanie potrwa dzień, ale być może inny członek zespołu wie, jak to zrobić w godzinę, jeśli będą ze sobą współpracować?
    -   pytania na spotkanie
        -   Co zrobiłeś wczoraj, aby przybliżyć zespół do osiągnięcia celu sprintu?
        -   Co zrobisz dzisiaj?
        -   Jakie przeszkody stoją na drodze zespołu?
-   Jeżeli zajmuje więcej niż kwadrans, przeprowadzasz je źle
-   Częstym problemem jest tendencja do traktowania przez ludzi tych codziennych zebrań jak okazji do indywidualnego zdawania raportów.

#### Tablica Agile

-   Prezentuje ona trzy poziomy stanu zadania: „Oczekujące”, „Wykonywane”, „Ukończone”
-   Celem jest transparentność, tablica to tylko środek do celu
-   Każdy ma dostęp do tablicy, może zobaczyć gdzie znajduje się zespół
-   W praktyce tablice są wirtualne
    -   hybrydowa praca nie jest przyjazna fizycznej tablicy

### Wdrożenie SCRUM'a

-   Wybór Właściciela Produktu
    -   posiada wizje produktu
    -   uwzględnia ryzyko, osiągnięcia oraz to co jest możliwe
    -   pasjonuje zespół (sprzedaje im wizje)
-   Wybór zespołu
    -   zaangażowani w swoją pracę
    -   musi posiadać wszystkie wymagane umiejętności do urzeczywistnienia wizji
    -   musi być niewielki (2 do 7 osób)
-   Wybór Scrum Master / Team Leader (moja definicja)
    -   Dba o to aby zespół nie zatrzymał się na przeszkodach
-   Utworzenie Rejestru Produktu według priorytetów
    -   Wszystko co może być kiedykolwiek wykonane przez zespół w kolejności priorytetów
    -   Wszystkie zadania które są potrzebne aby zrealizować wizje
    -   Ewoluuje przez cały czas istnienia
    -   Właściciel produktu dba o to aby zadania były wartościowe dla klientów i są realne do wykonania
-   Udoskonalanie i ocena Rejestru Produktu
    -   Zespół dla każdego zadania
        -   Czy jest zadanie wykonalne?
        -   Czy jest na tyle mały aby dało się wycenić zadanie?
        -   Czy mam dość informacji aby wykonać zadanie?
        -   Czy istnieje definicja ukończenia? (tak aby wszyscy byli zgodni że jest „wykonany”)
    -   Każde zadanie musi być możliwe do zaprezentowania w działaniu oraz dostarczenia
    -   Wyceniamy każde zadanie relatywnie np. małe, średnie, duże (książkowo, używajmy ciągu fibonacciego - 3, 5, 8, 13, 21, 34, 55)
-   Planowanie sprintu
    -   Nie dłuższy niż 4 tygodnie (optymalnie 1 - 2 tygodnie)
    -   Zespół patrzy na początek Rejestru Produktu i prognozuje co jest w stanie wykonać podczas kolejnego sprintu
    -   Z każdym kolejnym sprintem dokładniej szacujemy szybkość zespołu, tak abyśmy mogli oszacować termin dostarczenia
    -   Scrum Master / Team Lider próbuje zwiększyć szybkość zespołu
    -   Po ustaleniu co zrobimy na sprint musimy się tego trzymać, zmiany nie są mile widziane
    -   Zespół ma autonomie działania
-   Praca musi być widoczna
    -   Ogólnodostępna tablica z zadaniami dla każdego do wglądu, lub wykres ilość dni / ilość MD do spalenia
-   Codzienne spotkania (czyli codzienny scrum)
    -   Daily, max 15 min, Scrum Master / Team Leader oraz zespół, na stojąco (najlepiej)
        -   Każdy członek zespołu odpowiada na pytania
            -   Co zrobiłem wczoraj aby przybliżyć się do osiągnięcia celu sprintu?
            -   Co zrobię dzisiaj aby przybliżyć się do osiągnięcia celu sprintu?
            -   Czy są jakieś przeszkody blokujące osiągniecie celu sprintu?
        -   Cel spotkania
            -   Uświadomienie zespołowi w jakim punkcie sprintu się znajduje
            -   Czy wszystkie zadania zostaną dostarczone
            -   Czy mogę pomóc innym członkom zespołu w przezwyciężeniu trudności
        -   Zespół jest autonomiczny
            -   Nie ma składania raportu kierownictwu
            -   Scrum Master / Team Lider jest odpowiedzialny za zespół i jego prace
-   Ocena sprintu i wersja demo
    -   Pod koniec sprintu jesteśmy zdolni zaprezentować co zrobiliśmy, każdy ma prawo to zobaczyć
-   Retrospektywa sprintu
    -   Po sprincie znajdźmy chwile aby się zastanowić co możemy ulepszyć względem poprzedniego sprintu
    -   wymaga to emocjonalnej dojrzałości i atmosfery wzajemnego zaufania
    -   Nie szukamy winnych problemu, patrzymy na proces
        -   Dlaczego sprawy potoczyły się w taki sposób
        -   Dlaczego o tym zapomnieliśmy?
        -   Dzięki czemu moglibyśmy być szybsi?
    -   Szukamy rozwiązań jako zespół
    -   Akceptujemy krytykę, jesteśmy dojrzali. W przypadku krytyki szukamy rozwiązań zamiast przyjmować postawę obronną
    -   Uzgadniamy jaki mały krok (kaizen) możemy wykonać w kierunku poprawy
    -   W następnym sprincie ocenami czy udało się wdrożyć zmianę (testy akceptacyjne) i jakie są tego efekty (spodziewane większe szczęście zespołu)
