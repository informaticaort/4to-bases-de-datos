# Bases de Datos
Repositorio de la materia Bases de Datos, correspondiente al cuarto año de la orientación

## Modelado y Desarrollo de Bases de Datos SQL
Encontrarás material teórico y ejemplos de desarrollo de bases de datos SQL, tema que abordaremos en gran parte de la materia. 
Deberás tener instalado SQL Server y SQL Server Management Studio (SSMS). 

## Ciencia de Datos en Python / Jupyter Notebook
En la carpeta "DataScience Python" encontrarás todos los contenidos teóricos y prácticos que veremos en la materia, relacionados al Análisis y Exploración de Datos. 

Para programar y ejecutar los archivos con formato .ipynb, utilizaremos la herramienta [Google Colaboratory](https://colab.research.google.com). Tiene perfecta integración con Google Drive, y podrás alojar todos tus notebooks desarrollados sin problemas

## Algunos tips importantes

Para cargar archivos (por ejemplo, un archivo .csv alojado en algún repositorio de Github) desde Google Colaboratory, escribimos estas dos líneas:

`url = 'https://raw.githubusercontent.com/informaticaort/extra-datathon/master/datasets/titanic.csv'`

`df1 = pd.read_csv(url,error_bad_lines=False)`
