Ejercicios
==========

## 1. modificar movies.dat a `csv`

**input**: movies.dat

`1,Toy Story,1995,[Animation|Children's|Comedy]`

**output**: movies.csv

`1,Toy Story,1995,[Animation|Children's|Comedy]`

**solucion**: 
    / (\d)::(.*)\s\((\d+)\)::([^`]*) /
    $1,$2,$3,[$4]