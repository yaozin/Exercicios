# Exercicios
#Diferença entre número totla de cidades e número de cidades únicas 
SELECT COUNT(CITY) - COUNT(DISTINCT CITY) AS difference
FROM STATION;
