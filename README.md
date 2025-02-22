# Recipe_app

## Opis

Recipe_app to aplikacja umożliwiająca użytkownikom przeglądanie, dodawanie i zarządzanie przepisami kulinarnymi. Dzięki niej możesz łatwo organizować swoje ulubione przepisy i odkrywać nowe inspiracje kulinarne.

## Funkcje

- **Przeglądanie przepisów**: Przeglądaj dostępne przepisy z możliwością filtrowania według kategorii.
- **Dodawanie nowych przepisów**: Dodawaj własne przepisy, wprowadzając tytuł, składniki, instrukcje oraz zdjęcia.
- **Edycja i usuwanie przepisów**: Zarządzaj swoimi przepisami poprzez edycję lub usuwanie istniejących.
- **Wyszukiwanie**: Szybko znajdź przepisy po tytule lub składnikach.
- **Obsługa zdjęć**: Możliwość dodawania zdjęć powiązanych z przepisami.
- **Filtrowanie**: Wyszukuj przepisy według różnych kryteriów, co ułatwia znalezienie interesujących Cię pozycji.

## Wymagania

- Python 3.8 lub nowszy
- Docker

## Instalacja

1. **Klonowanie repozytorium**:

   ```bash
   git clone https://github.com/Foool1/Recipe_app.git
   cd Recipe_app
   ```

2. Użycie Dockera:

Uruchomienie aplikacji w kontenerze Docker:

```bash
docker-compose up --build
```

Aplikacja udostępnia interaktywną dokumentację API za pomocą Swaggera. Aby zapoznać się z pełną dokumentacją, otwórz w przeglądarce.
```bash
http://127.0.0.1:8000/api/docs/
```


Autoryzacja

Przed przetestowaniem zabezpieczonych endpointów wykonaj następujące kroki:

Rejestracja użytkownika – utwórz nowego użytkownika przy użyciu odpowiedniego endpointu.

Logowanie – zaloguj się, aby otrzymać token.

Autoryzacja w Swaggerze – w interfejsie Swaggera kliknij przycisk "Authorize" i wprowadź token w formacie:

Token "wygenerowany token"
