# Information for the database which can be included in the project

1. Film Title
2. Actors
3. Running time
4. Genre
5. Description
6. Year
7. Director

** DATABASE DESIGN

1. Films Table => filmid, filmtitle, running time, description

2. Year Table => year

3. Genre Table => genre

4. Director Table => director

5. Actors Table => actor_name

** ACTOR TABLE

1. id (primary key)
2. first name
3. last name
4. etc. (any additional columns you want to store on an actor)

** DIRECTOR TABLE

1. id
2. first name
3. last name

** GENRE TABLE

1. id
2. name

** Movie Table

1. id
2. title
3. description
4. running time
5. release date
6. Director ID -- this is a foreign key that refers to the id  of the director who directed the film
7. genre id -- like the director id, this refers to the id of the genre the film belongs to

** Actor-Movie Index Table

1. film id -- this is a foreign key that refers to the id of the film
2. Actor ID -- this is a foreign key that refers to the id of one actor in the film.

** SOUNDTRACKS

1. Composer name
2. Duration
3. Song/BGM name
