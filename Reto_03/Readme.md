# Reto 3.

1. Descargue los archivos csv que corresponden a las temporadas 2017/2018, 2018/2019, 2019/2020 y 2020/2021 de la Bundesliga 1 y que se encuentran en el siguiente enlace https://www.football-data.co.uk/germanym.php
2. Importe los archivos descargados a `R`
3. Usando la función `select` del paquete `dplyr`, seleccione únicamente las columnas `Date`, `HomeTeam`, `AwayTeam`, `FTHG`, `FTAG` y `FTR`
4. Combine cada uno de los data frames en un único data frame con ayuda de las funciones `rbind` y `do.call`
