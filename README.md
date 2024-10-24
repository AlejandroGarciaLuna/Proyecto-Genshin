Este proyecto se centra en la carga y análisis de un conjunto de datos de personajes del juego Genshin Impact, utilizando Python y varias bibliotecas como pandas, numpy y matplotlib. El objetivo principal es obtener estadísticas clave de los personajes en niveles avanzados y visualizarlas mediante gráficos.

**Estructura del Proyecto**
El proyecto se divide en las siguientes fases:

*Carga y limpieza de datos:*

Los datos se cargan desde un archivo CSV (genshin_cleaned_final.csv).
Se realiza la conversión de formatos de fechas y números, y se crean columnas adicionales para facilitar el análisis.

*Análisis de Estadísticas:*

Se calculan las medias de atributos clave como la vida (hp_90_90), el ataque (atk_90_90) y la defensa (def_90_90).
Se agrupan los personajes según diferentes categorías para realizar análisis comparativos.

*Visualización de Datos:*

Se generan gráficos para visualizar los datos, como gráficos de barras, gráficos de dispersión y gráficos de torta.

**Requisitos del Sistema**
Para ejecutar este proyecto, necesitas tener instaladas las siguientes dependencias:

Python 3.x (versión recomendada: 3.7 o superior)
**pandas**: Para la manipulación de datos.
**numpy**: Para operaciones numéricas.
**matplotlib**: Para la visualización de gráficos.

Puedes instalar las dependencias utilizando el siguiente comando:

bash
Copiar código
pip install pandas numpy matplotlib

**Instrucciones de Uso**
-Clona el repositorio o descarga los archivos directamente.
-Asegúrate de que el archivo CSV (genshin_cleaned_final.csv) esté en la misma carpeta que el código fuente.
-Ejecuta los scripts con Python para generar los análisis y gráficos.
