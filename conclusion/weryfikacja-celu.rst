****************************
Weryfikacja osiągnięcia celu
****************************


Celem pracy było dostarczenie prototypu oprogramowania zdolnego do wykorzystania podczas symulacji misji kosmicznych w habitacie. Oprogramowanie miało zawierać moduł zbierania statystyk dotyczących danych środowiskowych, parametrów biomedycznych oraz socjodynamicznych członków symulacji. Oprogramowanie musiało być wdrożone oraz wykorzystane podczas misji w celu zbierania statystyk oraz umożliwienia komunikacji wraz z uwzględnieniem opóźnień czasowych.

Wdrożenie polegało na wykorzystaniu z powodzeniem oprogramowania podczas misji. Weryfikacja miała polegać na ocenie aktywności użytkowników systemu oraz częstości korzystania z niego.


Określenie poziomu TRL systemu
==============================
Poziom :term:`gotowości technicznej <Technology Readiness Level>` (ang. *Technology Readiness Level*, *TRL*) służy do określenia dojrzałości rozwiązania oraz gotowości do wdrożenia. Skala została opracowana przez NASA :cite:`Sadin1988`, a obecnie używana jest przez wszystkie agencje kosmiczne oraz firmy zajmujące się wytwarzaniem rozwiązań o przeznaczeniu do zastosowania w sektorze kosmicznym :cite:`Dunbar2012`, :cite:`TRLESA2008`.

NASA definiuje również poziom gotowości technicznej dla projektów dotyczących oprogramowania :cite:`TRLNASA2013`. Autorskie tłumaczenie (:numref:`appendix-trl`) skali zamieszczone jest w zamieszczonym załączniku.

Poziom *TRL* 6 zdefiniowany jest jako: "dokonanie demonstracji technologii w środowisku zbliżonym do rzeczywistego" wraz z opisem:

    Stworzona prototypowa implementacja oprogramowania rozwiązująca pełnowymiarowe, realistyczne problemy. System częściowo zintegrowany z istniejącym sprzętem / oprogramowaniem. Dostępna jest ograniczona dokumentacja. Wykonalność inżynierska w pełni wykazana.

System *HabitatOS* jest rozwiązaniem, które spełnia założenia poziomu *TRL* 6, tj. został zintegrowany ze sprzętem habitatu, rozwiązuje pełnowymiarowe i realistyczne problemy oraz zademonstrowano jego działanie w środowisku zbliżonym do rzeczywistego.


Dalsze możliwości rozwoju oprogramowania
========================================
Obecnie trwa wdrożenie systemu w "mikrohabitacie" w Rzepienniku Strzyżewskim. Podczas dwóch tygodniowych symulowanych misji kosmicznych (jedna o charakterze księżycowym, druga o marsjańskim) sześcioosobowe załogi wykorzystywały system do pracy każdego dnia.

Konieczny jest rozwój mechanizmów uczenia maszynowego w systemie. Obecna szczątkowa implementacja pozwala jedynie na wsparcie procesów. W docelowym oprogramowaniu największą wartość przyniesie automatyzacja zadań na poziomie pozwalającym astronautom poświęcić maksymalnie dużo czasu na badania naukowe i pracę operacyjną, a nie utrzymanie systemów i habitatu.

Dzięki zastosowaniu algorytmów uczenia maszynowego i połączenia danych biomedycznych jak i psychologicznych możliwe będzie sterowanie urządzeniami, ich mocą oraz czasem załączania w celu optymalizacji temperatury i wilgotności. Umożliwi to dostosowywanie tych parametrów do cyklu dobowego jak również do stanu załogi.

Podczas tworzenia systemu zidentyfikowano, że konieczny byłby rozwój aplikacji mobilnych, tj. wersja na telefony *iOS*, *Android*, wersja na tablety oraz wersja na inteligentne zegarki (ang. *smart watch*).

Warstwa interfejsu użytkownika wymaga dokonania badań użyteczności (ang. *User Experience*, *UX*) w celu lepszego wsparcia procesu. Niektóre ekrany, tj. zbieranie danych socjodynamicznych, są dla użytkowników problematyczne. Spowodowane jest to dużą ilością pól do wypełnienia oraz niewielkim stopniem wsparcia od strony systemu. Rozwiązanie tzw. "kreatora" mogłoby pomóc w uzyskiwaniu lepszych informacji od użytkowników.

System *HabitatOS* jest projektem badawczym, który pozwoli na rozpoznanie problemów charakterystycznych dla prowadzenia kosmicznych misji eksploracyjnych głębokiej przestrzeni kosmicznej. System będzie zdolny również do wykorzystania w nowoczesnym i inteligentnym budownictwie przy zarządzaniu czujnikami analizie danych i wykrywaniu anomalii. System mógłby znaleźć również wykorzystanie w polskich bazach na Arktyce (*Hornsund*) oraz na Antarktyce (*Arctowski*) i Antarktydzie (*Dobrowolski*). Można go również zastosować przy obsłudze komór hipobarycznych i hiperbarycznych w centrach medycznych oraz w kopalniach.

Obecnie prowadzone są rozmowy na temat wdrożeń w habitatach organizacji *Mars Society*, tj. *MDRS* oraz *FMARS*, jak również w planowanym habitacie *LUNA* Europejskiej Agencji Kosmicznej.
