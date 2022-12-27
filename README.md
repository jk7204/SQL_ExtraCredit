# SQL_ExtraCredit

## Part 1
Identify at least four tables about at least two types of entities available on the internet and download them either manually or programmatically. The tables need to be from at least two distinct sources. For instance, the two entities could be countries and cities in them, or people of a certain type (e.g., business executives) and companies. Each of the four tables should have an entity in common with at least one of the other tables so that they can be linked together using a foreign key.

All foreign keys should be constrained so that it appears in, and is matched to, a primary key in another table.
You should hand in an SQLite database containing your tables. You should also hand in the SQL create table statements needed to create all the tables in your database, including the foreign key definitions. Each table should have a primary key.

4 tables (2 from API and 2 from Kaggle)
API:
- https://countriesnow.space/api/v0.1/countries/positions
- https://countriesnow.space/api/v0.1/countries/currency

Kaggle:
- https://www.kaggle.com/datasets/dumbgeek/countries-dataset-2020 (Includes 7 different dataset)

## Part 2

For each entity type that serves as a primary or foreign key, write SPARQL queries to extract all the Wikidata identifiers for the values of the key found in your data. For instance, if one of your columns contains U.S. States, the Wikidata identifier for New Jersey is Q1408 and the identifier for California is Q99.

After you find the identifiers, add them to the database tables from part 1 as a new column. Then add at least one table involving the same identifiers that is itself extracted from Wikidata using SPARQL.
