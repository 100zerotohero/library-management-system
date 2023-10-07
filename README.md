# Liibrary Management System
# Biblioteka Online
## Opis
Biblioteka Online jest systemem pozwalającym na zarządzanie zbiorami książek w bibliotece. System umożliwia dodawanie, usuwanie, wyszukiwanie i wypożyczanie książek, a także przechowuje informacje o użytkownikach biblioteki.
## Wymagania
Aby uruchomić Bibliotekę Online, należy spełnić następujące wymagania:
- Python (wersja 3.7 lub nowsza)
- Django (wersja 3.2.7)
- django-crispy-forms (wersja 1.12.0)
## Instalacja
Aby zainstalować Bibliotekę Online, wykonaj poniższe kroki:
1. Sklonuj repozytorium na swoje urządzenie:
   ```
   git clone https://github.com/twoj-uzytkownik/biblioteka-online.git
   ```
2. Przejdź do katalogu projektu:
   ```
   cd biblioteka-online
   ```
3. Zainstaluj wymagane biblioteki przy użyciu narzędzia pip:
   ```
   pip install -r requirements.txt
   ```
4. Uruchom migracje aby zainicjalizować bazę danych:
   ```
   python manage.py migrate
   ```
5. Uruchom serwer deweloperski:
   ```
   python manage.py runserver
   ```
Po wykonaniu powyższych kroków, Biblioteka Online powinna być dostępna pod adresem [http://localhost:8000](http://localhost:8000).
## Konfiguracja
Domyślne ustawienia Biblioteki Online zostały już skonfigurowane w pliku `settings.py`. W razie potrzeby, można dostosować ustawienia bazy danych, języka itp.
## Uruchamianie testów
Aby uruchomić testy jednostkowe, wykonaj poniższą komendę:
```
python manage.py test
```
## Dokumentacja API
Biblioteka Online udostępnia prosty interfejs API do zarządzania zasobami. Pełna dokumentacja API jest dostępna pod adresem [http://localhost:8000/api/docs/](http://localhost:8000/api/docs/).
## Wkładanie zmian
Jeśli chcesz przyczynić się do rozwoju Biblioteki Online, możesz to zrobić, przesyłając pull requesty. Upewnij się, że opisujesz dokładnie wprowadzane zmiany i dodajesz odpowiednie testy jednostkowe.
## Autorzy
- Aleksandra A.
## Licencja
Biblioteka Online jest dostępna na licencji MIT. Szczegółowe informacje można znaleźć w pliku LICENSE.
