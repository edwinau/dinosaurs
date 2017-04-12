1) dinosaurs=# SELECT COUNT (*) FROM dinos;
2) SELECT name, period FROM dinos WHERE period ILIKE 'Jurassic';
3) SELECT SUM(length) FROM dinos WHERE period = 'Cretaceous';

4) SELECT name, species, period FROM dinos WHERE period = 'Jurassic' OR period = 'Cretaceous' ORDER by species asc;

5) SELECT name, species, period, diet, t_order FROM dinos WHERE t_order = 'Saurischia' AND diet = 'Herbivorous';

6) SELECT name, id, length FROM dinos ORDER BY length LIMIT 1;
UPDATE dinos SET name='shortie' WHERE ID=160;   

7) SELECT name, species FROM dinos ORDER BY name asc LIMIT 1;

8) SELECT name, id, length FROM dinos ORDER BY length asc LIMIT 5;
- UPDATE dinos SET name='THE FAMOUS FIVE' WHERE ID=160 OR ID=250 OR ID=59 OR ID=139 OR ID=301;
