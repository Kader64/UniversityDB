# University Database – SQL Server

Projekt przedstawia kompletną relacyjną bazę danych stworzoną w **Microsoft SQL Server**, odwzorowującą strukturę uczelni wyższej.
Zawiera on pełną strukturę relacji między tabelami oraz przykładowe zapytania SQL.

---

## Zawartość repozytorium

W repozytorium znajdują się 3 główne pliki:

### `SQL Server [Database].txt`
Plik odpowiedzialny za:
- tworzenie bazy danych
- definicję tabel
- klucze główne (PRIMARY KEY)
- klucze obce (FOREIGN KEY)
- relacje między tabelami
- typy danych
- ograniczenia (constraints)

---

### `SQL Server [DATA].txt`
Plik zawierający:
- instrukcje `INSERT INTO`
- przykładowe dane testowe
- wypełnienie tabel rekordami
- realistyczne dane uczelni

---

### `SQL Server [QUERIES].txt`
Plik z przykładowymi zapytaniami SQL, m.in.:

- SELECT z JOIN
- Zapytania agregujące (COUNT, AVG, SUM)
- Podzapytania
- Filtrowanie danych (WHERE)
- Grupowanie (GROUP BY)
- Sortowanie (ORDER BY)

---

## Struktura bazy danych

Baza danych została zaprojektowana w sposób relacyjny i zawiera m.in. następujące tabele:

- `Students`
- `Professors`
- `Departments`
- `FieldsOfStudy`
- `Lecture`
- `Grades`
- `Scholarships`
- `Employees`
- `Library`
- `Rooms`
- `Recruitment`
- `Candidates`
- `Achievements`
- `Academy`
- `Deanery`

Relacje obejmują m.in.:

- Student → Grupa → Wydział  
- Student → Oceny → Wykłady  
- Profesor → Wykłady  
- Wydział → Kierunki  
- Sala → Wyposażenie  
- Kandydat → Rekrutacja  

---

## Schemat bazy danych

<div align="center">
<img width="900"  alt="obraz" src="https://github.com/user-attachments/assets/6ccd0980-03c7-4e8f-b07a-6eb6a98fd9c0" />
</div>


## Technologie

- Microsoft SQL Server
- Relacyjny model danych
- Diagram bazy danych (ERD)


## Autor

Projekt edukacyjny wykonany w celu nauki projektowania i implementacji baz danych w SQL Server.

---
