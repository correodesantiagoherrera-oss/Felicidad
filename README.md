# ¿El dinero da la felicidad?

Análisis con Python y pandas de los factores que se relacionan con la felicidad de los países, según el World Happiness Report 2019.

## Preguntas

- ¿Qué países son los más y los menos felices, y en qué puesto queda España?
- ¿Los países más ricos son más felices?
- ¿Qué factor va más de la mano con la felicidad?

## Datos

- Fuente: [World Happiness Report 2019 (Kaggle)](https://www.kaggle.com/datasets/PromptCloudHQ/world-happiness-report-2019)
- 156 países y 11 columnas.
- Todos los valores son **posiciones en un ranking** (1 = mejor), no puntuaciones.

## Principales conclusiones

- **Arriba y abajo:** los países más felices son europeos y sobre todo nórdicos, con Finlandia en primer lugar. Los menos felices son países del África subsahariana o afectados por guerras, como Afganistán, Siria o Sudán del Sur.
- **España** está en el puesto 30 de felicidad, el mismo que en riqueza. Destaca en esperanza de vida sana (puesto 3 del mundo), pero sale mal en emociones positivas y negativas (puesto 107 en ambas).
- **Dinero y felicidad:** la correlación entre el ranking de PIB per cápita y el de felicidad es de 0,81. Es una relación fuerte, pero con excepciones, como Costa Rica (muy feliz con renta media) o Hong Kong (muy rico y no tan feliz).
- **Factores más relacionados:** apoyo social (0,82), esperanza de vida sana (0,82) y PIB per cápita (0,81), prácticamente empatados. La corrupción es el factor menos relacionado (0,19).

## Limitaciones

- Los datos son rankings, así que miden quién va delante, no cuánta diferencia hay entre países.
- Faltan algunos datos, y no al azar: 8 países, en su mayoría monarquías del Golfo y China, no tienen dato de corrupción.
- Correlación no implica causalidad.

## Herramientas

Python, pandas y matplotlib, en Jupyter Notebook.

## Cómo ejecutarlo

1. Instala las librerías: `pip install pandas matplotlib jupyter`
2. Abre `analisis_felicidad.ipynb` y ejecuta todas las celdas.
