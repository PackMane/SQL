# SQL Project Descriptions & Functionality

Movies

Write SQL queries to answer questions about a database of movies.

Understanding

Provided to you is a file called movies.db, a SQLite database that stores data from
IMDb about movies, the people who directed and starred in them, and their ratings. In a
terminal window, run sqlite3 movies.db so that you can begin executing queries on
the database.
First, when sqlite3 prompts you to provide a query, type .schema and press enter.
This will output the CREATE TABLE statements that were used to generate each of the
tables in the database. By examining those statements, you can identify the columns
present in each table.
Notice that the movies table has an id column that uniquely identifies each movie, as
well as columns for the title of a movie and the year in which the movie was
released. The people table also has an id column, and also has columns for each
person’s name and birth year.
Movie ratings, meanwhile, are stored in the ratings table. The first column in the table
is movie_id: a foreign key that references the id of the movies table. The rest of the
row contains data about the rating for each movie and the number of votes the
movie has received on IMDb.
Finally, the stars and directors tables match people to the movies in which they
acted or directed. (Only principal stars and directors are included.) Each table has just
two columns: movie_id and person_id, which reference a specific movie and
person, respectively.

Houses

$ python import.py characters.csv
$ python roster.py Gryffindor
Lavender Brown, born 1979
Colin Creevey, born 1981
Seamus Finnigan, born 1979
Hermione Jean Granger, born 1979
Neville Longbottom, born 1980
Parvati Patil, born 1979
Harry James Potter, born 1980
Dean Thomas, born 1980
Romilda Vane, born 1981
Ginevra Molly Weasley, born 1981
Ronald Bilius Weasley, born 1980

Background

Hogwarts is in need of a student database. For years, the professors have been
maintaining a CSV file containing all of the students’ names and houses and years. But
that file didn’t make it particularly easy to get access to certain data, such as a roster of
all the Ravenclaw students, or an alphabetical listing of the students enrolled at the
school.
