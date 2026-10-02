# Memento Egzamini – instrukcja

*Memento egzamini* – pamiętaj o egzaminie.

Plan zajęć z USOS, terminy egzaminów, przedmioty i kontakty do prowadzących w jednej aplikacji na telefon i tablet.

**Adres aplikacji:** https://11rk1.github.io/Starosta/

Twoje notatki, zadania i własne wpisy zostają tylko na Twoim urządzeniu, a starosta ich nie widzi. Informacje od starosty (plan, terminy, przedmioty, kontakty do prowadzących) są publikowane w pliku `grupa.json` w tym repozytorium i pobierają się do aplikacji automatycznie.

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

## 3. Plan zajęć

Plan Twojej specjalizacji pobiera się automatycznie od starosty (punkt 4). Nic więcej nie musisz robić.

Przy zajęciach zobaczysz, jak się odbywają:
- **Teams** – zajęcia online na MS Teams (w USOS mają adres w Józefowie),
- **Zjazd** – zajęcia stacjonarne w Mińsku Mazowieckim.

Dni ze zjazdem są oznaczone „Zjazd w Mińsku”, a dni w całości zdalne mają oznaczenie „Online”.

**Własny link z USOS (opcjonalnie).** Jeśli chcesz, żeby plan aktualizował się sam:
1. W **USOSweb** wejdź w **Mój USOSweb** → **Plan zajęć**, wybierz eksport i skopiuj **Odnośnik do planu**.
2. W aplikacji wybierz **Plan** → **Połącz z USOS**, wklej link i stuknij **Zapisz i pobierz**.

Z własnym linkiem widzisz swój plan zamiast planu od starosty, a odświeża się on automatycznie co kilka godzin.

> Link z USOS to prywatny klucz do Twojego planu, który działa bez logowania. Nie wysyłaj go nikomu poza starostą.

## 4. Informacje od starosty

Plan zajęć, terminy egzaminów, warunki zaliczeń i kontakty do prowadzących **pobierają się same** przy każdym uruchomieniu aplikacji z internetem. Zmiany od starosty pojawiają się zwykle w ciągu kilku minut.

Wpisy od starosty mają dopisek „od starosty”. Twój plan z własnego linku, zadania i własne wpisy pozostają bez zmian.

Jeśli starosta wyśle plik `dla-grupy-RRRR-MM-DD.json`, możesz go też wczytać ręcznie: **Ustawienia → Wczytaj plik od starosty**.

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
- **Plan → Połącz z USOS** (albo **Linki USOS**) ma dwa pola: plan Cyberbezpieczeństwa i plan Detektywów. Link Detektywów weź od kogoś z tej specjalizacji. Odśwież plan przed wysłaniem pliku grupie.
- Przy terminach, przedmiotach i kontaktach ustaw pole **Dla kogo**: Cała grupa, Cyberbezpieczeństwo albo Detektywi. W zakładkach przełącznik **Wszyscy / Cyber / Detektywi** pokazuje, co widzi dana specjalizacja.
- **Automatyczna publikacja (jednorazowa konfiguracja):**
  1. Na github.com: zdjęcie profilowe → **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
  2. Nazwa dowolna, **Expiration** np. 1 rok, **Repository access: Only select repositories → Starosta**.
  3. **Permissions → Repository permissions → Contents: Read and write**. Potem **Generate token** i skopiuj token.
  4. W aplikacji: **Ustawienia → Połączenie z GitHubem**, wklej token i stuknij **Zapisz i opublikuj**.

  Od tej pory każda zmiana terminów, przedmiotów, kontaktów albo planu z USOS sama trafia do grupy po kilku sekundach. Token zostaje tylko na Twoim urządzeniu, nikomu go nie wysyłaj.
- **Ustawienia → Wyślij jako plik** to zapasowy sposób bez GitHuba. Do publikacji i pliku trafia plan z USOS obu specjalizacji. Nie trafiają do niego kontakty z rolą „Student”, zajęcia dodane ręcznie, zadania ani linki do USOS.
- Aktualizacja aplikacji: podmień pliki w repozytorium, a w `sw.js` zwiększ numer w `panel-starosty-vX`. Urządzenia pobiorą nową wersję przy kolejnym uruchomieniu.
