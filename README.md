# Proyecto final de TMIR.

## Objetivo General
El objetivo General de este proyecto es tomar la narración de un partido de soccer, extraer el script y hacer una estimación de las estadisticas del partido.

## Metodología o estrategia
1. **Limpieza de Datos:**
- Se eliminan los timestamps del contenido usando expresiones regulares.
2. **Preprocesamiento del Texto:**
- Sustitución de sinónimos.
- Tokenización y eliminación de stopwords y caracteres no alfabéticos.
- Gestión de palabras compuestas.
- Eliminación de duplicados consecutivos y palabras innecesarias.
- Se definen funciones para eliminar ocurrencias repetidas de ciertas palabras en el mismo comentario.
3. **Visualización de WordCloud:**
- Se crea unWordCloud usando los tokens procesados para visualizar las palabras más comunes en el corpus.
4. **Extracción de Estadísticas:**
- Se utilizan expresiones regulares para buscar patrones específicos y contar su ocurrencia.
5. **Comparación con Datos Reales:**
- Se crea un DataFrame con los datos reales y los datos estimados.
- Pro medio de un gráfico de barras se visualizan y comparan ambos conjuntos de datos.
