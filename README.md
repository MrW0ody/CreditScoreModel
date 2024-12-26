# Raport z Budowy Modelu Credit Scoringu

## Wymagania

Aby uruchomić projekt, należy upewnić się, że wszystkie wymagane biblioteki są zainstalowane. W tym celu przygotowano plik `requirements.txt` zawierający listę niezbędnych zależności.

## Instalacja

1. Upewnij się, że masz zainstalowanego **Python 3.12**.
2. Sklonuj repozytorium lub pobierz kod źródłowy.
3. W terminalu przejdź do katalogu projektu i wykonaj poniższą komendę:

   ```bash
   pip install -r requirements.txt
   

## W ramach projektu dostosowano hiperparametry modelu przy użyciu dwóch metod:

1. GridSearchCV – proces trwał około 22 minut na lokalnym komputerze.
2. RandomizedSearchCV – proces trwał około 9 minut na tym samym sprzęcie.
