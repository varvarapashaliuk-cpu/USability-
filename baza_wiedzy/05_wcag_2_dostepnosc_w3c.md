# Baza Wiedzy: W3C WCAG 2 (Web Content Accessibility Guidelines)

Źródło oficjalne: W3C WAI (https://www.w3.org/WAI/standards-guidelines/wcag/)

---

## O Standardzie WCAG 2
WCAG (Web Content Accessibility Guidelines) to międzynarodowy standard określający zasady projektowania i tworzenia stron oraz aplikacji internetowych dostępnych dla osób z niepełnosprawnościami (np. wzrokowymi, słuchowymi, ruchowymi czy poznawczymi).

---

## 4 Główne Zasady WCAG (POUR) dla Audytora AI:

### 1. Postrzegalność (Perceivable)
- **Tekst alternatywny:** Wszystkie elementy nietekstowe (obrazy, grafiki, ikony interaktywne) muszą posiadać opis tekstowy (`alt`).
- **Napisy i audiodeskrypcja:** Materiały wideo i audio zawierają napisy lub transkrypcję.
- **Kontrast:** Tekst musi posiadać odpowiedni kontrast w stosunku do tła (minimum 4.5:1 dla standardowego tekstu, 3:1 dla dużego tekstu).
- **Skalowalność:** Tekst można powiększyć do 200% bez utraty funkcjonalności i treści.

### 2. Funkcjonalność (Operable)
- **Dostępność z klawiatury:** Cała funkcjonalność strony jest dostępna przy użyciu samej klawiatury (klawisz Tab, Enter, Spacja).
- **Widoczny fokus (Focus Visible):** Elementy aktywne po przejściu klawiaturą mają wyraźnie widoczną obramówkę focusa.
- **Wystarczająco dużo czasu:** Użytkownik ma czas na przeczytanie i wykonanie akcji (brak wymuszonych limitów czasowych bez możliwości przedłużenia).
- **Zapobieganie napadom:** Brak elementów migających częściej niż 3 razy na sekundę.

### 3. Zrozumiałość (Understandable)
- **Czytelność:** Język strony jest wyraźnie określony w kodzie (np. `lang="pl"`).
- **Przewidywalność:** Nawigacja i komponenty działają w powtarzalny, przewidywalny sposób po wejściu w interakcję.
- **Pomoc przy błędach:** Formularze wyraźnie wskazują błędy wklejania/wpisywania i sugerują sposoby ich naprawy.

### 4. Rzetelność (Robust)
- **Zgodność z technologiami wspomagającymi:** Kod interfejsu jest poprawny semantycznie (używanie odpowiednich znaczników HTML i ról ARIA), co umożliwia prawidłowe odczytanie treści przez czytniki ekranowe.

---

## Wytyczne do Audytu na podstawie WCAG 2:
- Czy obrazy informacyjne mają uzupełniony tekst alternatywny (`alt`)?
- Czy kontrast tekstu do tła spełnia wymogi minimum 4.5:1?
- Czy każdy element aktywny ma widoczny stan skupienia (focus) po zaznaczeniu klawiaturą?
- Czy pola formularzy zawierają jasne etykiety (labels) oraz komunikaty błędów?
