# Drakon
Examples of python code 

## Drakon file it is a tables of SQLite DB.

Look to SQLite Drakon db:

```sh
sqlite3 first6.drn
```

List of table

```sh
.tables
```

Show table item:

```sh
select * from items;
```

Examples of different select:

```sh
select text,x,y from items;

select a,b,color from items;
```

Show any SQL code for Drakon db (INCLUDE, CREATE):

```sh
.dump
```

CREATE TABLE - создать таблицу

INSERT INTO - вставить строчки в таблицу

Exit from SQLite DB:

```sh
.exit
```
