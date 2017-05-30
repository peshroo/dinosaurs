DINOSAUR DB ANSWERS

1. SELECT COUNT(name) FROM dinos;

2. SELECT name FROM dinos WHERE period='Jurassic';

3. SELECT SUM(length) FROM dinos WHERE period='Jurassic';

4. SELECT SUM(length) FROM dinos WHERE period='Cretaceous';

5. SELECT name FROM dinos WHERE t_order='Saurischia' AND diet='Herbivorous';

6. UPDATE dinos SET name='Shortie' WHERE length in (SELECT MIN(length) FROM dinos);

7. SELECT name FROM dinos ORDER by name ASC LIMIT 1;

8. UPDATE dinos SET name='The Famous Five' WHERE length in(SELECT length FROM dinos WHERE length > 0 ORDER BY length DESC LIMIT 5);
