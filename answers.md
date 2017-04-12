1) dinosaurs=# SELECT COUNT (*) FROM dinos;
2) SELECT name, period FROM dinos WHERE period ILIKE 'Jurassic';
3) SELECT SUM(length) FROM dinos WHERE period = 'Cretaceous';

4) SELECT name, species, period FROM dinos WHERE period = 'Jurassic' OR 'Cretaceous' ORDER by species asc;
