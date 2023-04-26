# Análisis de datos COVID-19

Este repositorio contiene un análisis de datos del COVID-19 en México. Se utilizan datos abiertos proporcionados por https://www.gob.mx/salud/documentos/datos-abiertos-152127. El análisis se realiza con la ayuda de Python y sus librerías Numpy, Pandas y Matplotlib.

En el archivo analisis_covid.ipynb se encuentra el código completo del análisis de datos. Se muestran diferentes gráficas relacionadas con el número de ingresos, defunciones y letalidad a nivel nacional y en el municipio de Hermosillo, Sonora.

Una ves que ejecute el proyecto se descargará el archivo .csv correspondiente para llevar a cabo el análisis de los datos

Se recomienda la creación de un ambiente virtual con Anaconda y la instalación de las librerías necesarias para poder ejecutar el código sin problemas.

## Cambio de parámetros

### En la linea

**df = pd.read_csv('datos_abiertos_covid19.zip', nrows=2000000, compression='zip', header=0, sep=',', quotechar='"')**

"Si no tienes suficiente capacidad en tu equipo para analizar todos los datos del archivo .csv, puedo ajustar el valor de "nrows" a una muestra más pequeña que te permita realizar el análisis. Solo házmelo saber el número de filas que deseas que se incluyan. Por otro lado, si deseas analizar el conjunto completo de datos, puedo retirar el parámetro "nrows". Sin embargo, es importante tener en cuenta que esto podría requerir más capacidad de procesamiento y memoria por parte de tu equipo, por lo que asegúrate de que esté preparado para manejar el conjunto completo de datos."

¡Esperamos que este análisis sea de utilidad para todos aquellos interesados en conocer más sobre la situación del COVID-19 en México!
