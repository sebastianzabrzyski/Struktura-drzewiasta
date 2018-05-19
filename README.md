Aplikacja webowa do zarządzania strukturą drzewiastą, umożliwiająca:

- Dodawanie nowych węzłów do drzewa
- Rekursywne usuwanie węzłów z drzewa
- Przenoszenie węzłów do innych gałęzi
- Edycję nazwy węzłów
- Wyszukiwanie węzłów po nazwie
- Rozwijanie drzewa i wybranych gałęzi


# Demo

[Przejdź do strony z aplikacją](http://80.211.246.214/tree)

# Wykorzystane technologie i biblioteki:

- PHP 7
- MySQL 5.7
- JavaScript
- HTML 5
- CSS
- [jsTree](https://www.jstree.com/)

# Konfiguracja bazy danych:

Aplikacja pobiera dane z działającej lokalnie bazy MySQL zawierającej tabelę o naastępującej strukturze:

<img src="images/table.jpg">

Dane dostępowe można edytować w pliku [functions.php](functions.php).

<img src="images/functions.jpg">

Przykładową bazę danych można pobrać [tutaj](countries.sql).
