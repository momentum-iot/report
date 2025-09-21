# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Curso: Desarrollo de Soluciones IOT</strong><br>
    <strong>Profesor: Leon Baca, Marco Antonio </strong><br>
    <br>INFORME TRABAJO FINAL
</p>

<center>

#### Startup: **Momentum**
#### Product: **PumpUp**

</center>

### <center>Team  Members:</center>
<center>

| Codigo                           | Miembro       |
|----------------------------------|------------|
|  U202211212 | Del Castillo Bueno, Daniel Mateo |
|  U202015274 | Sanchez Montero, Carlos |
|       |  |
|  |  |
|              |  |
|          |  |

<br> AGOSTO 2025
</center>  
<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe
<center>

| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 0.0 | 01/09/2025 |Grupo 1 |Se crea el documento |  

</center>

# Project Report Collaboration Insights
[URL del repositorio](https://www.example.com)

(Imagenes de los commits cada entrega)


# Contenido



[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
[2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping) 
[2.4. Big Picture EventStorming.](#24-big-picture-eventstorming)

[2.5. Ubiquitous Language](#25-ubiquitous-language)  

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)  

[3.1. User Stories](#31-user-stories)  
[3.2. Impact Mapping](#32-impact-mapping)  
[3.3. Product Backlog](#33-product-backlog)  

[Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
[4.1. Strategic-Level Domain-Driven Design.](#41-strategic-level-domain-driven-design)
[4.1.1. Design-Level EventStorming.](#411-design-level-eventstorming)
[4.1.1.1 Candidate Context Discovery.](#4111-candidate-context-discovery)
[4.1.1.2 Domain Message Flows Modeling.](#4112-domain-message-flows-modeling)
[4.1.1.3 Bounded Context Canvases.](#4113-bounded-context-canvases)
[4.1.2. Context Mapping.](#412-context-mapping)
[4.1.3. Software Architecture.](#413-software-architecture)
[4.1.3.1. Software Architecture System Landscape Diagram.](#4131-software-architecture-system-landscape-diagram)
[4.1.3.2. Software Architecture Context Level Diagrams.](#4132-software-architecture-container-level-diagrams)
[4.1.3.2. Software Architecture Container Level Diagrams.](#4132-software-architecture-container-level-diagrams)
[4.1.3.3. Software Architecture Deployment Diagrams.](#4133-software-architecture-deployment-diagrams)
[4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
[4.2.X. Bounded Context: ](#42x-bounded-context)
[4.2.X.1. Domain Layer.](#42x1-domain-layer)
[4.2.X.2. Interface Layer.](#42x2-interface-layer)
[4.2.X.3. Application Layer.](#42x3-application-layer)
[4.2.X.4. Infrastructure Layer.](#42x4-infrastructure-layer)
[4.2.X.5. Bounded Context Software Architecture Component Level Diagrams.](#42x5-bounded-context-software-architecture-component-level-diagrams)
[4.2.X.6. Bounded Context Software Architecture Code Level Diagrams.](#42x6-bounded-context-software-architecture-code-level-diagrams)
[4.2.X.6.1. Bounded Context Domain Layer Class Diagrams.](#42x61-bounded-context-domain-layer-class-diagrams)
[4.2.X.6.2. Bounded Context Database Design Diagram.](#42x62-bounded-context-database-design-diagram)

[Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
[5.1. Style Guidelines.](#51-style-guidelines)
[5.1.1. General Style Guidelines.](#511-general-style-guidelines)
[5.1.2. Web, Mobile and IoT Style Guidelines.](#512-web-mobile-and-iot-style-guidelines)
[5.2. Information Architecture.](#52-information-architecture)
[5.2.1. Organization Systems.](#521-organization-systems)
[5.2.2. Labeling Systems.](#522-labeling-systems)
[5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
[5.2.4. Searching Systems.](#524-searching-systems)
[5.2.5. Navigation Systems.](#525-navigation-systems)
[5.3. Landing Page UI Design.](#53-landing-page-ui-design)
[5.3.1. Landing Page Wireframe.](#531-landing-page-wireframe)
[5.3.2. Landing Page Mock-up.](#532-landing-page-mock-up)
[5.4. Applications UX/UI Design.](#54-applications-uxui-design)
[5.4.1. Applications Wireframes.](#541-applications-wireframes)
[5.4.2. Applications Wireflow Diagrams.](#542-applications-mock-ups)
[5.4.2. Applications Mock-ups.](#542-applications-mock-ups)
[5.4.3. Applications User Flow Diagrams.](#543-applications-user-flow-diagrams)
[5.5. Applications Prototyping.](#55-applications-prototyping)


[6.3. Validation Interviews](#53-validation-interviews)  
[6.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)  
[6.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)  
[6.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  

[5.4. Video About-the-Product](#54-video-about-the-product)  

[Conclusiones](#conclusiones)  
[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  
[Video About-the-Team](#video-about-the-team)  
[Bibliografía](#bibliografía)  
[Anexos](#anexos)  
°
# Student Outcome
|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Trabaja en equipo para proporcionar liderazgo en forma conjunta.| Daniel Del Castillo:<br/> TB1: <p>Fomenté un ambiente colaborativo organizando las metas del proyecto y comunicando claramente la arquitectura propuesta, lo que permitió planificar tareas de manera ordenada y cumplir con los objetivos trazados en equipo.<p/> Compañero1:<br> *TB1:*  <p>* texto etc.. </p> |TB1 <p>Conclusion</p>|
|Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos|Daniel Del Castillo:<br/> TB1: <p>Asumí un rol activo al guiar al grupo con la definición de la arquitectura y distribución de responsabilidades, compartiendo el liderazgo y asegurando que cada integrante aporte de manera coordinada al desarrollo.<p/> Compañero1:<br> *TB1:*  <p>* texto etc.. </p> |TB1 <p>Conclusion</p>|
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-|
|Compañero 1 	![Imagen del compañero](image.jpg)|U20...|Ingenieria de software|C++, piton .etc|
|Carlos Sanchez Montero <img src="./assets/capitulo-1/miembros/carlos.jpeg">|U202015274|Ingenieria de software|C++, C#, Python, JavaScript, Java, Flutter, Vue, Angular|
|Alvaro Pinto Fuentes Rivera <img src="./assets/capitulo-1/miembros/alvaro.png">|U202213384|Ingenieria de software|C++, C#, Java, Python, SQL, Vue, Angular, Flutter, Kotlin|
|Daniel Mateo Del Castillo Bueno <img src="./assets/capitulo-1/miembros/mateo.png">|U202213384|Ingenieria de software|C++, Java, Flask, SQL, Vue, Angular, Flutter, React|
## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
El gimnasio funciona con procesos manuales para el control de accesos y el seguimiento de uso de máquinas. El registro de miembros se hace en planillas, lo que genera errores y pérdida de información. El control de aforo es manual y no refleja la ocupación en tiempo real. No existe trazabilidad confiable sobre quién ingresó, qué máquina usó o cuánto tiempo estuvo en el recinto. Los usuarios no tienen visibilidad de su historial de visitas ni métricas de esfuerzo. El personal no cuenta con herramientas para detectar alertas de uso indebido ni sobrecarga de equipos. Esto genera insatisfacción en los miembros y dificulta la gestión operativa.

Who: Miembros y staff del gimnasio.
What: Necesidad de digitalizar accesos, planes y uso de máquinas con trazabilidad.
Where: Gimnasios urbanos con alto flujo de usuarios.
When: Durante la operación diaria de ingreso, entrenamiento y salida.
Why: La gestión manual genera errores, pérdidas de datos y mala experiencia de usuario.
How: Integrando biometría, NFC, pulseras de ritmo cardiaco y una aplicación móvil.
How much: Inversión inicial en hardware IoT, desarrollo de software y capacitación de personal.

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lea°n UX Problem Statements.
#### 1.2.2.2. Lean UX Assumptions.
|Business Assumptions|User Assumptions|
|-|-|
|1. - 12. |1. - 6.|
#### 1.2.2.3. Lean UX Hypothesis Statements.
Texto
#### 1.2.2.4. Lean UX Canvas.
(imagen con texto)
## 1.3. Segmentos objetivo.
| Variables | Segmento 1 | Segmento 2  |
| - | - |-|
| Geográfica                |  |  |
| Demográfica               |  |  |
| Psicológica               |  |  |
| Función de comportamiento |  |  |
---

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

<table>
  <thead>
    <tr>
      <th colspan="2">Competitive Analysis Landscape</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>¿Por qué llevar a cabo este análisis?</td>
      <td>Para identificar la posición de PumpUp frente a sus competidores y definir estrategias que potencien sus ventajas y mitiguen riesgos en el mercado fitness.</td>
    </tr>
  </tbody>
</table>


<br>

<table>
  <thead>
    <tr>
      <th></th>
      <th></th>
      <th>PumpUp</th>
      <th>MOKOSmart</th>
      <th>VTAP NFC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="3">PERFIL</th>
      <td>Overview</td>
      <td>PumpUp es una plataforma que integra una app móvil y una web para administrar gimnasios. Los usuarios ingresan con una pulsera NFC que también mide su ritmo cardíaco y muestra el rendimiento en la app. Los gimnasios gestionan membresías y monitorean asistencia y progreso desde el panel web.</td>
      <td>Sistema que integra pulseras inteligentes (“fitness bracelets”) diseñadas para gimnasios, con sensores, conectividad y funcionalidades de monitoreo, entrada automática, análisis de actividad, salud, etc.</td>
      <td>Solución centrada en eliminar tarjetas físicas, fobs o claves QR para ingreso y acceso en gimnasios, usando pases digitales NFC que se almacenan en Apple Wallet o Google Wallet, junto con lectores especializados (VTAP readers) para detectar esos pases.</td>
    </tr>
    <tr>
      <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
      <td>PumpUp combina control de acceso inteligente y métricas de salud en tiempo real, algo que la mayoría de soluciones actuales ofrecen por separado, brindando comodidad, motivación y datos precisos en un solo ecosistema.</td>
      <td>MOKOSmart integra control de acceso y monitoreo de salud en pulseras personalizables, ofreciendo datos en tiempo real que aumentan el engagement y optimizan el uso del gimnasio.</td>
      <td>VTAP NFC permite un acceso rápido y seguro con pases digitales en Apple/Google Wallet, reduciendo costos y mejorando la experiencia sin cambiar toda la infraestructura.</td>
    </tr>
    <tr>
      <td>Mercado Objetivo</td>
      <td>PumpUp se dirige a gimnasios que buscan modernizar su gestión y ofrecer experiencias personalizadas a sus miembros.
También apunta a usuarios fitness que desean controlar su progreso y acceder fácilmente con tecnología innovadora.</td>
      <td>Dirigido a gimnasios que buscan diferenciarse con tecnología avanzada, ofreciendo pulseras personalizables para monitorear salud y optimizar el uso de sus instalaciones.</td>
      <td>Apunta a gimnasios que quieren modernizar el control de acceso, reduciendo costos y mejorando la experiencia mediante pases digitales en dispositivos móviles.</td>
    </tr>
    <tr>
      <th>Perfil de marketing</th>
      <td>Estrategia de Marketing</td>
      <td>PumpUp usará una estrategia B2B2C: alianzas con gimnasios para implementar su sistema y captar usuarios finales mediante promociones, pruebas gratuitas y contenido en redes. Además, destacará su tecnología innovadora en campañas digitales y demostraciones presenciales para generar confianza y adopción.</td>
      <td>Estrategia B2B enfocada en vender soluciones personalizables de hardware IoT a gimnasios y cadenas fitness mediante alianzas y branding propio.</td>
      <td>Estrategia B2B destacando la eficiencia, seguridad y modernidad de su sistema para atraer gimnasios que buscan digitalizar el acceso de sus miembros.</td>
    </tr>
    <tr>
      <th rowspan="3">Perfil del producto</th>
      <td>Productos y servicios</td>
      <td>PumpUp ofrece una app móvil para usuarios, una web para gimnasios y pulseras NFC con sensor de ritmo cardíaco integradas al sistema.</td>
      <td>Pulseras y dispositivos IoT personalizables con servicios de diseño, integración y análisis de datos para gimnasios.</td>
      <td>Lectores NFC compatibles con Apple/Google Wallet y servicios de gestión remota e integración con sistemas de acceso.</td>
    </tr>
    <tr>
      <td>Precios y costos</td>
      <td>US$ 30-40</td>
      <td>US$ 40-60</td>
      <td>US$ 160-200</td>
    </tr>
    <tr>
      <td>Canales de distribución (Web y/o Móvil)</td>
      <td>Web y Móvil<br>Web</td>
      <td>Móvil<br>Web</td>
      <td>Web y móvil<br>Web</td>
    </tr>
  </tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.


<table>
  <thead>
    <tr>
      <th>Competidores</th>
      <th></th>
      <th>PumpUp</th>
      <th>MOKOSmart</th>
      <th>VTAP NFC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="4">Análisis SWOT</th>
      <td>Fortalezas</td>
      <td>Combina acceso NFC y monitoreo cardíaco en un solo dispositivo, centralizando datos en tiempo real para optimizar la experiencia del usuario y la gestión del gimnasio.</td>
      <td>Ofrece pulseras IoT personalizables que combinan control de acceso y monitoreo de salud, con integración a dashboards para análisis y entrenamiento.</td>
      <td>Brinda acceso rápido y seguro con pases digitales NFC, reduciendo costos operativos y mejorando la experiencia sin fricción para los usuarios.</td>
    </tr>
    <tr>
      <td>Debilidades</td>
      <td>Requiere inversión inicial en pulseras y lectores NFC, además de depender de la correcta integración tecnológica y el mantenimiento constante de los dispositivos.</td>
      <td>Requiere inversión y mantenimiento constante de las pulseras, además de una integración técnica compleja con otros sistemas.</td>
      <td>Depende de que los usuarios tengan dispositivos compatibles y exige una inversión inicial alta en lectores NFC certificados.</td>
    </tr>
    <tr>
      <td>Oportunidades</td>
      <td>El creciente interés por el fitness digital y el uso de wearables permite posicionar a PumpUp como una solución innovadora para modernizar gimnasios y atraer a usuarios que buscan experiencias personalizadas.</td>
      <td>Creciente demanda de experiencias fitness personalizadas permite expandir sus wearables como herramienta de seguimiento y fidelización.</td>
      <td>La digitalización de accesos en gimnasios impulsa la adopción de pases móviles, abriendo mercado en centros que aún usan tarjetas físicas.</td>
    </tr>
    <tr>
      <td>Amenazas</td>
      <td>La competencia de grandes marcas de wearables y posibles avances tecnológicos que vuelvan obsoleta la solución pueden limitar el crecimiento de PumpUp.</td>
      <td>Competencia de wearables de marcas consolidadas como Fitbit o Apple y posibles regulaciones sobre datos biométricos.</td>
      <td>Avances rápidos en tecnologías de acceso podrían volver obsoletos sus lectores y existe riesgo de ciberataques si no se actualizan.</td>
    </tr>
  </tbody>
</table>


## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
Segmento 1: Propietarios y administradores de gimnasios independientes

1. Datos personales y contexto

- ¿Cuál es tu nombre y edad?
- ¿Cuál es tu nivel de estudios?
- ¿Qué cargo ocupas en el gimnasio?
- ¿Cuántos años llevas en el rubro fitness o administrando tu negocio?
- ¿Usas algún dispositivo en tu trabajo diario (computadora, tablet, celular)? ¿Cuál usas con más frecuencia?

2. Operación del gimnasio

- ¿Cuántos colaboradores y clientes activos tienes?
- ¿Cómo gestionas actualmente las inscripciones, pagos y asistencia?
- ¿Qué herramientas digitales utilizas hoy en tu negocio? (Excel, software especializado, redes sociales, apps de pago)

3. Objetivos y motivaciones

- ¿Cuál es tu principal meta con el gimnasio (crecer, fidelizar clientes, rentabilidad, expandirte)?
- ¿Qué tipo de experiencia quieres dar a tus clientes?
- ¿Qué te motivó a abrir o administrar un gimnasio pequeño en lugar de otro tipo de negocio?

4. Frustraciones y retos

- ¿Qué es lo más difícil de gestionar en tu día a día?
- ¿Qué problemas frecuentes enfrentas con clientes, pagos o entrenadores?
- ¿Qué limitaciones encuentras en la tecnología que usas actualmente?

5. Decisiones y expectativas

- ¿Qué factores consideras antes de invertir en un nuevo sistema o aplicación?
- ¿Qué te haría confiar y recomendar una solución digital a otros dueños?
- ¿Qué funcionalidades esperas que tenga una plataforma para ayudarte en la gestión del gimnasio?

<h3>Segmento 2: Clientes y usuarios de servicios de entrenamiento</h3>

1. Datos personales y contexto


- ¿Cuál es tu nombre y edad?
- ¿Cuál es tu ocupación o actividad principal?
- ¿Qué dispositivo usas más para tus actividades diarias (celular, laptop, tablet)?
- ¿Con qué frecuencia entrenas actualmente? ¿Dónde entrenas?

2. Hábitos y comportamiento

- ¿Prefieres entrenar solo, en clases grupales o con entrenador personal?
- ¿Qué canales usas para informarte sobre gimnasios o entrenadores (redes sociales, recomendación, internet)?
- ¿Qué aplicaciones relacionadas con salud o fitness usas?

3. Objetivos y motivaciones

- ¿Qué te motiva a entrenar (salud, estética, rendimiento, socializar)?
- ¿Qué resultados esperas de un gimnasio o programa de entrenamiento?
- ¿Qué significa para ti una “buena experiencia” en un gimnasio?

4. Frustraciones y retos

- ¿Qué problemas has tenido en gimnasios anteriores (horarios, saturación, trato, pagos)?
- ¿Qué te ha hecho abandonar un gimnasio o dejar de entrenar?
- ¿Qué dificultades encuentras en apps o plataformas de entrenamiento?

5. Decisiones y expectativas

- ¿Qué factores son más importantes al elegir un gimnasio (ubicación, precio, variedad de clases, entrenadores)?
- ¿Qué funcionalidades valoras en una aplicación que complemente tu experiencia de entrenamiento?
- ¿Qué te haría recomendar un gimnasio o app a tus amigos?

### 2.2.2. Registro de entrevistas.

**Segmento 1** 

Nombre: Piero Espinoza
Edad: 25 años 
Ocupación: Administrador de gimnasio  
<img src="./assets/capitulo-2/entrevistas/entrevista-piero.png">  
**Resumen:**
Piero Espinosa tiene 25 años y es administrador de un gimnasio desde hace aproximadamente 3 años. Actualmente gestiona un equipo de 5 empleados y atienden a unos 120 clientes activos. Su principal objetivo es mantener la rentabilidad del negocio y lograr un crecimiento sostenible sin perder la calidad del servicio. Busca diferenciarse de las grandes cadenas ofreciendo un trato más personalizado y un ambiente de confianza. Considera que la experiencia del cliente es clave para su fidelización y para generar recomendaciones. Uno de sus mayores retos es competir contra el marketing y los bajos precios de las grandes cadenas. Además, enfrenta problemas recurrentes de organización relacionados con horarios y pagos que consumen mucho tiempo. Afirma que la tecnología que usan actualmente es básica y no integra todas las funciones necesarias. Al invertir en tecnología evalúa cuidadosamente el costo-beneficio, buscando herramientas fáciles de usar, con buen soporte y a bajo costo. Recomendaría una solución digital si realmente le ayudara a ahorrar tiempo, organizar mejor las operaciones y fortalecer la relación con los clientes.

Nombre: Mateo Vilchez
Edad: 20 años 
Ocupación: Asistente de administrador de gimnasio  
<img src="./assets/capitulo-2/entrevistas/entrevista-mateo.png">  
**Resumen:**
Mateo Vílchez Ríos, de 20 años y estudiante universitario, administró durante medio año un gimnasio pequeño en Trujillo llamado Albert Gym, donde la gestión se hacía de forma manual en cuadernos y con carnés de cartón, apoyándose únicamente en Facebook para promociones. Su experiencia incluyó trabajar junto a otro administrador y un entrenador de planta, enfrentando como principales retos la pérdida de clientes frente a cadenas con mejores ofertas, la baja fidelidad, problemas de control de membresías vencidas y la dificultad de mantener la satisfacción de los usuarios. Su objetivo era expandir el gimnasio y modernizarlo, ofreciendo una experiencia más segura y ordenada, con apoyo de herramientas digitales que eviten errores y caídas durante el horario laboral. Al evaluar nuevas soluciones, prioriza que el software sea confiable, fácil de adaptar a un gimnasio pequeño y con soporte personalizado. Entre las funcionalidades que espera están la gestión de matriculados y sus planes, el control del personal, la administración de promociones y la posibilidad de que el entrenador de planta registre rutinas o seguimientos básicos para los clientes.

**Segmento 2**  
Nombre: Darlin Bringas
Edad: 40 años 
Ocupación: Coordinadora de eventos  

<img src="./assets/capitulo-2/entrevistas/entrevista-darlin.png">  

**Enlace a la entrevista:**  
[Ver entrevista completa](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213384_upc_edu_pe/ETxU1L3TVeBLs5cHibYyz0ABomyxa4EorpyXIOu2karU6w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=NMQNqF)

**Resumen:**
Darlin Bringas tiene 40 años y trabaja como coordinadora de eventos. Actualmente entrena 3 veces por semana en SmartFit y prefiere las clases grupales porque le brindan mayor motivación. Su principal motivación para entrenar es mantener su salud y mantenerse activa físicamente. Busca un gimnasio ideal que tenga buen ambiente, entrenadores atentos y horarios flexibles que se adapten a su rutina laboral. Para medir sus avances utiliza métodos tradicionales como el peso, las medidas corporales y su resistencia física durante los entrenamientos. Ha enfrentado dificultades en gimnasios anteriores principalmente relacionadas con horarios poco accesibles y excesiva saturación durante las horas punta. La falta de motivación y la mala atención por parte de algunos entrenadores han sido factores que la han llevado a abandonar gimnasios en el pasado. Cuando evalúa aplicaciones de fitness, encuentra problemas con interfaces en inglés, complejidad de uso y falta de adaptación a sus rutinas personales. Los factores más importantes para elegir un gimnasio son la ubicación, la calidad de los entrenadores y el precio. Se informa principalmente a través de redes sociales y valora en una aplicación digital características como facilidad de uso, recordatorios de clases y seguimiento de su progreso personal.

### 2.2.3. Análisis de entrevistas.
**Segmento 1:**
{texto}
**Segmento 2:**
{texto}
## 2.3. Needfinding.
### 2.3.1. User Personas.
**Segmento 1:**  
![Imagen User Persona 1](image.jpg)

**Segmento 2:**
![Imagen User Persona 1](image.jpg)

### 2.3.2. User Task Matrix.
| --- | ------ | Segmento 1  | ------/----- | Segmento 2  | ---------- |
| --- | ------ | ----------- | ------------ | ----------- | ---------- |
| ID  | Titulo | Importancia | Frecuencia   | Importancia | Frecuencia |
| U01X| {Texto}| Alta        | Alta         | Media       | Baja       |
### 2.3.3. User Journey Mapping.
**Registration:**
Why would they trust us?
- s
- s
- s
  
**Onboarding and first use:**
How can they feel successful?
- s
- s
- s  
  
**Sharing:**
Why would they invite others?
- s
- s
- s

### 2.3.4. Empathy Mapping.
**Segmento 1:**
![Empathy Map Segmento1](image.jpg)

**Segmento 2:**
![Empathy Map Segmento1](image.jpg)
### 2.3.5. As-is Scenario Mapping.

**Segmento 1**  
Escenario: {escenario}

As Is:
| Fases| Fase 1 | Fase 2| Fase 3| Fase 4|
| -------- | --------- | --------- | ------- | --------- |
| Doing | texto| texto | texto| texto|
| Thinking | texto| texto | texto| texto|
| Feeling  | texto| texto | texto| texto|

**Segmento 2**  
Escenario: Dificultad para entender Matemáticas

As Is:
| Fases| Fase 1 | Fase 2| Fase 3| Fase 4|
| -------- | --------- | --------- | ------- | --------- |
| Doing | texto| texto | texto| texto|
| Thinking | texto| texto | texto| texto|
| Feeling  | texto| texto | texto| texto|
## 2.4 Big Picture EventStorming.

## 2.5. Ubiquitous Language.
```
Texto ubiquo: Definicion de este
```

---

# Capítulo III: Requirements Specification

## 3.1. User Stories.

| ID Épica | Nombre de la Épica             | Descripción                                                                 |
|----------|--------------------------------|-----------------------------------------------------------------------------|
| EP01     | Gestión de accesos             | Controlar entradas y salidas con distintos métodos de autenticación como NFC, biometría o tarjetas. |
| EP02     | Seguridad y monitoreo          | Garantizar la seguridad del edificio mediante alertas en tiempo real, paneles de control y gestión de incidentes. |
| EP03     | Monitoreo de ocupación         | Medir y visualizar la cantidad de personas en zonas del edificio en tiempo real y con reportes históricos. |
| EP04     | Infraestructura IoT Edge       | Asegurar que el sistema funcione localmente cuando no haya conexión a internet y que sincronice los datos con la nube. |
| EP05     | Integración corporativa        | Conectar el sistema con servicios y directorios existentes como Active Directory, LDAP o APIs de terceros. |
| EP06     | Administración y reporting     | Brindar a administradores y propietarios reportes financieros, de uso de espacios y estadísticas para toma de decisiones. |
| EP07     | Experiencia del usuario final  | Ofrecer a empleados y visitantes accesos rápidos, simples y confiables mediante aplicaciones o dispositivos. |
| EP08     | Gestión técnica y mantenimiento| Permitir a equipos de TI y operadores gestionar dispositivos IoT, realizar actualizaciones y monitorear el estado del sistema. |
| EP09     | Landing Page y marketing       | Mostrar información pública del servicio, beneficios, características principales y contacto para nuevos clientes. |


| ID   | Título                      | Descripción                                                                                      | Criterios de Aceptación                                                                                                        | Relacionado con (Epic ID) |
|------|-----------------------------|--------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| US01 | Acceso con huella biométrica| Como miembro quiero ingresar al gimnasio con mi huella para evitar el uso de credenciales físicas| Given que la huella está enrolada, When el miembro presenta la huella, Then el sistema valida y permite el ingreso.<br>Given que la huella no coincide, When el miembro intenta ingresar, Then el sistema rechaza el acceso y registra el intento fallido. | EP01                      |
| US02 | Registro de entrada y salida| Como administrador quiero que el sistema registre entradas y salidas para controlar la ocupación en tiempo real| Given que un miembro ingresa, When se valida el acceso, Then el sistema registra la hora de entrada.<br>Given que un miembro sale, When se detecta el check-out, Then el sistema registra la hora de salida. | EP01                      |
| US03 | Bloqueo de acceso            | Como administrador quiero bloquear el acceso de un miembro con plan vencido para cumplir con las reglas del gimnasio| Given que el plan está vencido, When el miembro intenta ingresar, Then el sistema rechaza el acceso y muestra un registro en la bitácora.<br>Given que el administrador bloquea un miembro manualmente, When este intenta acceder, Then el sistema rechaza la validación. | EP01                      |
| US04 | Acceso con tarjeta NFC       | Como miembro quiero ingresar al gimnasio con tarjeta NFC para contar con otra opción de autenticación rápida| Given que la tarjeta NFC está vinculada, When el miembro presenta la tarjeta, Then el sistema valida y abre el acceso.<br>Given que la tarjeta no está registrada, When se intenta usar, Then el sistema rechaza el acceso y lo registra como intento fallido. | EP01                      |
| US05 | Consulta de estado del plan    | Como miembro quiero consultar el estado de mi plan para saber si está vigente o próximo a vencer           | Given que el miembro accede a la app, When consulta su plan, Then el sistema muestra si está vigente, vencido o en pausa.                      | EP02                      |
| US06 | Renovación de membresía        | Como administrador quiero registrar la renovación de un plan para mantener actualizado el estado del miembro| Given que el administrador renueva el plan, When guarda los cambios, Then el sistema actualiza el estado y registra la fecha de vigencia.      | EP02                      |
| US07 | Suspensión de membresía        | Como administrador quiero suspender temporalmente un plan para atender solicitudes especiales de miembros   | Given que el administrador suspende un plan, When confirma la acción, Then el sistema cambia el estado a suspendido y guarda la trazabilidad. | EP02                      |
| US08 | Validación de acceso por plan  | Como miembro quiero que el sistema valide mi plan antes de ingresar para cumplir con las reglas del gimnasio| Given que el plan está vigente, When el miembro intenta ingresar, Then el acceso se autoriza.<br>Given que el plan está vencido, When intenta ingresar, Then el sistema rechaza el acceso. | EP02                      |
| US09 | Consulta de aforo actual       | Como miembro quiero consultar el aforo en tiempo real para decidir el mejor momento de ir al gimnasio       | Given que el miembro abre la app, When solicita aforo, Then el sistema muestra número de usuarios activos y porcentaje de ocupación.           | EP03                      |
| US10 | Monitoreo de aforo por sede    | Como administrador quiero visualizar el aforo por sede para supervisar la ocupación y tomar decisiones      | Given que el administrador ingresa al dashboard, When selecciona la sede, Then el sistema muestra número de usuarios actuales en tiempo real. | EP03                      |
| US11 | Alertas de sobreocupación      | Como administrador quiero recibir alertas cuando la ocupación supere el límite permitido                    | Given que la ocupación excede el 90%, When ocurre la validación, Then el sistema genera una alerta en el dashboard y envía notificación.      | EP03                      |
| US12 | Historial de visitas           | Como miembro quiero consultar mi historial de visitas para llevar un registro de asistencia personal        | Given que el miembro accede a la sección historial, When solicita ver registros, Then el sistema muestra entradas y salidas con fechas.       | EP03                      |
| US13 | Buffer de eventos en el IoT Edge                    | Como administrador quiero que el gateway IoT almacene eventos localmente cuando la conexión a la nube se pierde, para evitar pérdida de datos. | Given que el gateway pierde conexión con la nube, When los dispositivos generan eventos, Then el gateway almacena localmente cada evento con timestamp y identificador único.<br>Given que el gateway recupera la conexión, When inicia la sincronización, Then el gateway envía los eventos almacenados en el orden original y marca cada evento como sincronizado.<br>Given que la nube recibe el mismo evento duplicado, When se detecta duplicado, Then el sistema descarta el duplicado y conserva un único registro. | EP04                      |
| US14 | Autorización local durante corte de nube            | Como miembro quiero que el gateway permita el acceso si mi autorización está en caché del borde cuando la nube está inalcanzable. | Given que la autorización del miembro está en la caché del gateway, When el miembro presenta su credencial y la nube no está disponible, Then el gateway autoriza el acceso y registra el evento localmente.<br>Given que la autorización no está en la caché, When el miembro intenta acceder durante la desconexión, Then el gateway deniega el acceso y registra el intento.                                                         | EP04                      |
| US15 | Estado operativo del IoT Edge                       | Como administrador quiero conocer el estado operativo del gateway para reaccionar ante fallos.                          | Given que el gateway está operativo, When el administrador consulta el estado, Then el sistema informa "online" con el último heartbeat y la versión del firmware.<br>Given que el gateway no responde, When el administrador consulta el estado, Then el sistema informa "offline" con la marca de tiempo del último heartbeat y el código de error si está disponible.                                           | EP04                      |
| US16 | Actualización remota de firmware del gateway        | Como administrador quiero aplicar actualizaciones de firmware al gateway de manera remota para mantener seguridad y estabilidad. | Given que existe un paquete de firmware válido, When el administrador solicita la actualización, Then el gateway descarga, instala la actualización y reporta el resultado de la operación.<br>Given que la instalación falla, When el gateway detecta fallo, Then el gateway ejecuta el rollback a la versión previa y reporta el error.                                                    | EP04                      |
| US17 | Sincronización de usuarios desde directorio corporativo | Como administrador quiero sincronizar usuarios desde el directorio corporativo para mantener consistencia de cuentas.    | Given que el directorio contiene un registro de usuario con atributos requeridos, When la tarea de sincronización se ejecuta, Then el sistema crea o actualiza el registro local con los atributos mapeados y asigna el rol por defecto si aplica.<br>Given que el registro en el directorio está deshabilitado, When la sincronización detecta esto, Then el sistema marca el usuario como deshabilitado localmente. | EP05                      |
| US18 | Autenticación con SSO corporativo                   | Como miembro quiero autenticarme con mis credenciales corporativas para usar la misma identidad.                         | Given que el SSO está configurado y el miembro dispone de credenciales corporativas válidas, When el miembro inicia sesión usando SSO, Then el sistema valida el token y emite un token de acceso local que identifica al miembro.<br>Given que el token SSO es inválido o expirado, When el miembro intenta iniciar sesión, Then el sistema rechaza la autenticación y registra el intento.         | EP05                      |
| US19 | Propagación de cambios de roles desde el directorio | Como administrador quiero que los cambios de rol en el directorio se reflejen en el sistema para mantener permisos consistentes. | Given que el rol de un usuario cambia en el directorio, When la sincronización detecta el cambio, Then el sistema actualiza el rol del usuario local y registra el cambio en la bitácora.<br>Given que el directorio envía un rol no mapeado, When el sistema recibe el rol, Then el sistema asigna el rol por defecto y registra la incidencia para revisión.                                    | EP05                      |
| US20 | Generar reporte de ocupación por periodo            | Como administrador quiero generar reportes de ocupación en un rango de fechas para analizar uso de las instalaciones.    | Given que el administrador solicita un reporte con un rango de fechas válido, When el sistema procesa la solicitud, Then el sistema devuelve un reporte con total de visitas, ocupación máxima por periodo y ocupación promedio.<br>Given que el rango de fechas es inválido, When se procesa la solicitud, Then el sistema responde con error 400 y mensaje descriptivo.                         | EP06                      |
| US21 | Exportar reportes en formato CSV                    | Como administrador quiero exportar reportes en CSV para realizar análisis externos.                                    | Given que un reporte está disponible, When el administrador solicita la exportación, Then el sistema entrega el archivo CSV con campos: fecha, site_id, ocupacion_actual, ocupacion_maxima.<br>Given que ocurre un fallo en la generación del archivo, When el administrador solicita la exportación, Then el sistema responde con error 500 y registra el fallo.                          | EP06                      |
| US22 | Descarga de historial personal                      | Como miembro quiero descargar mi historial de visitas para revisar mi asistencia.                                      | Given que el miembro tiene registros de visitas en el rango solicitado, When el miembro solicita su historial, Then el sistema devuelve la lista de visitas con timestamps de entrada y salida.<br>Given que no existen registros en el rango solicitado, When el miembro solicita su historial, Then el sistema devuelve una lista vacía.                                       | EP06                      |
| US23 | Alertas por anomalías en patrones de acceso         | Como administrador quiero recibir alertas cuando se detecten patrones anormales de acceso para investigar incidentes.   | Given que las reglas de anomalía detectan un patrón (ej. múltiples accesos fallidos o picos inusuales), When ocurre la detección, Then el sistema genera una alerta con tipo de incidente, site_id y marcas de tiempo.<br>Given que la alerta existe, When el administrador consulta la lista de alertas, Then el sistema presenta la alerta con estado "new" hasta que se marque como "reviewed". | EP06                      |
| US24 | Integración con pasarela de pagos Culqi          | Como miembro quiero realizar pagos mediante Culqi para completar mis transacciones en la aplicación. | Given que el miembro selecciona un plan de pago válido, When procede a pagar con Culqi, Then el sistema redirige a la pasarela de Culqi y confirma el resultado.<br>Given que la transacción es exitosa, When Culqi devuelve la confirmación, Then el sistema registra el pago, activa el servicio y muestra un comprobante digital al miembro.                | EP07                      |
| US25 | Gestión de reembolsos                            | Como administrador quiero procesar reembolsos en Culqi para resolver incidencias de pago.            | Given que existe una transacción confirmada, When el administrador solicita un reembolso válido, Then el sistema envía la solicitud a Culqi y actualiza el estado de la transacción a "reembolsado".<br>Given que Culqi rechaza el reembolso, When el administrador consulta el estado, Then el sistema muestra el error y mantiene el estado original.          | EP07                      |
| US26 | Registro de facturación automática               | Como administrador quiero que el sistema genere comprobantes al completarse un pago con Culqi.       | Given que una transacción es exitosa, When Culqi envía confirmación, Then el sistema genera automáticamente un comprobante con número de operación, monto, fecha y datos del miembro.<br>Given que falla la generación, When el sistema intenta registrar el comprobante, Then notifica el error al administrador y marca el pago como pendiente de facturación. | EP07                      |
| US27 | Registro de logs de auditoría                    | Como administrador quiero que todas las operaciones relevantes se registren en un log de auditoría.  | Given que un usuario realiza una acción (ej. inicio de sesión, actualización de rol, pago), When la acción se completa, Then el sistema registra un evento en el log con usuario, acción, timestamp y resultado.<br>Given que un administrador consulta los logs, When solicita un rango de fechas, Then el sistema devuelve los eventos en orden cronológico. | EP08                      |
| US28 | Control de accesos por rol                       | Como administrador quiero definir permisos por rol para restringir acciones sensibles.                | Given que un usuario intenta realizar una acción, When el rol asignado no tiene permiso, Then el sistema bloquea la acción y registra el intento en el log.<br>Given que el usuario tiene permiso, When realiza la acción, Then el sistema la ejecuta y registra el evento en auditoría.                                                                    | EP08                      |
| US29 | Notificación de intentos fallidos                | Como administrador quiero recibir notificaciones de intentos de acceso fallidos para detectar riesgos.| Given que un miembro intenta iniciar sesión repetidamente con credenciales incorrectas, When el número de intentos excede el umbral, Then el sistema envía una notificación al administrador con detalles del usuario, IP y timestamp.<br>Given que el administrador consulta la notificación, Then puede marcarla como atendida o pendiente.                 | EP08                      |
| US30 | Visualización de información general en landing  | Como miembro quiero visualizar información clara en la landing page para entender la propuesta.      | Given que el visitante accede a la landing, When se carga la página, Then el sistema muestra secciones de valor, beneficios, planes y llamadas a la acción con botones de registro o contacto.<br>Given que el visitante cambia de idioma (ej. ES/EN), When selecciona la opción, Then el sistema muestra la misma información en el idioma elegido.            | EP09                      |
| US31 | Formulario de contacto                           | Como miembro quiero llenar un formulario de contacto en la landing para solicitar más información.   | Given que el visitante completa los campos obligatorios (nombre, correo, mensaje), When envía el formulario, Then el sistema valida los campos y envía la solicitud al correo de soporte.<br>Given que falta un campo obligatorio, When intenta enviar, Then el sistema muestra un mensaje de error y no envía el formulario.                             | EP09                      |
| US32 | Registro inicial desde la landing                | Como miembro quiero registrarme desde la landing para comenzar a usar la aplicación.                 | Given que el visitante accede a la landing, When selecciona la opción de registrarse, Then el sistema redirige al flujo de registro en la aplicación.<br>Given que el visitante completa los datos requeridos, When confirma el registro, Then el sistema crea la cuenta y lo redirige al panel inicial de la aplicación.                               | EP09                      |
| TS01 | API de autenticación segura | Como Developer, necesito implementar autenticación con JWT en Flask para proteger los recursos internos. | **Given** un usuario con credenciales válidas **When** realiza login **Then** recibe un token JWT. <br> **Given** credenciales inválidas **When** intenta login **Then** recibe error 401. | EP02 |
| TS02 | Middleware de validación de token | Como Developer, necesito middleware en Flask que valide tokens JWT en los endpoints protegidos. | **Given** un request con token válido **When** llega a un endpoint protegido **Then** se autoriza. <br> **Given** un token inválido **When** intenta acceso **Then** recibe error 403. | EP02 |
| TS03 | Configuración de base de datos MySQL | Como Developer, necesito conectar el monolito en Flask a una instancia de MySQL para almacenar usuarios, membresías y datos de IoT. | **Given** la aplicación corriendo **When** ejecuta conexión a MySQL **Then** debe ser exitosa. <br> **Given** query inválida **When** se ejecuta **Then** retorna error controlado. | EP01 |
| TS04 | Gestión de equipos IoT en backend | Como Developer, necesito implementar módulos internos en Flask para registrar y actualizar equipos IoT Edge. | **Given** un request válido **When** se registra un dispositivo **Then** queda guardado en MySQL. | EP04 |
| TS05 | Monitoreo y almacenamiento de sensores | Como Developer, necesito que el backend reciba datos de sensores IoT Edge y los almacene en la base de datos. | **Given** un sensor transmite datos **When** llegan al backend **Then** se registran en MySQL. | EP04 |
| TS06 | Configuración HTTPS en Flask | Como Developer, necesito habilitar HTTPS para que todas las comunicaciones cliente-servidor estén cifradas. | **Given** un request por HTTPS **When** llega al servidor **Then** se procesa correctamente. <br> **Given** un request HTTP **When** llega al servidor **Then** se redirige a HTTPS. | EP02 |
| TS07 | Implementación de CORS seguro | Como Developer, necesito configurar CORS en Flask para aceptar únicamente dominios autorizados. | **Given** un request desde dominio autorizado **When** llega al servidor **Then** se permite. <br> **Given** un dominio no autorizado **When** intenta acceder **Then** se bloquea con error 403. | EP02 |
| TS08 | Logs de auditoría | Como Developer, necesito implementar registro de eventos de acceso y operaciones críticas en el sistema monolítico. | **Given** un usuario accede con éxito **When** inicia sesión **Then** se registra en los logs. <br> **Given** ocurre un error crítico **When** se genera excepción **Then** se guarda en los logs. | EP01 |
| TS09 | API de pagos con Culqi | Como Developer, necesito integrar en el monolito la API de Culqi para procesar pagos de membresías. | **Given** datos de tarjeta válidos **When** se procesan **Then** Culqi responde con transacción confirmada. <br> **Given** datos inválidos **When** se procesan **Then** se rechaza el pago. | EP06 |
| TS10 | Envío de notificaciones internas | Como Developer, necesito implementar un módulo en Flask que gestione notificaciones por correo electrónico para administradores y miembros. | **Given** un evento programado **When** ocurre (ej. mantenimiento) **Then** se envía notificación por correo. | EP05 |

## 3.2. Impact Mapping.

![Impact Mapping](image.jpg)

## 3.3. Product Backlog.

| #Orden | User Story ID | Titulo| Descripción| Story Points (1/2/3/5/8) |
| ------ | ------------- | ----- | ---------- | ------------------------ |
| 1 | US30 | Visualización de información en landing | Como miembro quiero visualizar información clara en la landing page para entender la propuesta. | 2 |
| 2 | US31 | Formulario de contacto | Como miembro quiero llenar un formulario de contacto en la landing para solicitar más información. | 1 |
| 3 | US32 | Registro inicial desde la landing | Como miembro quiero registrarme desde la landing para comenzar a usar la aplicación. | 2 |
| 4 | US01 | Acceso con huella biométrica | Como miembro quiero ingresar al gimnasio con mi huella para evitar el uso de credenciales físicas. | 5 |
| 5 | US02 | Registro de entrada y salida | Como administrador quiero que el sistema registre entradas y salidas para controlar la ocupación en tiempo real. | 5 |
| 6 | US03 | Bloqueo de acceso | Como administrador quiero bloquear el acceso de un miembro con plan vencido para cumplir con las reglas del gimnasio. | 3 |
| 7 | US04 | Acceso con tarjeta NFC | Como miembro quiero ingresar al gimnasio con tarjeta NFC para contar con otra opción de autenticación rápida. | 3 |
| 8 | US05 | Consulta de estado del plan | Como miembro quiero consultar el estado de mi plan para saber si está vigente o próximo a vencer. | 2 |
| 9 | US06 | Renovación de membresía | Como administrador quiero registrar la renovación de un plan para mantener actualizado el estado del miembro. | 3 |
| 10 | US07 | Suspensión de membresía | Como administrador quiero suspender temporalmente un plan para atender solicitudes especiales de miembros. | 2 |
| 11 | US08 | Validación de acceso por plan | Como miembro quiero que el sistema valide mi plan antes de ingresar para cumplir con las reglas del gimnasio. | 3 |
| 23 | US20 | Generar reporte de ocupación por periodo | Como administrador quiero generar reportes de ocupación en un rango de fechas para analizar uso de las instalaciones. | 5 |
| 24 | US23 | Alertas por anomalías en accesos | Como administrador quiero recibir alertas cuando se detecten patrones anormales de acceso para investigar incidentes. | 3 |
| 25 | US21 | Exportar reportes en formato CSV | Como administrador quiero exportar reportes en CSV para realizar análisis externos. | 2 |
| 26 | US25 | Gestión de reembolsos | Como administrador quiero procesar reembolsos en Culqi para resolver incidencias de pago. | 3 |
| 27 | US22 | Descarga de historial personal | Como miembro quiero descargar mi historial de visitas para revisar mi asistencia. | 2 |
| 28 | US24 | Integración con pasarela de pagos Culqi | Como miembro quiero realizar pagos mediante Culqi para completar mis transacciones en la aplicación. | 5 |
| 29 | US27 | Registro de logs de auditoría | Como administrador quiero que todas las operaciones relevantes se registren en un log de auditoría. | 3 |
| 30 | US26 | Registro de facturación automática | Como administrador quiero que el sistema genere comprobantes al completarse un pago con Culqi. | 3 |
| 31 | US28 | Control de accesos por rol | Como administrador quiero definir permisos por rol para restringir acciones sensibles. | 3 |
| 32 | US29 | Notificación de intentos fallidos | Como administrador quiero recibir notificaciones de intentos de acceso fallidos para detectar riesgos. | 2 |
| 33 | US10 | Monitoreo de aforo por sede | Como administrador quiero visualizar el aforo por sede para supervisar la ocupación y tomar decisiones. | 5 |
| 12 | TS01 | API de autenticación segura | Como Developer necesito implementar autenticación con JWT en Flask para proteger los recursos internos. | 5 |
| 13 | TS03 | Configuración de base de datos MySQL | Como Developer necesito conectar el monolito en Flask a una instancia de MySQL para almacenar usuarios, membresías y datos de IoT. | 5 |
| 14 | TS02 | Middleware de validación de token | Como Developer necesito middleware en Flask que valide tokens JWT en los endpoints protegidos. | 3 |
| 15 | TS06 | Configuración HTTPS en Flask | Como Developer necesito habilitar HTTPS para que todas las comunicaciones cliente-servidor estén cifradas. | 3 |
| 16 | TS07 | Implementación de CORS seguro | Como Developer necesito configurar CORS en Flask para aceptar únicamente dominios autorizados. | 2 |
| 17 | TS09 | API de pagos con Culqi | Como Developer necesito integrar en el monolito la API de Culqi para procesar pagos de membresías. | 5 |
| 18 | TS08 | Logs de auditoría | Como Developer necesito implementar registro de eventos de acceso y operaciones críticas en el sistema monolítico. | 3 |
| 19 | TS04 | Gestión de equipos IoT en backend | Como Developer necesito implementar módulos internos en Flask para registrar y actualizar equipos IoT Edge. | 3 |
| 20 | TS05 | Monitoreo y almacenamiento de sensores | Como Developer necesito que el backend reciba datos de sensores IoT Edge y los almacene en la base de datos. | 3 |
| 21 | TS10 | Envío de notificaciones internas | Como Developer necesito implementar un módulo en Flask que gestione notificaciones por correo electrónico para administradores y miembros. | 2 |
| 22 | US02 | Registro de entrada y salida | Como administrador quiero que el sistema registre entradas y salidas para controlar la ocupación en tiempo real. | 5 |
| 23 | US10 | Monitoreo de aforo por sede | Como administrador quiero visualizar el aforo por sede para supervisar la ocupación y tomar decisiones. | 5 |
| 24 | US13 | Buffer de eventos en el IoT Edge | Como administrador quiero que el gateway IoT almacene eventos localmente cuando la conexión a la nube se pierde, para evitar pérdida de datos. | 5 |
| 25 | US14 | Autorización local durante corte de nube | Como miembro quiero que el gateway permita el acceso si mi autorización está en caché del borde cuando la nube está inalcanzable. | 3 |
| 26 | US09 | Consulta de aforo actual | Como miembro quiero consultar el aforo en tiempo real para decidir el mejor momento de ir al gimnasio. | 3 |
| 27 | US11 | Alertas de sobreocupación | Como administrador quiero recibir alertas cuando la ocupación supere el límite permitido. | 3 |
| 28 | US15 | Estado operativo del IoT Edge | Como administrador quiero conocer el estado operativo del gateway para reaccionar ante fallos. | 3 |
| 29 | US16 | Actualización remota de firmware del gateway | Como administrador quiero aplicar actualizaciones de firmware al gateway de manera remota para mantener seguridad y estabilidad. | 5 |
| 30 | US27 | Registro de logs de auditoría | Como administrador quiero que todas las operaciones relevantes se registren en un log de auditoría. | 3 |
| 31 | US23 | Alertas por anomalías en accesos | Como administrador quiero recibir alertas cuando se detecten patrones anormales de acceso para investigar incidentes. | 3 |
| 32 | US29 | Notificación de intentos fallidos | Como administrador quiero recibir notificaciones de intentos de acceso fallidos para detectar riesgos. | 2 |
| 33 | US20 | Generar reporte de ocupación por periodo | Como administrador quiero generar reportes de ocupación en un rango de fechas para analizar uso de las instalaciones. | 5 |
| 34 | US21 | Exportar reportes en formato CSV | Como administrador quiero exportar reportes en CSV para realizar análisis externos. | 2 |
| 35 | US24 | Integración con pasarela de pagos Culqi | Como miembro quiero realizar pagos mediante Culqi para completar mis transacciones en la aplicación. | 5 |
| 36 | US26 | Registro de facturación automática | Como administrador quiero que el sistema genere comprobantes al completarse un pago con Culqi. | 3 |
| 37 | US25 | Gestión de reembolsos | Como administrador quiero procesar reembolsos en Culqi para resolver incidencias de pago. | 3 |
| 38 | US22 | Descarga de historial personal | Como miembro quiero descargar mi historial de visitas para revisar mi asistencia. | 2 |
| 39 | US12 | Historial de visitas | Como miembro quiero consultar mi historial de visitas para llevar un registro de asistencia personal. | 2 |
| 40 | US17 | Sincronización de usuarios desde directorio corporativo | Como administrador quiero sincronizar usuarios desde el directorio corporativo para mantener consistencia de cuentas. | 3 |
| 41 | US18 | Autenticación con SSO corporativo | Como miembro quiero autenticarme con mis credenciales corporativas para usar la misma identidad. | 3 |
| 42 | US19 | Propagación de cambios de roles | Como administrador quiero que los cambios de rol en el directorio se reflejen en el sistema para mantener permisos consistentes. | 2 |

# Capítulo IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design.

### 4.1.1. Design-Level EventStorming.

#### 4.1.1.1 Candidate Context Discovery.

#### 4.1.1.2 Domain Message Flows Modeling.

#### 4.1.1.3 Bounded Context Canvases.

### 4.1.2. Context Mapping.
### 4.1.3. Software Architecture.
#### 4.1.3.1. Software Architecture System Landscape Diagram.
#### 4.1.3.2. Software Architecture Context Level Diagrams.
#### 4.1.3.2. Software Architecture Container Level Diagrams.
#### 4.1.3.3. Software Architecture Deployment Diagrams.
## 4.2. Tactical-Level Domain-Driven Design


### 4.2.X. Bounded Context:
#### 4.2.X.1. Domain Layer.
#### 4.2.X.2. Interface Layer.
#### 4.2.X.3. Application Layer.
#### 4.2.X.4. Infrastructure Layer.
#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams..

##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.X.6.2. Bounded Context Database Design Diagram.

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines.
### 5.1.1. General Style Guidelines.
### 5.1.2. Web, Mobile and IoT Style Guidelines.
## 5.2. Information Architecture.
### 5.2.1. Organization Systems.
### 5.2.2. Labeling Systems.
### 5.2.3. SEO Tags and Meta Tags
### 5.2.4. Searching Systems.
### 5.2.5. Navigation Systems.
## 5.3. Landing Page UI Design.
### 5.3.1. Landing Page Wireframe.
### 5.3.2. Landing Page Mock-up.
## 5.4. Applications UX/UI Design.
### 5.4.1. Applications Wireframes.
### 5.4.2. Applications Wireflow Diagrams.
### 5.4.2. Applications Mock-ups.
### 5.4.3. Applications User Flow Diagrams.
## 5.5. Applications Prototyping.


# Capítulo VI: Product Implementation, Validation & Deployment
## 6.1. Software Configuration Management.
### 6.1.1. Software Development Environment Configuration.
### 6.1.2. Source Code Management.
### 6.1.3. Source Code Style Guide & Conventions.
### 6.1.4. Software Deployment Configuration.

## 6.2. Landing Page, Services & Applications Implementation.

### 6.2.X. Sprint n
#### 6.2.X.1. Sprint Planning n.
#### 6.2.X.2. Aspect Leaders and Collaborators.
#### 6.2.X.3. Sprint Backlog n.
#### 6.2.X.4. Development Evidence for Sprint Review.
#### 6.2.X.5. Testing Suite Evidence for Sprint Review.
#### 6.2.X.6. Execution Evidence for Sprint Review.
#### 6.2.X.7. Services Documentation Evidence for Sprint Review.
#### 6.2.X.8. Software Deployment Evidence for Sprint Review.
#### 6.2.X.9. Team Collaboration Insights during Sprint.

## 6.3. Validation Interviews.
### 6.3.1. Diseño de Entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿[Opinion de idea de propuesta]? 

**Entrevistas usuario segmento 2**
1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?  
   
**Entrevistas usuario segmento 2**
1. ¿Lorem? 
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem? 
### 6.3.2. Registro de Entrevistas.
**Segmento 1**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)  
{texto mucho}

**Segmento 2**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)
{texto}
### 6.3.3. Evaluaciones según heurísticas.
| HEURÍSTICA   | EVALUACIÓN | NOTA      |
| --------------------------------------------- | ---------- | --------- |
| Visibilidad del estado del sistema            |            | {texto}   |
| Coincidencia entre el sistema y el mundo real |            | {texto}   |
| Control y libertad del usuario                |            | {texto}   |
| Consistencia y estándares                     |            | {texto}   |
| Prevención de errores                         |            | {texto}   |
| Mostrar antes que recordar                    |            | {texto}   |
| Flexibilidad y eficiencia de uso              |            | {texto}   |
| Diseño estético y minimalista                 |            | {texto}   |
| Comunicar errores con facilidad               |            | {texto}   |
| Ayuda y documentación                         |            | {texto}   |
## 6.4. Video About-the-Product.
[URL del video about the product](https://www.example.com)
# Conclusiones

1. La arquitectura definida permitió organizar el sistema en dominios y módulos claros, favoreciendo la modularidad y la integración con servicios externos sin comprometer la coherencia del monolito planteado.

2. El alcance del proyecto se centró en equilibrar la experiencia de usuario, representada principalmente en la landing page, con el desarrollo de procesos internos como la gestión de planes, reservas y pagos, asegurando valor tanto para los usuarios finales como para la operación del sistema.

3. La gestión del backlog permitió mantener un control ordenado de las 42 historias de usuario, priorizando las relacionadas a la landing page y asignando esfuerzos realistas a cada tarea, lo que facilita la ejecución de sprints y el seguimiento del avance del proyecto.


# Video About-the-Team.
[URL del video about the team](https://www.example.com)

# Bibliografía

Bass, L., Clements, P., & Kazman, R. (2021). Software Architecture in Practice (4th ed.). Addison-Wesley.

Richards, M., & Ford, N. (2020). Fundamentals of Software Architecture: An Engineering Approach. O’Reilly Media.

Fowler, M. (2018). Patterns of Enterprise Application Architecture. Addison-Wesley.

Hossain, E., Muhammad, G., & Rahman, M. (2020). Cloud and IoT-based smart security and monitoring systems: A comprehensive review. Sustainable Cities and Society, 61, 102360. https://doi.org/10.1016/j.scs.2020.102360

Rozanski, N., & Woods, E. (2012). Software Systems Architecture: Working with Stakeholders Using Viewpoints and Perspectives (2nd ed.). Addison-Wesley.

# Anexos
Entevistas needfinding: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211212_upc_edu_pe/EXvX6UhgOwRHu-TdxGSTKJgBtMWEiwYBFuJdf7YpkJPKMQ?e=Om1c40&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D




