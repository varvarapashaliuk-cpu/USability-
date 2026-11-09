# Baza Wiedzy: Atlassian Design System

Źródło oficjalne: Atlassian Design (https://atlassian.design/)

---

## O Atlassian Design System
Atlassian Design System to kompendium zasad i komponentów służących do budowania narzędzi pracy zespołowej, systemów zarządzania zadaniami oraz złożonych aplikacji webowych (np. Jira, Confluence, Trello).

---

## Kluczowe Filary i Wzorce UX dla Audytora AI:

### 1. Komunikacja i Stan Systemu (Messaging & Feedback)
- **Flag / Toast Notifications:** Krótkie powiadomienia informujące o sukcesie akcji lub błędzie, które nie zmuszają użytkownika do zatrzymania pracy.
- **Inline Messages:** Komunikaty o błędach umieszczane bezpośrednio w miejscu ich wystąpienia (np. tuż pod błędnie wypełnionym polem formularza).
- **Modal Dialogs:** Okna modalne używane wyłącznie do krytycznych decyzji lub akcji (np. potweirdzenie usunięcia projektu).

### 2. Praca na Danych i Skomplikowane Formularze (Data & Forms)
- **Clear Form Hierarchy:** Formularze podzielone na sekcje ze zrozumiałą kolejnością pól, wyraźnie oznaczonymi polami wymaganymi oraz opcjonalnymi.
- **Table & Lists:** Tabele z danymi wyposażone w jasne filtry, opcje sortowania oraz stronicowanie (pagination) dla zachowania przejrzystości.
- **Empty States:** Ekran "brak danych" (gdy np. brak wyników wyszukiwania) zawsze zawiera wytyczne lub przycisk zachęcający do akcji (np. "Stwórz pierwsze zadanie").

### 3. Nawigacja i Struktura Widoku (Layout & Navigation)
- **Sidebar & Collapsible Panels:** Boczne panele nawigacyjne, które użytkownik może zwijać, aby zyskać więcej przestrzeni do pracy.
- **Breadcrumbs (Ścieżka powrotna):** Wyraźny wskaźnik pokazujący, gdzie użytkownik znajduje się w strukturze projektu.

---

## Wytyczne do Audytu na podstawie Atlassian Design System:
- Czy sytuacje z brakiem danych (Empty States) dają użytkownikowi jasną informację, co zrobić dalej?
- Czy formularze zawierają walidację na żywo z komunikatami tuż pod błędnym polem?
- Czy powiadomienia systemowe nie przeszkadzają w wykonywaniu głównego zadania na stronie?
