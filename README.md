# SteloOS — SunoOS

Przeglądarkowy system operacyjny w jednym pliku (`index.html`), inspirowany m.in. [Luma](https://simplyluma.com/).

- Menedżer okien: przeciąganie za pasek tytułu, zmiana rozmiaru z 8 kierunków, minimalizacja/maksymalizacja (dwuklik na pasku też działa), focus aktywnego okna, „pokaż pulpit" (klik w pasek górny)
- Aplikacje: Filer (siatka/lista z kolumnami Typ/Rozmiar/Modyfikacja, szukanie), Settings (motyw, akcent, tapeta, tint), **Czat** (rozmowy + odpowiedzi), **Notatki** (edytor, trwałe w `localStorage`), **Aparat** (podgląd z kamery + migawka), **Statystyki** (wykres w czasie rzeczywistym), **Airdrop** (wysyłanie z paskiem postępu), **Obszary robocze**
- Launcher „All apps" (klik w logo — zaćmienie Słońca `assets/suno-logo.jpg`) z szukajką
- Ekran blokady + menu zasilania (QS: zablokuj / uśpij / restart), tryb nocny, poziom baterii (gdy API dostępne)
- Dock z wyspami: główny dok (menu | przypięte aplikacje | pozostałe — przypnij przez menu kontekstowe lub Ustawienia), wyspa szybkiego dostępu (Dokumenty / Pobrane / Obrazy / Muzyka — wybór przypiętych), miniatury otwartych okien (zamykanie ✕ z miniatury), kropki „uruchomiona aplikacja” w kolorze akcentu, QS, kalendarz; tryb aranżacji i widoczność wysp wyłącznie z Ustawień
- Motyw systemowy: dopóki nie wybierzesz motywu ręcznie, SunoOS podąża za preferencją systemową (`prefers-color-scheme`, także na żywo) — bez mignięcia tłem przy starcie
- Ustawienia trwałe w `localStorage` (`suno-prefs`): motyw (tylko wybór ręczny), akcent, tapeta, przezroczystość szkła (suwak), mrożenie (blur) wł/wył, tint, tryb nocny

Start: otwórz `index.html` w przeglądarce albo włącz GitHub Pages.
