# Bank Bonus PWA 1.7

## Publikacja przez GitHub Pages
1. Zaloguj się na GitHub i utwórz nowe repozytorium, np. `bank-bonus`.
2. Ustaw repozytorium jako publiczne (dla bezpłatnego GitHub Pages).
3. Wgraj bezpośrednio do katalogu głównego repozytorium wszystkie pliki z tej paczki.
4. Otwórz Settings → Pages.
5. W sekcji Build and deployment wybierz Deploy from a branch, gałąź `main` i katalog `/ (root)`, następnie Save.
6. Poczekaj na publikację i otwórz wygenerowany adres HTTPS.

## Instalacja na iPhonie
1. Otwórz opublikowany adres w Safari.
2. Wybierz Udostępnij → Dodaj do ekranu początkowego.
3. Ustaw nazwę `Bank Bonus` i wybierz Dodaj.
4. Uruchamiaj aplikację z nowej ikony.

## Ważne informacje o danych
- Aplikacja zachowuje dotychczasowe klucze localStorage: `bankbonus_v1_1` oraz `bankbonus_v1_1_history`.
- Dane są przechowywane lokalnie w pamięci przeglądarki/aplikacji na danym urządzeniu. Nie ma synchronizacji z innymi urządzeniami ani konta użytkownika.
- Przed pierwszym użyciem PWA wyeksportuj kopię danych ze starej wersji w Safari, a następnie zaimportuj ją w PWA. Safari i zainstalowana aplikacja mogą mieć oddzielne magazyny danych.
- Kopię zapasową można eksportować/importować w zakładce „Moje promocje”.
- Nie usuwaj danych Safari ani aplikacji bez wcześniejszego eksportu kopii.
- Service worker działa po opublikowaniu pod HTTPS (GitHub Pages zapewnia HTTPS). Po aktualizacji plików może być konieczne ponowne uruchomienie aplikacji lub odświeżenie strony przy dostępie do internetu.

## Zawartość
- `index.html` — aplikacja Bank Bonus 1.7
- `manifest.webmanifest` — nazwa, ikony i ustawienia PWA
- `service-worker.js` — cache aplikacji i obsługa offline
- pliki PNG — ikony i favicon
