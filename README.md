<div align="center">
	
  
## Universidad Peruana de Ciencias Aplicadas

![Image](assets/upc-logo.png)

## TB1 "StayMap"


**1ASI0730  -  Aplicaciones Web**

Carrera de Ingeniería de Software


**NRC:** 4376

**Profesor:** Hugo Allan Mori Paiva

**Integrantes:**

Collantes Carrillo, Diego Mateo (u202311823)

Lizarbe Alvarez, Ariana Nickole (u202311704)

Ortiz Cardenas, Johanna Antuanete (u202310358)

Zegarra Lopez, Renato Sebastian Rubber (u202311558)

Zúñiga Murillo, Diego Sebastian (u202310636)


**2025**
</div>

## Registro de Versiones del Informe
<div align="center">
<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TB1</td>
      <td>27/04/2025</td>
      <td>
	- Collantes Carrillo, Diego Mateo <br>
	- Lizarbe Alvarez, Ariana Nickole <br>
	- Ortiz Cardenas, Johanna Antuanete <br>
	- Zegarra Lopez, Renato Sebastian Rubber <br> 
	- Zúñiga Murillo, Diego Sebastian <br>
      </td>
      <td></td>
    </tr>
    <tr>
      <td>TP</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TB2</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TF</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>

## Contents

- [STUDENT OUTCOME](#student-outcome)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [CAPÍTULO I: INTRODUCCIÓN](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      	- [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
	- [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
	- [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
	- [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
	- [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
	- [5.2.1.6. Software Deployment Evidence for Sprint Review](#5216-software-deployment-evidence-for-sprint-review)
	- [5.2.1.7. Team Collaboration Insights during Sprint](#5217-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## STUDENT OUTCOME
ABET - EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias. En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro.

<table border="1">
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Comunica oralmente con efectividad a diferentes rangos de audiencia</td>
      <td>
        <strong>Collantes Carrillo, Diego Mateo</strong><br>
        TB1: Como parte del equipo de STAYMAP, me encargué de diseñar los diagramas C4 y UML para representar la arquitectura del sistema. Presenté estos diagramas al equipo y a los stakeholders, explicando su estructura y cómo cada componente se integra en el proyecto.<br>
        <strong>Lizarbe Alvarez, Ariana Nickole</strong><br>
        TB1: Desarrollé la Landing Page de STAYMAP, como modelo inicial en figma, enfocándome en un diseño atractivo y funcional. Mi objetivo fue comunicar claramente el propósito de la plataforma a los usuarios potenciales y recoger sus primeras impresiones.<br>
        <strong>Ortiz Cardenas, Johanna Antuanete</strong><br>
        TB1: Elaboré el Modelo C4 y diagrama de clases UML de STAYMAP, detallando los niveles de abstracción del sistema. Mi contribución ayudó a que tanto el equipo técnico como los clientes entendieran la escalabilidad y las conexiones entre módulos.<br>
        <strong>Zegarra Lopez, Renato Sebastian Rubber</strong><br>
        TB1: Diseñé la base de datos de STAYMAP, definiendo las tablas, relaciones y consultas principales. Mi trabajo aseguró que los datos se almacenaran de manera eficiente y estuvieran listos para su implementación.<br>
        <strong>Zúñiga Murillo, Diego Sebastián</strong><br>
        TB1: Realicé los análisis de entrevistas con usuarios potenciales de STAYMAP y señalé sus necesidades. Registré y comuniqué los hallazgos al equipo para que el desarrollo se alineara con las expectativas del público objetivo.
      </td>
      <td>
        <strong>Collantes Carrillo, Diego Mateo</strong><br>
        TB1: Los diagramas que creé facilitaron la comunicación técnica dentro del equipo y con los stakeholders, evitando malentendidos en las fases iniciales de STAYMAP.<br>
        <strong>Lizarbe Alvarez, Ariana Nickole</strong><br>
        TB1: La Landing Page que desarrollé no solo presentó STAYMAP de manera profesional, sino que también nos permitió validar el interés de los usuarios antes del lanzamiento.<br>
        <strong>Ortiz Cardenas, Johanna Antuanete</strong><br>
        TB1: El Modelo C4 que elaboré se convirtió en una herramienta clave para explicar la complejidad técnica de STAYMAP de manera accesible, incluso para perfiles no técnicos.<br>
        <strong>Zegarra Lopez, Renato Sebastian Rubber</strong><br>
        TB1: El diseño de la base de datos que propuse optimizó el rendimiento de STAYMAP, sentando las bases para un sistema escalable y confiable.<br>
        <strong>Zúñiga Murillo, Diego Sebastian</strong><br>
        TB1: Las entrevistas que conduje revelaron insights valiosos, permitiendo que STAYMAP priorizara funciones clave como la personalización de búsquedas y la confiabilidad de las reseñas.
      </td>
    </tr>
    <tr>
      <td>Comunica por escrito con efectividad a diferentes rangos de audiencia</td>
      <td>
        <strong>Collantes Carrillo, Diego Mateo</strong><br>
        TB1: Lideré la creación de documentos técnicos especializados para STAYMAP, transformando complejos diagramas arquitectónicos en guías accesibles con versiones para equipos de desarrollo (detalle técnico) y stakeholders (enfoque ejecutivo).<br>
        <strong>Lizarbe Alvarez, Ariana Nickole</strong><br>
        TB1: Diseñé la estrategia de contenido multiplataforma para STAYMAP, desarrollando desde whitepapers técnicos hasta copywriting persuasivo para la Landing Page, ajustando registro y profundidad según cada canal.<br>
        <strong>Ortiz Cardenas, Johanna Antuanete</strong><br>
        TB1: Estructuré el sistema de documentación modular de STAYMAP, creando plantillas estandarizadas para reportes técnicos que permitieron escalar la comunicación del proyecto sin perder consistencia.<br>
        <strong>Zegarra Lopez, Renato Sebastian Rubber</strong><br>
        TB1: Publiqué artículos técnicos en el blog interno de STAYMAP explicando patrones de diseño de bases de datos, estableciéndome como referente para consultas escritas del equipo.<br>
        <strong>Zúñiga Murillo, Diego Sebastian</strong><br>
        TB1: Implementé un sistema de síntesis de feedback con dashboards escritos automatizados para STAYMAP, transformando datos cualitativos en informes ejecutivos mensuales.
      </td>
      <td>
        <strong>Collantes Carrillo, Diego Mateo</strong><br>
        TB1: La documentación que preparé se convirtió en la referencia principal para el equipo técnico, asegurando una correcta implementación de los diagramas en STAYMAP.<br>
        <strong>Lizarbe Alvarez, Ariana Nickole</strong><br>
        TB1: Los textos que desarrollé comunicaron efectivamente el propósito de STAYMAP, recibiendo comentarios positivos tanto de usuarios como del equipo interno.<br>
        <strong>Ortiz Cardenas, Johanna Antuanete</strong><br>
        TB1: Las guías que escribí permitieron que nuevos integrantes del equipo pudieran entender rápidamente el Modelo C4 y su aplicación en STAYMAP.<br>
        <strong>Zegarra Lopez, Renato Sebastian Rubber</strong><br>
        TB1: La documentación de la base de datos que elaboré facilitó el trabajo diario del equipo, evitando confusiones en el manejo de la información.<br>
        <strong>Zúñiga Murillo, Diego Sebastian</strong><br>
        TB1: Mis informes organizaron el feedback de los usuarios de manera clara, permitiendo priorizar funciones importantes para STAYMAP.
      </td>
    </tr>
  </tbody>
</table>

# 5.1.2. Source Code Management

## 5.1.3. Source Code Style Guide & Conventions

Para el desarrollo de la interfaz responsive del sistema StayMap se utilizaron tecnologías web como HTML, CSS y JavaScript. A continuación, se presentan las convenciones seguidas en la implementación:

**HTML**

Se aplicó una estructura clara y organizada mediante el uso de etiquetas semánticas y contenedores:

	<header></header>


Encabezado general de la página.

	<nav></nav>

Barra de navegación.

	<main></main>

Contenedor principal del contenido.


	<div class="container">
	
Se utilizó para agrupar bloques de contenido relacionados.

	<footer>

Pie de página con información adicional.


Los títulos se declararon jerárquicamente usando las etiquetas 

	<h1> a <h6>

Las imágenes se insertaron mediante la etiqueta 

	<img>

incluyendo el atributo alt.

Ejemplo:

	<header>
 	 <h1>StayMap</h1>
	</header>



	<div class="container">
  	<p>Contenido relacionado agrupado.</p>
	</div>


	<img src="imagen.jpg" alt="Descripción de la imagen">


**CSS**
Los estilos se definieron en un archivo externo. Se emplearon las siguientes prácticas:
Nombres de clases en formato kebab-case (ej. .contenedor-principal).


- Separación por secciones (tipografía, layout, botones).


- Uso de media queries para diseño responsive.


- Colores definidos por variables CSS para facilitar su reutilización.


Ejemplo:


	h1 {
 	 font-size: 24px;
	  color: #0066cc;
	}

**JavaScript**

Se utilizó JavaScript para interacciones básicas de la interfaz. Las principales convenciones fueron:
Uso de nombres en camelCase.


- Separación del código en archivos externos.


- Comentarios explicativos cuando fue necesario.



		function mostrarMenu() {
  			// Código para mostrar u ocultar el menú
		}

**Buenas prácticas generales**

- Indentación de 2 espacios.


- Uso correcto de etiquetas semánticas y atributos de accesibilidad.


- Organización de archivos en carpetas: /css, /js, /img.


- Separación del contenido (HTML), presentación (CSS) y comportamiento (JavaScript).

## 5.1.4. Software Deployment Configuration

Para la publicación de nuestra landing page y aplicación web, utilizamos GitHub Pages, una herramienta gratuita de GitHub que permite alojar sitios estáticos directamente desde un repositorio. Esta opción resultó ideal para presentar el proyecto de forma accesible, sin necesidad de servidores adicionales ni configuraciones complejas.

A continuación, se detallan los pasos que seguimos para configurar el despliegue:

1. Creación del repositorio en GitHub:
Iniciamos el proceso creando un nuevo repositorio en GitHub, donde alojaremos todos los archivos relacionados con el proyecto de la landing page, incluyendo el HTML, CSS y JavaScript.

2. Preparación del entorno local:
Clonamos el repositorio en nuestra computadora utilizando Git, lo que nos permitió trabajar de manera local, realizar pruebas y organizar el contenido antes de subirlo a la nube.

3. Organización de los archivos del proyecto:
Diseñamos una estructura clara de carpetas que incluyera el archivo principal index.html, las hojas de estilo y los scripts necesarios para el correcto funcionamiento de la página. Esta organización facilitó el mantenimiento y despliegue del proyecto.

4. Configuración de GitHub Pages:
Una vez que el contenido estuvo listo y subido al repositorio, procedimos a activar GitHub Pages. Para ello:

- Accedimos a la pestaña Settings del repositorio.

- En la sección Pages, seleccionamos la rama principal (por ejemplo, main) y la carpeta raíz como fuente de publicación.

- Guardamos los cambios y GitHub generó automáticamente la URL pública para visualizar el sitio.

5. Verificación del despliegue:
Después de unos minutos, GitHub Pages procesó el contenido y dejó disponible nuestra landing page en línea. Accedimos al enlace proporcionado para comprobar que todo funcionaba correctamente y que los archivos se renderizaban sin errores.

# 5.2. Landing Page, Services & Applications Implementation

## 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="2">Sprint Planning Background</th>
  </tr>
  <tr>
    <td>Date</td>
    <td>2025-04-19</td>
  </tr>
  <tr>
    <td>Time</td>
    <td>11:00PM</td>
  </tr>
  <tr>
    <td>Location</td>
    <td>Virtual, via discord</td>
  </tr>
  <tr>
    <td>Prepared by</td>
    <td>Lizarbe Álvarez, Ariana Nickole</td>
  </tr>
  <tr>
    <td>Attendees (to planning meeting)</td>
    <td>Lizarbe Alvarez, Ariana Nickole / Ortiz Cardenas, Johanna Antuanete / Zúñiga Murillo, Diego Sebastian / Collantes Carrillo, Diego Mateo / Zegarra López, Renato Rubber Sebastian</td>
  </tr>
  <tr>
    <td>Sprint Goal & User Stories</td>
    <td></td>
  </tr>
  <tr>
    <td>Sprint n Goal</td>
    <td>Diseñar y desarrollar una landing page funcional y responsiva que comunique efectivamente los valores de StayMap, permita la navegación básica y esté alineada con la arquitectura de información planteada para fans y artistas.</td>
  </tr>
  <tr>
    <td>Sprint n Velocity</td>
    <td>Para la planificación de este sprint se utilizará la escala de Fibonacci (1, 2, 3, 5, 8...) para estimar el esfuerzo relativo de cada historia de usuario, permitiendo una mejor comparación y afinación de la carga de trabajo.</td>
  </tr>
  <tr>
    <td>Sum of Story Points</td>
    <td>15</td>
  </tr>
</table>

### 5.2.1.2. Aspect Leaders and Collaborators

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="7">5.2.1.2. Aspect Leaders and Collaborators</th>
  </tr>
  <tr>
    <th>Team Member</th>
    <th>Github Username</th>
    <th>UX UI DESIGN</th>
    <th>DIAGRAMA UML</th>
    <th>C4 MODEL</th>
    <th>DATABASE DESIGN</th>
    <th>ENTRE VISTAS</th>
  </tr>
  <tr>
    <td>Collantes Diego</td>
    <td>D4D3v4l</td>
    <td>C</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Lizarbe Ariana</td>
    <td>ariaalizz</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Ortiz Johanna</td>
    <td>Antuanet01</td>
    <td>C</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Zegarra Renato</td>
    <td>ReiZCode</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Zúniga Diego</td>
    <td>DekayDe Canela</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
  </tr>
</table>

### 5.2.1.3. Sprint Backlog 1

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="8">Sprint 1</th>
  </tr>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item/Task</th>
  </tr>
  <tr>
    <th>id</th>
    <th>title</th>
    <th>id</th>
    <th>title</th>
    <th>description</th>
    <th>estimation</th>
    <th>assigned to</th>
    <th>status</th>
  </tr>
  <tr>
    <td>US01</td>
    <td>Ver beneficios para fans</td>
    <td>TSK01</td>
    <td>Diseñar sección de beneficios para fans</td>
    <td>Crear una sección en la landing page que muestre los beneficios para los fans.</td>
    <td>2 horas</td>
    <td>Ariana</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US02</td>
    <td>Ver beneficios para artistas</td>
    <td>TSK02</td>
    <td>Diseñar sección de beneficios para artistas</td>
    <td>Crear una sección en la landing page que muestre los beneficios para los artistas.</td>
    <td>2 horas</td>
    <td>Diego</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US03</td>
    <td>Acceder a testimonios</td>
    <td>TSK03</td>
    <td>Implementar módulo de testimonios</td>
    <td>Permitir a los usuarios visualizar testimonios de otros fans y artistas.</td>
    <td>1 hora</td>
    <td>Antuanete</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US04</td>
    <td>Registrase en la landing page</td>
    <td>TSK04</td>
    <td>Crear formulario de registro</td>
    <td>Implementar el formulario de registro para nuevos usuarios.</td>
    <td>2 horas</td>
    <td>Diego</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US05</td>
    <td>Iniciarse sin en la landing page</td>
    <td>TSK05</td>
    <td>Implementar login en landing page</td>
    <td>Permitir a usuarios registrados iniciarse desde la landing page.</td>
    <td>5 horas</td>
    <td>Diego</td>
    <td>in process</td>
  </tr>
</table>

### 5.2.1.4. Development Evidence for Sprint Review

<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit id</th>
      <th>Commit message</th>
      <th>Commit Message Body</th>
      <th>Committed on</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5">ariaalizz</td>
      <td>louis-tour.png</td>
      <td>07cbb65</td>
      <td>archive .png</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>starymapiogo.png</td>
      <td>2fe5ae4</td>
      <td>archive.png</td>
      <td>logo StayMap</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>taylor.jpeg</td>
      <td>5be819f</td>
      <td>archive.png</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>styles.css</td>
      <td>0253b2a</td>
      <td>archive.css</td>
      <td>image design</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>index.html</td>
      <td>4c24312</td>
      <td>archive.html</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td rowspan="5">DekayDeCanela</td>
      <td>fans.css</td>
      <td>754862b</td>
      <td>archive.css</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>artista.css</td>
      <td>2eb7f30</td>
      <td>archive.css</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>sk-tour.jpg</td>
      <td>c3f347c</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>main.html</td>
      <td>d1a23bc</td>
      <td>archive.html</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>skz-concert.jpg</td>
      <td>9e327a8</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td rowspan="5">D4D3val</td>
      <td>skz-tour.jpg</td>
      <td>7be9471</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>niall-tour.jpg</td>
      <td>d7c95a4</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>monkeys-tour.jpg</td>
      <td>5c55361</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>emilia-tour.jpg</td>
      <td>6706966</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>main.css</td>
      <td>485049f</td>
      <td>archive.css</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td rowspan="4">ReizCode</td>
      <td>fans.html</td>
      <td>65ed194</td>
      <td>archivo .html</td>
      <td>landing desing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>harry.jpg</td>
      <td>599a130</td>
      <td>archivo .jpg</td>
      <td>landing image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>louis.jpg</td>
      <td>566a2e9</td>
      <td>archivo .jpg</td>
      <td>landing image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>stay.jpg</td>
      <td>1488808</td>
      <td>archivo .jpg</td>
      <td>landing image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td rowspan="4">Antuanet01</td>
      <td>artista.html</td>
      <td>eb55af7</td>
      <td>archivo .html</td>
      <td>landing desing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>main.js</td>
      <td>145dd26</td>
      <td>archivo .js</td>
      <td>landing page logic</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>close-icon.png</td>
      <td>221c792</td>
      <td>archivo .png</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>hamburger-icon.png</td>
      <td>fca3f79</td>
      <td>archivo .png</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
  </tbody>
</table>

### 5.2.1.5. Execution Evidence for Sprint Review

En este Sprint, nos enfocamos en el diseño e implementación de la Landing Page de StayMap. Esta página fue desarrollada para captar la atención de los visitantes, mostrando de manera clara y atractiva el valor que ofrece la plataforma tanto para fans como para artistas. Se implementaron las siguientes secciones:

- Beneficios para Usuarios: Se diseñó una sección destacando las ventajas de usar StayMap, como descubrir eventos locales, hacer check-in en conciertos y conectar con otros fans.

- Beneficios para Artistas: Se creó un apartado dirigido a artistas emergentes, resaltando cómo StayMap puede ayudarlos a aumentar su visibilidad y conectar con nuevas audiencias.

- Testimonios de Fans: Se incorporaron testimonios de usuarios reales, mostrando sus experiencias positivas con la plataforma y reforzando la confianza en el servicio.

- Conciertos Programados Cerca de Ti: Se añadió una sección dinámica que muestra eventos musicales próximos en función de la ubicación del usuario, incentivando la exploración y asistencia a conciertos locales.

**Screenshots de las principales vistas:**

Sección de Inicio:

<div align="center">
  <img src="assets/capturas/captura-inicio.png" alt="inicio" style="width: 80%">
</div>

Sección de Para Fans:

<div align="center">
  <img src="assets/capturas/captura-fans.png" alt="cap fans" style="width: 80%">
</div>

Sección de Para Artistas:

<div align="center">
  <img src="assets/capturas/captura-artistas.png" alt="artistas" style="width: 80%">
</div>

**Enlace de la Landing Page:** https://the-rumbling.github.io/StayMap-Landing_Page/

**Link de video de visualización y navegación:**
Para complementar, se preparó un video donde se muestra la navegación completa de la Landing Page, recorriendo cada sección implementada y explicando brevemente su propósito.
Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311704_upc_edu_pe/EUI7wWHl6_BIldMBylSryzwBIvr_c_QHEKdGhnRZnkBG9w?e=Tix91B


### 5.2.1.6. Software Deployment Evidence for Sprint Review

**Las principales actividades de Deployment llevadas a cabo fueron:**

   - Creación de repositorio en GitHub: Se creó un repositorio público dedicado para la Landing Page, facilitando el control de versiones y la colaboración futura.

   - Configuración de Git: Se configuró el entorno local para trabajar con Git, incluyendo la identificación de usuario (git config --global user.name y git config --global user.email).

   - Inicialización de proyecto Git: Se ejecutó la inicialización del repositorio local (git init), la adición de archivos (git add .) y la generación de un primer commit (git commit -m "Subiendo landing page").

   - Asociación a repositorio remoto: Se estableció el enlace entre el repositorio local y GitHub mediante git remote add origin, permitiendo realizar el push del proyecto.

**Publicación mediante GitHub Pages:**

   - En la sección Settings > Pages del repositorio, se configuró la publicación seleccionando la rama main y la carpeta raíz (/ (root)).

   - Se habilitó el hosting automático, lo que permitió que la Landing Page estuviera disponible en línea a través de un URL público proporcionado por GitHub.

1. Repositorio creado en GitHub:

<div align="center">
  <img src="assets/capturas/captura-repositorio.png" alt="repositorio" style="width: 80%">
</div>

2. Configuración de Git y primer Push:

<div align="center">
  <img src="assets/capturas/captura-bash.png" alt="bash" style="width: 80%">
</div>

3. Configuración de GitHub Pages:

<div align="center">
  <img src="assets/capturas/captura-pages.png" alt="pages" style="width: 80%">
</div>

4. Landing Page publicada:

<div align="center">
  <img src="assets/capturas/captura-landing.png" alt="landing" style="width: 80%">
</div>

### 5.2.1.7. Team Collaboration Insights during Sprint

Desarrollo de Actividades de Implementación:
Durante este Sprint, el equipo trabajó de manera colaborativa para la implementación de la Landing Page del proyecto. Las tareas principales incluyeron:

	- Diseño y estructuración del contenido HTML.

	- Aplicación de estilos CSS para el diseño visual.

	- Configuración del entorno local de desarrollo.

	- Uso de Git para control de versiones.

	- Coordinación para el despliegue de la Landing Page mediante GitHub Pages.

La colaboración se realizó principalmente a través de GitHub, donde cada miembro del equipo realizó commits documentando los avances individuales y contribuyendo al repositorio compartido. Se fomentó la revisión mutua de cambios y la sincronización de actividades para garantizar una entrega integrada y de calidad.

**Gráficos de colaboración (GitHub Insights):**



Los gráficos de contribución muestran cómo cada miembro participó de manera activa en la implementación del producto. Se evidencia un flujo de trabajo constante mediante pushes regulares y trabajo en paralelo en los diferentes elementos de la Landing Page.
