Proyecto Retail Pro 

📊 Descripción del proyecto 

Retail Pro es un proyecto de análisis de datos aplicado al sector retail, desarrollado con el objetivo de transformar datos de ventas en información útil para la toma de decisiones comerciales. 

El proyecto parte de una base de datos de ventas y utiliza consultas SQL para analizar el comportamiento de las ventas, los productos y los clientes. Posteriormente, los resultados son utilizados para desarrollar análisis y visualizaciones en Power BI. 

El objetivo principal es identificar patrones y oportunidades comerciales que permitan al equipo de negocio tomar decisiones basadas en datos. 

🎯 Objetivos 

Analizar la evolución mensual de las ventas. 

Identificar los productos con mayor facturación. 

Detectar clientes recurrentes y su nivel de gasto. 

Comparar la facturación mensual respecto del promedio. 

Utilizar JOIN para relacionar información de diferentes tablas. 

Transformar los resultados obtenidos mediante SQL en información útil para el análisis comercial. 

Desarrollar visualizaciones y dashboards en Power BI. 

🛠 Herramientas y funciones utilizadas 

SQL 

SELECT, WHERE, GROUP BY, ORDER BY y funciones de agregación (SUM, COUNT, AVG).  

INNER JOIN y LEFT JOIN para relacionar tablas.  

HAVING para filtrar resultados agrupados.  

CASE y subconsultas para generar análisis y comparaciones.  

Power BI 

Power Query: conexión a Excel, eliminación de duplicados, eliminación/reemplazo de valores nulos, cambio de tipos de datos, renombrado y eliminación de columnas, y Merge de consultas.  

Modelado: creación de relaciones 1:N y tabla calendario.  

DAX: creación de medidas con SUM, CALCULATE, TOTALYTD, SAMEPERIODLASTYEAR, VAR y DIVIDE.  

Visualización: creación de matrices, KPIs y gráficos para analizar los resultados comerciales. 



| Herramienta     | Uso                                |
| --------------- | ---------------------------------- |
| **SQL Server**  | Consultas y análisis de ventas     |
| **Power Query** | Limpieza y transformación de datos |
| **Power BI**    | Modelado, DAX y visualización      |
| **GitHub**      | Versionado y documentación         |

 

📁 Estructura del repositorio 

Proyecto-Retail-Pro/ 
│ 
├── Ventas_Tech_DB.sql 
│   └── Script de creación y carga de la base de datos 
│ 
├── m4_consultas_negocio.sql 
│   └── Consultas orientadas al análisis comercial 
│ 
├── m5_consultas_joins.sql 
│   └── Consultas utilizando JOIN entre tablas 
│ 
├── Pipeline_ETL_Luberriaga_Giuliana (1).pbix 
│   └── Desarrollo de Power BI relacionado con el proceso ETL 
│ 
├── Luberriaga_Giuliana_Checkpoint2.pbix 
│   └── Dashboard y análisis desarrollado en Power BI 
│ 
└── README.md 
    └── Documentación del proyecto 

🗄️ Scripts SQL 

El proyecto contiene tres archivos principales de SQL: 

1. Ventas_Tech_DB.sql 

Este script contiene la estructura necesaria para trabajar con la base de datos del proyecto y sus datos de ventas. 

Debe ejecutarse primero, ya que genera la base sobre la cual posteriormente se ejecutarán las consultas de análisis. 

2. m4_consultas_negocio.sql 

Contiene consultas orientadas a responder preguntas de negocio. 

Entre los análisis realizados se encuentran: 

Resumen ejecutivo mensual. 

Ranking de productos. 

Identificación de clientes recurrentes. 

Comparación de los meses respecto del promedio de facturación. 

Estas consultas permiten obtener información que puede utilizarse como base para definir acciones comerciales. 

3. m5_consultas_joins.sql 

Contiene consultas que utilizan JOIN para combinar información proveniente de diferentes tablas de la base de datos. 

Esto permite enriquecer el análisis y obtener información relacionada entre ventas, productos, clientes y otras entidades disponibles en la base. 

▶️ Cómo ejecutar los scripts SQL 

Requisitos 

Para ejecutar los scripts es necesario contar con un gestor de bases de datos compatible con SQL Server, como SQL Server Management Studio (SSMS). 

Paso 1 — Clonar el repositorio 

Desde una terminal: 

git clone https://github.com/GiulianaLub/Proyecto-Retail-Pro.git 

Luego ingresar a la carpeta: 

cd Proyecto-Retail-Pro 

También es posible descargar el repositorio directamente desde GitHub. 

Paso 2 — Crear la base de datos 

Abrir SQL Server Management Studio y ejecutar el archivo: 

Ventas_Tech_DB.sql 

Este script debe ejecutarse antes que las consultas de análisis. 

Paso 3 — Ejecutar las consultas de negocio 

Una vez creada y cargada la base de datos, abrir: 

m4_consultas_negocio.sql 

Ejecutar las consultas para obtener los principales indicadores y análisis comerciales. 

Paso 4 — Ejecutar las consultas con JOIN 

Abrir: 

m5_consultas_joins.sql 

y ejecutar las consultas correspondientes para analizar la información combinando diferentes tablas. 

📈 Análisis comercial 

A partir de las consultas SQL se pueden obtener hallazgos que sirven como soporte para el equipo comercial. 

Por ejemplo: 

Productos: identificar los productos que generan mayor facturación permite priorizar su disponibilidad de stock y reducir oportunidades de venta perdidas. 

Clientes: identificar clientes recurrentes y su nivel de gasto permite desarrollar estrategias de fidelización y acciones orientadas a incrementar su frecuencia o volumen de compra. 

Evolución mensual: detectar meses por encima o por debajo del promedio permite diseñar acciones comerciales específicas para períodos de menor facturación. 

Los resultados numéricos obtenidos mediante SQL constituyen la base para posteriormente interpretar los datos y desarrollar estrategias comerciales y de marketing. 

📊 Power BI 

Los archivos .pbix permiten continuar el análisis realizado mediante SQL y presentar los resultados de manera visual e interactiva. 

Para utilizarlos: 

Descargar o clonar el repositorio. 

Abrir el archivo .pbix con Microsoft Power BI Desktop. 

Verificar las conexiones a las fuentes de datos. 

Actualizar los datos si es necesario. 

Explorar los dashboards y visualizaciones. 

🔄 Flujo del proyecto 

Base de datos 
      ↓ 
  SQL Server 
      ↓ 
Consultas SQL 
      ↓ 
Análisis de datos 
      ↓ 
   Power BI 
      ↓ 
Visualización de KPIs 
      ↓ 
Insights comerciales 
      ↓ 
Toma de decisiones 

💡 Resultado esperado 

El proyecto busca demostrar cómo una base de datos transaccional puede convertirse en información de valor para el negocio mediante un proceso de análisis que combina SQL + Power BI. 

El resultado final permite pasar de los datos operativos a indicadores, visualizaciones e insights que pueden servir como soporte para la toma de decisiones comerciales. 

👩‍💻 Autora 

Giuliana Luberriaga 

Proyecto desarrollado como parte del proceso de formación en Data Analytics. 
