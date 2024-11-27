# TAREA FINAL-PARTE 2

Resolución de los ejercicios con GeoDataFrame: https://colab.research.google.com/drive/1dpnCEQJ2KYbmDDyYrIUggnoykgLQmIjt#scrollTo=z320Yt7VZAFI

PREGUNTA 5

Se subió la data de indicadores de Perú y el mapa de Distritos del Perú. Hacemos un Merge con las columnas distrito y DISTRITO, convertimos todo a mayúscula y eliminamos los espacios en blanco antes o después del texto. Procedemos a hacer la limpieza, eliminando tildes, convirtiendo caracteres, combinando provincias y distritos para evitar los nombres repetidos. Buscamos la coincidencia entre datos y el porcentaje de similitud. Sustituimos y aplicamos los cambios, para luego tener una columna con provincia y distrito junto. Finalmente eliminamos las columnas innecesarias o las que no usaremos.

PREGUNTA 6

Creamos un histograma para visualizar la distribución de IDH2019. Usamos fisherjenks para dividir los datos en clases, departamento provincia y distrito. Con Rook se usa para ver los vecinos que comparten un borde. Con Queen se usa para ver los vecinos que comparten un borde o un vértice. Escogemos la provincia de índice 1831, vemos cuántos polígonos vecinos tiene y cuáles son. Finalmente se grafica los polígonos de la provincia de Lima con el polígono de índice 1831 con sus vecinos para los 3 casos, usando rook, usando queen y usando KNN.

