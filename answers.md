1) dinosaurs=# SELECT COUNT (*) FROM dinos;
2) SELECT name, period FROM dinos WHERE period ILIKE 'Jurassic';
3) SELECT SUM(length) FROM dinos WHERE period = 'Cretaceous';

4) SELECT name, species, period FROM dinos WHERE period = 'Jurassic' OR period = 'Cretaceous' ORDER by species asc;

5) SELECT name, species, period, diet, t_order FROM dinos WHERE t_order = 'Saurischia' AND diet = 'Herbivorous';

6)

7) SELECT name, species, period, diet, FROM dinos WHERE t_order = 'Saurischia' AND diet = 'Herbivorous';
