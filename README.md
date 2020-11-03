# MTA-Good-Life
Gamemod RPG do gry Multi Theft Auto, napisany głównie w języku LUA, w oparciu o bazę danych MySQL.Kod był rozwijany ponad rok
# Autorzy

-Johy*
-Soczek
-Stary
# Dlaczego wydaliśmy ten kod?

Ten kod został wydany ponieważ projekt został zamknięty oraz GoToRPG zaprzestało rozwijania serwera na podstawie wydanego kodu
# Zawartość opublikowanego kodu

W repozytorium znajduje sie:

-Wyczyszczona struktura bazy danych

-Skrypty napisane w języku LUA

W repozytorium nie ma:

-Kodu PHP do zmiany hasła

-Podmianek

-Systemu emp w radiowozach

-Kolczatek

-Modeli 3d

-Panelu Juniora

# Gdzie uruchomić serwer

Oprogramowanie to nie wymaga żadnego specjalnego serwera dedykowanego. Aby go uruchomić, wystarczy zwykły hosting współdzielony. W rzeczy samej polecamy skorzystanie z takiego hostingu w firmach:

-ServerProject - http://serverproject.pl/ - Hostingowali GoToRPG i nadal hostingują
-ServHost - http://servhost.pl/
-V-store - https://v-store.org/

# Sprawy Techniczne

# Logi
Wszystkie logi przechowywane są w katalogu GoodLife-Logi. Przy restarcie tego zasobu tworzony jest nowy plik z logami. Logi znajdują się też w bazie danych

# hasła graczy
Hasła graczy zapisywane są w tabeli goodlife_users w skrócie MD5 a skrypt odpowiadający za hasła jest zakodowany aby zapobiec w przypadku wycieku bazy danych wtargnięć np na Portale Społecznościowe
