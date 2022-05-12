Reseña la historia de SQL.

    El Dr. EF Codd publicó el artículo, "Un modelo relacional de datos para grandes bancos de datos compartidos", en junio de 1970 en la revista Communications of the ACM de la Asociación de Maquinaria Informática (ACM) . El modelo de Codd ahora se acepta como el modelo definitivo para los sistemas de administración de bases de datos relacionales (RDBMS). El lenguaje de consulta en inglés estructurado (SEQUEL) fue desarrollado por IBM Corporation, Inc., para utilizar el modelo de Codd. SEQUEL más tarde se convirtió en SQL (todavía se pronuncia "secuela"). En 1979, Relational Software, Inc. (ahora Oracle) presentó la primera implementación comercial de SQL. Hoy en día, SQL se acepta como el lenguaje RDBMS estándar.
    Las primeras bases de datos informáticas aparecieron a finales de la década de 1960, En su artículo, Codd propuso una idea completamente nueva: modelar datos con la noción matemática de relaciones. (Hoy los llamamos tablas). El modelo de datos relacionales de Codd permitió una mayor flexibilidad que los modelos de datos jerárquicos y de red. Se pueden agregar nuevas relaciones sin modificar las relaciones existentes. En principio el modelo de Codd IBM no estaba ansioso por implementar sus sugerencias. En ese momento, tenían IMS , una base de datos jerárquica muy exitosa. 
    Dos cosas fueron importantes para Chamberlin y Boyce en el diseño de SEQUEL. En primer lugar, querían que fuera accesible para usuarios habituales sin conocimientos matemáticos o de programación. El personal de System R incluso reclutó a un grupo de estudiantes para aprender SEQUEL y ver si encontraban fácil la sintaxis. Además, querían que el lenguaje contuviera elementos de modificación y definición de datos, algo muy nuevo en ese momento.

Ejemplifica los Gestores de Bases de Datos según el tipo de BD.

     I- MySQL
    Es el sistema gestor de bases de datos relacional por excelencia. Es un SGBD multihilo y multiusuario utilizado en la gran parte de las páginas web actuales. Además  es el más usado en aplicaciones creadas como software libre.
    Las principales ventajas de este Sistema Gestor de Bases de datos son:
    °-Facilidad de uso y gran rendimiento
    °-Facilidad para instalar y configurar
    °-Soporte multiplataforma
    °-Soporte SSL
    La principal desventaja es la escalabilidad, es decir, no trabaja de manera eficiente con bases de datos muy grandes que superan un determinado tamaño.
    
    II-MariaDB
    Este SGBD es una derivación de MySQL que cuenta con la mayoría de características de este e incluye varias extensiones.
    Entre las principales características de este Sistema Gestor de Bases de datos se encuentran:
    °-Aumento de motores de almacenamiento
    °-Gran escalabilidad
    °-Seguridad y rapidez en transacciones
    °-Extensiones y nuevas características relacionadas con su aplicación para Bases de datos NoSQL.
    
    III-SQLite
    Más que un Sistema Gestor de bases de datos como tal, SQLite es una biblioteca escrita en C que implementa un SGBD y que permite transacciones sin necesidad de un servidor ni configuraciones.
    Las principales características de SQLite son:
    °-El tamaño, al tratarse de una biblioteca, es mucho menor que cualquier SGBD
    °-Reúne los cuatro criterios ACID (Atomicidad, Consistencia, Aislamiento y Durabilidad) logrando gran estabilidad
    °-Gran portabilidad y rendimiento
    La gran desventaja de SQLite es la escalabilidad ya que no soporta bases de datos que sean muy grandes.
    
    IV-PostgreSQL
    Este sistema gestor de base de datos relacional está orientado a objetos y es libre, publicado bajo la licencia BSD.
    Sus principales características son:
    °-Control de Concurrencias multiversión (MVCC)
    °-Flexibilidad en cuanto a lenguajes de programación
    °-Multiplataforma
    °-Dispone de una herramienta (pgAdmin, https://www.pgadmin.org/) muy fácil e intuitiva para la administración de las bases de datos.
    °-Robustez, Eficiencia y Estabilidad.
    La principal desventaja es la lentitud para la administración de bases de datos pequeñas ya que está optimizado para gestionar grandes volúmenes de datos.
    
    V-Microsoft SQL Server
    Es un sistema gestor de bases de datos relacionales basado en el lenguaje Transact-SQL, capaz de poner a disposición de muchos usuarios grandes cantidades de datos de manera simultánea.
    °-Soporte exclusivo por parte de Microsoft.
    °-Escalabilidad, estabilidad y seguridad.
    °-Posibilidad de cancelar consultas.
    °-Potente entorno gráfico de administración que permite utilizar comandos DDL y DML.
    °-Aunque es nativo para Windows puede utilizarse desde hace ya un tiempo en otras plataformas como Linux o Docker.
    Su principal desventaja es el precio. Cuenta con un plan gratuito (Express) pero lo normal es la elección de alguno de los planes de pago disponibles (Standard,    Developer, Enterprise o SQL Azure, la versión de SQL Server en la nube).
    
    VI-Oracle
    Tradicionamente, Oracle ha sido el SGBD por excelencia para el mundo empresarial, considerado siempre como el más completo y robusto, destacando por:
    °-Soporte de transacciones.
    °-Estabilidad.
    °-Escalabilidad.
    °-Multiplataforma.
    La principal desventaja, al igual que SQL Server, es el coste del software ya que, aunque cuenta con una versión gratuita (Express Edition o XE), sus principales opciones son de pago.
    
    VIII-MongoDB
    Estamos ante el Sistema Gestor de Bases de Datos no relacionales (SGBD NoSQL) más popular y utilizado actualmente. MongoDB es un SBGD NoSQL orientado a ficheros que almacena la información en estructuras BSON con un esquema dinámico que permite su facilidad de integración.
    Las principales características de MongoDB son:
    °-Indexación y replicación
    °-Balanceo de carga
    °-Almacenamiento en ficheros
    °-Consultas ad hoc
    °-Escalabilidad horizontal
    °-Open Source
    Como desventaja principal, MongoDB no es un SGBD adecuado para realizar transacciones complejas.
    
    IX-Redis
    Redis está basado en el almacenamiento clave-valor. Podríamos verlo como un vector enorme que almacena todo tipo de datos, desde cadenas, hashses, listas, etc. El principal uso de este SGBD es para el almacenamiento en memoria caché y la administración de sesiones.
    Las características principales son:
    °-Atomicidad y persistencia
    °-Gran velocidad
    °-Simplicidad
    °-Multiplataforma
    
    x-Cassandra
    Al igual que Redis, Cassandra también utiliza almacenamiento clave-valor. Es un SGBD NoSQL distribuido y masivamente escalable.
    Dispone de un lenguaje propio para las consultas denominado CQL (Cassandra Query Languaje).
    Las principales características de este SGBD NoSQL son:
    °-Multiplataforma
    °-Propio lenguaje de consultas (CQL)
    °-Escalado lineal y horizontal
    °-Es un SGBD distribuido
    °-Utiliza una arquitectura peer-to-peer
    

