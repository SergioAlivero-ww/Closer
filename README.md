Closer — system automatyzacji konwersji rezerwacji dla hoteli
Data rozpoczęcia: 30.08.2025

Projekt Closer ma na celu stworzenie narzędzia pomagającego hotelom w automatyzacji procesu konwersji klientów z rezerwacji pośrednich (np. Booking.com) na rezerwacje bezpośrednie. Dzięki temu hotele mogą znacząco zredukować koszty prowizji i zyskać bliższy kontakt z gośćmi.

Aktualnie projekt jest we wczesnej fazie — powstaje front-end aplikacji webowej, która umożliwi klientom hotelu wygodny wybór nagród zachęcających do zmiany typu rezerwacji oraz prosty, przejrzysty proces potwierdzania rezerwacji bezpośredniej.

W repozytorium znajdują się podstawowe pliki HTML, CSS i JavaScript, które będą dalej rozwijane i integrowane.

<!-- Aktualizacja projektu - 31.08.2025.  -->

Dzisiaj przygotowałem pełną strukturę HTML dla strony, którą zobaczy użytkownik po kliknięciu w link otrzymany po założeniu rezerwacji przez Booking.com.

Ta strona jest pierwszym, kluczowym etapem całego procesu — obejmuje powitanie, wybór prezentu, instrukcję "Jak otrzymać prezent" oraz potwierdzenie wyboru z formularzem do podania e-maila.

W kolejnym kroku planuję skupić się na stworzeniu stylów CSS, aby ta strona wyglądała atrakcyjnie i działała poprawnie na różnych urządzeniach.

Po dopracowaniu wyglądu będę kontynuował pracę, tworząc popup potwierdzający poprawne złożenie wyboru oraz zachęcający do sprawdzenia swojej skrzynki e-mail.

Na dzień dzisiejszy moim priorytetem jest zakończenie front-endu pierwszej strony i dopracowanie jej wyglądu CSS, co będzie solidnym fundamentem do dalszych etapów projektu.

Na dziś konczę na tym, ze stworzyłem strukturę HTML. Jutro z rana zaczynam pisac CSS i planować następne kroki


<!-- 02.09.2025. -->

Aktualny status

Dziś rozpocząłem pracę nad częścią wizualną strony, głównie CSS sekcji powitalnej i prezentów. Pracuję nad układem, kolorystyką i podstawowym stylem, tak aby strona dobrze wyglądała na tle zdjęcia hotelu.

Plan na jutro

Dokończyć wizualny aspekt całej strony powitalnej i sekcji prezentów.

Zacząć rozwijać prostą mechanikę interakcji (wybór prezentów, podstawowa logika JS).

Przemyśleć i zaplanować logikę procesu rezerwacji i potwierdzeń, by móc później zacząć implementację backendu.

<!-- 04.09.2025 -->

Dziś wstępnie dokończyłem CSS. Do zrobienia zostało jeszcze dopracowanie paddingów i marginesów, czcionek oraz może kolorów, żeby całość była jeszcze bardziej spójna i atrakcyjna wizualnie.

Następne kroki na dziś:

Końcowy szlif wizualny (głównie paddingi, marginesy, czcionki, kolory)

Zaprojektowanie i ostylowanie wyboru prezentów przez radio buttony, żeby były estetyczne i nowoczesne

Sprawienie, żeby cała sekcja wyboru prezentów była w pełni użyteczna i atrakcyjna graficznie

<!-- 02.10.2025 -->



Przerwałem prace nad Closer na ok. miesiąc, żeby dokończyć kurs JS i wrócić spokojnie z solidnymi podstawami. Uznałem, że to lepsze niż ciągłe rozrywanie się między kursem a projektem. Dziś jest 2 października — mam 28 dni na dokończenie MVP i wchodzę w Closer na pełnej.

Na ten moment jest gotowy szkielet UI (HTML + CSS). Dziś poprawiam CSS (fonty, spacing, stany przycisków) i układam plan startu prac nad logiką oraz funkcjonalnościami. To dla mnie nowy obszar, więc świadomie idę małymi krokami.”

Krótki plan na najbliższe dni

Dzień 1: porządki w CSS + dodanie linku do polityki prywatności i stanów przycisków.

Dzień 2: formularz e‑mail z walidacją i komunikatami sukces/błąd; zapamiętywanie wyboru prezentu w przeglądarce.

Dzień 3: szkic modeli danych (Reservation, Offer, GiftSelection) i mock endpointów do pobierania ofert.

Dzień 4: reguła „prezent ≈ 5% wartości rezerwacji” i render 3 najlepszych propozycji.

Dzień 5: ekran podsumowania i prosta analityka zdarzeń (kliknięcia, wysłanie formularza, wybór prezentu).

