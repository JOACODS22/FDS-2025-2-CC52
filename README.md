# FDS-2025-2-CC52
Objetivo del Proyecto: Conocer las características clave de los clientes que compran una bicicleta e implementar un modelo de Scoring de Venta que identifique a los clientes más propensos a realizar una compra.
Nombre de los alumnos participantes: Joaquin Miguel Del Solar Gamarra
[Breve descripción del conjunto de datos](DescripcionConjuntoDatos.pdf)
Conclusiones: Las conclusiones preliminares derivadas del análisis exploratorio refuerzan la necesidad de construir un modelo de scoring. Se observa que los clientes con mayores ingresos, alrededor de 68779 dólares frente a 55270 dólares, presentan una mayor propensión a la compra, por lo que esta variable será relevante en el modelo predictivo. También se identifica que los clientes que trabajan en áreas de Management y Professional suelen poseer más coches. Dado que el producto evaluado es una bicicleta, será necesario analizar si esto implica una menor intención de compra por disponer de más alternativas de transporte o una mayor probabilidad asociada a un mayor poder adquisitivo.
En cuanto a la edad y la propiedad de vivienda, se observa que los propietarios tienden a ser ligeramente mayores, lo cual podría relacionarse con una mayor estabilidad financiera.
Respecto a la metodología CRISP-DM, se resalta la importancia del proceso iterativo. Si los hallazgos no son concluyentes o si el modelo de regresión logística no alcanza un nivel de desempeño adecuado, será necesario retornar a la fase de preparación de datos para mejorar el feature engineering, por ejemplo agrupando categorías de variables como distancia de traslado o nivel educativo, o volver a la fase de modelado para evaluar métodos alternativos como Random Forest o Gradient Boosting, que pueden capturar mejor interacciones no lineales entre las variables.
MIT License
Copyright (c) 2025 [Joaquin Del Solar]
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND...
