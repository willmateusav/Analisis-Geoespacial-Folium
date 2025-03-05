# 📍 Análisis Geoespacial con Folium

Este repositorio contiene códigos en Python que utilizan **Folium** para el análisis geoespacial puntual, generando mapas interactivos con visualizaciones específicas.

## 📂 Contenido del Archivo

El archivo compartido es un **Jupyter Notebook (.ipynb)** estructurado de la siguiente manera:

1. **Librerías Utilizadas**  
   Se importan las librerías necesarias para la manipulación de datos, visualización geoespacial y procesamiento de archivos.

2. **Configuraciones Generales**  
   Se establecen los parámetros iniciales y configuraciones esenciales para la ejecución del análisis.

3. **Lectura del Archivo .parquet**  
   Se carga el archivo de datos en formato **.parquet**, optimizado para el manejo de grandes volúmenes de información.

4. **Visualización del Punto Central** *(Opcional)*  
   Se muestra el punto que se considerará como centro de la circunferencia en el mapa interactivo.

5. **Ingreso de Parámetros**  
   Se definen los valores para:
   - **Latitud** 📍
   - **Longitud** 🌍
   - **Radio de la Circunferencia** 🎯 (en metros)

6. **Identificación de Puntos Dentro de la Circunferencia**  
   Se filtran los datos para detectar los puntos que se encuentran dentro del área determinada y se visualizan en un **heatmap**.

7. **Visualización del Resultado**  
   Se genera el mapa con los puntos destacados, permitiendo una exploración interactiva.

8. **Análisis de los Datos Obtenidos**  
   Se realiza un estudio sobre la distribución y características de los datos dentro del área seleccionada.

---

## 🚀 Tecnologías Utilizadas

- **Python 🐍**
- **Folium 🗺️**
- **Pandas 📊**
- **Geopandas 🌍**
- **Parquet 📂**

📌 *Este proyecto es ideal para aplicaciones en geolocalización, estudios urbanos y análisis de proximidad.*

---

✨ **Contribuciones y mejoras son bienvenidas. ¡Explora, usa y colabora!**
