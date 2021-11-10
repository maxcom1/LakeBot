# 🌚 Beta 0.3 (10.11)
🎯 **Krótki opis:**
Dodano moduł muzyczny w fazie beta, poprawiono i dodano kilka komend

⛳️ **Nowe komendy, funkcje i zmiany:**
 * Nowa komenda: `.join` - Przywołuje bota na kanał głosowy
 * Nowa komenda: `.play [utwór/link]` - Puszcza lub dodaje do kolejki wybrany utwór
 * Nowa komenda: `.skip` - Pomija aktualnie odtwarzany utwór. Jeśli na kanale głosowym są więcej niż 2 osoby, to 3/4 słuchaczy musi zaakceptować pominięcie
 * Nowa komenda: `.forceskip` - Wymusza pominięcie utworu
 * Nowa komenda: `.nowplaying` - Pokazuje co aktualnie gra bot
 * Nowa komenda: `.leave` - Bot wychodzi z kanału głosowego
 * Nowa komenda: `.pause` - Zatrzymuje/wznawia utwór
 * Nowa komenda: `.volume [1-100]` - Zmienia głośność utworu
 * Nowa komenda: `.kolejka` - Pokazuje aktualną kolejkę utworów
 * Nowa komenda: `.scroll [0-100]` - Przewija utwór do danego momentu (podawany w procentach, np. *50.5*)
 * Nowa komenda: `.loop` - Zapętla utwór
 * Nowa komenda: `.loopqueue` - Zapętla kolejkę
 * Nowa komenda: `.move [pozycja] <pozycja>` - Przesuwa utwór w kolejce (kolejność odtwarzania)
 * Nowa komenda: `.player` - Pokazuje szczegóły dotyczące serwerowego odtwarzacza
 * Nowa komenda: `.playskip [utwór/link]` - Pomija aktualnie grany utwór (jeśli jest) i puszcza wybrany
 * Nowa komenda: `.playtop [utwór/link]` - Dodaje wybrany utwór na początek kolejki, lub puszcza go jeśli w kolejce nie ma żadnych pozycji
 * Nowa komenda: `.remove [pozycja w kolejce]` - Usuwa daną pozycję z kolejki
 * Nowa komenda: `.replay` - Cofa aktualnie grany utwór do początku
 * Nowa komenda: `.resume` - Wznawia utwór jeśli jest zatrzymany
 * Nowa komenda: `.shuffle` - Miesza kolejkę
 * Nowa komenda: `.skipto [pozycja w kolejce]` - Pomija aktualnie odtwarzany utwór i przechodzi do wybranej pozycji z kolejki
 * Nowa komenda: `.destroy` - Niszczy odtwarzacz serwera. (Jest aktualnie niedostępna publicznie ze względu na niepełne skończenie)
 * Nowa komenda: `.calc [działanie]` - Oblicza działanie matematyczne
 * Nowa komenda: `.embed`
 * Dodano nowe funkcjonalności komendy `.pomoc` i poprawiono kilka błędów
 * Wiele zmian i poprawek w komendach deweloperskich
 * Naprawa kilku niedopatrzeń i problemów
 * Inne mniejsze zmiany i funkcje  
 **---------------------------**  
 Aktualnie moduł muzyczny znajduje się w fazie testów beta i może on zawierać różne błędy.
 Jeśli jednak chcesz odblokować moduł muzyczny na Twoim serwerze, skontaktuj się na discordzie: [maxcom1#0988](https://discord.com/users/440129212414951425)

# 🌚 Beta 0.2 (08.09 - 31.10)
🎯 **Krótki opis:**
Kilka komend i poprawa działania bota

⛳️ **Nowe komendy, funkcje i zmiany:**
 * Nowa komenda: `.stonoga` - To jest jakieś nieporozumienie!
 * Nowa komenda: `.papaj` - Wysyła losowego papaja
 * Nowa komenda: `.cat` - Wysyła losowego kota
 * Nowa komenda: `.baza` - Baza ~~produktów~~ zawartości
 * Nowa komenda: `.eval`
 * Przebudowano `.pomoc`
 * Inne mniejsze zmiany i funkcje  

**⚙️Beta 0.2.14 (31.10):**  
 * Wprowadzenie nowego modułu (dostępność limotowana czasowo)
 * Więcej szczegółów pod `.pomoc`!

**⚙️Beta 0.2.12 & 0.2.13 (31.10):**  
 * Małe poprawki techniczne

**⚙️Beta 0.2.11 (28.10):**  
 * Nowa komenda: `.halloween`
 * Wiele nowych funkcji i zmian, które pojawią się już niedługo :)

**⚙️Beta 0.2.10 (08.10):**  
 * Małe poprawki techniczne

**⚙️Beta 0.2.9 (04.10):**  
 * Małe zmiany w kilku komendach

**⚙️Beta 0.2.8 (28.09):**  
 * Poprawiono działanie `.stonoga`

**⚙️Beta 0.2.7 (27.09):**  
 * Małe poprawki

**⚙️Beta 0.2.6 (27.09):**  
 * Nowa komenda: `.święta` - Hoł hoł hoł!
 * Nowa komenda: `.karambit` - Nie da się opisać ;)
 * Nowa komenda: `.runtime`
 * Dodano kolejki
 * Dodano nowe funkcje statusów
 * Naprawiono błąd z `.mem`
 * Inne, mniejsze poprawki

**⚙️Beta 0.2.5 (19.09):**  
 * Niektóre operacje są teraz wykonywane asynchronicznie, co wpłynie na zmiejszenie czasu odpowiedzi (rzadki błąd)

**⚙️Beta 0.2.4 (19.09):**  
 * Nowa komenda: `.mnm`
 * Zmiany techniczne

**⚙️Beta 0.2.3 (19.09):**  
 * Zmiana aliasów niektórych komend
 * Zmiany techniczne

**⚙️Beta 0.2.2 (10.09):**  
 * Nowa komenda: `.chmurki` - Chmurki <3
 * Nowa komenda: `.emoji` - Uczucia z ręki..
 * Nowa komenda: `.google` - Wyszukaj w google!
 * Usprawniono komendy z obrazkami

**⚙️Beta 0.2.1 (10.09):**  

 * Nowa komenda: `.mem` - losowy mem!
 * Nowa komenda: `.nosacz` - Janusz!!!
 * Nowa komenda: `.reverse` - odwróć tekst!
 * Nowa komenda: `.dog` - losowy piesek!
 * Przebudowano `.pomoc`
 * Usprawniono komendy fun
 * Naprawiono błędy
 * JDA 4.3.0.310 > 4.3.0.324

# 🌚 Beta 0.1 (20.08)
🎯 **Krótki opis:**
Pierwsza wersja bota, wprowadzająca 3 podstawowe komendy

⛳️ **Nowe komendy, funkcje i zmiany:**
 * Nowa komenda: `.pomoc` - spis komend i ich opis
 * Nowa komenda: `.changelog` - zmiany w ostatniej wersji
 * Nowa komenda: `.orlen` - Wyświetla ceny naszych paliw 🍻
 * Nowa komenda: `.dodaj` - pozwala dodać bota na serwer
 * Nowa komenda **[BETA]**: `.clear` - usuwa wiadomoći
 * Nowa komenda: `.reload` (komenda dewelo perska)
 * Nowa komenda: `.shutdown` (komenda deweloperska)
 * Nowa funkcja: Dodano odpowiedź na ping
 * Nowa funkcja: Animowany status aktywności
 * Bot jest teraz online 24/7!
