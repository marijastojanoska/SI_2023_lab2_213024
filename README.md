# Marija Stojanoska 213024

2. Control Flow Graph

![SI_lab2_213024](https://github.com/marijastojanoska/SI_2023_lab2_213024/assets/130248771/ad12e49a-daa9-4def-96a4-0159e4bca575)

3. Ciklomatska kompleksnost e 11. Ako od brojot na rebra (35) go odzememe brojot na jazli (26) i dodademe 2, se dobiva rezultatot. Isto taka mozheme i da izbroime kolku regioni postojat (11) ili pak da gi izborime predikatnite jazli (10) i da dodademe 1.

4. Every branch (5 testovi)

![image](https://github.com/marijastojanoska/SI_2023_lab2_213024/assets/130248771/aab97cc8-2aa6-490d-b241-fab29a3b2d23)

Prviot test sluchaj vo glavno sluzhi za da go opfati specijalniot sluchaj na exception odnosno jazlolot 2-22.
Vtoriot test sluzhi za da gi opfati sluchaite kade shto: usernameot e null odnosno jazol 3-4, emailot e validen odnosno uspeshno da vleze vo jazol 6-7 i vo jazlite od ciklusot kade shto gi bara username i email i istite gi naogja vo listata, i passwordot koga e so pomalku od 8 karakteri odnosno jazol 15-16.
Tretiot test vo glavno sluzhi za uspeshno da se izvrshi jazol 19-20 odnosno onamu kade shto passwordot sodrzhi specijalen karakter.
Chetvrtiot test sluzhi za da go fati sluchajot kade shto passwordot ima prazno mesto odnosno jazol 17-21.
Pettiot sluchaj sluzhi za da se pomine jazolot 18.2-21 odnosno koga passwordot nitu ima prazno mesto nitu specijalen karakter nitu e pomal od 8 karakteri.

5. Multiple Condition (4 testa)   

![mcondition](https://github.com/marijastojanoska/SI_2023_lab2_213024/assets/130248771/47470883-51a5-4ab4-b969-dfc625fe0e80)

Vistinitosna tablica za tri promenlivi treba da sodrzhi 6 kombinacii na true i false (ttt,ttf,tft,ftf,fft,fff) no bidejki stanuva zbor za operacija ili mozheme prvite tri kombinacii (ttt,ttf,tft) da gi spoime vo edna (txx) bidejki chim se proveri prviot sluchaj nema potreba da se proveruvaat slednite dva. Prvite tri testa imaat ist kraen rezultat odnosno site tri testa go opfakjaat exceptionot odnosno pominuvanjeto na jazlite 1-2 i 2-22. Chetvrtiot sluchaj e koga site tri uslova se false i izbrav prozivolno vrednosti za password username i email i gi pominuvaat soodvetnite jazli.

