<h1 align="center"> Proyecto Análisis del Mercado de Criptomonedas </h1>

### Desarrollado por: Alejandra Salas
🎯Objetivo: Analizar el mercado de criptomonedas mediante la extracción de datos de la API Coingecko.

## Índice

* [Descripción del proyecto](#descripción-del-proyecto)

* [Repositorio](#repositorio)

* [Criptomonedas seleccionadas](#criptomonedas-seleccionadas)

* [Reporte de análisis](#reporte-de-análisis)

* [Key Performance Indicator](#key-performance-indicator)
  


</h1>

## Descripción del proyecto

Estudio detallado de 15 criptomonedas en el mercado de activos actual en dólares, para entender el comportamiento del mercado y crear recomendaciones en base a los estudios obtenidos a traves de la API de Coingecko.

## Repositorio:

* :hammer:Extract, Transform and Load (ETL) :El archivo `ETL.py` explica la extracción de datos a través de la libreria pycoingecko, definiendo 3 funciones para la obtención de los datos precio, capitalización del mercado y volúmen de las criptomonedas elegidas en los periodos 01 de enero del 2010 al 15 de agosto del 2023 con la divisa transable, el dólar. Así mismo, se comprimen los datos mediante los Id's de cada criptomoneda.

* :mag: Exploratory Data Analyst (EDA): En la carpeta `EDA` se puede observar el analisis exploratorio de los datos obtenidos en el proceso de ETL, realizando una búsqueda de valores faltantes, valores duplicados, valores atípicos, comportamiento de las variables y relaciones que existen entre ellas. (Se utilizó la librería plotly, la cuál es interactiva en los archivos .ipynb pero no al momento de subirlo al Github).

## Criptomonedas seleccionadas
1. Bitcoin
2. Ethereum
3. Tether
4. Binancecoin
5. Ripple
6. Usd-coin
7. Staked-ether
8. Cardano
9. Dogecoin
10. Solana
11. Tron
12. Polkadot
13. Matic-network
14. Shiba-inu
15. Litecoin

## Reporte de análisis

En el proceso del EDA se identificaron comportamientos, patrones y tendencias particulares de cada criptomoneda elegida, acerca del precio, capitalización del mercado y volúmen. Estas son:

* Alta volatilidad en el precio de las criptomonedas en el período elegido.
* Elevada y positiva correlación entre el precio y la capitalización del mercado de las criptomonedas en el período elegido. 
* Aumento en el volúmen de transacción de las criptomonedas en el mercado.

## Key Performance Indicator
Se plantearon 3 KPI's para la toma de decisiones al momento de adquirir estos activos financieros:

1. Variación procentual de precio: Mide la variación en el precio de una criptomoneda en un período específico. Su cálculo es la diferencia entre el 
precio actual y el precio anterior dividido entre el precio anterior. Esto refleja cuánto ha aumentado o disminuido el precio en relación al valor anterior.

2.  Relación volúmen - capitalización del mercado: Compara la cantidad del volúmen de cada criptomoneda en un período específico con la capitalizacion del mercado. Una relación alta sugiere que el valor del volúmen es alto en comparación con la capitalización del mercado que tiene una relación positiva con el precio, mientras un valor de la relación bajo indica lo contrario.

3. Potencial de crecimiento: Indica el potencial de crecimiento restante de una criptomoneda en comparación con su estimación total de crecimiento.

Espero les haya gustado el desarrollo de este proyecto, cualquier consulta pueden escribirme a **[LinkedIn](https://www.linkedin.com/in/alejandra-lizeth-salas-talavera/)**
