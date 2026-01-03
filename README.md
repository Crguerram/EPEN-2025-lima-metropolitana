# EPEN-2025-lima-metropolitana
Análisis del mercado laboral en Lima Metropolitana usando microdatos de la EPEN 2025 (INEI). Elaboración de Dashboard en Power BI con indicadores ponderados.

📌 Descripción del proyecto
Este proyecto presenta un analisis del mercado laboral en Lima Metropolitana usando microdatos de la Encuesta Permanente de Empleo Nacional (EPEN) 2025,correspondientes al trimestre móvil abril-mayo-junio,
publicados por el INEI

El objetivo es analizar y explorar la situacion del empleo, el perfil demográfico y las brechas de ingreso, aplicando factores de expansión para obtener estimaciones poblacionales representativas y tomar acciones pertinentes
en pro de la igualdad entre géneros.

Como resultado final se elaboró un dashboard de 3 páginas, el cual es pieza fundamental para un portafolio como Analista de Datos Jr.

🎯 Objetivos del análisis
-Estimar población y PEA a través de factores de expansión.
-Analizar el mercado laboral,tasa de empleo y la condición de actividad en el Perú.
-Analizar las diferencias por sexo y por nivel educativo.

 📂 Fuente de datos
 Entidad: INEI
 Dataset: Encuesta Permanente de Empleo Nacional (EPEN),descargados  desde el Portal de Datos Abiertos de Perú
 Periodo: Trimestre móvil Abr-May-Jun 2025
 Cobertura: Geográfica: Lima Metropolitana

 ⚙️ Metodología
 -Preparación y limpieza de datos:
 Carga del archivo csv en Power Bi, revisión y corrección de tipos de datos,creación de identificadores y de dimensiones.

 -Modelado de datos: diseño de un modelo estrella con Fact_Persona como tabla de hechos. 
 Se empleó relaciones de 1 a muchos y se creó una tabla de medidas DAX.

 -Uso de factor de expansión:
 Aplicación de factor de expansión fa_amj25 para población estimada,PEA,ocupados,ingresos promedio ponderados.

 📊 Dashboard (Power BI)

El dashboard está organizado en 3 páginas:

🟦 Página 1 – Panorama laboral

KPIs de población, PEA por condición de actividad, ocupados y tasa de empleo por sexo.

🟦 Página 2 – Perfil demográfico

Población y PEA por sexo.

Distribución de la población por nivel educativo.

Tasa de empleo según nivel educativo.

🟦 Página 3 – Ingresos

Ingreso promedio mensual ponderado.

Comparación de ingresos por sexo.

Ingreso promedio por nivel educativo.

Brechas de ingreso por sexo y educación.


🔎 Principales hallazgos

La tasa de empleo en Lima Metropolitana supera el 90 % dentro de la PEA.

Existe una mayor participación laboral masculina.

El nivel educativo se asocia positivamente con el empleo y los ingresos.

El ingreso promedio mensual estimado es de aproximadamente S/ 1 273.

Persisten brechas de ingreso por sexo (hombres ganan más que mujeres), incluso dentro de los mismos niveles educativos.
 
 
 


