# Agent N8N ✨

Zautomatyzowany agent stworzony na platformie **n8n (low-code)** z wykorzystaniem **Google Gemini** jako zaawansowanego modelu AI. Ma na celu inteligentne usprawnienie codziennych zadań związanych z kalendarzem, komunikacją, zarządzaniem zadaniami i pamięcią kontekstową.

## 🚀 Co potrafi?

| Kategoria | Funkcjonalność | Narzędzie |
| :--- | :--- | :--- |
| **Inteligencja** | **Model AI** (LangChain Agent) wykorzystujący **Google Gemini** do inteligentnego przetwarzania zapytań. | `AI Agent`, `Google Gemini Chat Model` |
| **Zarządzanie Czasem** | Szybkie **dodawanie wydarzeń** i **sprawdzanie kalendarza** na dany okres. | `Google Calendar Tool` |
| **Komunikacja** | Wysyłanie wiadomości e-mail. | `Gmail Tool` |
| **Zadania** | **Tworzenie nowych zadań** i list zadań. | `Google Tasks Tool` |
| **Pamięć Kontekstowa** | **Utrzymanie kontekstu rozmowy** dla spójnych interakcji. | `Simple Memory` |
| **Personalizacja** | **Odczyt i aktualizacja personalizowanych informacji** w zewnętrznym dokumencie. | `Google Docs Tool` |
| **Integracja Zewnętrzna** | **Interakcja z zewnętrznym serwerem pamięci (MCP)** (Client i Server). | `MCP Client`, `Personal MCP Memory Server` |
| **Info** | Sprawdzanie aktualnej daty i godziny. | `Date & Time` |
| **Bezpieczeństwo** | **Weryfikacja tożsamości użytkownika** (ID czatu) przed wykonaniem zadań. | `If`, `Data Table` |

## ⚙️ Technologia

* **Platforma Automatyzacji:** n8n (LangChain Agent)
* **Model AI:** Google Gemini (przez Google API)
* **Kanał Komunikacji:** Telegram
* **Integracje:** Google API (Calendar, Gmail, Tasks, Docs), Telegram, MCP (Memory Server, Client), Data Table.
