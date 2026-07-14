# Licznik Tort do OBS

## Konfiguracja Firebase
1. Utwórz projekt w Firebase Console.
2. Dodaj aplikację internetową.
3. Utwórz Realtime Database.
4. Wklej konfigurację aplikacji do `assets/firebase-config.js`.
5. W Realtime Database → Rules wklej zawartość `firebase-rules.json`.

## Publikacja na GitHub Pages
1. Utwórz repozytorium.
2. Wgraj wszystkie pliki z paczki.
3. Wejdź w Settings → Pages.
4. Wybierz publikację z gałęzi `main`, katalog `/root`.

## Adresy
Panel:
`https://LOGIN.github.io/REPO/control.html?room=tort`

OBS:
`https://LOGIN.github.io/REPO/overlay.html?room=tort`

W OBS dodaj Źródło przeglądarki i ustaw 500 × 250.

Parametr `room` musi być taki sam w panelu i overlayu. Dla prywatnego użycia zastosuj trudniejszą nazwę pokoju.
