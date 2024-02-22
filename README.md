 <center> <h1 style="color:#d48a13">🏡  El sector inmobiliarion en el condado de King (USA)  🏡 </h1> </center>

<p align="center">
  <img src="https://github.com/Vicgutgam/King-Real-Estate/blob/main/Im%C3%A1genes/Condado%20de%20King.png" width="75%">
  <br>
  <small><em>Antigua bandera del Condado de King y ubicación dentro del estado de Washington.</em></small>
</p>

## Sobre el proyecto.

Este proyecto se enmarca dentro del Bootcamp de Análisis de Datos impartido por la escuela IRONHACK. En esta ocasión, el Dataframe nos hablará sobre el mercado inmobiliario en el condado de King en EEUU  entre mediados del 2014 y 2015 y las características de las viviendas que fueron vendida.

## Sobre el Condado de King-Seattle y el sector inmobiliario.

Es interesante saber que el condado de King se encuentra en el estado estadounidense de Washington, es decir la costa Oeste. Su población según el censo del año 2020 era de 2,269,675 y curiosamente se ha visto un leve descenso de la población. Por población el condado de King es el mayor del estado de Washington, y hace el número 14 de los más poblados de todos los Estados Unidos. Es uno de los más avanzados condados en el ámbito educativo de toda la nación y aproximadamente la mitad de su población posee un título universitario.

La sede de condado es la ciudad de Seattle, que también es la mayor ciudad del estado de Washington. Cerca de dos terceras partes de la población habita en los alrededores de la ciudad. El condado de King se encuentra también en el ranking de los 100 condados con mayores ingresos de los Estados Unidos de América. 

Aunque se vio afectada por la Gran Recesión, Seattle ha conservado una economía comparativamente fuerte y se caracteriza por la creación de empresas, especialmente en construcción sustentable y tecnologías limpias. Lo cual se puede traducir en puestos de trabajo de gran cualificación que supone a la vez una subida considerable de los precios de la vivienda.



## Desarrollo del proyecto.
<ol>
  <li>Presentación de los objetivos:</li>
  <ol>
      <li>Comprender qué características impactan más significativamente el precio de la vivienda</li>
      <li>Explorar propiedades valoradas en $650 mil y más para obtener información más detallada</li>
    </ol>
  </li>
  <li>Pre-work. El presente Dataframe está en bastantes buenas condiciones, no presentó ningún null o elementos parecidos. Se modificó solamente la columnas de año de renovación para simplicar un poco la presentación de los datos.</li>
  <li>Realización del EDA, donde se comprobó la distribución,  los OUTLIERS, las correlaciones y la multicolinealidad de algunos elementos.</li>
  <li>Procesamiento de los datos.
    <ol>
      <li>X-y Split</li>
      <li>Creación de modelos de MACHINE LEARNING: se aplicaron los modelos de Regresión Lineal, Ridge, Lasso, Knn, XGBoots y Decision Tree.</li>
    </ol>
    
  ![image](https://github.com/Vicgutgam/King-Real-Estate/assets/155966045/8b738627-2ff2-4fa2-93c6-54475a5e2246)

  </li>
  <li>Conclusiones:</li>
  <ol>
      <li>Objetivo 1: con los datos obtenidos, llegamos a la conclusión que el tamaño de la vivienda y la tenencia de baños, son los elementos que más influyen en el precio de la vivienda. </li>
      <li>Objetivo 2:</li>
      <ol>
      <li>El precio de la vivienda está estrechamente vinculado a la ubicación por lo que si encontramos una vivienda en una zona concreta con outlier inferior podría ser una buena inversión. Y lo mismo pasaría para saber si una vivienda es cara en una zona concreta (a rasgos generales).</li>
      <li>Las dimensiones de la vivienda estan relacionadas con el Zip.code y sobre todo con el coste del mismo.</li>
       <li>Los años de renovación. Como norma general veremos que las casas renovadas hace poco tendrán un coste por encima de las que no tengan una renovación.</li>
           </ol>
  </li>
</ol>


  ![image](https://github.com/Vicgutgam/King-Real-Estate/assets/155966045/0c4dd2de-7d6c-452f-93d4-d0b2cb1434fa)


## Herramientas:
**Soporte técnico**
* **JupyterLab**

**Librerías**

* **Pandas**: manipulación y análisis de datos
* **Numpy**: Matrices y funciones matemáticas.
* **Matplotlib**: Data visualization.
* **Seaborn**: Runs on top of matplotlib, HD data visualization.
* **Sklearn**: para procesos de Machine Learning

## Bibliografía:
<ul>
  <li> Seattle: https://es.wikipedia.org/wiki/Seattle</li>
  <li> Condado de King: https://es.wikipedia.org/wiki/Condado_de_King_(Washington)</li>
  <li>Información inmobiliaria:
    <ul>
      <li>https://www.acantoinmobiliaria.com/blog/que-factores-influyen-en-precio-una-vivienda.html</li>
      <li>https://www.solerahogar.es/que-factores-afectan-el-valor-de-la-vivienda/</li>
    </ul>
  </li>
  
</ul>
