# Telecom X - Análisis de Evasión de Clientes

Una empresa enfrenta una alta tasa de cancelaciones y necesita comprender los factores que llevan a la pérdida de clientes.

El desafío será recopilar, procesar y analizar los datos, utilizando Python y sus principales bibliotecas para extraer información valiosa. A partir del análisis, el equipo de Data Science podrá avanzar en modelos predictivos y desarrollar estrategias para reducir la evasión.

## ¿Qué haré?

✅ Importar y manipular datos desde una API de manera eficiente.

✅ Aplicar los conceptos de ETL (Extracción, Transformación y Carga) en la preparación de los datos.

✅ Crear visualizaciones estratégicas para identificar patrones y tendencias.

✅ Realizar un Análisis Exploratorio de Datos (EDA) y generar un informe con insights relevantes.

## Herramientas a utilizar
- Pandas
- Matplotlib
- Numpy

## Estructura del proyecto
Teniendo en mi poder la base de datos en formato CSV he decidido organizar mi proyecto de la siguiente forma:
1. Introducción: explicación del problema, objetivo del análisis
2. Limpieza y tratamiento de datos: importación, limpieza y procesamiento de la base de datos
3. Análisis exploratorio de los datos: una vez comprendido el problema y obtenidos los datos se muestran los análisis, que incluyen gráficos que me permitieron identificar patrones
4. Conclusiones: presento y desarrollo los hallazgos, se describe cómo afectan el comportamiento de los clientes
5. Recomendaciones: a partir de los hallazgos se desarrollan algunas sugerencias estratégicas

## Ejemplos de gráficos e insights obtenidos
1. Distribución de la evasión de clientes. 
Se muestra cómo se distribuyen los clientes evasores y no evasores. Podemos ver un total de 7.043 clientes, de los cuales 1.861 son `churn` o evasores.
![Gráfico de distribución de clientes](https://drive.google.com/uc?id=1Vgn496HYpckEW1RSdBi-TeZ0PDSilb4k)
2. Correlación Meses de contrato, Gasto Mensual y Evasión. Se puede observar el cargo mensual pagado según los meses contratados, en amarillo destacan los clientes Churn. Se hace visible que los clientes evasores se acumulan mayoritariamente en las porciones de bajos meses contratados.
![Gráfico de dispersión](https://drive.google.com/uc?id=1htSADXw2Wq5UYHe4k4odwUM3EDfxQEGP)

## Instrucciones para ejecutar el notebook
El notebook fue creado en Google Colab, por lo que puedes ejecutarlo ahí o si prefieres también en un entorno local.

### Entorno local
1. Clonar repositorio
2. Crear y activar un entorno virtual (recomendado). Si lo ejecutas en VSCode, te dará opciones para hacerlo.
```bash
python -m venv venv
# En Windows:
.\venv\Scripts\activate
# En macOS/Linux:
source venv/bin/activate
```
3. Instalar dependencias
4. Puedes usar Jupyter Notebook o ejecutarlo en tu IDE

Si es que elegiste Jupyter Notebook:
  1. Asegúrate de tener instalado Jupyter Notebook
```bash
pip install jupyter
```
  2.   Iniciar Jupyter Notebook
```bash
jupyter notebook
```
  3. Abrir y ejecutar el notebook
     - en la interfaz Jupyter navega hasta el archivo
     - click en el archivo para abrirlo

### Google Colab
1. Hacer click en el archivo Challenge_TelecomX.ipynb
2. Click en botón Open in Collab
3. Ejecuta el notebook:
    - El menú te permitirá ejecutar todas las celdas. Navega por el menú: `Runtime` > `Run all`
