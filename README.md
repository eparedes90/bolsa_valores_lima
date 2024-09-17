# Algoritmo de descarga de datos de la Bolsa de Valores de Lima
¿Necesitas datos de Balance General, Estado de Resultados y Flujo de Efectivo de las empresas que cotizan en la Bolsa de Valores de Lima? ¿Necesitas la evolución de sus indicadores financieros críticos?
En este repositorio encontrarás un algoritmo de websrapping que utiliza la página web www.smv.gob.pe para descargar estos datos de la empresa de tu preferencia. Además, podrás elaborar automáticamente indicadores financieras importantes con sus respectivos gráficos

## Índice
- webscrapping.ipynb: Jupyter Notebook con el algoritmo de descarga. Solo debes incluir el nombre de la empresa en la función respectiva
- analysis.ipynb: Jupyter Notebook con la codificación para limpiar los datos descargados, elaborar los indicadores financieros y graficar
- graphs: Carpeta que contiene todos los gráficos generados de los indicadores financieros
- venv: Environment utilizado
- balance.csv: Archivo csv producto de efectuar el algoritmo de descarga. Los datos son correspondientes al Balance General
- flujo.csv: Archivo csv producto de efectuar el algoritmo de descarga. Los datos son correspondientes al Flujo de Efectivo
- resultados.csv: Archivo csv producto de efectuar el algoritmo de descarga. Los datos son correspondientes al Estado de Resultados
