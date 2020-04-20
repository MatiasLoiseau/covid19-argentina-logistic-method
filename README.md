# covid20-argentina-logistic-method

### Se usó un modelo logístico para predecir el día final que va a frenar de crecer el número de infectados según los reportes oficiales de Argentina

### ACLARACIÓN: este modelo no tiene en cuenta los fallecidos, ni los recuperados.

Voy a crear una tabla para ver cómo varía el resultado según los datos del día.

| Día de testeo | Cese del crecimiento de infectados| Total de infectados hasta esa fecha |
| ------------- | ------------- | ------------- |
| 23 de Marzo  | 25 de abril | 1237 (± 662)|
| 24 de Marzo  | 2 de mayo | 1892 (± 1054)|
| 25 de Marzo | 18 de junio | 7362372 (± 13060409469)|
| 26 de Marzo | 9 de mayo | 3921 (± 2261) |
| 27 de Marzo | 2 de mayo | 2280 (± 481) |
| 28 de Marzo | 28 de abril | 1412 (± 145) |
| 29 de Marzo | 21 de abril | 1250 (± 78) |
| 30 de Marzo | 26 de abril | 1431 (± 89) |
| 31 de Marzo | 25 de abril | 1512 (± 76) |
| 1 de Abril | 26 de abril | 1535 (± 58) |
| 2 de Abril | 28 de abril | 1666 (± 62) |
| 3 de Abril | 2 de mayo | 1745 (± 56) |
| 4 de Abril | 7 de mayo | 1822 (± 52) |
| 5 de Abril | 3 de mayo | 1907 (± 51) |
| 6 de Abril | 3 de mayo | 1957 (± 45) |
| 7 de Abril | 9 de mayo | 2010 (± 41) |
| 8 de Abril | 7 de mayo | 2061 (± 38) |
| 9 de Abril | 9 de mayo | 2129 (± 39) |
| 10 de Abril | 8 de mayo | 2193 (± 39) |
| 11 de Abril | 17 de mayo | 2323 (± 54) |
| 12 de Abril | 16 de mayo | 2500 (± 58) |
| 13 de Abril | 17 de mayo | 2632 (± 69) |
| 14 de Abril | 17 de mayo | 2632 (± 69) |
| 15 de Abril | 21 de mayo | 2780 (± 81) |
| 16 de Abril | 23 de mayo | 2917 (± 89) |
| 17 de Abril | 26 de mayo | 3037 (± 93) |
| 18 de Abril | 30 de mayo | 3138 (± 93) |
| 19 de Abril | 30 de mayo | 3238 (± 93) |

El dataset lo cree en base a los datos diarios oficiales (fuente: https://www.argentina.gob.ar/coronavirus/informe-diario)

El código fue basado en el de Gianluca Malato: https://towardsdatascience.com/covid-19-infection-in-italy-mathematical-models-and-predictions-7784b4d7dd8d
