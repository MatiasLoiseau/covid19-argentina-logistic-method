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

El dataset lo cree en base a los datos diarios oficiales (fuente: https://www.argentina.gob.ar/coronavirus/informe-diario)

El código fue basado en el de Gianluca Malato: https://towardsdatascience.com/covid-19-infection-in-italy-mathematical-models-and-predictions-7784b4d7dd8d
