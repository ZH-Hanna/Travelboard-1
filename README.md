# Travelboard :earth_americas::v:
## Dokumentacja: 


### 1. Charakterystyka  oprogramowania 
Nazwa skrócona: TravelBoard

Nazwa pełna: TravelBoard - asystent podróżnika

Krótki opis: Aplikacja mobilna służąca jako asystent podróży, która pomoże użytkownikowi w wyborze atrakcji w podróży, pokazująca prognozę pogody w określonym miejscu i pozwalająca po przejrzeniu informacji prowadzić osobisty dziennik wpisów.


### 2. Prawa autorskie 
Autorzy: Eliza Sinkevich, Hanna Zhuk, Irina Frolova

Licencja: MIT

### 3. Specyfikacja wymagań

#### Wymagania funkcjonalne
| Identyfikator | Kategoria | Podkategoria | Nazwa krótka | Opis | Priorytet |
|:-:|:-:|:-|:-|:-|:-:|
|1|funkcjonalne|Nawigacja|Wybór miasta|Możliwość ustawienia swojego miasta|1|
|2|funkcjonalne|Nawigacja|Mapa z atrakcjami|Wyświetlenie mapę regionu wraz z orientacyjną lokalizacją atrakcji w postaci pinezek na mapie|1|
|3|funkcjonalne|Dostosowanie wyników|Informacja o atrakcji|Po kliknięciu na pinezkę system powinien wyświetlić podstawowe informacje o atrakcji: nazwę, opis, lokalizację|1|
|4|funkcjonalne|Dostosowanie wyników|Wyszukiwarka atrakcji|Wyszukiwanie atrakcji w sposób przeklikania zdjęć z opisem|2|
|5|funkcjonalne|Dostosowanie wyników|Filtrowanie atrakcji|Możliwość filtrowania atrakcji według zainteresowań|3|
|6|funkcjonalne||Pogoda|Wyświetlenie informacje meteorologiczne w zakładce "Pogoda"|3|
|7|funkcjonalne|Projektowe|Podłączenie bazy danych|Zapis danych z wykorzystaniem SQLite|2|

#### Wymagania niefunkcjonalne
| Identyfikator | Kategoria | Podkategoria | Nazwa krótka | Opis | Priorytet |
|:-:|:-:|:-|:-|:-|:-:|
|1|niefunkcjonalne|Statystyki||Dokładny zapis statystyk|2|
|2|niefunkcjonalne|Nawigacja||Szybka nawigacja w aplikacji |1|
|3|niefunkcjonalne|GUI|Wygląd interfejsów|intuicyjny i estetyczny interfejs|1|
|4|niefunkcjonalne|Bezpieczeństwo||Zgodność z wymogami bezpieczeństwa|2|
|5|niefunkcjonalne|Elastyczność integracji||Elastyczność pod względem możliwości integracji z innymi popularnymi serwisami społecznościowymi |3|
|6|niefunkcjonalne|Dostępność|| Dostęp dla użytkowników do użytku w dowolnym momencie |1|
|7|niefunkcjonalne|Prywatność||Zachowanie prywatności użytkowników|2|


### 4. Projekt (język UML)


### 5. Architektura systemu/oprogramowania

#### Architektura rozwoju 
| Lp | Nazwa produktu | Przeznaczenie w projekcie | Wersja  | 
|:-:|:-|:-|:-:|
|1|Java|Backend aplikacji|8|
|2|Xml|Frontend aplikacji|--|
|3|SQLite|Zarządzanie relacyjną bazą danych z atrakcjiami | 3.35.3 |


#### Architektura uruchomieniowa 
| Lp | Nazwa produktu | Przeznaczenie w projekcie | Wersja  | 
|:-:|:-|:-|:-:|
|1|Android Studio|Środowisko IDE używane przy tworzeniu projektu|4.1.2|
|2|Windows 10 |System operacyjny używany przy tworzeniu projektu|10.0.19041.867|
|3|Git| Systemy kontroli wersji aplikacji |2.31.1|
|4|GitHub| Utrzymywanie projektu na serwerze, do którego mają dostęp członkowie zespołu||


### 6. Testy

