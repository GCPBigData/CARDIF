Jose R F Junior web2ajax@gmail.com jferreira@grupoabraxas.com

PRUEBA TECNICA ESPECIALISTA E INGENIERO INTEGRACION DE DATOS

INTEGRACION DE DATOS

1 - ¿Qué es una base de datos analítica?

2 - ¿En qué se diferencia de una transaccional?

3 - ¿Qué es una vista materializada?

4 - ¿Qué es un hint?, ¿Cuáles conoce?

5 - Con base en el archivo adjunto diseñe un diagrama entidad relación que permita cargar la información normalizada. Asumiendo que el archivo adjunto fue cargado en la tabla del schema de staging STG_CO.STG_ARCHIVO_HISTORICO, escriba un código pl sql que cargue el modelo de datos del paso anterior, asuma que todos los campos de la staging son tipo varchar2(255). Con base en la información cargada en las estructuras de datos generadas, escriba un query que genere un reporte con las personas con más de 2 siniestros en el año 2020, listando los certificados de esos siniestros. Genere un query/vista en la que pueda consultar los clientes y sus certificados en estado vigente.

6 - ¿Defina que es gobierno de datos? ¿Qué partes tiene?

7 - ¿Defina que es calidad de datos? ¿Cuáles son los criterios mínimos para tener un dato de calidad?

8 - Defina la importancia de la calidad de los datos.

9 - Menciones tres atributos relacionados con la Calidad de los datos.

10 - Establezca un proceso técnico sencillo para la estandarización y mejora de una base de clientes para analizar los datos y darles remediación conforme a los atributos de data Quality.

11 - Mencione lo más importante a tener en cuenta en una herramienta de data Quality.

12 - Mencione 3 herramientas informáticas posibles pata el seguimiento y presentación de indicadores de Calidad de Datos.

https://colab.research.google.com/drive/1SeGJRaecz7CXZIJMGP_L-KC0_O9P35lL?usp=sharing


Big Data Engineer Jose R F Junior
web2ajax@gmail.com

jferreira@grupoabraxas.com

GitHub Project : CARDIF

PRUEBA TECNICA ESPECIALISTA E INGENIERO INTEGRACION DE DATOS

INTEGRACION DE DATOS

1 - ¿Qué es una base de datos analítica?

2 - ¿En qué se diferencia de una transaccional?

3 - ¿Qué es una vista materializada?

4 - ¿Qué es un hint?, ¿Cuáles conoce?

5 - Con base en el archivo adjunto diseñe un diagrama entidad relación que permita cargar la información normalizada. Asumiendo que el archivo adjunto fue cargado en la tabla del schema de staging STG_CO.STG_ARCHIVO_HISTORICO, escriba un código pl sql que cargue el modelo de datos del paso anterior, asuma que todos los campos de la staging son tipo varchar2(255). Con base en la información cargada en las estructuras de datos generadas, escriba un query que genere un reporte con las personas con más de 2 siniestros en el año 2020, listando los certificados de esos siniestros. Genere un query/vista en la que pueda consultar los clientes y sus certificados en estado vigente.

6 - ¿Defina que es gobierno de datos? ¿Qué partes tiene?

7 - ¿Defina que es calidad de datos? ¿Cuáles son los criterios mínimos para tener un dato de calidad?

8 - Defina la importancia de la calidad de los datos.

9 - Menciones tres atributos relacionados con la Calidad de los datos.

10 - Establezca un proceso técnico sencillo para la estandarización y mejora de una base de clientes para analizar los datos y darles remediación conforme a los atributos de data Quality.

11 - Mencione lo más importante a tener en cuenta en una herramienta de data Quality.

12 - Mencione 3 herramientas informáticas posibles pata el seguimiento y presentación de indicadores de Calidad de Datos.

1 - ¿Qué es una base de datos analítica?
image.png

El predictive analytics se sirve de la información contenida en las bases de datos para poder realizar pronósticos que ayuden al negocio en la toma de decisiones. El área de marketing es una de las que más se benefician de estos repositorios de conocimiento en bruto. Sin embargo, no todas las bases de datos pueden emplearse para apoyar a la inteligencia de negocio. Bases de datos analíticas: características y tipos Las bases de datos transaccionales no son la primera opción para llevar a cabo esta función predictiva, al no estar diseñadas para una finalidad de análisis, sino para el día a día de las operaciones. Las bases de datos analíticas son la alternativa más idónea al tratarse, generalmente, de sistemas de sólo lectura que almacenan datos históricos sobre las métricas de negocio. A ellas recurren los analistas y usuarios de negocio para lanzar sus consultas previas a la elaboración de informes. Entre sus características principales destacan:

La información allí recogida se debe actualizar regularmente. Además de los registros históricos se deben incorporar los datos de transacciones recientes de los sistemas operativos corporativos. Pueden formar parte de un almacén de datos. Deben ser escalables. Las bases de datos analíticas no son siempre iguales ni se trabaja con ellas de la misma forma. Su estructura, orientación analítica y cualidades cambian en función del tipo de base de datos de que se trate. En el mercado pueden encontrarse los siguientes tipos: Bases de datos estructurada en columnas: emplea esta estructura para sustituir a las filas y poder reducir el número de elementos de datos a leer para poder procesar cada consulta. Dispositivos de almacenamiento de datos: no se trata de bases de datos en sí, sino que son un formato híbrido que combina éstas con el hardware y herramientas de BI en una plataforma integrada. Su principal ventaja es la accesibilidad usuaria y su interfaz intuitiva, que facilita su uso. Bases de datos in memory: estas bases de datos cargan la información en la memoria del sistema en un formato comprimido, no relacional, que racionaliza la carga de trabajo que implica el procesamiento de las consultas. Bases de datos MPP: su principal característica es el procesamiento en paralelo, que se apoya en diferentes servidores para compartir la carga de trabajo asociada al lanzamiento de consultas porparte de los diferentes usuarios de negocio. Bases de datos OLAP: se ocupan del procesamiento analítico en línea en base a cubos multidimensionales de datos agregados para el análisis de la información.

image.png

2 - ¿En qué se diferencia de una transaccional?
image.png

La principal diferencia entre OLAP y OLTP: Tipo de procesamiento La principal distinción entre los dos sistemas está en sus nombres: analítico frente a transaccional. Cada sistema está optimizado para ese tipo de procesamiento.

OLAP está optimizado para realizar análisis de datos complejos para una toma de decisiones más inteligente. Los sistemas OLAP están diseñados para ser utilizados por científicos de datos, analistas comerciales y trabajadores del conocimiento, y admiten inteligencia comercial (BI), minería de datos y otras aplicaciones de soporte de decisiones.

image.png

OLTP, por otro lado, está optimizado para procesar una gran cantidad de transacciones. Los sistemas OLTP están diseñados para que los utilicen los trabajadores de primera línea (p. ej., cajeros, cajeros bancarios, recepcionistas de hoteles) o para aplicaciones de autoservicio de clientes (p. ej., banca en línea, comercio electrónico, reservas de viajes).

Otras diferencias clave entre OLAP y OLTP Enfoque: los sistemas OLAP le permiten extraer datos para análisis complejos. Para impulsar las decisiones comerciales, las consultas a menudo involucran una gran cantidad de registros. Por el contrario, los sistemas OLTP son ideales para realizar actualizaciones, inserciones y eliminaciones simples en las bases de datos. Las consultas generalmente involucran solo uno o unos pocos registros. Fuente de datos: una base de datos OLAP tiene un esquema multidimensional, por lo que puede admitir consultas complejas de múltiples hechos de datos a partir de datos actuales e históricos. Diferentes bases de datos OLTP pueden ser la fuente de datos agregados para OLAP y pueden organizarse como un almacén de datos. OLTP, por otro lado, utiliza un DBMS tradicional para acomodar un gran volumen de transacciones en tiempo real. Tiempo de procesamiento: en OLAP, los tiempos de respuesta son mucho más lentos que en OLTP. Las cargas de trabajo son de lectura intensiva e involucran enormes conjuntos de datos. Para transacciones y respuestas OLTP, cada milisegundo cuenta. Las cargas de trabajo involucran operaciones simples de lectura y escritura a través de SQL (lenguaje de consulta estructurado), que requieren menos tiempo y menos espacio de almacenamiento. Disponibilidad: dado que no modifican los datos actuales, los sistemas OLAP se pueden respaldar con menos frecuencia. Sin embargo, los sistemas OLTP modifican los datos con frecuencia, ya que esta es la naturaleza del procesamiento transaccional. Requieren copias de seguridad frecuentes o simultáneas para ayudar a mantener la integridad de los datos.

3 - ¿Qué es una vista materializada?
image.png

Vistas materializadas

Una vista materializada (a veces conocida como vista ordenada, proyectada y materializada o vista SPM) es una vista cuyas columnas se han ordenado, proyectado y materializado (es decir, almacenada físicamente en una tabla exclusiva).

En cada vista materializada, el sistema añade automáticamente una columna que especifica, para cada registro de la vista, el número de bloque del registro correspondiente de la tabla base). El sistema también crea automáticamente un mapa de zonas para cada vista materializada.

Una vista materializada mejora el rendimiento de las consultas de los modos siguientes: Reduce la cantidad de datos que deben transferirse desde el disco durante las exploraciones. Como sus datos están ordenados, el mapa de zonas resultante para las columnas ORDER BY es más eficiente de lo que sería si no. Como los datos están ordenados y cuenta con un mapa de zonas, una consulta cuyo objetivo sean solo unos pocos registros puede recuperar las ubicaciones de bloque de los registros de la base de datos con más celeridad que por otros medios. Las vistas materializadas puede utilizarse para mejorar el rendimiento sin tener que reescribir las aplicaciones. El planificador/optimizador de consultas automáticamente utiliza una vista materializada si hacerlo es más rápido que utilizar la tabla base correspondiente.

4 - ¿Qué es un hint?, ¿Cuáles conoce?
image.png

En varias implementaciones de SQL, una sugerencia (hint) es una adición al estándar SQL que indica al motor de la base de datos cómo ejecutar la consulta. Por ejemplo, una sugerencia (hint) puede decirle al motor que use o no un índice (incluso si el optimizador de consultas decide lo contrario).

Index Hints

Las sugerencias (hint) de índice brindan al optimizador información sobre cómo elegir índices durante el procesamiento de consultas. Las sugerencias (hint) de índice, descritas aquí, difieren de las sugerencias (hint) de optimización, descritas en la Sección 8.9.3, “Sugerencias (hint) de optimización”. Las sugerencias (hint) de índice y optimizador se pueden usar por separado o juntas.

Las sugerencias (hint) de índice se aplican a las declaraciones SELECT y UPDATE. También funcionan con sentencias DELETE de varias tablas, pero no con DELETE de una sola tabla, como se muestra más adelante en esta sección.

Las sugerencias (hint) de índice se especifican después de un nombre de tabla. (Para conocer la sintaxis general para especificar tablas en una instrucción SELECT, consulte la Sección 13.2.10.2, “Cláusula JOIN”). La sintaxis para hacer referencia a una tabla individual, incluidas las sugerencias (hint) de índice, tiene este aspecto:

tbl_name [[AS] alias] [index_hint_list]

index_hint_list:
    index_hint [index_hint] ...

index_hint:
    USE {INDEX|KEY}
      [FOR {JOIN|ORDER BY|GROUP BY}] ([index_list])
  | {IGNORE|FORCE} {INDEX|KEY}
      [FOR {JOIN|ORDER BY|GROUP BY}] (index_list)

index_list:
    index_name [, index_name] ...
Oracle SQL Hints Tuning

image.png

Hay muchas sugerencias (hint) de Oracle disponibles para que el desarrollador las utilice en el ajuste de las sentencias SQL que están incrustadas en PL/SQL.

Primero debe obtener el plan de explicación de su SQL y determinar qué cambios se pueden hacer para que el código funcione sin usar sugerencias, si es posible. Sin embargo, las sugerencias (hint) de Oracle como ORDERED, LEADING, INDEX, FULL y las diversas sugerencias de Oracle AJ y SJ pueden dominar un optimizador salvaje y brindarle un rendimiento óptimo.

Las sugerencias (hint) de Oracle se incluyen en los comentarios de los comandos SQL DELETE, SELECT o UPDATE o se designan con dos guiones y un signo más. Para mostrar el formato, solo se usará la instrucción SELECT, pero el formato es idéntico para los tres comandos.

Oracle Hint Meaning
( + ) Debe estar inmediatamente después del indicador de comentario, le dice a Oracle que esta es una lista de sugerencias. ALL_ROWS Utilice el enfoque basado en costos para obtener el mejor rendimiento. CHOOSE Predeterminado, si las estadísticas están disponibles, se usará el costo, si no, la regla. FIRST_ROWS Utilice el enfoque basado en costos para obtener el mejor tiempo de respuesta. RULE Utilice un enfoque basado en reglas; esto cancela cualquier otra sugerencia especificada para esta declaración. Access Method Oracle Hints: CLUSTER(table) Esto le dice a Oracle que realice un escaneo de clúster para acceder a la tabla. FULL(table) Esto le dice al optimizador que haga un escaneo completo de la tabla especificada. HASH(table) Le dice a Oracle que elija explícitamente el método de acceso hash para la tabla. HASH_AJ(table) Transforma una subconsulta NOT IN en un hash anti-join. ROWID(table) Fuerza un escaneo de ID de fila de la tabla especificada. INDEX(table [index]) Fuerza una exploración de índice de la tabla especificada utilizando los índices especificados. Si se especifica una lista de índices, el optimizador elige el que tiene el costo más bajo. Si no se especifica ningún índice, el optimizador elige el índice disponible para la tabla con el costo más bajo. INDEX_ASC (table [index]) Igual que INDEX solo realiza una búsqueda ascendente del índice elegido, esto es funcionalmente idéntico a la instrucción INDEX. INDEX_DESC(table [index]) Igual que ÍNDICE excepto que realiza una búsqueda descendente. Si se accede a más de una tabla, se ignora. INDEX_COMBINE(table index) Combina los índices de mapa de bits en la tabla si el costo muestra que hacerlo daría un mejor rendimiento. INDEX_FFS(table index) Realice un escaneo rápido de índice completo en lugar de un escaneo de tabla. MERGE_AJ (table) Transforma una subconsulta NOT IN en una combinación anticombinación. AND_EQUAL(table index index [index index index]) Esta sugerencia provoca una fusión en varios índices de una sola columna. Dos deben ser especificados, cinco pueden ser. NL_AJ Transforma una subconsulta NOT IN en un anti-join NL (bucle anidado). HASH_SJ(t1, t2) Insertado en la subconsulta EXISTS; Esto convierte la subconsulta en un tipo especial de unión hash entre t1 y t2 que conserva la semántica de la subconsulta. Es decir, incluso si hay más de una fila coincidente en t2 para una fila en t1, la fila en t1 se devuelve solo una vez. MERGE_SJ (t1, t2) Insertado en la subconsulta EXISTS; Esto convierte la subconsulta en un tipo especial de combinación de combinación entre t1 y t2 que conserva la semántica de la subconsulta. Es decir, incluso si hay más de una fila coincidente en t2 para una fila en t1, la fila en t1 se devuelve solo una vez. NL_SJ Insertado en la subconsulta EXISTS; Esto convierte la subconsulta en un tipo especial de combinación de bucle anidado entre t1 y t2 que conserva la semántica de la subconsulta. Es decir, incluso si hay más de una fila coincidente en t2 para una fila en t1, la fila en t1 se devuelve solo una vez. Oracle Hints for join orders and transformations:
ORDERED Esta sugerencia obliga a unir las tablas en el orden especificado. Si sabe que la tabla X tiene menos filas, ordenarla primero puede acelerar la ejecución en una combinación. STAR Obliga a la tabla más grande a unirse en último lugar mediante una unión de bucles anidados en el índice. STAR_TRANSFORMATION Hace que el optimizador use el mejor plan en el que se usa una transformación de inicio. FACT(table) Al realizar una transformación de estrella, utilice la tabla especificada como tabla de hechos. NO_FACT(table) Al realizar una transformación de estrella, no utilice la tabla especificada como tabla de hechos. PUSH_SUBQ Esto hace que las subconsultas no fusionadas se evalúen en el punto más temprano posible del plan de ejecución. REWRITE(mview) Si es posible, obliga a la consulta a utilizar la vista materializada especificada; si no se especifica ninguna vista materializada, el sistema elige lo que calcula que es la vista adecuada. NOREWRITE Desactiva la reescritura de consultas para la declaración, utilícela cuando los datos devueltos deben ser concurrentes y no pueden provenir de una vista materializada. USE_CONCAT Obliga a que las condiciones OR combinadas y el procesamiento IN en la cláusula WHERE se transformen en una consulta compuesta mediante el operador de conjunto UNION ALL. NO_MERGE (table) Esto hace que Oracle una cada tabla especificada con otra fuente de fila sin una combinación de ordenación y combinación. NO_EXPAND Previene la expansión del procesamiento OR e IN. Oracle Hints for Join Operations:
USE_HASH (table) Esto hace que Oracle una cada tabla especificada con otra fuente de fila con una unión hash. USE_NL(table) Esta operación fuerza un bucle anidado utilizando la tabla especificada como tabla de control. USE_MERGE(table,[table, - ]) Esta operación fuerza una operación de ordenación, fusión y unión de las tablas especificadas. DRIVING_SITE La sugerencia obliga a que la ejecución de la consulta se realice en un sitio diferente al seleccionado por Oracle. Esta sugerencia se puede usar con optimización basada en reglas o basada en costos. LEADING(table) La sugerencia hace que Oracle use la tabla especificada como la primera tabla en el orden de combinación. Oracle Hints for Parallel Operations:
[NO]APPEND Esto especifica que los datos se agregarán o no al final de un archivo en lugar de en el espacio libre existente. Úselo solo con los comandos INSERT. NOPARALLEL (table Esto especifica que la operación no debe realizarse en paralelo. PARALLEL(table, instances) Esto especifica que la operación se realizará en paralelo. PARALLEL_INDEX Permite la paralelización de un escaneo rápido de índice completo en cualquier índice. Other Oracle Hints: CACHE Especifica que los bloques recuperados para la tabla en la sugerencia se colocan en el extremo utilizado más recientemente de la lista LRU cuando la tabla se explora por completo. NOCACHE Especifica que los bloques recuperados para la tabla en la sugerencia se colocan en el extremo menos usado recientemente de la lista LRU cuando la tabla se escanea por completo. [NO]APPEND Para las operaciones de inserción, se agregarán (o no se agregarán) los datos en el HWM de la tabla. UNNEST Activa la opción UNNEST_SUBQUERY para la declaración si el parámetro UNNEST_SUBQUERY se establece en FALSO. NO_UNNEST Desactiva la opción UNNEST_SUBQUERY para la declaración si el parámetro UNNEST_SUBQUERY se establece en TRUE. PUSH_PRED Inserta el predicado de combinación en la vista.

image.png

Sugerencias (hint) del optimizador Cuando invoca un comando DELETE, INSERT, SELECT o UPDATE, el servidor genera un conjunto de planes de ejecución; después de analizar esos planes de ejecución, el servidor selecciona un plan que (generalmente) devolverá el conjunto de resultados en la menor cantidad de tiempo. La elección del plan por parte del servidor depende de varios factores:

● El costo de ejecución estimado de las operaciones de manejo de datos.

● Valores de parámetros asignados a parámetros en la sección Ajuste de consulta del archivo postgresql.conf.

● Estadísticas de columna recopiladas por el comando ANALYZE.

Como regla general, el planificador de consultas seleccionará el plan menos costoso. Puede usar una sugerencia de optimizador para influir en el servidor mientras selecciona un plan de consulta.

Una sugerencia de optimizador es una directiva (o directivas múltiples) incrustadas en una sintaxis similar a un comentario que sigue inmediatamente a un comando ELIMINAR, INSERTAR, SELECCIONAR o ACTUALIZAR. Las palabras clave en el comentario indican al servidor que emplee o evite un plan específico al producir el conjunto de resultados.

Sinopsis

{ ELIMINAR | INSERTAR | SELECCIONAR | ACTUALIZAR } /*+ { pista [ comentario ] } [...] */
  declaración_cuerpo

{ ELIMINAR | INSERTAR | SELECCIONAR | ACTUALIZAR } --+ { pista [ comentario ] } [...]
declaración_cuerpo Las sugerencias del optimizador se pueden incluir en cualquiera de los formularios que se muestran arriba. Tenga en cuenta que en ambas formas, un signo más (+) debe seguir inmediatamente a los símbolos de comentario de apertura /* o --, sin espacios intermedios, o el servidor no interpretará los siguientes tokens como sugerencias.

Si está utilizando el primer formulario, la sugerencia y el comentario opcional pueden abarcar varias líneas. La segunda forma requiere que todas las sugerencias y comentarios ocupen una sola línea; el resto de la declaración debe comenzar en una nueva línea.

5 - Con base en el archivo adjunto diseñe un diagrama entidad relación que permita cargar la información normalizada.
Las tablas de dimensiones describen las entidades comerciales, las cosas que modela. Las entidades pueden incluir productos, personas, lugares y conceptos, incluido el tiempo mismo. La tabla más consistente que encontrará en un esquema en estrella es una tabla de dimensión de fecha. Una tabla de dimensiones contiene una columna (o columnas) clave que actúa como un identificador único y columnas descriptivas.

Las tablas de hechos almacenan observaciones o eventos y pueden ser órdenes de venta, saldos de existencias, tipos de cambio, temperaturas, etc. Una tabla de hechos contiene columnas de clave de dimensión que se relacionan con tablas de dimensión y columnas de medidas numéricas. Las columnas de clave de dimensión determinan la dimensionalidad de una tabla de hechos, mientras que los valores de clave de dimensión determinan la granularidad de una tabla de hechos. Por ejemplo, considere una tabla de hechos diseñada para almacenar objetivos de venta que tiene dos columnas de clave de dimensión Fecha y Clave de producto. Es fácil entender que la mesa tiene dos dimensiones. Sin embargo, la granularidad no se puede determinar sin tener en cuenta los valores clave de la dimensión. En este ejemplo, considere que los valores almacenados en la columna Fecha son el primer día de cada mes. En este caso, la granularidad es a nivel mes-producto.

Generalmente, las tablas de dimensiones contienen un número relativamente pequeño de filas. Las tablas de hechos, por otro lado, pueden contener una gran cantidad de filas y seguir creciendo con el tiempo.

image.png

image.png

Apache Spark es un motor de análisis unificado de código abierto para el procesamiento de datos a gran escala. Spark proporciona una interfaz para programar clústeres con paralelismo de datos implícito y tolerancia a fallas.

image.png

image.png

!apt-get install openjdk-8-jdk-headless -qq > /dev/null
!wget -q https://archive.apache.org/dist/spark/spark-3.0.0/spark-3.0.0-bin-hadoop3.2.tgz
!tar -xvf spark-3.0.0-bin-hadoop3.2.tgz
import os
os.environ["JAVA_HOME"] = "/usr/lib/jvm/java-8-openjdk-amd64"
os.environ["SPARK_HOME"] = "/content/spark-3.0.0-bin-hadoop3.2"
Instalando FindSpark
!pip install -q findspark

# tornar o pyspark "importável"
import findspark
findspark.init('spark-3.0.0-bin-hadoop3.2')
Importando as bibliotecas do PySpark
%time 

from pyspark import SparkContext, SparkConf
from pyspark.sql import SQLContext, SparkSession
from pyspark.streaming import StreamingContext
from pyspark.sql.types import StructType, StructField, DoubleType, IntegerType, StringType
%time 
ss = SparkSession.builder.master("local[*]").getOrCreate()
sc = SparkContext.getOrCreate(SparkConf().setMaster("local[*]"))
sql_sc = SQLContext(sc)
ssc = StreamingContext(sc, 2)
from pyspark.sql import SparkSession

spark = SparkSession \
    .builder \
    .appName("Python Spark create RDD example") \
    .config("spark.some.config.option", "some-value") \
    .getOrCreate()
https://docs.google.com/spreadsheets/d/1oC1LYWCFXxhZzBf898iJsu1p5-2J8gA9YlMMq4GhmdA/edit?usp=sharing

dfcsv = spark.read.csv('/content/20210627_DATASET.CSV', header=True, inferSchema=True, sep=";", nullValue=True, encoding="utf-8")
dfcsv.show(100)
¡Conversión a parquet!
image.png

schema = StructType([
            StructField("CERTIFICADO", StringType(), True),
            StructField("PRODUCTO", StringType(), True),
            StructField("DOCUMENTO", StringType(), True),
            StructField("TIPO_DE_DOCUMENTO", StringType(), True),
            StructField("NOMBRE", StringType(), True),
            StructField("APELLIDO", StringType(), True),
            StructField("DIRECCION", StringType(), True),
            StructField("TELEFONO", StringType(), True),
            StructField("BARRIO", StringType(), True),
            StructField("CIUDAD", StringType(), True),
            StructField("ESTADO_CERTIFICADO", StringType(), True),
            StructField("FECHA_EMISION_POLIZA", StringType(), True),
            StructField("CIUDAD_EMISION", StringType(), True),
            StructField("DEPARTAMENTO_EMISION", StringType(), True),
            StructField("CIUDA_NACIMIENTO", StringType(), True),
            StructField("DEPARTAMENTO_NACIMIENTO", StringType(), True),
            StructField("FECHA_SINIESTRO", StringType(), True),
            StructField("IDENTIFICADOR_SINIESTRO", StringType(), True),
            StructField("ESTADO_SINIESTRO", StringType(), True)])
rdd = sc.textFile("/content/20210627_DATASET.CSV").map(lambda line: line.split(";"))
dfparquet = sql_sc.createDataFrame(rdd, schema)
dfparquet.write.parquet('/content/20210627_DATASET')
parDF=spark.read.parquet('/content/20210627_DATASET')
parDF.printSchema()
parDF.show()
parDF.createOrReplaceTempView("view")
parDF.show()
parDF = sql_sc.sql("SELECT ESTADO_CERTIFICADO, DOCUMENTO, NOMBRE, APELLIDO, to_date(FECHA_SINIESTRO, 'dd/MM/yyyy') AS FECHA_SINIESTRO FROM view WHERE ESTADO_CERTIFICADO LIKE 'V' AND FECHA_SINIESTRO BETWEEN '01/01/2000' AND '31/12/2000' GROUP BY ESTADO_CERTIFICADO, DOCUMENTO,NOMBRE,APELLIDO,FECHA_SINIESTRO")
parDF.show()
parDF.createOrReplaceTempView("viewREsult")
parDF.show(100)
parDF = sql_sc.sql("SELECT COUNT(DOCUMENTO), ESTADO_CERTIFICADO, DOCUMENTO, NOMBRE AS NOMBRE, APELLIDO AS APELLIDO FROM viewREsult GROUP BY ESTADO_CERTIFICADO, DOCUMENTO, NOMBRE, APELLIDO HAVING COUNT(DOCUMENTO) > 1")
parDF.show(100)
# 6 - ¿Defina que es gobierno de datos? ¿Qué partes tiene?
image.png

El gobierno de datos consiste en la capacidad de una organización para gestionar el conocimiento que tiene sobre su información de forma que pueda responder a preguntas tales como ¿qué sabemos sobre nuestra información?, ¿de dónde provienen esos datos?, ¿están estos datos alineados con nuestra política de empresa?

El gobierno de datos proporciona un enfoque holístico para administrar, mejorar y aprovechar la información de forma que pueda ayudarnos a ganar percepción y generar confianza en decisiones y operaciones empresariales.

La importancia clave del gobierno de datos
Lograr una buena gobernabilidad y gestión de datos empresariales implica abordar la gestión de los datos como lo que son en realidad, un activo de gran valor tanto a nivel operativo como para crear valor de mercado y convertirlos en una información crítica para el negocio. Tal y como señala David Newman, vicepresidente de investigación de Gartner, "un alto porcentaje de organizaciones de todo el mundo se dedican a la gestión y desarrollo de los datos como un activo de la empresa". Esa óptima gestión de datos clave para el éxito empresarial requiere de un marco que acoja un gobierno de datos, entendido como el ejercicio de diseñar, controlar y monitorizar todo lo relativo a los datos desde un enfoque holístico, en el que participen los implicados, desde el gobierno corporativo de la empresa y el departamento de TI hasta un consejo de gestión de datos que represente a las partes interesadas.

La función de gobierno de datos es conseguir que todas las funciones de datos se realicen del modo más eficiente, cumpliendo con lo planeado. Se trata, en suma, de asegurar que los datos cumplen con las demandas, al tiempo que se consigue una reducción de costes en lo que respecta a su gestión y a su protección, éste último un aspecto importante en lo que respecta al cumplimiento de normativas y a la preservación de la privacidad.

Por qué es necesario un gobierno de datos
"Los datos son el activo más importante de un organización y, sin normas y sin calidad de datos, la organización no funciona", apunta Valeh Nazemoff, vicepresidente senior y coofundador de Acolyst. No en vano, la misma necesidad de aplicar una política de data governance demuestra la importancia y el valor de los datos dentro de la organización.

David Waddington, vicepresidente senior y cofundador de The Information Difference Ldt. centra las ventajas que aporta implementar una gobernabilidad de datos en nueve aspectos, que resumimos a continuación:

Apoyar las iniciativas de BI/Data Warehousing.

Apoyar una iniciativa MDM.

Facilitar la migración de datos heredados.

Cumplir con la normativa y requisitos legislativos.

Reducir el riesgo empresarial.

Mejorar la flexibilidad empresarial y la agilidad de negocio.

Apoyar actualizaciones de software operativo.

Reducir los costos.

Apoyar el manejo de fusiones y adquisiciones.

Todas ellas, qué duda cabe, son interesantes razones que, por si solas o en conjunto, justifican el gobierno de datos. Además de éstas, destacamos las siguientes:

Accesibilidad de los datos: Conseguimos una mayor accesibilidad de los datos que, a su vez, serán oportunos y confiables, siempre en función de la política definida y de un significado global.

Asegurar que los datos cumplen con las demandas: Alude a la oportunidad y calidad de los datos como resultado de la aplicación de un proyecto de gobierno de datos.

Gestionar los datos como un activo: La gestión y desarrollo de los datos como un activo ayudará a satisfacer a usuarios internos y clientes, así como a tomar mejores y más rápidas decisiones, pues contaremos con información confiable y accesible cuando la necesitemos.

Asegurar la integridad: El gobierno de datos evita y previene incoherencias entre distintos sistemas o aplicaciones, con la ventaja que, por ejemplo, ello supone para que no falten datos a la hora de operar, de hacer evaluaciones o de ofrecer un determinado servicio o información.

Responder a las demandas actuales: Establecer un marco para la gobernanza de datos nos ayuda a conseguir una mayor disponibilidad, facilidad de uso, consistencia, integridad y seguridad de los datos, requisitos clave para apoyar las iniciativas más actuales de BI, que normalmente requieren aplicaciones rápidas, con un acceso en tiempo real a los datos.

Agregar valor: Un plan de data governance, por último, ayuda a definir y establecer los diferentes tipos de comunicación necesaria para agregar valor a la organización a partir de una visión global capaz de transformar el negocio en su conjunto. Los equipos de gestión podrán tomar decisiones informadas basadas en datos más fiables. No olvidemos que la información crítica es relevante, si no esencial, para tomar decisiones.

7 - ¿Defina que es calidad de datos? ¿Cuáles son los criterios mínimos para tener un dato de calidad?
Calidad de datos
Es la cualidad de un conjunto de información recogida en una base de datos, un sistema de información o un data warehouse que reúne entre sus atributos la exactitud, completitud, integridad, actualización, coherencia, relevancia, accesibilidad y confiabilidad necesarias para resultar útiles al procesamiento, análisis y cualquier otro fin que un usuario quiera darles.

¿Cuáles son los atributos de la calidad de la información?
Precisa (Accurate) Que la información debe ser precisa y exacta parece obvio. Pero en la práctica, los datos utilizados para diferentes propósitos requieren diferentes niveles de precisión. En los sistemas de inteligencia empresarial se producen constantemente problemas relacionados con la inexactitud. Es un problema de calidad de la información bien conocido, al cual los profesionales de sistemas de información se enfrentan desde el diseño de sistemas hasta la implementación y el mantenimiento.

Completa (Complete) La información incompleta puede provocar una toma de decisiones errónea. Pero tenemos el problema de que una información completa para una persona podría ser incompleta para otra. Por ejemplo, el vicepresidente de marketing y el director de investigación y desarrollo de una compañía farmacéutica pueden estar interesados en pruebas de ensayos clínicos de un nuevo fármaco, pero cada uno pueden requerir diferentes niveles de detalle. Se trata de algo a tener en cuenta al fijar los objetivos de calidad de la información.

Compatible (Compatible) La calidad de la información se encuentra no sólo en la información en sí misma, sino también en la forma en que se puede combinar con otra información. Esto ocurre a menudo cuando la información implica a varios sistemas que trabajan juntos, en una integración de datos, por ejemplo. En estos casos es importante disponer de una arquitectura de la información adecuada con una estructura dinámica que pueda crecer junto a las necesidades del cliente.

Orientada al usuario (User-targeted) La información debe ser comunicada en un estilo, formato, detalle y complejidad, que sea compatible con las necesidades de los usuarios de esa información. Por ejemplo, unos altos directivos pueden necesitar unos breves informes que les permitan comprender la rentabilidad del negocio a simple vista, mientras que los gerentes de operaciones pueden necesitar información más detallada que les permita una correcta toma de decisiones diaria.

Relevante (Relevant) El componente clave para la calidad de la información es que la información se dirija a las personas adecuadas. Si no es así, quien reciba la información pensará que ésta no es relevante para sus necesidades y la desechará. Esto no quiere decir que la información irrelevante para alguien es información es de baja calidad. Simplemente indica que la información no se ha dirigido a la persona que puede darle uso.

Accesible (Accessible) La información accesible es la información que se puede obtener cuando es necesaria. La accesibilidad depende de quien la tiene que recibir y también de las circunstancias específicas en un momento dado. Para una buena calidad de la información la puntualidad y la accesibilidad deben complementarse entre sí. Aplicaciones para el control de movimientos bancarios o de tarjetas de crédito y las de inversión en bolsa, son ejemplos de la importancia de esta característica.

Oportuna (Timely) Lo acabamos de apuntar. La información oportuna o puntual es la que todavía es útil. Es actual. La información tiene un tiempo de vida que depende de la rapidez con que nueva información puede ser procesada y comunicada sustituyendo a la anterior. La puntualidad de la información va de la mano de la exactitud de la información.

Fácil de usar (Easy to use) La información debe ser comprensible para los usuarios. El formato y la estructura deben ser usados teniendo en cuenta quien es el receptor.

8 - Defina la importancia de la calidad de los datos.
Calidad de datos es la cualidad de un conjunto de información recogida en una base de datos, un sistema de información o un data warehouse que reúne entre sus atributos la exactitud, completitud, integridad, actualización, coherencia, relevancia, accesibilidad y confiabilidad necesarias para resultar útiles al procesamiento, análisis y cualquier otro fin que un usuario quiera darles.

A nivel ejecutivo, cada vez es más importante para los directores de empresas de cualquier tamaño no solo poseer datos sino, sobre todo, disponer de información fiable que les permita tomar mejores decisiones. Al mismo tiempo, la toma de decisiones basadas en la información y, a nivel tecnológico, en la liberación del dato, aconseja organigramas adaptados, lo cual suele implicar una significativa transformación organizacional hacia un enfoque data driven.

Sea cual fuere el organigrama empresarial, los datos confiables son esenciales tanto para tomar decisiones estratégicas acertadas, basadas en los datos, como para la buena marcha de la empresa a nivel operativo, tanto interna como externamente. Sin embargo, lograrlo requiere de un importante trabajo que, sin lugar a dudas, bien merece el esfuerzo.

9 - Menciones tres atributos relacionados con la Calidad de los datos.
Exactitud

Integridad

Actualización

Relevancia

Coherencia

Confiabilidad

Presentación apropiada

Accesibilidad

10 - Establezca un proceso técnico sencillo para la estandarización y mejora de una base de clientes para analizar los datos y darles remediación conforme a los atributos de data Quality.
Integridad La integridad mide el nivel de manipulación de los datos debido a, normalmente, errores de transcripción, como los redondeos en las cifras o una precipitada limpieza por parte de profesionales sin las habilidades necesarias. Las estrategias de automatización de la recogida, almacenamiento y gestión de la información de los data engineers ayudan a evitar este tipo de pérdidas de calidad.

Fiabilidad Los datos deben reflejar una recogida de inputs estable y consistente a lo largo del tiempo. La fiabilidad es importante para que los cambios en los datos sean reconocidos como tales y no como una modificación intencionada en el proceso de recolección.

Validez La validez mide la calidad de la información obtenida en función de cómo los datos representan aquello que se quiere estudiar o si los análisis y las conclusiones pueden responder a las preguntas deseadas.

Puntualidad La puntualidad refleja la relevancia de los datos en el momento en que se analizan. La recogida y el análisis de la información deben hacerse en las fechas adecuadas, y es importante tener en cuenta de cara a la toma de decisiones que los datos desfasados no siempre serán útiles.

Eficacia La eficacia es la relación entre los datos y los errores. Podemos considerar como errores las entradas en la base de datos con partes incompletas o redundantes, las entradas repetidas, los caracteres extraños o la información corrupta.

Completitud La completitud está relacionada con el atributo anterior y hace referencia al número de valores vacíos que aparecen en un conjunto de datos. Los data scientists tienen que borrar a menudo las entradas en las bases de datos con algún campo sin información para que no se alteren los resultados del análisis, así que cuantos menos valores desconocidos aparezcan, mejor.

Estabilidad La estabilidad mide el índice de error en la transformación de los datos. Los cambios de formato y las migraciones de la información muchas veces conllevan modificaciones inesperadas y no deseadas que pueden invalidar el análisis final.

Oscuridad Los datos oscuros son aquellos que se recopilan, procesan y almacenan como parte de las actividades comerciales cotidianas, pero que no se utilizan en los análisis, a pesar del espacio que ocupan en memoria y de los recursos que se deben destinar para su recolección y mantenimiento.

11 - Mencione lo más importante a tener en cuenta en una herramienta de data Quality.
Las herramientas de calidad de datos ayudan a las organizaciones a garantizar datos precisos y presentarlos con coherencia. Sus funciones incluyen verificación automatizada de direcciones de clientes, deduplicación de datos y correspondencia de datos.

12 - Mencione 3 herramientas informáticas posibles pata el seguimiento y presentación de indicadores de Calidad de Datos.
PieSync Este software ofrece una solución de integración específicamente para datos de clientes. Tener datos de contactos aislados es una de las amenazas más comunes para la calidad de datos. Dado que PieSync funciona de manera bidireccional y en tiempo real, ayuda a los administradores de datos a garantizar la coherencia, integridad, precisión y accesibilidad de los datos del cliente con una configuración muy sencilla.

SAS Es una suite de software con diferentes productos para administrar, mejorar, integrar y gobernar datos. Uno de sus productos mejor valorados es SAS Data Management, diseñado para gestionar la integración y limpieza de datos. También proporciona formas poderosas de implementar la gobernanza de datos. Además ofrece SAS Data Quality como una solución para abordar problemas de calidad sin la necesidad de moverlos.

Talend Open Studio Es parte de una suite de código abierto. Además de contar con muchas funciones para resolver problemas de integración, también es muy flexible y fácil de usar. Las empresas medianas ahorran gran tiempo con las opciones de «arrastrar y soltar» del software.

OpenRefine Anteriormente era Google Refine. Esta herramienta gratuita de código abierto es ideal para administrar y limpiar datos. Se centra en transformar y reformatear datos dispares para estandarizarlos. Este software te permite agregar innumerables extensiones y complementos para que puedas trabajar con muchas fuentes y formatos de datos. La utilizan empresas de todos los tamaños.