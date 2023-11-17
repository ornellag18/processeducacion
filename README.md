## Paso 1: redirigirte a la carpeta del proyecto

## paso 2: cree el ambiente virtual
python -menv mienv

# Paso 3: Activar el entorno virtual
myenv\Scripts\activate

## paso 4: instalar las librerias del archivo requirements txt
pip install -r requirements.txt

## paso 5: luego de descargar el csv mas reciente de la siguiente url 
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## paso 6: ejecutar la app
python get_excel_resumen_es.py