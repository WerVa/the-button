# 🟢 The Button

Prosta aplikacja w Django z jednym przyciskiem `Ping`, który wysyła zapytanie do backendu i wyświetla odpowiedź w przeglądarce.

---

## 📦 Wymagania

- Python 3.8+
- Docker (opcjonalnie)
- `pip` lub `virtualenv` (jeśli uruchamiasz bez Dockera)

---

## 🚀 Uruchamianie aplikacji

Masz dwie możliwości:

---

### ✅ Opcja 1: Uruchomienie w Dockerze (rekomendowane)

🔹 1.  `sudo docker-compose up --build`

### ✅ Opcja 2: Uruchomienie lokalnie (bez Dockera)

🔹 1. Stwórz wirtualne środowisko:

`python3 -m venv venv`

🔹 2. Aktywuj środowisko:

`source venv/bin/activate`  # (na Windows: venv\Scripts\activate)

🔹 3. Zainstaluj wymagania:

`pip install -r requirements.txt`

🔹 4. Uruchom serwer
`python manage.py runserver`


## Bezpieczeństwo

- Nie uruchamiaj aplikacji w trybie debug w środowisku produkcyjnym.
- Nie przechowuj sekretów (np. kluczy i haseł) bezpośrednio w kodzie repozytorium; używaj zmiennych środowiskowych.
- Jeśli uruchamiasz aplikację publicznie, ogranicz dostęp do hosta i portów tylko do zaufanych użytkowników lub sieci.
- Regularnie aktualizuj zależności z plików `requirements.txt` oraz obrazy Dockera, jeśli są używane.
