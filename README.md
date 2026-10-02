# Memento Egzamini – instrukcja

*Memento egzamini* – pamiętaj o egzaminie.

Plan zajęć z USOS, terminy egzaminów, przedmioty i kontakty do prowadzących w jednej aplikacji na telefon i tablet.

**Adres aplikacji:** https://11rk1.github.io/Starosta/

Wszystkie dane zostają na Twoim urządzeniu. Nic nie jest wysyłane na serwer, a starosta nie widzi Twojego planu ani notatek.

---

## 1. Instalacja

### iPhone i iPad
1. Otwórz adres aplikacji w **Safari** (nie w Chrome ani w przeglądarce Messengera).
2. Stuknij **Udostępnij** (kwadrat ze strzałką) → **Do ekranu początkowego** → **Dodaj**.
3. Od teraz uruchamiaj aplikację z ikony **Memento**.

### Android
1. Otwórz adres aplikacji w **Chrome**.
2. Stuknij **Zainstaluj** na stronie głównej aplikacji albo w menu **⋮** wybierz **Zainstaluj aplikację** (na niektórych telefonach: **Dodaj do ekranu głównego**).
3. Uruchamiaj aplikację z ikony **Memento**.

> Korzystaj zawsze z ikony. Dane zapisane w zwykłej karcie przeglądarki są osobne i nie przeniosą się do zainstalowanej aplikacji.

## 2. Wybierz specjalizację

Przy pierwszym uruchomieniu na ekranie Przegląd wybierz **Cyberbezpieczeństwo** albo **Detektywi**. Zobaczysz wtedy wpisy dla całej grupy i dla swojej specjalizacji. Specjalizację zmienisz w **Ustawieniach**.

## 3. Plan zajęć z USOS

1. Zaloguj się do **USOSweb** → **Mój USOSweb** → **Plan zajęć**.
2. Wybierz eksport planu i skopiuj **Odnośnik do planu** (ikona kopiowania obok linku).
3. W aplikacji wejdź w **Plan** → **Połącz z USOS**, przytrzymaj palec w polu, wybierz **Wklej** i stuknij **Zapisz i pobierz**.

Plan odświeża się sam co kilka godzin. Możesz też odświeżyć go ręcznie przyciskiem **Odśwież z USOS**.

> Link z USOS to prywatny klucz do Twojego planu, który działa bez logowania. Nie wysyłaj go nikomu.

## 4. Informacje od starosty

Starosta co jakiś czas wysyła na grupę plik `dla-grupy-RRRR-MM-DD.json` z terminami egzaminów, warunkami zaliczeń i kontaktami do prowadzących.

1. Zapisz plik na urządzeniu: na iPhonie i iPadzie przez **Zachowaj w Plikach**, na Androidzie trafi do **Pobranych**.
2. W aplikacji stuknij **Wczytaj plik od starosty** na ekranie Przegląd albo w **Ustawienia → Wczytaj plik od starosty**.

Wpisy od starosty mają dopisek „od starosty”. Gdy wczytasz nowszy plik, zostaną zaktualizowane, a Twój plan, zadania i własne wpisy pozostaną bez zmian.

## 5. Przypomnienia w kalendarzu

W **Terminach** albo w **Planie** stuknij **Do kalendarza**, wybierz maksymalnie 2 przypomnienia i otwórz utworzony plik.

- **iPhone i iPad:** wybierz **Dodaj wszystkie**. Przypomnienia przyjdą jako zwykłe powiadomienia z Kalendarza.
- **Android:** plik otworzy się w aplikacji kalendarza, jeśli obsługuje import plików `.ics` (np. Kalendarz Samsung). Kalendarz Google na telefonie tego nie potrafi. Wtedy zaimportuj plik na komputerze przez calendar.google.com → **Ustawienia → Importuj i eksportuj**.

Każde wydarzenie dodawaj tylko raz, bo ponowne dodanie tworzy duplikaty.

## 6. Kopia i przenoszenie danych

**Ustawienia → Zapisz kopię do pliku** zapisuje wszystkie Twoje dane do jednego pliku. Plik możesz trzymać w iCloud Drive, na Dysku Google albo na pendrive. Na nowym urządzeniu wybierz **Ustawienia → Wczytaj kopię**.

Usunięcie aplikacji z ekranu albo wyczyszczenie danych przeglądarki kasuje dane, dlatego rób kopię co jakiś czas.

---

## Dla starosty

- W **Ustawieniach** wybierz tryb **Starosta** i swoją specjalizację.
- Przy terminach, przedmiotach i kontaktach ustaw pole **Dla kogo**: Cała grupa, Cyberbezpieczeństwo albo Detektywi. W zakładkach przełącznik **Wszyscy / Cyber / Detektywi** pokazuje, co widzi dana specjalizacja.
- **Ustawienia → Udostępnij grupie** tworzy plik z terminami, przedmiotami i kontaktami. Plik wyślij na grupę, a po każdej zmianie wyślij nowy. Do pliku nie trafiają kontakty z rolą „Student”, Twój plan, zadania ani link do USOS.
- Aktualizacja aplikacji: podmień pliki w repozytorium, a w `sw.js` zwiększ numer w `panel-starosty-vX`. Urządzenia pobiorą nową wersję przy kolejnym uruchomieniu.
