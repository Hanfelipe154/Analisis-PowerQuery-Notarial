# Pipeline de Datos ETL: Automatización de Reportes Notariales (REL SNR)

## 📖 Descripción del Proyecto
Este proyecto optimiza la gestión de datos de radicaciones REL mediante un flujo de **ETL (Extracción, Transformación y Carga)** desarrollado en **Power Query**. El sistema unifica múltiples reportes de oficinas de registro (ORIPS) en un único modelo de datos estandarizado, eliminando el procesamiento manual y garantizando la integridad de la información.

## 🛠️ Desafíos Técnicos y Soluciones
* **Parametrización de Rutas:** Implementé una variable dinámica (`RutaFinal`) que permite la portabilidad del proyecto entre diferentes equipos sin necesidad de modificar cada consulta manualmente.
* **Normalización de Fechas:** Resolución de conflictos de configuración regional y formatos heterogéneos (ej. formatos tipo `DD-MMM-YYYY`) mediante el uso de **M Language** y ajustes de Localización (Locale).
* **Calidad de Datos (Data Cleaning):** Limpieza automática de duplicados, normalización de nombres de actos jurídicos y filtrado por oficinas registrales (ej. Ibagué).

## ⚙️ Tecnologías Utilizadas
* **Power Query (Excel):** Motor principal de transformación de datos.
* **M Language:** Scripts personalizados para la limpieza profunda de celdas.
* **Excel Avanzado:** Tablas dinámicas y segmentación para el reporte final.

## 🚀 Cómo utilizar este repositorio
1. Descarga los archivos `.xlsx` de la carpeta principal.
2. Abre el archivo maestro `REGISTRADAS.xlsm`.
3. Ajusta la variable `RutaFinal` en Power Query para que apunte a tu carpeta local.
4. Haz clic en "Actualizar todo" para ver la magia de la automatización.

## 📸 Visualización del Proceso
<img width="1364" height="701" alt="image" src="https://github.com/user-attachments/assets/7a19e199-6285-4fcf-aff5-7af7b55248d3" />
<img width="1365" height="718" alt="image" src="https://github.com/user-attachments/assets/846b7a77-0862-4e35-9724-e3be55d80dd5" />

