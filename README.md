# University Database – SQL Server

A complete relational database built in **Microsoft SQL Server** that models the structure of a university. The project includes the full schema with relationships between tables, sample data, and a set of example SQL queries.

<img width="900"  alt="obraz" src="https://github.com/user-attachments/assets/6ccd0980-03c7-4e8f-b07a-6eb6a98fd9c0" />

## Repository Contents

| File | Description |
| --- | --- |
| `SQL Server [Database].txt` | Database schema: database creation, tables, primary keys, foreign keys, relationships, data types and constraints |
| `SQL Server [DATA].txt` | Sample data: `INSERT INTO` statements populating the tables with realistic university records |
| `SQL Server [QUERIES].txt` | Example queries demonstrating how to work with the data |

## Database Structure

The database is designed as a relational model and contains the following tables:

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

### Key Relationships

- **Student → Group → Department**
- **Student → Grades → Lectures**
- **Professor → Lectures**
- **Department → Fields of Study**
- **Room → Equipment**
- **Candidate → Recruitment**

## Example Queries

The queries file demonstrates:

- `SELECT` with `JOIN`
- Aggregate functions (`COUNT`, `AVG`, `SUM`)
- Subqueries
- Filtering with `WHERE`
- Grouping with `GROUP BY`
- Sorting with `ORDER BY`

## Technologies

- Microsoft SQL Server (T-SQL)
- Relational data model
- Entity Relationship Diagram (ERD)

## Author

**Wojciech Lichtoń** – [@Kader64](https://github.com/Kader64)

An educational project created to practice database design and implementation in SQL Server.
