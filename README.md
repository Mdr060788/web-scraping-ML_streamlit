# Automatizando mis decisiones de compra en Mercado Libre con Python, Streamlit, Selenium, Echarts, Power BI.
Cómo utilicé Python, Selenium, Streamlit, Echarts y Power Bi para crear una aplicación que automatice el raspado de datos en una pagina web de productos. 
En este caso, Mercado Libre, para luego visualizar los resultados y realizar un análisis más profundo utilizando Power BI.

![App](https://github.com/Mdr060788/web-scraping-ML_streamlit/blob/master/assets/logo.png)

Dentro de la interfaz, ingresamos el producto, ejecutamos el proceso y se abrirá un navegador que recorrerá las páginas automáticamente obteniendo los datos 
relevantes que hayamos indicado en nuestro código.

![App](https://github.com/Mdr060788/web-scraping-ML_streamlit/blob/master/assets/inicio.gif)

Una vez finalizado el proceso, se mostrarán los resultados recopilados en un gráfico interactivo creado con el complemento de @andfanilo https://github.com/andfanilo/streamlit-echarts
streamlit-echarts. Un gráfico de barras de echarts, representa los precios de los productos y un precio promedio. 
Debajo, una tabla donde se encuentra el título, precio, producto, la imagen, sus características, y el enlace al mismo. Ambos son receptivos a un slider 
donde podemos elegir el rango de precio que estamos buscando.

![App](https://github.com/Mdr060788/web-scraping-ML_streamlit/blob/master/assets/resultados.gif)

Aunque la aplicación en Streamlit me proporcionó una vista general de los productos y sus precios, quería realizar un análisis más minucioso para tomar 
una decisión informada. Aquí es donde Power BI, una herramienta de análisis de datos y visualización de Microsoft, entró en juego. Conecté los datos 
extraídos por la aplicación y creé un informe interactivo que me ayudó a explorar los productos en más detalle, filtrar por características, marca, línea, 
valoración, modelo, etc.

![App](https://github.com/Mdr060788/web-scraping-ML_streamlit/blob/master/assets/canillas.gif)

El mismo reporte lo terminé incrustando dentro de la app, esto me brinda una experiencia completa y me ayuda a realizar un análisis más profundo antes de 
tomar una decisión final.

![App](https://github.com/Mdr060788/web-scraping-ML_streamlit/blob/master/assets/colchones.jpg)

Este proyecto está inspirado y creado gracias al material de @lkuffo. https://github.com/lkuffo/web-scraping

Si quiere leer el artículo completo en Medium: https://medium.com/@maurodanielrossi/web-scraping-python-streamlit-26d2478e550d




