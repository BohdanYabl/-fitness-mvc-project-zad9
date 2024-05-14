# # Fitness MVC Projekt

## Spis treści
1. Opis
2. Funkcjonalności
3. Instrukcje użytkowania

## Opis
Projekt Fitness MVC to aplikacja webowa, która umożliwia zarządzanie treningami fitness. Pozwala dodawać, edytować, przeglądać i usuwać treningi.

## Funkcjonalności
- Przeglądanie listy treningów fitness.
- Dodawanie nowych treningów.
- Edycja istniejących treningów.
- Usuwanie treningów.
- Wyszukiwanie treningów po nazwie

## Instrukcje użytkowania
### Uruchomienie aplikacji
1. Upewnij się, że na Twoim komputerze zainstalowany jest Node.js.
2. Sklonuj repozytorium projektu na swój lokalny komputer.
3. Otwórz terminal i przejdź do katalogu projektu.
4. W terminalu wpisz npm install, aby zainstalować wszystkie niezbędne zależności.
5. Uruchom serwer, wpisując w terminalu npm start.

### Dodatkowe pakiety
Projekt korzysta z następujących paczek:
- express - framework do tworzenia aplikacji webowych w Node.js.
- ejs - szablon silnika widoku do generowania interfejsu użytkownika.
- mongoose - biblioteka do obsługi MongoDB w Node.js.
- dotenv - biblioteka do ładowania zmiennych środowiskowych z pliku .env.
- method-override - middleware do obsługi metod HTTP innych niż GET i POST.
- body-parser - middleware do parsowania ciała żądania HTTP.
- nodemon - narzędzie do automatycznego restartowania serwera po zmianach w plikach.

### Konfiguracja pliku .env
Projekt wymaga pliku .env z następującą zmienną środowiskową:
DATABASE_URL=mongodb://localhost/trainings

Pamiętaj, aby utworzyć plik .env w głównym katalogu projektu i dodać do niego odpowiednią wartość dla zmiennej DATABASE_URL.

### Interakcja z aplikacją
- Po uruchomieniu aplikacji możesz przeglądać listę treningów, dodawać nowe, edytować istniejące oraz usuwać je.
- Aby dodać nowy trening, kliknij na link "Add training" na pasku nawigacyjnym.
- Aby edytować istniejący trening, kliknij na link "Edit" przy odpowiednim treningu na stronie głównej.
- Aby usunąć trening, kliknij na link "Delete" przy odpowiednim treningu na stronie głównej