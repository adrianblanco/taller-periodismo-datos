# Taller de periodismo de datos

======
#### Del 23 al 27 de abril, Agencia Efe
#### Instructor: Adrián Blanco
======

### Esquema del curso

## I. <a href="#intro">Introducción y conceptos clave</a> (4h)

* ¿Qué es el periodismo de datos?
* Fuentes: ¿Dónde puedo encontrar datos para mis historias?
* Propuestas de proyectos a realizar durante el curso

## II. <a href="#analisis">Análisis de datos</a> (4h)

* Extracción y limpieza de datos
* Operaciones estadísticas básicas
* Aprende a trabajar con Excel y Google Spreadsheet

## III. <a href="#visualizacion">Visualización de datos</a> (4h)

* Gráficos, mapas y herramientas gráficas para mejorar mis artículos
* Cómo diseñar gráficos con Datawrapper
* Visualización avanzada con Flourish

## IV. <a href="#storytelling">De los datos a la historia</a> (4h)

* Cómo encajar los datos dentro de la historia
* Storytelling
* Edición del proyecto final

=========

## I. <a href="#intro">Introducción y conceptos clave</a>e (4h)

* ¿Qué es el periodismo de datos?


"If you torture the data long enough, it will confess to anything"

— ['How to lie with statistics' por Darrell Huff, ](http://faculty.neu.edu.cn/cc/zhangyf/papers/How-to-Lie-with-Statistics.pdf)

 “En vez de quedarse con esa información y practicar el periodismo Gollum, quedarse con el anillo y no compartirlo, decidieron compartirlo con el Consorcio, porque entendieron que era un tema global que tocaba a más de 200 países”

— [Mar Cabra, editora de la unidad de datos del ICIJ, ](http://www.unidiversidad.com.ar/mar-cabra-y-el-periodismo-gollum)

"Los datos pueden ser la fuente del periodismo de datos, o pueden ser la herramienta con la que se narra la historia o ambas cosas. Como cualquier fuente, debe tratarse con escepticismo; y como cualquier herramienta, debemos ser conscientes de cómo puede modelar y limitar las historias que se crean con la misma"

— [Paul Bradshaw, Birmingham City University](http://interactivos.lanacion.com.ar/manual-data/introducci%C3%B3n_0.html)

* Fuentes: ¿Dónde puedo encontrar datos para mis historias?

Una de las primeras preguntas que nos podemos hacer cuando nos encargan una historia o tengo una idea para desarrollar es ¿dónde puedo acceder a los datos que apoyen a mi historia?

No existe una fórmula mágica, dependerá del tema, del tipo de historia, de las fuentes oficiales disponibles. Incluso, a veces no habrá datos y tendremos que solicitarlos o construir nuestra propia base de datos.

####Fuentes estadísticas oficiales

Para la mayoría de temas del día a día, y desde un contexto español, podemos servirnos de dos fuentes de datos principales:

* Instituto Nacional de Estadística (INE). Es probablemente la fuente de datos y estadísticas más completa de España. Prácticamente cualquier estadística oficial que busquemos

* Eurostat: es el portal estadístico europeo. Podemos trabajar directamente con las bases de datos que ofrece o consultar los resumenes que publica.

Cómo utilizar Eurostat (en inglés)
http://ec.europa.eu/eurostat/statistics-explained/index.php/Accessing_European_statistics

http://ec.europa.eu/eurostat/statistics-explained/index.php/Main_Page/es

http://ropengov.github.io/r/2015/05/01/eurostat-package-examples/

Fuentes de otros países:

* Office for National Statistics (ONS) https://www.ons.gov.uk/
* Oficina estadísitica federal alemana - Destatis https://www.destatis.de/EN/Homepage.html
* Todas las oficinas estadísticas oficiales


####Open Data | Datos abiertos

¿Qué son los datos abiertos?
Los datos abiertos son datos que pueden ser utilizados, reutilizados y redistribuidos libremente por cualquier persona, y que se encuentran sujetos, cuando más, al requerimiento de atribución y de compartirse de la misma manera en que aparecen.

— [Open Data Handbook](http://opendatahandbook.org/guide/es/what-is-open-data/)

Las instituciones han comenzado a publicar datos en formato abierto, aunque a veces no son tan abiertos como los pintan. Un ejemplo: un .pdf nunca será un formato abierto y todavía siguen publicando en este tipo de formatos.

Algunos ejemplos son:

Madrid, portal de datos abiertos
Barcelona, portal de datos abiertos

Open Data in github
https://github.com/collections/open-data

####Fuentes privadas abiertas

También hay fuentes de datos abiertos en la web a las que podemos acudir:

* ProPublica Data Store
* FiveThirtyEight
* Cool Datasets
* ewsletter
* Open Knowledge

En España, desde que el XXX se aprobase la ley de Transparencia, las instituciones, las comunidades y los ayuntamientos han comenzado a publicar


####Cómo buscar fuentes

* Repositorios
Un ejemplo es el de la organización sin ánimo de lucro destinada a la investigación, Propublica.
ProPublica cuenta con ...

* A través de Google y mediante la búsuqeda avanzada pueden buscarse fuentes utilizando la siguiente sintáxis. Si introducimos en el buscador:

```

término de búsuqeda filetype:tipo_de_archivo site:url


```


Un ejemplo:

```

índice general precios vivienda filetype:xls site:gob.es


```

¿Y si no hay datos?

* Solicitudes de acceso a la información: Conocidas como FOIAs en inglés. Es aquella solicitud que presentamos a una administración amaparados por la ley de Trasnparencia española

Para poder realizar esta solicitud, debemos


Transparencia y solicitudes información y datos



Otra opción de la que debe valerse cualquier periodista de datos son las solicitudes de información, en especial cuando trabaja en un tema para el que no hay datos públicos pero sí posrían estar en posesión de la Administración. Para poder desenvolverse correctamente, lo fundamental es conocer 'al dedidllo' la Ley Xxxxx.



Vamos a ver algunos de los puntos clave:

*

* Art 4. Tipos de límites

*


De esta forma, para realizar las solicitudes de información debemos tener.

Podemos utilizar la siguiente plantilla como base:

```
Estimado [Ministerio u organismo de la Admon. Pública],

En virtud de la Ley 19/2013 de Transparencia, Acceso a la Información Pública y Buen Gobierno, les solicito la siguiente información relativa al uso de la infraestructura viaria  por parte de empresas privadas con detalle de:

[CONTENIDO DE LA SOLICITUD]

En caso de que la información no se encuentre tal y como pido en esta solicitud, me gustaría que se me entregue tal y como consta en los registros públicos, para evitar así cualquier acción previa de reelaboración.

Les agradecería que me pudieran remitir la información solicitada en uno de estos formatos: .csv, .txt, .xls ó .xlsx

Les recuerdo que disponen de un plazo máximo de un mes para remitir dicha información.

Muchas gracias
```


Importante:

* Un mes para responder a nuestra solicitud desde el inicio de la tramitación.

* Ese mes puede extenderse con otro mes de prórroga en caso de que la Administración necesite más tiempo para tramitar la solicitud. Es decir, en general, podrían respondernos en el plazo de una semana a dos meses.

* Por tanto, es importante que guardemos registro del día en que presentamos la solictud y estemos atentos al día de respuesta límite.



En ocasiones nos denegarán la solicitud. Si nuestra petición está justificada podemos recurrir al Consejo de Transparencia y Buen Gobierno (CTBG).



El modelo de reclamación puede encontrarse en el siguiente link. En él debemos argunentar por qué consideramos que no se está atendiendo a nuestro derecho de acceso a la información y justificarlo de acuerdo a los artículos de la ley. También podemos servirnos de estas interpretaciones del CTBG sobre aspectos muy concretos de la ley. Por ejemplo, como periodistas y según el Xxxx, podemos


* Fácil, creo la base de datos. Es lo que pensamos al realizar este proyecto sobre la violencia de género en España. Las estadísticas que proporciona el ministerio XXXX son muy pobres así que decidimos recopilar una base de datos más completa con cada caso.

Es sólo un ejemplo, alrededor nuestro hay miles de documentos desperdigados a los que si encontramos un encuadre, podemos construir nuestra propia base de datos.

Para ello, simplemente hay que tener en cuenta:

* Cómo vamos a estructurar esa base de datos. Es fundamental para poder manejar más tarde los datos de forma adecuada.
* Los nombres de las variables deen ser sencillos. Si es necesario incluiremos un archivo de metadatos explicando cada una de las variables.

#### Formatos

Una vez tengo localizadas la fuente que voy a utilizar es muy importante,

* .xls, .xlsx: es el formato en el que Excel guarda un conjunto de datos en formato tabla. Se puede abrir y trabajar con él con Excel, LibreOffice, OpenOffice, Google Spreadsheet...
* .csv: documento en formato abierto sencillo para representar datos en forma de tabla, en las que las columnas se separan por comas y las filas por saltos de línea.
* .tsv: documento en formato abierto sencillo para representar datos en forma de tabla, en las que las columnas se separan por tabulaciones y las filas por saltos de línea
* .json: es un formato ligero de intercambio de datos. Leerlo y escribirlo es simple para humanos, mientras que para las máquinas es simple interpretarlo y generarlo. [Más info](https://json.org/json-es.html)
* .pdf: es el mayor enemigo del periodista de datos. Formato de documento portátil es un formato de almacenamiento para documentos digitales. Es de tipo compuesto ya que incluye imagen vectorial, mapa de bits y texto.
* Formato web, HTML: En estos casos si los datos no se pueden copiar o si a pesar de que podemos copiarlos no podemos pegarlos o exportarlos en un formato adecuado, la única opción que no queda es extraer los datos de la web de forma automatizada. En inglés, a este proceso se le conoce como web scraping. Implica conocer un lenguaje de programación como, por ejemplo, Python.

Si lo nuestro no es la programación, existen algunas herramientas gratuitas que pueden facilitarnos el trabajo como son:

* Tabula
* Import.io
* Web scraper

* Propuestas de proyectos a realizar durante el curso

El objetivo del curso es que desarrolléis una historia con datos durante esta semana.

Para ello:

* Identifica un tema que te interese y expón la tesis que quieras afirmar o refutar.
* Busca bases de datos que apoyen o refuten ese tema.
* Identifica el formato de cada una de ellas y analiza cómo puedes trabajar con ellas.

#### Tipo o formato de los valores o datosAdem

ás del formato del archivo, otro concepto clave es el tipo de dato de cada una de nuestras variables. En función del programa o lenguaje de programación existen diferentes tipos de datos. Los principales para trabajar con Excel o spreadsheet:

* Texto o storytelling
* Numérico
* Fecha
