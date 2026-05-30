# Dostępność cyfrowa dla osób w spektrum autyzmu

Projekt edukacyjny prezentujący dwie wersje strony internetowej —
jedną zgodną z zasadami projektowania przyjaznego osobom w spektrum autyzmu,
drugą celowo łamiącą te zasady. Powstał jako materiał dydaktyczny
do nauki UX i dostępności cyfrowej.

## 🔗 Linki

- [Strona główna z omówieniem](https://TWOJA-NAZWA.github.io/autyzm-dostepnosc/)
- [✅ Strona dostępna — Biblioteka Miejska](https://TWOJA-NAZWA.github.io/autyzm-dostepnosc/dostepna.html)
- [❌ Strona niedostępna — MegaSklep](https://TWOJA-NAZWA.github.io/autyzm-dostepnosc/niedostepna.html)

## 📁 Zawartość repozytorium

| Plik | Opis |
|---|---|
| `omowienie.html` | Strona główna z pełną analizą porównawczą |
| `dostepna.html` | Formularz wypożyczenia książki — dobre praktyki UX |
| `niedostepna.html` | Sklep internetowy — celowo złamane zasady dostępności |

## ✅ Zasady zastosowane na stronie dostępnej

- Spokojne kolory — paleta kremowo-szałwiowa, tło off-white `#f5f2eb`
- Font **Atkinson Hyperlegible** (zaprojektowany przez Braille Institute) 17px, interlinia 1.65
- Kontrast tekstu ≥ 4.5:1 (zgodność z WCAG 2.1 AA)
- Liniowy formularz krok po kroku ze wskaźnikiem postępu
- Widoczne etykiety i opisy pomocnicze przy każdym polu
- Konkretne komunikaty błędów — co poszło nie tak i jak to naprawić
- Spójna, przewidywalna nawigacja z breadcrumbs
- Brak autoplay, brak migania, brak dźwięków
- Pełna obsługa klawiatury i czytników ekranu (skip link, ARIA landmarks, focus-visible)
- Respektowanie systemowego ustawienia `prefers-reduced-motion`

##  Zasady złamane na stronie niedostępnej

- Nagłówek migający z częstotliwością ~3 Hz (ryzyko napadu epileptycznego)
- Tło `#ff00ff` (magenta) + neony we wszystkich kanałach kolorów jednocześnie
- Dźwięk autoplay (beep 880 Hz) co 4 sekundy bez zgody użytkownika
- Pop-up blokujący treść, powracający co 8 sekund
- Fałszywy timer odliczający w nieskończoność — manipulacja lękiem
- Etykiety pól formularza ukryte przez `display: none`
- Przycisk „KUP" animowany i skaczący po ekranie
- Ważny tekst ukryty (biały na białym tle)
- Strona sama się przewija bez zgody użytkownika
- `outline: none !important` — całkowity brak fokusa klawiatury
- Chaotyczna hierarchia nagłówków bez logicznej struktury

## Zasoby

- [WCAG 2.1 — Web Content Accessibility Guidelines](https://www.w3.org/TR/WCAG21/)
- [Atkinson Hyperlegible Font](https://brailleinstitute.org/freefont)
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [A11y Project Checklist](https://www.a11yproject.com/checklist/)
- [prefers-reduced-motion — MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion)
