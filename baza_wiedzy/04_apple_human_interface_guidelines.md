# Baza Wiedzy: Apple Human Interface Guidelines (HIG)

Źródło oficjalne: Apple Developer (https://developer.apple.com/design/human-interface-guidelines/)

---

## O dokumentacji Apple HIG
Human Interface Guidelines (HIG) to oficjalny zbiór wytycznych i dobrych praktyk projektowych pomagających w tworzeniu wysokiej jakości interfejsów dla platform ekosystemu Apple (iOS, iPadOS, macOS, watchOS, visionOS).

---

## Kluczowe Filary Projektowe dla Audytora AI:

### 1. Podstawy Projektowania (Design Fundamentals)
- **Clarity (Przejrzystość):** Tekst musi być czytelny na każdym rozmiarze ekranu, ikony powinny jednoznacznie przekazywać znaczenie, a nawigacja nie może przytłaczać użytkownika.
- **Deference (Subtelność interfejsu):** Interfejs płynnie wspomaga użytkownika, nie rywalizując z jego treścią. Elementy sterujące nie odciągają uwagi od kluczowych zadań.
- **Depth (Głębia i warstwy):** Zastosowanie płaszczyzn, warstw oraz cieniowania pomaga użytkownikowi zrozumieć hierarchię i zależności między elementami.

### 2. Dostępność i Włączenie (Accessibility & Inclusion)
- **Minimum Target Size:** Klikalne elementy (np. przyciski) muszą mieć odpowiednio duży obszar dotykowy (minimum 44x44 punkty na iOS), aby łatwo można było w nie trafić palcem.
- **Dynamic Type:** Wsparcie dla skalowania czcionek – tekst zmienia rozmiar według ustawień systemowych użytkownika.
- **Kontrast i Kolor:** Kolor nie może być jedynym nośnikiem informacji (np. stan błędu powinien zawierać ikony lub tekst, a nie tylko czerwoną ramkę).

### 3. Nawigacja i Interakcja (Navigation & Interaction)
- **Spójna Nawigacja:** Używanie jasnych wzorców nawigacyjnych (np. pasek kart Tab Bar na dole ekranu w iOS dla najważniejszych sekcji).
- **Feedback i Gesty:** Każdy gest użytkownika (np. przunięcie, dotknięcie) powinien wywołać natychmiastową i przewidywalną odpowiedź wizualną lub haptyczną.

---

## Wytyczne do Audytu na podstawie Apple HIG:
- Czy interaktywne przyciski spełniają wymóg minimalnego rozmiaru obszaru dotyku (44x44 pt)?
- Czy hierarchia treści pozwala na łatwe skanowanie ekranu wzrokiem?
- Czy ikony i etykiety są proste i jednoznaczne dla użytkownika?
