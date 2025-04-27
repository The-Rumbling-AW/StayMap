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
