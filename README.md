# SteloOS — SunoOS

Przeglądarkowy system operacyjny w jednym pliku (`index.html`), inspirowany m.in. [Luma](https://simplyluma.com/).

- Menedżer okien: przeciąganie za pasek tytułu, zmiana rozmiaru z 8 kierunków, minimalizacja/maksymalizacja (dwuklik na pasku też działa), focus aktywnego okna, „pokaż pulpit" (klik w pasek górny)
- Aplikacje: Filer (siatka/lista z kolumnami Typ/Rozmiar/Modyfikacja, szukanie), Settings (motyw, akcent, tapeta, tint), **Czat** (rozmowy + odpowiedzi), **Notatki** (edytor, trwałe w `localStorage`), **Aparat** (podgląd z kamery + migawka), **Statystyki** (wykres w czasie rzeczywistym), **Airdrop** (wysyłanie z paskiem postępu), **Obszary robocze**, **Kalkulator** (klik + klawiatura), **Zadania** (trwałe w `suno-tasks`), **Zegar** (stoper, Spacja = start/stop)
- Systemowe menu kontekstowe (PPM) na pulpicie, w Filerze (pliki: otwórz / info / kosz) i na ikonach doku (otwórz / przypnij)
- Toasty wewnątrz okien z akcją **Cofnij** (np. plik do kosza, usunięte zadanie) — dostępne dla czytników ekranu (`role=status`)
- Geometria okien zapisywana między wizytami (`suno-wins`); przy pierwszym starcie rozkład deterministyczny (anchoring do wymiarów ekranu, na wąskich ekranach kaskada); link `index.html?app=<nazwa>` otwiera tryb jednej aplikacji, `?app=none` — czysty pulpit
- Launcher „All apps" (klik w logo — zaćmienie Słońca `assets/suno-logo.jpg`) z szukajką
- Ekran blokady + menu zasilania (QS: zablokuj / uśpij / restart), tryb nocny, poziom baterii (gdy API dostępne)
- Dock z wyspami: główny dok (menu | przypięte aplikacje | pozostałe — przypnij przez menu kontekstowe lub Ustawienia), wyspa szybkiego dostępu (Dokumenty / Pobrane / Obrazy / Muzyka — wybór przypiętych), kropki „uruchomiona aplikacja” w kolorze akcentu (elipsa = aplikacja na wierzchu; klik na aktywną ikonę minimalizuje), QS, kalendarz; tryb aranżacji i widoczność wysp wyłącznie z Ustawień
- Motyw systemowy: dopóki nie wybierzesz motywu ręcznie, SunoOS podąża za preferencją systemową (`prefers-color-scheme`, także na żywo) — bez mignięcia tłem przy starcie
- Ustawienia trwałe w `localStorage` (`suno-prefs`): motyw (tylko wybór ręczny), akcent, tapeta, przezroczystość szkła (suwak), mrożenie (blur) wł/wył, tint, tryb nocny

Start: otwórz `index.html` w przeglądarce albo włącz GitHub Pages.

Skróty: **Win/Meta + Spacja** otwiera wyszukiwarkę aplikacji z dowolnego miejsca (na Windowsie, gdzie system przechwytuje Win+Spację, działa też **Ctrl + Spacja**); **Ctrl/Cmd + F** — szukajka w przednim oknie (Filer/Ustawienia), **Ctrl/Cmd + N** — nowa notatka, **Spacja** — start/stop stopera (Zegar); **Esc** zamyka warstwy.
