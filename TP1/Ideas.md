# Ideas a analizar

## Santiago 

1 . [x] BarPlot usuarios nuevos vs viejos.  
2 . Modelos buscados por sistema operativo (analizar si la gente que tiene mac busca mas iphone que android, analogo con microsoft o linux / android).
3 . [x] BarPlot channels.

## Bautista

- [x] Analisis general de los datos: cantidad de eventos en escala de tiempo, info del set de datos.
- [x] Vista de los paises que mas participaron en la plataforma: choropleth plot tanto por paises, como por region
especializandome en Brazil.
- [x] Topicos como producto mas vendido, evento con mayor ocurrencia, y demas.

* Buscando una relacion entre eventos por escala de timpo, o algun patron de compra.

## Daniela
- [x] Cantidad de ventas por mes desde Enero hasta Junio. Medición a partir del evento 'conversion'.
- [x] Ver si el set de datos se encuentra ordenado. Desde que fecha hasta qué fecha hay datos,
- [x] Según la columna 'model', verificar cual marca es la más vendida en todo el set de datos. Observar que esta columna, la primera palabra es la marca del dispositivo. 
- Buscar algún tipo de patrón en los usuarios según los eventos que realizan. Ver que relación podría existir en ciertos eventos.

## Emanuel

- [x] Evolución de la cantidad de usuarios nuevos durante los meses Enero-Mayo.
- [x] Evolución de ingresos al sitio a traves de campañas de marketing online Enero-Mayo.
- [x] Porcentaje de dispositivos usados para visitar el sitio.

* Productos más comprados por pais-region.
* Analisis de los terminos más buscados.
* Buscando relación entre los productos más visitados y los que efectivamente son los más comprados.

# Enunciado 

Algo a tener en cuenta es que no todos los datos descritos en las columnas corresponde a
todos los tipos de eventos.

Por otro lado es importante tener en cuenta que el carácter temporal de los eventos para un
usuario nos indican una progresión de los mismos en el tiempo, por lo cual es factible
analizarlos de esa forma.

Por último, deberian tener en cuenta que dado que los usuarios están navegando catálogos de
productos hacia un flujo de compra en una página de producto es posible derivar información
entre eventos para poder enriquecer unos y otros.

El objetivo del primer TP es realizar un análisis exploratorio del set 
datos del TP. Queremos ver qué cosas podemos descubrir sobre los datos que puedan resultar interesantes. Los
requisitos de la primera entrega son los siguientes:

El análisis debe estar hecho en Python Pandas o R.
El análisis debe entregarse en formato papel en una carpeta en donde se incluya el
reporte completo y todas las visualizaciones generadas. Es altamente recomendable
que las visualizaciones se impriman en color.

Informar el link a un repositorio Github en donde pueda bajarse el código completo para
generar el análisis.

Agregar en Kaggle un kernel con el análisis exploratorio realizado.
La evaluación del TP se realizará en base al siguiente criterio:


## Topicos de Enunciado

**Originalidad del análisis exploratorio.** 
Calidad del reporte. ¿Está bien escrito? ¿Es claro y preciso?
Calidad del análisis exploratorio: qué tipo de preguntas se hacen y de qué forma se
responden, ¿es la respuesta clara y concisa con respecto a la pregunta formulada?
Calidad de las visualizaciones presentadas.
- ¿Tienen todos los ejes su rótulo?
- ¿Tiene cada visualización un título?
- ¿Es entendible la visualización sin tener que leer la explicación?
- ¿El tipo de plot elegido es adecuado para lo que se quiere visualizar?
- ¿Es una visualización interesante?
- ¿El uso del color es adecuado?
- ¿Hay un exceso o falta de elementos visuales en la visualización elegida?
- ¿La visualización es consistente con los datos?
Conclusiones presentadas.
- ¿Presenta el grupo un listado de "insights" aprendidos sobre los datos en base al
análisis realizado? ¿Es interesante?
- ¿Pudieron descubrir **features en el campo ‘model’** ? ¿Cuales fueron?
- ¿Identificaron **patrones o funnels de usuarios que realizan
checkouts/conversiones** en Trocafone?
- ¿Se comportan de forma distinta dependiendo del **tipo de dispositivo
desde el cual acceden**?
- ¿Se comportan de forma distinta dependiendo del **tipo de fuente de
tráfico** al que pertenecen?
- ¿Realizaron algún análisis sobre **búsquedas que realizan los usuarios** y las
keywords que utilizan apoyándose en algún tipo de visualización?
- ¿Realizaron algún análisis de **lugar donde se originan las visitas de los usuarios
de Trocafone** (a nivel país, regiones más importantes o ciudades más
importantes) apoyándose en algún tipo de visualización?-
- ¿Pudieron descubrir features jerarquizando información de alguno de los
campos (por ejemplo “**screen_resolution**”)?
- ¿El análisis realiza un aporte a Trocafone?
