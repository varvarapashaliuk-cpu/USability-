# Baza Wiedzy: Przykłady Heurystyk w Praktyce (Witly.ai)

Źródło: Witly.ai (https://witly.ai) - "10 heurystyk z przykładami z własnych zakupów"

---

## 1. Widoczność statusu systemu (Visibility of System Status)
- **Definicja:** System powinien zawsze informować użytkownika o tym, co się dzieje poprzez odpowiedni feedback w rozsądnym czasie.

- **Przykłady z rynku (Allegro / InPost):**
  - Allegro prowadzi kupującego przez etapowe statusy przesyłki: „Oczekuje na nadanie”, „Nadana”, „W drodze”, „Odbierz przesyłkę”.
  - Aplikacja InPost po zalogowaniu numerem telefonu sama pokazuje wszystkie paczki adresowane do użytkownika bez konieczności ręcznego wpisywania numerów przesyłek.

- **Dobre praktyki wdrożeniowe:**
  - Paski/liczniki postępu w nagłówku (np. „0 z 4 kroki”).
  - Natychmiastowe przeliczanie ceny po zmianie wariantu (bez opóźnień i niespodzianek w koszyku).
  - Dynamiczne przyciski filtrów pokazujące liczbę wyników przed ich zastosowaniem (np. „Pokaż 418 produktów”).
  - Potwierdzenie dodania do koszyka od razu z powiadomieniem aria-live dla czytników ekranu.

---

## 2. Zgodność systemu ze światem rzeczywistym (Match Between the System and the Real World)
- **Definicja:** System powinien posługiwać się językiem, słowami i pojęciami znanymi użytkownikowi z codziennego życia.
