# Panel Starosty – instalacja na iPadzie

Aplikacja działa w całości na Twoim urządzeniu. Dane zapisują się w pamięci iPada, nie na żadnym serwerze. Kopię zapisujesz przyciskiem **Kopia → Zapisz kopię do pliku** w aplikacji Pliki (iCloud Drive, „Na moim iPadzie” albo dysk USB).

## 1. Wystaw pliki pod adresem https (jednorazowo, za darmo)

iPadOS instaluje takie aplikacje tylko ze strony https. Najprościej przez GitHub Pages:

1. Na github.com załóż nowe repozytorium, np. `panel-starosty` (może być publiczne, bo w plikach nie ma Twoich danych).
2. **Add file → Upload files** i wrzuć wszystkie pliki z tego folderu: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`.
3. **Settings → Pages → Branch: main → Save**. Po minucie strona będzie pod adresem `https://<twoj-login>.github.io/panel-starosty/`.

## 2. Zainstaluj na iPadzie

1. Otwórz ten adres w **Safari**.
2. Stuknij **Udostępnij → Do ekranu początkowego → Dodaj**.
3. Uruchamiaj aplikację z ikony „Starosta”. Działa też bez internetu.

To samo zrobisz na iPhonie i Macu (Safari → Plik → Dodaj do Docka). Każde urządzenie ma osobne dane; przenosisz je plikiem kopii (**Kopia → Wczytaj z pliku**).

## Ważne

- Dane z ikony na ekranie początkowym są oddzielne od danych w zwykłej karcie Safari. Korzystaj zawsze z ikony.
- Usunięcie ikony z ekranu początkowego usuwa też dane. Rób kopię regularnie, np. raz w tygodniu.
- Po zmianie plików aplikacji zmień w `sw.js` numer w `panel-starosty-v1`, żeby iPad pobrał nową wersję.
