# Interaktywna mapa Europy

Prosty projekt HTML/JS z: 
- mapą Europy z podziałem na kraje,
- tabelą z wartościami dla krajów,
- automatycznym kolorowaniem według legendy,
- resetowaniem danych do stanu domyślnego.

## Uruchomienie

1. Otwórz katalog projektu w przeglądarce.
2. Możesz też uruchomić lokalny serwer:

```bash
cd /ścieżka/do/projektu
python -m http.server 8000
```

Następnie otwórz:

```text
http://localhost:8000
```

## Jak działa kolorowanie

W tabeli wpisujesz liczbę:
- 0 → czarny
- 1 → zielony
- 2 → czerwony
- brak danych → bez koloru

## Wartość domyślna

Projekt przyjmuje przykładowe dane:
- Polska = 1
- Niemcy = 1
- Anglia = 2
- Francja = 0

Pozostałe kraje pozostają bez koloru.
