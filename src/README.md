
# Scraping Web de Productos.

Este proyecto realiza scraping de datos de productos de un sitio web, limpia y analiza los datos, y los guarda en archivos CSV.

## Requisitos:

- Python 3.7+
- pandas
- beautifulsoup4
- requests
- matplotlib
- time
- logging

## Instalación.

Para instalar las dependencias creamos un archivo "txt" el cual guardamos todas las dependecias para una rapida instalación.
Su metodo de uso es utilizando PIP y es con el siguiente comando:

````bash
pip install -r .\dep.txt
````

## Estructura de las carpetas.

````bash
PROYECTO-PYTHON
|-- data/
|    |- processed/
|    |   |__ cleaned_products.csv    
|    |
|    |- raw/
|        |__ products.csv
|
|-- notebooks/
|    |__ exploration.ipynb
|
|-- src/
|    |- analysis/
|        |__ __init__.py
|        |__ analysis.py
|    |- decorators/
|        |__ __init__.py
|        |__ decorators.py
|    |- scraping/
|        |__ __init__.py
|        |__ scraper.py
| 
|__ dep.txt
|__ README.md
|__ requerimientos.txt    
````

## Ejecución del Scraper.

Para ejecutar el scraper lo que hay que realizar es:

````bash
python .\src\scraping\scraper.py
````

Esto nos va a generar un CSV en la carpeta "RAW" dentro de la carpeta "DATA" llamado "products.csv"

## Ejecución para el análisis de datos.

Para ejecutar el script para análisis de datos lo que hay que realizar es:

````bash
python .\src\analysis\analysis.py
````

Esto nos va a generar un CSV en la carpeta "PROCESSED" dentro de la carpeta "DATA" llamado "cleaned_products.csv"


#### Proyecto Final Python -- Cristina Estefanía Alvarado Pérez
#### Correo: calvaradop2012@gmail.com

