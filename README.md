# Gourmet Paradise Bot

## Opis
**Gourmet Paradise** to interaktywny asystent restauracji zaprojektowany, aby ułatwić komunikację z klientami. Bot odpowiada na pytania dotyczące menu, rekomenduje dania i napoje, informuje o cenach oraz czasie przygotowania, a także pomaga w rezerwacji stolików.

## Funkcje
- **Rekomendacje Menu:** Bot oferuje sugestie dotyczące dań i napojów na podstawie preferencji kuchni użytkownika.
- **Informacje o Daniach:** Udziela informacji o składnikach, cenach i przewidywanym czasie przygotowania dań.
- **Rezerwacja Stolików:** Pomaga w rezerwacji stolików na zewnątrz, utrzymując kontekst rozmowy.
- **Obsługa Alergii:** Rejestruje informacje o alergiach użytkownika i sugeruje odpowiednie dania.
- **Różnorodne Odpowiedzi:** Używa tagu `<random>` do oferowania różnorodnych i naturalnych odpowiedzi.

## Technologia
Bot działa na zasadzie dopasowywania wzorców zapytań użytkownika do odpowiednich szablonów odpowiedzi, korzystając z danych z pliku `menu.maps`. Utrzymuje kontekst rozmowy za pomocą tagów `<that>` i `<topic>`, oferując spójną i angażującą interakcję.
Kod źródłowy źródłowy znajduje się w `/files/udc.aiml`
