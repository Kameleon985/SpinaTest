Jedyne pliki w których coś zmieniałem poza folderem spina to ThirdPersonCharacter i ThirdPerson_AnimBP
Łączny czas wykoniania to jakieś 7-8 godzin głównie z powodu problemów przy importowaniu dodatkowych animacji które się nie chciały zretargetować na szkielet z UE4
Atakowanie jest pod LPM, unik pod kontrolem. Niestety nie miałem lepszej animacji uniku więc jest kucanie.
Przeciwnik wyrywa gracza na dwa sposoby - wzrokowo i w ograniczonym obszarze słuchowo. Gracz wydaje dźwięki przy chodzeniu i atakowaniu (nawet jak w nic nie trafi).
Jest kilka rzeczy które od razu rzucają się w oczy do poprawy ale z racji że miał być to prosty prototyp to nie chciałem nad tym spędzać za dużo czasu. 
Pierwsza to na pewno brak wykorzystania EQSa, na te skromne potrzeby nie był potrzebny ale w przypadku jakiegokolwiek rozwoju projektu trzeba by napewno z niego skorzystać do nawigacji.
Drugi to brak drużyn u przeciwników, w przypadku kiedy interesuje nas tylko wrogie nastawienie do gracz to nie jest wielki problem bo można to sprawdzać po prostym tagu ale generalnie jest to kiepskie rozwiazanie.
Trace ataku powinien mieć oddzielny kanał. Należałoby też usunać redundacje kodu z funkcji ataku (możnaby to przenieś do combat componentu, ale w prawdziwej grze raczej do interfejsu który byłby wołany z broni)
