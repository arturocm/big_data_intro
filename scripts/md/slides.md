title: Agenda
class: after

- Innovación en Tecnología de Información
- ¿Qué es Data Science?
- Componentes de Data Science
- Solución Tradicional vs Nueva Propuesta
- Tipos de Soluciones en Data Science
- Tipos de Proyectos
- Acerca de nosotros

---

title: Innovación en Tecnología de Información
subtitle: ¿Por qué es importante?
class: segue dataday nobackground

---
title: Innovación en Tecnología de Información

- La innovación tecnológica es el conjunto de actividades científicas, tecnológicas, financieras y comerciales que permiten introducir nuevos o mejorados servicios, productos, procesos, técnicas y/o sistemas organizacionales.

- Para poder innovar es necesario considerar cambios en los sistemas tecnológicos así también como cambios en los paradigmas tecnológicos.

- La innovación en una empresa le permite:
	- Ser más eficiente
	- Incrementar su nivel de competitividad
	- Mejorar la calidad de sus servicios o productos
---

title: Innovación en Tecnología de Información

- <b>Resultados esperados</b>:
	- Desarrollo de nuevos productos
	- Implementación de nuevos procesos o sistemas

- <b>Indicadores de ÉXITO</b>:
	- Rentabilidad económica y financiera de la inversión
	- Crecimiento de las ventas

- <b>Requerimientos críticos</b>: 
	- Identificación de las necesidades del negocio
	- Capacidad de gestión tecnológica de la organización

---

class: dark quote nobackground

<aside class="gdbar right bottom"><img src="images/logos/logo_square.png"></aside>
<article class="flexbox vleft auto-fadein">
<q>
<b>Data Science</b> es un campo interdisciplinario que involucra los procesos y sistemas para extraer conocimiento o un mejor entendimiento de grandes volúmenes de datos en sus diferentes formas y formatos.
</q>
<div class="author">
Dr. Alex Liu <br>
Principal Data Scientist <br>
IBM Corp.
</div>
</article>

---
title: Componentes de Data Science
subtitle: Solución Tradicional vs Nueva Propuesta
class: segue dataday nobackground

---
title: <img src="images/proceso/all_small.png" alt="all_stages" style="width:300px">

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome-animation/0.0.8/font-awesome-animation.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">

<div class="container-fluid"> 
	<div class="col-md-6">
		<h1 style= "color:#1F77B4">
			<i class="fa fa-mixcloud fa-3x"></i>
			Recolección
		</h1>
		<h1 style= "color:#FF7F0E">
			<i class="fa fa-server fa-3x"></i>
			Almacenamiento
		</h1>
	</div>
	<div class="col-md-6">
		<h1 style= "color:#2CA02C">
			<i class="fa fa-code-fork fa-3x"></i>
			Combinación
		</h1>
		<h1 style = "color:#D62728">
			<i class="fa fa-flask fa-3x"></i>
			Análisis
		</h1>
		<h1 style= "color:#9467BD">
			<i class="fa fa-line-chart fa-3x"></i>
			Visualización
		</h1>
	</div>
</div>
---
title: <img src="images/proceso/1.png" alt="Mountain View" style="width:300px"> Recolección

Conectarse a data estructurada y no-estrucutrada:

- Clicks, Sensores, Teléfonos Móbiles, etc.
- APIs (Application Program Interface):
	- Redes Sociales, Servicios en Línea, OAuth (Open standard for Authorization)
- Conectores a Bases de Datos (obdc, jbdc, etc.)
- Formatos comunes: XML, Json, csv, xlxs, ...
- Muestreo, encuestas, etc. 

---
title: <img src="images/proceso/1.png" alt="Mountain View" style="width:300px"> Recolección (ejemplos)

<div class="container-fluid"> 
	<div class="col-md-5">
	<h2>Solución Tradicional</h2>
		<img src="images/pipeline/collect/a_1.png" alt="Excel" style="width:100px">
		<img src="images/pipeline/collect/a_2.png" alt="Access" style="width:100px">
		<img src="images/pipeline/collect/a_3.png" alt="Google" style="width:100px">
	</div>
	<div class="col-md-2">
		<br>
		<br>
		<i class="fa fa-arrow-right faa-passing animated fa-4x"></i>
	</div>
	<div class="col-md-5">
	<h2>Nueva Propuesta</h2>
		<img src="images/pipeline/collect/b_1.png" alt="SocialNwk" style="width:200px">
		<img src="images/pipeline/collect/b_2.png" alt="Photo" style="width:75px">
		<img src="images/pipeline/collect/b_3.png" alt="API" style="width:75px">
		<img src="images/pipeline/collect/b_4.png" alt="Smartphone" style="width:75px">
		<img src="images/pipeline/collect/b_5.png" alt="IoT" style="width:75px">
		<img src="images/pipeline/collect/b_6.png" alt="Rasby" style="width:75px">
		<img src="images/pipeline/collect/b_7.png" alt="Arduino" style="width:75px">
		<img src="images/pipeline/collect/b_8.png" alt="Sound" style="width:75px">
		<img src="images/pipeline/collect/b_9.ico" alt="Movie" style="width:75px">
		<img src="images/pipeline/collect/b_10.png" alt="Voice" style="width:75px">
	</div>
</div>
---
title: <img src="images/proceso/2.png" alt="Mountain View" style="width:300px"> Almacenamiento

Recolectar, integrar y administrar datos históricos:

- Base de Datos Relacionales
- Base de Datos No Relacionales
- Hadoop Distributed File System (HDFS)
- Resilient Distributed Datasets (RDD) 
- Cloud Services
---
title: <img src="images/proceso/2.png" alt="Mountain View" style="width:300px"> Almacenamiento

<div class="container-fluid"> 
	<div class="col-md-3">
	<h2>Solución Tradicional</h2>
		<img src="images/pipeline/store/a_1.png" alt="SQL Server" style="width:100px">
	</div>
	<div class="col-md-2">
		<br>
		<br>
		<i class="fa fa-arrow-right faa-passing animated fa-4x"></i>
	</div>
	<div class="col-md-7">
	<h2>Nueva Propuesta</h2>
		<img src="images/pipeline/store/b_02.png" alt="SQL Server" style="width:150px">
		<img src="images/pipeline/store/b_01.png" alt="SQL Server" style="width:150px">
		<img src="images/pipeline/store/b_1.png" alt="SQL Server" style="width:75px">
		<img src="images/pipeline/store/b_2.png" alt="SQL Server" style="width:75px">
		<img src="images/pipeline/store/b_3.png" alt="SQL Server" style="width:75px">
		<img src="images/pipeline/store/b_4.png" alt="SQL Server" style="width:300px">

	</div>
</div>
---
title: <img src="images/proceso/3.png" alt="Mountain View" style="width:300px"> Combinación

Validación y dimensionalización de data, aplicando reglas de negocio "on the fly" para análisis contextuales:

- Reporte de excepciones y validaciones
- Notificaciones y alertas de soporte
- Transformaciones de Negocio

Puede considerarse como parte del Almacenamiento de datos

---
title: <img src="images/proceso/4.png" alt="Mountain View" style="width:300px"> Análisis

Ejecución de Análisis <b>descritivos</b> y <b>predictivos</b> por medio de librerias estadísticas de funciones y features:

- Análisis Exploratorio, Distribuciones y su significado
- Causality
- Transformaciones y Features
- Machine Learning

---
title: <img src="images/proceso/5.png" alt="Mountain View" style="width:300px"> Análisis

<div class="container-fluid"> 
	<div class="col-md-5">
	<h2>Solución Tradicional</h2>
		<img src="images/pipeline/collect/a_1.png" alt="Excel" style="width:100px">
	</div>
	<div class="col-md-2">
		<br>
		<br>
		<i class="fa fa-arrow-right faa-passing animated fa-4x"></i>
	</div>
	<div class="col-md-5">
	<h2>Nueva Propuesta</h2>
		<ul>
			Lenguajes de Programación
			<br>
				<img src="images/pipeline/analyze/b_1.png" alt="R" style="width:100px">
				<img src="images/pipeline/analyze/b_2.png" alt="Python" style="width:100px">
			<br>
			Herramientas de BI
			<br>
				<img src="images/pipeline/analyze/b_3.png" alt="R" style="width:100px">
				<img src="images/pipeline/analyze/b_4.png" alt="Python" style="width:100px">
				<img src="images/pipeline/analyze/b_5.png" alt="R" style="width:100px">
				<img src="images/pipeline/analyze/b_6.png" alt="Python" style="width:100px">
				<img src="images/pipeline/analyze/b_7.png" alt="Python" style="width:100px">
		</ul>
	</div>
</div>
---
title: <img src="images/proceso/4.png" alt="Mountain View" style="width:300px"> Visualización

<div class="container-fluid"> 
	<div class="col-md-3">
	<h2>Solución Tradicional</h2>
		<img src="images/pipeline/collect/a_1.png" alt="Excel" style="width:100px">
		<img src="images/pipeline/collect/a_2.png" alt="Access" style="width:100px">
		<img src="images/pipeline/collect/a_3.png" alt="Google" style="width:100px">
	</div>
	<div class="col-md-2">
		<br>
		<br>
		<i class="fa fa-arrow-right faa-passing animated fa-4x"></i>
	</div>
	<div class="col-md-7">
	<h2>Nueva Propuesta</h2>
		<ul>
			Open Source
			<br>
				<img src="images/pipeline/visualize/a_1.png" alt="R" style="width:100px">
				<img src="images/pipeline/visualize/a_2.png" alt="Python" style="width:100px">
				<img src="images/pipeline/visualize/a_3.png" alt="Python" style="width:100px">
				<img src="images/pipeline/visualize/a_4.png" alt="Python" style="width:100px">

			<br>
			Requieren Licencia
			<br>
				<img src="images/pipeline/visualize/b_1.png" alt="R" style="width:200px">
				<img src="images/pipeline/visualize/b_2.png" alt="Python" style="width:200px">
				<img src="images/pipeline/visualize/b_3.png" alt="Python" style="width:200px">
				<img src="images/pipeline/visualize/b_4.png" alt="Python" style="width:200px">
		</ul>
	</div>
</div>
---

title: Data Science
subtitle: Q&A
class: segue dataday nobackground

