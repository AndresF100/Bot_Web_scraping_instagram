# Bot para minado de información con fines de benchmark

## Descripción

Este proyecto consiste en un bot desarrollado en Python para el minado de información en Instagram con fines de benchmark. 
El bot utiliza la biblioteca Selenium para la automatización del navegador y la recopilación de datos. 
Posteriormente, los datos recolectados son visualizados y analizados en Power BI. Este proyecto es únicamente para uso educacional y de investigación.

## Advertencia

**Este bot está diseñado exclusivamente para fines educacionales y de investigación. 
No debe ser utilizado para ningún propósito comercial ni para actividades que violen los términos de servicio de Instagram. 
El uso indebido de esta herramienta puede resultar en la suspensión de cuentas y en acciones legales.**

## Requisitos

### Software

- Python 3.8 o superior
- Web driver (preferiblemente Google Chrome)
- Power BI Desktop

### Bibliotecas de Python

- `selenium`
- `pandas`
- `openpyxl`

## Instalación

1. **Clonar el repositorio**
    ```bash
    git clone https://github.com/usuario/instagram-scraper-benchmark.git
    cd instagram-scraper-benchmark
    ```

2. **Instalar las dependencias**
    ```bash
    pip install selenium pandas openpyxl
    ```

3. **Descargar el WebDriver de Chrome**
    - Descargar la versión correspondiente de [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads).
    - Colocar el archivo `chromedriver` en el directorio del proyecto o en una ubicación accesible desde el sistema.

## Uso

### Configuración del Bot

1. **Configuración del archivo `Config_scraper.py`**
    Crear un archivo `Config_scraper.py` en el directorio del proyecto con el siguiente contenido:
    ```python
    # config.py
    user =  # insert an email registered on instragram
    password = # insert a password
    ```

2. **Ejecución del Bot**
    Ejecutar el script principal para iniciar el bot de minado de información BOT_v1.ipynb.
    

### Visualización de los Datos

1. **Exportación de los Datos**
    - Los datos recolectados se exportarán en formato csv (archivos `comments.csv` y `general.csv`) en el directorio del proyecto.

2. **Importación en Power BI**
    - Abrir Power BI Desktop.
    - Actualizar la fuente de datos.
      

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cualquier cambio que desees realizar.


---
