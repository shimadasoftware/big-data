# <img src="https://github.com/shimadasoftware/big-data/assets/73977456/311cd96c-6049-464c-a0bb-201c5c272515" alt="Italian Trulli" style="width:30px;height:30px;"> Introducción a Big Data

## Conceptos básicos

![image](/img/piramid.png)

### Datos

Un dato es una representación simbólica (numérica, alfabética, algorítmica, espacial, etc.) de un atributo o variable cuantitativa o cualitativa. Los datos describen hechos empíricos, sucesos y entidades.

![image](/img/relación%20data%20e%20información.png)

### Cuánta información se genera cada día

**Byte** es un término creado por Werner Buchholz en 1957 como una **unidad de información digital** equivalente a cuatro bits (binary digit, dígito binario) originalmente y posteriormente como estándar se adoptó que 1 byte equivale a ocho bits. La palabra byte proviene de bite, que significa mordisco, como la cantidad más pequeña de datos que un ordenador podía "morder" a la vez.

![image](/img/tablaunidades.jpg)

### Tipos de datos

![image](/img/datos%20estructurados%20vs%20no%20estructurados.png)

- **Datos Estructurados:**
  
La gran mayoría de las fuentes de datos tradicionales son originadas por datos del tipo estructurados, datos con formato o esquema fijo, que poseen campos fijos y bien definidos.

![image](/img/datos%20estructurados.png)

- **Datos NO Estructurados:**
  
Son las estructuras de datos más difíciles de manejar, podemos encontrar entre los datos no estructurados más conocidos:

  - Documentos PDF o Word.
  - Audios y videos.
  - Correos electrónicos.
  - Ficheros multimedia de imagen.
  - Artículos y textos, entre otros.

![image](/img/datos%20no%20estructurados.png)

- **Datos Semi Estructurados:**

Son un híbrido entre los datos estructurados y los datos no estructurados, podríamos decir entonces de manera sencilla, que no presentan una estructura
perfectamente definida como los datos estructurados, pero sí presentan una organización definida en sus metadatos donde describen los objetos y sus relaciones.

![image](/img/datos%20no%20estructurados.png)

### Escalamiento

![image](/img/escalamiento.png)

### Problemas actuales con los datos

Surgen nuevos tipos de datos y necesidades que actualmente los sistemas no son suficientemente buenos o adecuados para poder atacar estos problemas pues las
empresas son más exigentes y buscan exprimir al máximo sus recursos para obtener el mayor beneficio. Sería semejante a escuderías de F1 que buscan superar al rival buscando la diferencia hasta en los grados de regulación de un alerón, analizando y optimizando al mayor detalle.

- **Tipos de datos (variedad)**

  - Han surgido nuevos tipos de datos que se quieren almacenar: datos no estructurados.
  - Las BD Relacionales no pueden almacenar este tipo de datos.

- **Escalabilidad**

  - En búsqueda de la rapidez y rendimiento en consultas o procesamiento de datos se busca escalar siempre en horizontal.

- **Modelo relacional**
  
  - El modelo relacional no da soporte para todos los problemas. No podemos atacar todos los problemas con el mismo enfoque, queremos optimizar al 100% nuestro sistema y no podemos ajustar nuestros sistemas a estas BD.

- **Velocidad**

  - Esta es una de las "3 V's" del Big Data (velocidad, variedad, volumetría). La velocidad de generación de datos hoy en día es muy elevada, simplemente hay que verlo con las redes sociales actuales, aunque las empresas medias y muchas de las grandes no se ven afectadas por ello.

### Big Data

Existen muchas definiciones de Big Data.

- Big data es una coleccién de datos grande, complejos, muy dificil de procesar a través de herramientas de gestión y procesamiento de datos tradicionales.

- “Big Data” son datos cuyo volumen, diversidad y complejidad requieren nueva arquitectura, técnicas, algoritmos y analisis para gestionar y extraer valor y conocimiento oculto en ellos...

- “Volumen masivo de datos, tanto estructurados como no-estructurados, los cuales son demasiado grandes y difíciles de procesar con las bases de datos y el software tradicionales" (ONU, 2012).

- “Es un conjunto de datos cuyo tamaño está más allá de la capacidad de la mayoría de los software utilizados para capturar, gestionar y procesar la información dentro de un lapso tolerable de tiempo.”

- “Datos masivos es un término que hace referencia a una cantidad de datos tal que supera la capacidad del software habitual para ser capturados, gestionados y procesados en un tiempo razonable.”

- El término “Big Data” ha sido vapuleado en los últimos años bajo la acusación de que los de Marketing y los Analistas han estirado y comprimido el término para llevarlo a cubrir multitud de problemas, tecnología y productos. Sin embargo en esencia Big Data sigue siendo lo mismo que planteó Doug Laney en 2001, las tres Uves, Volumen, Velocidad y Variedad y sigue señalando desafíos que exigen recursos y procesos de computación no-habituales. (Seth Grimes, Alta Plana Corporation).

### Características de Big Data

- **Escalabilidad lineal:** es decir, que permita aumentar la capacidad de procesamiento linealmente añadiendo nuevo hardware de forma ilimitada.

- **Tolerancia a fallos:** de tal forma que si uno o varios nodos se averían, el sistema siga funcionando sin pérdida de disponibilidad ni pérdida de ningún dato.

- **Despliegue sobre hardware económico de propósito general:** (inexpensive commodity hardware) que permita la creacion de granjas de servidores con un numero elevado de nodos con unos costes sostenidos. También tienen que permitir el despliegue en Cloud (cada vez mas habitual sobre todo en startups).

- **Procesamiento distribuido y localidad de los datos:** entendido como la ejecucidén de los procesos analiticos se realizan lo mas cercanos de donde se encuentra el dato almacenado, evitando tanto el trasiego de la informacién como el cuello de botella que puede suponer un almacenamiento centralizado.

![image](/img/traditional%20vs%20bigdata.png)

### Las V en Big Data

![image](/img/big%20data%20v.png)

- **Volume:** grandes volúmenes de información

Se está pasando de hablar en Gigabytes o Terabytes a tamaños de datos de Petabytes, Exabytes o Zettabytes. Volúmenes que se nos escapan.

- **Variety:** información de tipos muy diversos

Ya no solo tenemos información estructurada en Bases de Datos o Archivos. Ahora empezamos a tener información con tipos diferentes y totalmente desestructurada.

- **Velocity:** velocidad con la que se genera la información

La velocidad a la que se genera esta información hace imposible gestionarla con sistemas de base de datos convencionales. Las empresas y las personas ya no quieren estar al día, quieren “estar al segundo”.

- **Veracity:** La veracidad puede entenderse como el grado de confianza que se establece sobre los datos a utilizar

Dentro de la caracterización del Big Data la Veracidad determina su cuarta dimensión, y es de gran importancia para un analista de datos, ya que la veracidad de los mismos determinará la calidad de los resultados y la confianza en los mismos. Por lo tanto un alto volumen de información que crece a velocidad muy rápida y basada en datos estructurados y desestructurados y provenientes de una gran variedad fuentes, hacen inevitable dudar del grado de veracidad de los mismos.

- **Value:** representa el aspecto más relevante del Big Data

Actualmente el valor marginal de los datos se representa mediante la siguiente gráfica. En dicha gráfica se observa que a medida que aumenta el volumen y complejidad de los datos, su valor marginal disminuye considerablemente, debido a su dificultad de explotación.

### Big Data en distintos campos

- Web y Medios Sociales

  - Datos de flujos de Clicks
  - Feeds de Twitter
  - Entradas de Facebook
  - Contenido Web

- Maquina a Maquina

  - Lectura de medidores inteligentes
  - Lecturas RFID (identificación por radiofrecuencia)
  - Lectura sensores de plataformas petroleras
  - Señales de GPS

- Datos de transacciones grandes

  - Demandas de salud
  - Llamadas de Telecomunicaciones
  - Registro de detalles
  - Registros de Facturación

- Biometría

  - Reconocimiento Facial
  - Genética

- Generado por los humanos

- Registros de voz de centros de llamadas
- Correo electrónico
- Registros médicos electrónicos

### Big Data: revolución de la gestión

1. Liderazgo

- Crear equipos comprometidos para dar respuesta de objetivos

2. Gestión del talento

- Nuevos Roles (Científicos de datos )

3. Tecnología

- Hadoop
- NoSQL
- Cloud computing

4. Toma de Decisiones
   
- Definir objetivo a alcanzar
- Construcción de modelos predictivos

5. Cultura corporativa
   
- Desarrollar analíticas que demuestren con sencillez la evaluación del negocio.
- Crear herramientas sencillas usables para cualquier funcionario.
- Desarrollar capacidades necesarias para sacar mejor provecho.

### ¿Qué son los Datos Abiertos (Open Data)?

“Los datos Abiertos (open data) son datos que pueden ser libremente utilizados, reutilizados y redistribuidos por cualquier persona” (ver Open Knowledge Foundation).

Los datos abiertos presuponen su publicación y difusión de información en la Internet, sin limitaciones de acceso ni de uso, compartida en formato electrónico y abierto. El formato abierto permite la combinación de conjuntos de datos de diferentes orígenes, su reutilización y difusión, libremente y de forma automatizada.

¿Cuándo un dato es un dato abierto?

Un dato es considerado abierto cuando existen:

- **Disponibilidad y acceso:** el dato tiene que estar disponible en la Internet (online), integralmente, sin limitaciones de acceso.

- **Reutilización y redistribución:** el dato tiene que ser ofrecido en condiciones y en un formato conveniente, que permitan su reutilización, combinación con conjuntos de datos de diferentes orígenes, su difusión y redistribución. Esto significa que los datos deben ser preferiblemente procesable por maquinas, en formato no-propietario, y no cubierto por licencias que puedan limitar su uso.

- **Participación universal:** el dato tiene que estar disponible sin limitaciones de uso, todos deben poder usar, reutilizar y redistribuir la información, sin discriminación con las áreas de actuación, personas o grupos.

### Formatos de datos abiertos

http://www.navarra.es/home_es/Open-Data/

**Formatos**

La información se publica en formatos de datos estructurados para facilitar que pueda ser utilizada de forma automática por los lenguajes de programación. De esta manera, se intenta cumplir el objetivo de reutilizar al máximo la información publicada.

**Formatos estructurados**

Estos son los formatos más utilizados para publicar los datos:

**XML (eXtensible Markup Language)**

Es un metalenguaje extensible de etiquetas desarrollado por el W3C que permite definir lenguajes para diferentes necesidades. Es el estándar para el intercambio de información estructurada entre diferentes plataformas.

Más información: www.w3.org/standards/xml/core

**CSV (Comma-separated values)**

Valores separados por coma. Los ficheros CSV son un tipo de documento en formato abierto sencillo para representar datos en formato de tabla. Las columnas se separan por comas (o punto y coma) y las filas por saltos de línea.

Más información: tools.ietf.org/html/rfc4180

**RSS (Really Symple Sindication)**

Es un formato XML para la distribución de contenidos de páginas web. Facilita la publicación de información actualizada a los usuarios suscritos a la fuente RSS sin necesidad de usar un navegador, utilizando un software especializado en este formato.

Más información: http://es.wikipedia.org/wiki/RSS

**SHP (Shapefile)**

Shapefile es un formato propietario estándar de datos espaciales, desarrollado por la compañía ESRI, que,almacena tanto la geometría como la información alfanumérica. Este formato no está preparado para almacenar, información topológica.

Más información: http://es.wikipedia.org/wiki/Shapefile

**XLS (Microsoft Office Excel)**
Microsoft Office Excel es un formato propietario de Microsoft que muestra la información en celdas organizadas en filas y columnas, y cada celda contiene datos o fórmulas, con referencias relativas o absolutas a otras celdas.

Más información: http://es.wikipedia.org/wiki/Microsoft_Excel

**JSON (JavaScript Object Notation)**

Es un formato ligero para el intercambio de datos basado en la notación literal de objetos de JavaScript. Su sintaxis es simple, por lo que facilita el tratamiento en los navegadores. Además, su concisión reduce el tamaño de flujo de datos entre cliente y servidor.

Más información: json.org/json-es.html

**RDF (Resource Description Framework)**

Es una especificación del W3C para el modelado de información y la descripción de recursos, que se hace con la forma de sujeto-predicado-objeto. La combinación de RDF con otras herramientas permite añadir significado a las páginas y es una de las tecnologías esenciales para la web semántica.

Más información: www.w3.org/standards/techs/rdf#w3c_all

**ODS (Operational Data Store)**

Es un contenedor de datos activos, es decir operacionales que ayudan al soporte de decisiones y a la operación. Es un formato de archivo abierto y estándar para el almacenamiento de hojas de cálculo que muestra información en celdas organizadas en filas y columnas, y cada celda contiene datos o fórmulas, con referencias relativas o absolutas a otras celdas.

Más información: http://es.wikipedia.org/wiki/ODS

**KML (Keyhole Markup Language)**

Es una gramática XML y un formato de archivo para la creación de modelos y el almacenamiento de funciones geográficas como puntos, líneas, imágenes, polígonos y modelos que se mostrarán principalmente en aplicaciones de mapas. KML es utilizado para compartir lugares e información entre aplicaciones.

Más información: http://es.wikipedia.org/wiki/KML

### NoSQL vs SQL

![image](/img/NoSQL%20vs%20SQL.png)

![image](/img/Nosql%20vs%20sql%20features.png)

NoSQL o **“no solo SQL"**, hace referencia a que dichas bases de datos **difieren** del **modelo clasico RDBMS**, estas son especialmente util cuando una empresa necesita acceder y analizar grandes cantidades de datos o su enfoque arquitectural esta disenado para distribuir los centros de datos y sus esquemas de datos no son fijos.

Un sistema de administración de bases de datos relacionales (RDBMS) es un programa que se usa para crear, actualizar y administrar bases de datos relacionales. Algunos de los RDBMS más conocidos son MySQL, PostgreSQL, MariaDB, Microsoft SQL Server y Oracle Database.

**NoSQL** – "not only SQL” – es una categoría general de sistemas de gestión de bases de datos que difiere de los RDBMS en diferente modos:

– No tienen schemas, no permiten JOINs, no intentan garantizar ACID y escalan horizontalmente.

– Tanto las bases de datos NoSQL como las relacionales son tipos de Almacenamiento Estructurado.

– El término fue acuñado en 1998 por Carlo Strozzi y resucitado en 2009 por Eric Evans.

– Evans sugiere mejor referirse a esta familia de BBDD de nueva generación como “Big Data” mientras que Strozzi considera ahora que NoREL es un mejor nombre

El término fue acuñado en 1998 por Carlo Strozzi y resucitado en 2009 por Eric Evans
– Evans sugiere mejor referirse a esta familia de BBDD de nueva generación como “Big Data” mientras que Strozzi considera ahora que NoREL es un mejor nombre.

La principal diferencia radica en cómo guardan los datos (por ejemplo, almacenamiento de un recibo):

– En una RDBMS tendríamos que partir la información en diferentes tablas y luego usar un lenguaje de programación en la parte servidora para transformar estos datos en objetos de la vida real.

– En NoSQL, simplemente guardas el recibo. NoSQL es libre de schemas, tú no diseñas tus tablas y su estructura por adelantado.

**Características principales de NoSQL**

- Fáciles de usar en clústers de balanceo de carga convencionales, ya que facilitan **escalabilidad horizontal**.

- Guardan **datos persistentes** (no sólo cachés).

- **No tienen esquemas fijos y permite la migración del esquema** sin tener que ser reiniciadas o paradas.

- Suelen tener un **sistema de consultas propio** en vez de usar un lenguaje de consultas estándar.

- Tienen propiedades ACID en un nodo del clúster y son **“eventualmente consistentes”** en el clúster.

**RDBMS vs NoSQL**

- Los RDBMS tradicionales nos permiten definir la estructura de un esquema que demanda reglas rígidas y garantizan ACID

- Las aplicaciones web y sistemas de información modernos presentan desafíos muy distintos a los sistemas empresariales tradicionales (e.j. sistemas bancarios):

  - Datos a escala web
  - Alta frecuencia de lecturas y escrituras
  - Cambios de esquema de datos frecuentes
  - Las aplicaciones sociales (no bancarias) no necesitan el mismo nivel de ACID

- Consecuencia de la aparición de soluciones NoSQL
  - Cassandra, MongoDB, Jackrabbit , CouchDB, BigTable, Dynamo o Neo4j
