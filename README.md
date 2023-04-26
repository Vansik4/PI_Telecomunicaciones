<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Telecomunicaciones`**</h1>


### **Resumen**

En este proyecto, se nos ha encomendado el análisis del comportamiento del sector de las telecomunicaciones en Argentina, con un enfoque en el acceso a internet. Nuestro objetivo es ayudar a una empresa prestadora de servicios de telecomunicaciones a mejorar la calidad de sus servicios, identificar oportunidades de crecimiento y plantear soluciones personalizadas para sus posibles clientes. Para lograrlo, se nos ha solicitado que visualicemos un KPI específico en un dashboard de Power BI y que establezcamos tres KPIs adicionales a partir de nuestro análisis. Este proyecto nos brinda la oportunidad de aprender sobre el uso de tecnología y análisis de datos para tomar decisiones informadas y resolver problemas en un mercado en constante evolución. En la sección de material de apoyo se pueden encontrar más detalles sobre los KPIs y el contexto del proyecto.

### **Desarrollo del Proyecto**

`Análisis Exploratorio de los datos` (_Exploratory Data Analysis = EDA_)

Durante el desarrollo de este proyecto, se llevó a cabo una exploración de datos efectiva (EDA) con el fin de identificar patrones y outliers relevantes en los datos. Gracias a esto, se logró realizar las correcciones necesarias a través del proceso de extracción, transformación y carga (ETL), asegurando así la calidad y consistencia de los datos utilizados en las posteriores fases del proyecto. Este enfoque riguroso en la exploración y preprocesamiento de los datos garantiza una mayor confiabilidad y validez en los resultados obtenidos.

[EDA_Datasets.ipynb](https://github.com/Vansik4/PI_Telecomunicaciones/blob/main/EDA_Datasets.ipynb)

`Dashboard`

Completé la creación del dashboard utilizando Power BI, el cual fue alimentado con los archivos CSV ya procesados y limpios. La visualización generada en el dashboard permite una comprensión más clara y concisa de los datos analizados, lo que permitirá la toma de decisiones de una manera más efectiva y eficiente.

[Presentacion PI_Telecomunicaciones.pbix](https://github.com/Vansik4/PI_Telecomunicaciones/blob/main/Presentacion%20PI_Telecomunicaciones.pbix)

`KPIs y Analisis`

Al momento de realizar el EDA como parte prioritaria del proyecto, noté que había una base de datos extremadamente grande, algunas incluso redundantes. Decidí trabajar solamente con las bases de datos que se enfocan en el acceso a internet para realizar un estudio correcto del tema, que en este caso es el acceso actual que tienen las familias al internet.

Me enfoqué en los conjuntos de datos que tienen correlación con las provincias de Argentina para crear un dashboard más dinámico y atractivo a la hora de presentarlo, donde se pueda ver la relación entre las velocidades de descarga y cómo el tiempo hace que el servicio esté más al alcance de todos, vamos a analizar algunas graficas y las conclusiones que podemos sacar

+ Primer KPI (Penetración de internet por cada 100 hogares)

<img src ="https://raw.githubusercontent.com/Vansik4/PI_Telecomunicaciones/main/src/Diagrama_boxdf1.JPG">

Podemos obsevar algunos valores atipicos en Mendoza, Neuquén y san juan donde los accesos por cada 100 hogares son significativamente más altos 
que en el resto de las provincias. También podemos observar que la mayoría de las provincias tienen una mediana similar en cuanto al acceso a Internet, mientras que la Ciudad de Buenos Aires tiene la mediana más alta de todas las provincias. 
Este análisis nos permite identificar patrones y anomalías en los datos que pueden ser útiles para tomar decisiones y mejorar la penetración de Internet en diferentes regiones del país.

<img src ="https://raw.githubusercontent.com/Vansik4/PI_Telecomunicaciones/main/src/diagram_linedf1.JPG">

Podemos ver provincias como San Luis y Formosa con un amplio nivel de penetración de acceso a internet a lo largo del tiempo, 
lo que sugiere un fuerte compromiso y apoyo de los gobiernos locales en la expansión de la conectividad en estas regiones. 
Por otro lado, notamos una estabilidad notoria en Buenos Aires, la provincia con mayor población en el país y una de las más desarrolladas económicamente, lo que podría deberse a que ya se ha alcanzado un alto grado de penetración de acceso a internet en la región.

+ Segundo KPI (Internet Por tecnologia y localidad)

<img src ="https://raw.githubusercontent.com/Vansik4/PI_Telecomunicaciones/main/src/df2_1.JPG">

A partir de esta información, se puede concluir que hay una mayor cantidad de datos recolectados en las provincias más pobladas y con mayor actividad económica, como Buenos Aires, Córdoba y Santa Fe. Además, puede ser que en las provincias menos pobladas y económicamente menos activas se utilicen menos servicios de internet y tecnología en general. Es importante tener en cuenta que los datos pueden estar sesgados debido a la forma en que se recolectaron y a las fuentes de datos disponibles.

+ Tercer KPI (Internet por velocidad de bajada)

<img src ="https://raw.githubusercontent.com/Vansik4/PI_Telecomunicaciones/main/src/df3_1.JPG">

Este gráfico de barras apilado muestra la distribución de las velocidades de internet para cada provincia, 
donde cada barra representa la velocidad de internet promedio para cada provincia y los segmentos de cada barra representan la distribución 
de las velocidades de internet en diferentes rangos de velocidad.

Basándonos en el gráfico de barras, podemos concluir que la velocidad de internet de bajada en Argentina presenta una distribución desigual a lo largo de las distintas provincias. Se puede observar una gran variabilidad en las velocidades de internet, desde los valores más bajos de 0.256 mbps hasta los valores más altos de 100 mbps. 
Algunas provincias como Chaco, Buenos Aires, Misiones y Neuquén presentan una mayor dispersión en las velocidades de internet, mientras que CABA, San Juan y San Luis presentan una distribución más homogénea. 
Es importante tener en cuenta que los datos analizados corresponden a una muestra y no representan necesariamente la totalidad de la población de Argentina. Por lo tanto, es recomendable continuar explorando los datos y realizar análisis estadísticos más detallados para obtener una comprensión más profunda de la distribución de la velocidad de internet de bajada en Argentina.

+ Cuarto KPI (historico velocidad de internet)

<img src ="https://raw.githubusercontent.com/Vansik4/PI_Telecomunicaciones/main/src/df4.JPG">

Podemos observar cómo la velocidad media de bajada varía a lo largo de los años y trimestres. 
También podemos observar si hay alguna tendencia en la velocidad de bajada en cada provincia.

`Algunas Recomendaciones`

Podemos ver provincias como San Luis y Formosa con un amplio nivel de penetración de acceso a internet a lo largo del tiempo, lo que sugiere un fuerte compromiso y apoyo de los gobiernos locales en la expansión de la conectividad en estas regiones. Por otro lado, notamos una estabilidad notoria en Buenos Aires, la provincia con mayor población en el país y una de las más desarrolladas económicamente, lo que podría deberse a que ya se ha alcanzado un alto grado de penetración de acceso a internet en la región.

Sin embargo, también podemos observar algunos valores atípicos en Mendoza, Neuquén y San Juan, donde la penetración de acceso a internet parece haber disminuido en algunos momentos durante el período de estudio. Esto podría ser debido a factores como interrupciones en el servicio o cambios en la infraestructura de red que afectan temporalmente la conectividad en estas regiones.