# PESEL tester
Prosta aplikacja, która może zostać elementem większego systemu, gdzie potrzebna jest walidacja numeru PESEL

# TODO lista rozwojowa
Walidacja danych wejściowych

- Sprawdź, czy użytkownik wpisał dokładnie 11 cyfr

- Pokaż ostrzeżenie, jeśli długość lub typ danych są błędne

Czysta separacja logiki

- Przenieś algorytm sprawdzania PESEL-a do osobnej funkcji is_valid_pesel(pesel_str)

Lepsze GUI

- Opcjonalnie zamiast zmieniać tekst przycisku, dodaj osobny Label do pokazywania komunikatu (zielony/czerwony tekst)

- Dodaj przycisk „Wyczyść” do resetowania formularza

Dodatkowe funkcje (opcjonalnie)

- Odczytaj datę urodzenia z PESEL-a i pokaż ją w GUI

- Rozpoznaj płeć (na podstawie 10. cyfry — parzysta = kobieta, nieparzysta = mężczyzna)

