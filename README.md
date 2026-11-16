# TaskHub (pracovní název)

Osobní přehled úkolů, kategorií a návyků. Webová apka (PWA), kterou si nainstaluješ na iPhone přes Safari → Sdílet → Přidat na plochu.

- Data jsou jen v zařízení (localStorage), bez účtu, bez sledování.
- Záloha: Nastavení → Zkopírovat zálohu / Načíst zálohu ze souboru.
- Funguje offline (service worker `sw.js`). Při vydání zvyš `CACHE` v `sw.js` a `APP_VERSION` v `index.html`.
- Texty CS/EN jsou v objektu `STRINGS`, barvy a rozměry v CSS tokenech (`:root`).
- Datový formát je verzovaný (`DATA_VERSION` + `MIGRATIONS`), aktualizace nemažou data.

## Licence zdrojů
- Písmo Plus Jakarta Sans: SIL Open Font License 1.1 (načítá se z Google Fonts; pro nativní verzi přibalit).
- Ikony v aplikaci a ikona apky: vlastní kresba, bez cizích licencí.
- Žádné externí knihovny.
