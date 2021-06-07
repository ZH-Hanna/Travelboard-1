# Travelboard :earth_americas::v:
 

## Dokumentacja:
- [Charakterystyka  oprogramowania](#id-section1)
- [Prawa autorskie](#id-section2)
- [Specyfikacja wymagań](#id-section3)
- [Projekt (język UML)](#id-section4)
- [Architektura systemu/oprogramowania](#id-section5)
- [Scenariusze testów](#id-section6)


<div id='id-section1'/>

## 1. Charakterystyka  oprogramowania 
Nazwa skrócona: TravelBoard

Nazwa pełna: TravelBoard - asystent podróżnika

Krótki opis: Aplikacja mobilna służąca jako asystent podróży, która pomoże użytkownikowi w wyborze atrakcji w podróży, pokazująca prognozę pogody w określonym miejscu i pozwalająca po przejrzeniu informacji prowadzić osobisty dziennik wpisów.


<div id='id-section2'/>

## 2. Prawa autorskie 
Autorzy: Eliza Sinkevich, Hanna Zhuk, Irina Frolova

Licencja: MIT

<div id='id-section3'/>

## 3. Specyfikacja wymagań

#### Wymagania funkcjonalne
| Identyfikator | Kategoria | Podkategoria | Nazwa krótka | Opis | Priorytet |
|:-:|:-:|:-|:-|:-|:-:|
|1|funkcjonalne||||1|
|2|funkcjonalne||||1|
|3|funkcjonalne|Nawigacja|Wybór miasta|Możliwość ustawienia miasta|1|
|4|funkcjonalne|Nawigacja|Mapa z atrakcjami|Wyświetlenie mapę regionu wraz z orientacyjną lokalizacją atrakcji w postaci pinezek na mapie|1|
|5|funkcjonalne|Dostosowanie wyników|Informacja o atrakcji|Po kliknięciu na pinezkę system powinien wyświetlić podstawowe informacje o atrakcji: nazwę, opis, lokalizację|1|
|6|funkcjonalne|Dostosowanie wyników|Wyszukiwarka atrakcji|Przeglądania atrakcji z opisem w sposób przewijania|2|
|7|funkcjonalne|Projektowe|Pogoda|Wyświetlenie informacje meteorologiczne w zakładce "Pogoda"|3|
|8|funkcjonalne|Projektowe|Podłączenie bazy danych|Zapis danych z wykorzystaniem SQLite|2|

#### Wymagania niefunkcjonalne
| Identyfikator | Kategoria | Podkategoria | Nazwa krótka | Opis | Priorytet |
|:-:|:-:|:-|:-|:-|:-:|
|1|niefunkcjonalne|Statystyki|Zapis statystyk ulubionych atrakcji|Dokładny zapis statystyk ulubionych atrakcji użytkownika do systemu doboru podobnych|1|
|2|niefunkcjonalne|GUI|Nawigacja|Szybka nawigacja w aplikacji |1|
|3|niefunkcjonalne|GUI|Wygląd interfejsów|Intuicyjny i estetyczny interfejs|1|
|4|niefunkcjonalne|Bezpieczeństwo|Ocena cyberbezpieczeństwa|Ocena bezpieczeństwa skupia się na zredagowaniu protokołów bezpieczeństwa oraz list kontrolnych, wprowadzeniu standardów pisania kodu, wprowadzeniu zapór bezpieczeństwa i strategii długoterminowej.|3|
|5|niefunkcjonalne|Bezpieczeństwo|Testy penetracyjne|Ocena bieżącego stanu bezpieczeństwa w sposób przeprowadzeniu kontrolowanego ataku|3|
|6|niefunkcjonalne|Elastyczność integracji|Integracja z serwisami społecznościowymi|Elastyczność pod względem możliwości integracji z innymi popularnymi serwisami społecznościowymi |3|
|7|niefunkcjonalne|Dostępność|--| Dostęp dla użytkowników do użytku w dowolnym momencie |1|
|8|niefunkcjonalne|Prywatność|--|Zachowanie prywatności użytkowników|2|



<div id='id-section4'/>

## 4. Projekt (język UML)

### ⠀Diagram przypadków użycia 

![alt text](img/Diagram.png)

### ⠀Diagram wdrożenia

![alt text](img/dw.png)



<div id='id-section5'/>

## 5. Architektura systemu/oprogramowania

### Architektura rozwoju 
| Lp | Nazwa produktu | Przeznaczenie w projekcie | Wersja  | 
|:-:|:-|:-|:-:|
|1|Java|Backend aplikacji|8|
|2|Xml|Struktura widoków aplikacji|--|
|3|SQLite|Zarządzanie relacyjną bazą danych z atrakcjiami | 3.35.3 |


### Architektura uruchomieniowa 
| Lp | Nazwa produktu | Przeznaczenie w projekcie | Wersja  | 
|:-:|:-|:-|:-:|
|1|Android Studio|Środowisko IDE używane przy tworzeniu projektu|4.1.2|
|2|Windows 10 |System operacyjny używany przy tworzeniu projektu|10.0.19041.867|
|3|Git| Systemy kontroli wersji aplikacji |2.31.1|
|4|GitHub| Utrzymywanie projektu na serwerze, do którego mają dostęp członkowie zespołu|--|

![alt text](img/1.png) ![alt text](img/2.png) ![alt text](img/3.png) ![alt text](img/4.png) ![alt text](img/5.png) ![alt text](img/6.png) ![alt text](img/7.png) ![alt text](img/8.png) ![alt text](img/9.png) ![alt text](img/10.png) ![alt text](img/11.png) ![alt text](img/12.png) ![alt text](img/13.png) ![alt text](img/14.png) ![alt text](img/15.png) ![alt text](img/16.png)


<div id='id-section6'/>

## 6. Scenariusze testów
| Identyfikator | Priorytet |Kroki do wykonania | Oczekiwany rezultat |  
|:-:|:-:|:-|:-|
|R1|1|Kliknąć przycisk 'Wyszukaj' w menu głównym i wpisać wybrane miasto|Wyświetlenie modułu z atrakcjami wybranego miasta|
|R2|1|Kliknąć przycisk 'Mapa' w menu głównym|Wyświetlenie modułu z mapami (mapa z atrakcjami)|
|R3|1|||
|R4|2|||
|R5|3|||
|R6|3|Kliknąć przycisk 'Pogoda' w ...|Wyświetlenie się modułu z pogodą|
|R7|2|||

