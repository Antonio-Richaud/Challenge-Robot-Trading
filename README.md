
# Challenge-Robot-Trading 🤓📊👾

Para este primer proyecto del bootcamp de Data Science vamos a contruir un Robot Trading (sencillo) en Python capaz de tomar decisiones de compra y venta de Bitcoin en tiempo real, comparto con todo el amor del mundo mi trabajo para que más personas puedan formarse en este mundo de la Ciencia de Datos.


[@Antonio Richaud](https://www.antonio-richaud.com/)


![Logo](https://www.aluracursos.com/assets/img/challenges/logos/challenges-logo-data.1712144089.svg)


## Pasos a seguir

1. **Configuración del ambiente:** Para empezar, podemos utilizar un entorno virtual como Google Colaboratory, o si lo desean, puedes usar el editor Python de tu preferencia.

2. **Obtención de datos:** Necesitaremos acceder a una API que proporcione datos históricos de precios de Bitcoin en formato JSON. Por otro lado, necesitaremos realizar Web Scraping en un site de noticias para obtener el precio actual y algunos indicadores de tendencias del Bitcoin.

3. **Limpieza de datos:** Una vez que tengamos los datos históricos deberemos cargarlos en un DataFrame de Pandas para poder manipularlos y analizarlos, deberemos identificar y eliminar los outliers, además de tratar cualquier valor nulo o duplicados en la base. Finalmente, con la base limpia, calcularemos el precio promedio del Bitcoin.

4. **Toma de decisiones:** Una vez que tengamos el precio promedio, lo comparamos con el precio actual y tendencia del Bitcoin, que previamente obtuvimos con Web Scraping. Si el precio actual es mayor/igual que la media y la tendencia es de baja, entonces se debe vender, pero si el precio actual es menor que la media y la tendencia es de alta, entonces se debe comprar.

5. **Visualización:** Utilizaremos la librería Matplotlib para crear un gráfico donde se muestre la evolución del precio del Bitcoin durante el periodo seleccionado, y una línea recta que pase sobre el precio medio. Por último, muestra un mensaje en el gráfico que indique “Vender”, “Comprar” o “Mantener” según sea la decisión del algoritmo.

6. **Automatización:** Finalmente, cuando tengamos el algoritmo de decisión, es hora de automatizar el proceso. Utiliza la librería de Python "time" para ejecutar el algoritmo de decisión cada 5 minutos y actualizar el gráfico. 🤠



## Información que me ayudo

 - [yFinance](https://pypi.org/project/yfinance/)
 - [Modulo: Display](https://ipython.readthedocs.io/en/stable/api/generated/IPython.display.html)
