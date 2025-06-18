En primera instancia, necesitamos entender cómo funciona el reconocimineto facial. Enliastando una serie de pasos:
1. Obtener la imágen
2. Detectar # rostros
3. Calcular los embeddings (encrustaciones) de cada uno de los rostros
   P.E  1000005345435325463434
4. Retornar en PostgreSQL en un vector columna
5. De una foto externa, detectar el rostro
6. Calcular el embedding de nuestro rostro externo
7. Usar vectores de similaridad para encontrar otras fotos.
