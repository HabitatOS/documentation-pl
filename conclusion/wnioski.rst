*******
Wnioski
*******

W pracy postawiono dwie hipotezy badawcze:

    #. możliwe jest stworzenie oprogramowania symulującego złożoność prowadzenia misji księżycowych,

    #. oprogramowanie badawcze może stanowić podwaliny lub przetarcie szlaków w celu stworzenia systemów produkcyjnych.

W celu potwierdzenia słuszności założeń, stworzono prototypowy system i wdrożono go w środowisku zbliżonym do rzeczywistego. Po uzyskaniu informacji zwrotnej od użytkowników wprowadzono poprawki błędów i dokonano kolejnej ewaluacji podczas symulacji misji załogowych.

Największym problemem w trakcie implementacji rozwiązania okazał się system czasu. Wraz ze swoistą specyfiką opóźnień wynikających z prędkości światła oraz różnego czasu trwania doby na Księżycu, Marsie i Ziemi wymagał odmiennej implementacji dla każdej z lokalizacji. Ponadto koniecznym było stworzenie konwertera stref czasowych nie tylko pomiędzy różnymi lokacjami za Ziemi, ale również na innych ciałach niebieskich.

Wraz z odmienną implementacją systemu czasu, konieczne było wprowadzenie symulowanych opóźnień w każdym z komponentów systemu. Opóźnienie zależne jest od lokacji użytkownika, tj. podczas komunikacji między astronautami przebywającymi w tym samym miejscu opóźnienie nie powinno występować. Podczas komunikacji między astronautami przebywającymi w różnych strefach czasowych na tej samej planecie, system czasu nie powinien wykazywać opóźnienia, ale koniecznym jest uwzględnienie stref czasowych. Natomiast dla komunikacji na dystans, np. centrum kontroli misji z astronautami na Marsie pełny tryb opóźnienia czasowego musi zostać wdrożony.

Kolejną implikacją złożonego systemu czasu jest odmienny charakter planowania zadań i tworzenia grafiku dla zespołów na :term:`niskiej orbicie okołoziemskiej <Low Earth Orbit>` (ang. *Low Earth Orbit*, *LEO*), w stacjach badawczych na Księżycu oraz na Marsie. W tej ostatniej lokacji ze względu na brak stałego wsparcia wynikający z opóźnień w komunikacji, konieczne jest zapewnienie większej autonomii w planowaniu i wykonywaniu zadań, jak również niezależności od pomocy :term:`wiodących badaczy <Primary Investigator>` (ang. *Primary Investigator*, *PI*).
