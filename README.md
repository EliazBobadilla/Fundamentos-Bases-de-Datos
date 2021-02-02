<div align="center">
  <h1>Fundamentos de Bases de Datos</h1>
</div>

Este repositorio contiene notas  y desarrollo de ejercicios del curso de [Fundamentos de Bases de Datos](https://platzi.com/clases/bd) de [Platzi](https://platzi.com/r/EliazBobadilla).

Si llegas aqui desde [Platzi](https://platzi.com/r/EliazBobadilla), y ya manejas [Git y GitHub](https://platzi.com/clases/git-github/), te recomiendo hacerle un  ```git clone``` para que lo trabajes de forma local.Si no simplemente descarga el codigo fuente en formato *zip*.

**Si este repositorio te ayudo, o simplemente te gusto,considera darle una estrella.**

### Indice
- [Conceptos Básicos y Contexto Histórico](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#CONCEPTOS-BÁSICOS-Y-CONTEXTO-HISTÓRICO)
  - [Historia del almacenamiento de la información](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Historia-del-almacenamiento-de-la-información)
  - [Surgimiento de las bases de datos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Surgimiento-de-las-bases-de-datos)
- [Introducción a las bases de Datos Relacionales](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#INTRODUCCIÓN-A-LAS-BASES-DE-DATOS-RELACIONALES)
  - [Historia de las RDB](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Historia-de-las-RDB)
  - [Entidades y atributos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Entidades-y-atributos)
  - [Entidades del Platziblog](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Entidades-del-Platziblog)
  - [Relaciones](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Relaciones)
    - [Tipos de cardinalidad](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Tipos-de-cardinalidad)
    - [Cardinalidad muchos a muchos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Cardinalidad-muchos-a-muchos)
  - [Diagrama ER](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Diagrama-ER)
  - [Tipos de datos y constraints](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Tipos-de-datos-y-constraints)
    - [Datos de texto](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Datos-de-texto)
    - [Datos numéricos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Datos-numéricos)
    - [Datos de fecha y hora](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Datos-de-fecha-y-hora)
    - [Datos lógicos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Datos-lógicos)
    - [Los constraints](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Los-constraints)
  - [La Normalización](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#La-Normalización)
    - [Normalizacion de Platziblog](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Normalizacion-de-Platziblog)
- [RDBMS (MySQL)](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#RDBMS-(MySQL))
  - [RDB ¿Qué?](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#RDB-¿Qué?)
  - [Clientes gráficos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Clientes-gráficos)
  - [Servicios administrados](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Servicios-administrados)
- [SQL hasta en la sopa](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#SQL-hasta-en-la-sopa)
  - [Historia del SQL](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Historia-del-SQL)
  - [Create view y DDL alter](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Create-view-y-DDL-alter)
  - [DDL drop](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#DDL-drop)
  - [DML](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#DML)
  - [DCL Y TCL](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#DCL-Y-TCL)
  - [¿Que es standar en SQL?](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#¿Que-es-standar-en-SQL?)
  - [Creando Tablas](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Creando-tablas)
    - [Tablas independientes](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Tablas-independientes)
    - [Tablas dependientes](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Tablas-dependientes)
    - [Tablas transitivas](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Tablas-transitivas)
- [Consultas a una base de datos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Consultas-a-una-base-de-datos)
  - [¿Por qué las consultas son tan importantes?](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#¿Por-qué-las-consultas-son-tan-importantes?)
  - [Estructura básica de un Query](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Estructura-básica-de-un-Query)
    - [SELECT](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#SELECT)
    - [FROM](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#FROM)
    - [Utilizando la sentencia FROM](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Utilizando-la-sentencia-FROM)
    - [WHERE](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#WHERE)
    - [Utilizando la sentencia WHERE nulo y no nulo](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Utilizando-la-sentencia-WHERE-nulo-y-no-nulo)
    - [GROUP BY](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#GROUP-BY)
    - [ORDER BY y HAVING](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#ORDER-BY-y-HAVING)
  - [El interminable agujero de conejo (Nested queries)](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#El-interminable-agujero-de-conejo-(Nested-queries))
  - [¿Cómo convertir una pregunta en un query SQL?](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#¿Cómo-convertir-una-pregunta-en-un-query-SQL?)
  - [Preguntándole a la base de datos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Preguntándole-a-la-base-de-datos)
  - [Consultando PlatziBlog](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Consultando-PlatziBlog)
- [Introducción a la bases de datos NO relacionales](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Introducción-a-la-bases-de-datos-NO-relacionales)
  - [¿Qué son y cuáles son los tipos de bases de datos no relacionales?](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Qué-son-y-cuáles-son-los-tipos-de-bases-de-datos-no-relacionales)
  - [Servicios administrados y jerarquía de datos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Servicios-administrados-y-jerarquía-de-datos)
- [Manejo de modelos de datos en bases de datos no relacionales](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Manejo-de-modelos-de-datos-en-bases-de-datos-no-relacionales)
  - [Top level collection con Firebase](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Top-level-collection-con-Firebase)
  - [Creando y borrando documentos en Firestore](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Creando-y-borrando-documentos-en-Firestore)
  - [Colecciones vs subcolecciones](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Colecciones-vs-subcolecciones)
  - [Recreando Platziblog](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Recreando-Platziblog)
  - [Construyendo Platziblog en Firestore](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Construyendo-Platziblog-en-Firestore)
  - [Proyecto final: transformando tu proyecto en una db no relacional](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#proyecto-final-transformando-tu-proyecto-en-una-db-no-relacional)
- [Bases de datos en la vida real](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Bases-de-datos-en-la-vida-real)
  - [Bases de datos en la vida real](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Bases-de-datos-en-la-vida-real)
  - [Big Data](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Big-Data)
  - [Data warehouse](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Data-warehouse)
  - [Data mining](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Data-mining)
  - [ETL](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#ETL)
  - [Business intelligence](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Business-intelligence)
  - [Machine Learning](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Machine-Learning)
  - [Data Science](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Data-Science)
  - [¿Por qué aprender bases de datos hoy?](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#¿Por-qué-aprender-bases-de-datos-hoy?)
- [Bonus](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Bonus)
  - [Bases de datos relacionales vs no relacionales](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Bases-de-datos-relacionales-vs-no-relacionales)
  - [Elegir una base de datos](https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#Elegir-una-base-de-datos)



https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md#https://github.com/EliazBobadilla/Fundamentos-Bases-de-Datos/blob/main/Notas/NotasFinal.md# 

### Datos del Profesor:
El curso es dictado por **Israel Vázquez** ,Senior Web Developer en SF startup YouNoodle.

- [**Perfil de Platzi**](https://platzi.com/p/isravazquezmorales)
- [**Facebook**](https://www.facebook.com/isra.baurel)
- [**Linkdedin**](https://www.linkedin.com/in/israel-baurel-v%C3%A1zquez-morales/?originalSubdomain=mx)
