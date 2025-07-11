# BRANTO Browser History Chrome Extension

Nowoczesna wtyczka do przeglądarki Chrome zbudowana w React, zgodna z Manifest V3, umożliwiająca wygodne przeglądanie historii odwiedzanych stron.

---

## 📋 Spis treści

- [Opis projektu](#opis-projektu)
- [Plan działania](#plan-działania)
- [Struktura projektu](#struktura-projektu)
- [Licencja](#licencja)

---

## 📝 Opis projektu

Wtyczka pozwala użytkownikowi na szybki podgląd historii przeglądania w formie czytelnej listy. UI zbudowany jest w React, a całość spełnia wymagania Manifest V3 Chrome Extensions.

---

## 🚀 Plan działania

### 1. Analiza wymagań i projekt funkcjonalny

- Określenie głównych funkcji: wyświetlanie historii, prosty UI, zgodność z Manifest V3.
- Opracowanie makiet UI.
- Sprawdzenie ograniczeń API Chrome.

### 2. Konfiguracja projektu

- Inicjalizacja projektu React (np. Vite).
- Organizacja struktury folderów (`public/`, `src/`).
- Przygotowanie pliku `manifest.json` z wymaganymi uprawnieniami.

### 3. Implementacja

- Integracja z API Chrome (`chrome.history`).
- Komunikacja między popupem a service workerem (jeśli potrzebna).
- Budowa interfejsu w React: lista historii, wyszukiwarka, paginacja.
- Stylizacja komponentów.

### 4. Testowanie

- Testy jednostkowe.
- Testy integracyjne w przeglądarce.
- Weryfikacja na różnych systemach.

### 5. Budowanie i pakowanie

- Konfiguracja procesu build (Webpack/Vite).
- Generowanie wersji produkcyjnej.
- Pakowanie do formatu zip zgodnego z Chrome Web Store.

### 6. Dokumentacja i publikacja

- Instrukcja instalacji i użytkowania.
- Opis uprawnień i funkcji.
- Publikacja lub testowanie lokalne.

---

## 📁 Struktura projektu

my-chrome-extension/ <br>
├── public/ <br>
│ ├── manifest.json <br>
│ └── icons/ <br>
├── src/ <br>
│ ├── components/ <br>
│ ├── App.jsx <br>
│ └── index.js <br>
├── package.json <br>
└── README.md <br>

---

## 📄 Licencja

Na ten moment licencja nie została jeszcze wybrana.  
Status: *do ustalenia, WIP (work in progress), ciąg dalszy nastąpi (cdn).*

---
