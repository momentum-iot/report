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
|  U202213384 | Pinto Fuentes Rivera, Alvaro Felipe  |
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
|Trabaja en equipo para proporcionar liderazgo en forma conjunta.|Compañero1:<br> *TB1:*  <p>* texto etc.. </p> |TB1 <p>Conclusion</p>|
|Trabaja en equipo para proporcionar liderazgo en forma conjunta|Compañero1:<br> *TB1:*  <p>* texto etc.. </p> |TB1 <p>Conclusion</p>|
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-|
|Compañero 1 	![Imagen del compañero](image.jpg)|U20...|Ingenieria de software|C++, piton .etc|
|Carlos Sanchez Montero <img src="./assets/capitulo-1/miembros/carlos.jpeg">|U202015274|Ingenieria de software|C++, C#, Python, JavaScript, Java, Flutter, Vue, Angular|
|Alvaro Pinto Fuentes Rivera <img src="./assets/capitulo-1/miembros/alvaro.png">|U202213384|Ingenieria de software|C++, C#, Java, Python, SQL, Vue, Angular, Flutter, Kotlin|

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
#### 1.2.2.1. Lean UX Problem Statements.

**Problem Statement:**

**1. Domain:**

El dominio corresponde al sector fitness y bienestar, específicamente a la gestión tecnológica de gimnasios independientes y centros de entrenamiento de pequeña y mediana escala. Se centra en el uso de tecnologías IoT, biometría, sensores de actividad y plataformas digitales para automatizar procesos operativos, mejorar la experiencia del usuario y optimizar la gestión de recursos en gimnasios urbanos con alto flujo de usuarios.

**2. Customer Segments:**

**Propietarios y administradores de gimnasios independientes:**
- Gestionan procesos manuales de control de accesos y seguimiento de equipos
- Carecen de herramientas tecnológicas integradas para la gestión operativa
- Tienen recursos económicos limitados para invertir en tecnología costosa
- Buscan diferenciarse de las grandes cadenas con un servicio más personalizado
- Necesitan optimizar la rentabilidad sin perder calidad en el servicio

**Usuarios y miembros de gimnasios:**
- Buscan una experiencia de entrenamiento moderna y personalizada
- Quieren visibilidad de su progreso y métricas de rendimiento
- Valoran la comodidad en procesos de acceso y gestión de membresías
- Desean evitar la saturación y tener información en tiempo real del gimnasio

**3. Pain Points:**

**Gestión manual y propensa a errores:** Los registros en planillas generan pérdida de información, errores en facturación y dificultades para el seguimiento de miembros activos.

**Falta de control de aforo en tiempo real:** El control manual no permite conocer la ocupación actual, generando sobresaturación en horas pico y subutilización en otros horarios.

**Ausencia de trazabilidad de uso de equipos:** No existe información confiable sobre qué máquinas usa cada miembro, cuánto tiempo entrena, o si hay uso indebido de los equipos.

**Experiencia de usuario limitada:** Los miembros no tienen acceso a su historial de visitas, métricas de progreso o información útil para mejorar su entrenamiento.

**Herramientas tecnológicas fragmentadas:** Las soluciones existentes son costosas, complejas de implementar o no integran todas las funcionalidades necesarias para gimnasios pequeños.

**Carga operativa excesiva para el personal:** La gestión manual consume tiempo valioso que podría dedicarse a atención al cliente y mejora del servicio.

**4. Gap:**

Existe una brecha crítica en el acceso a soluciones de gestión inteligente para gimnasios que sean:

**Accesibles económicamente para gimnasios independientes:** El mercado está dominado por soluciones empresariales costosas, diseñadas para grandes cadenas y fuera del alcance de gimnasios pequeños y medianos.

**Fáciles de implementar y usar:** Muchas tecnologías requieren infraestructura compleja, capacitación extensa o soporte técnico constante, lo cual no es viable para operaciones pequeñas.

**Integradas y completas:** Las soluciones actuales suelen cubrir solo aspectos específicos (pagos, accesos, o entrenamiento) sin ofrecer una plataforma unificada.

**Enfocadas en la experiencia dual:** Pocas herramientas equilibran las necesidades operativas del gimnasio con la experiencia y engagement de los usuarios.

**5. Vision / Strategy:**

La visión de Momentum con PumpUp es democratizar el acceso a la gestión inteligente de gimnasios, convirtiendo la tecnología IoT en una ventaja competitiva accesible para cualquier gimnasio independiente. Para eso, se propone:

- Desarrollar una solución IoT modular y escalable que integre control de accesos biométrico, monitoreo de equipos y gestión de miembros en una sola plataforma.
- Ofrecer automatización de procesos operativos críticos, reduciendo la carga administrativa y mejorando la precisión en la gestión de datos.
- Diseñar una experiencia de usuario intuitiva tanto para administradores como para miembros, con dashboards visuales y aplicación móvil fácil de usar.
- Proporcionar insights y analytics en tiempo real que permitan tomar decisiones informadas sobre operación, marketing y mejora del servicio.
- Crear un ecosistema conectado que fomente la fidelización de miembros a través de gamificación, seguimiento de progreso y recomendaciones personalizadas.
#### 1.2.2.2. Lean UX Assumptions.

**Business Assumptions:**

1. Los propietarios de gimnasios independientes están dispuestos a adoptar tecnología IoT si perciben una mejora directa en eficiencia operativa y rentabilidad.

2. La creciente competencia con grandes cadenas de gimnasios generará demanda por soluciones tecnológicas que permitan diferenciación y mejor servicio al cliente.

3. La tendencia post-pandemia hacia el fitness digital y el seguimiento de salud personal continuará impulsando la adopción de tecnologías de monitoreo.

4. Existen líneas de financiamiento para digitalización de pequeñas empresas que podrían facilitar la adquisición de soluciones como PumpUp.

5. Las regulaciones de aforo y control sanitario permanecerán como requerimientos operativos, favoreciendo sistemas de monitoreo automático.

6. El mercado latinoamericano de gimnasios independientes tiene una base diversa que requiere soluciones flexibles y adaptables a diferentes tamaños de operación.

7. La brecha tecnológica entre gimnasios grandes y pequeños crea una oportunidad significativa para democratizar el acceso a tecnología avanzada.

8. Las recomendaciones y el marketing boca a boca serán canales clave para generar confianza y promover la adopción en el sector fitness local.

**Business Outcomes:**

- Aumento sostenido de ventas y adopción de PumpUp en gimnasios independientes de Lima y principales ciudades del Perú.
- Reducción del tiempo de gestión administrativa entre 40% y 60% mediante automatización de procesos operativos.
- Mejora en la retención de miembros hasta en un 35% gracias a mejor experiencia de usuario y engagement.
- Expansión del mercado objetivo hacia otros países de la región con ecosistemas de gimnasios independientes similares.
- Creación de alianzas con distribuidores de equipos de gimnasio, proveedores de software fitness y consultores del sector.
- Posicionamiento de Momentum como referente de innovación en el sector fitness tech en eventos especializados y medios del sector.
- Generación de datos valiosos del comportamiento de usuarios y operación de gimnasios para futuros desarrollos de producto.

**User Assumptions:**

**¿Quién es el usuario?**
- Propietarios y administradores de gimnasios independientes de 25-50 años con experiencia en el sector fitness.
- Miembros de gimnasios urbanos de 18-45 años, tech-savvy, que valoran la conveniencia y el seguimiento de su progreso fitness.

**¿Qué problemas tiene nuestro producto que resolver?**
- Gestión manual ineficiente, falta de control de aforo, ausencia de trazabilidad de uso de equipos, experiencia de usuario limitada, herramientas fragmentadas.

**¿Qué características son importantes?**
- Control de acceso biométrico/NFC, monitoreo en tiempo real de aforo y equipos, dashboard administrativo intuitivo, app móvil para miembros, analytics e insights operativos.

**¿Dónde encaja nuestro producto en su trabajo o vida?**
- En la gestión diaria del gimnasio para administradores, y en la rutina de entrenamiento para miembros, proporcionando datos útiles y automatizando procesos manuales.

**¿Cuándo y cómo es usado nuestro producto?**
- Durante toda la operación del gimnasio; se utiliza a través de una aplicación web para administradores y móvil para miembros, funcionando con sensores IoT instalados en el gimnasio.

**¿Cómo debe verse nuestro producto y cómo comportarse?**
- Debe tener interfaces limpias y modernas, ser responsive y funcionar de manera confiable offline cuando sea necesario.
- El sistema debe comportarse de forma predictiva, con notificaciones relevantes y procesos automatizados transparentes.

**User Outcomes:**

- Mayor control operativo con visibilidad en tiempo real de todos los aspectos del gimnasio (aforo, equipos, miembros).
- Ahorro de tiempo administrativo significativo, permitiendo enfocar más recursos en atención al cliente y mejora del servicio.
- Incremento en la satisfacción y retención de miembros gracias a una experiencia más moderna y personalizada.
- Reducción del estrés operativo al contar con sistemas automatizados que manejan tareas repetitivas.
- Mejor toma de decisiones basada en datos reales sobre patrones de uso, horarios pico y preferencias de miembros.
- Adopción de una cultura de gestión basada en datos que mejore la profesionalización del negocio.
- Mayor competitividad frente a gimnasios grandes gracias a tecnología de nivel empresarial.
- Escalabilidad para el crecimiento del negocio sin incrementar proporcionalmente la carga operativa.

**Feature Assumptions:**

- Los sensores IoT podrán operar de manera confiable en el ambiente de un gimnasio (humedad, temperatura, vibraciones) sin requerir mantenimiento frecuente.
- El sistema de control de acceso biométrico/NFC funcionará rápidamente y sin fricciones, incluso durante las horas pico.
- La plataforma web será intuitiva y accesible desde dispositivos diversos, incluyendo tablets y smartphones de gama media.
- La aplicación móvil funcionará eficientemente en dispositivos Android e iOS, con sincronización en tiempo real cuando haya conectividad.
- Los reportes y analytics estarán personalizados por tipo de gimnasio, tamaño de operación y objetivos específicos del negocio.
- El sistema tendrá capacidad de integración con otros software comunes en gimnasios (facturación, CRM, redes sociales).
- La solución será escalable desde gimnasios pequeños (50 miembros) hasta medianos (500+ miembros) con configuración modular.
- El producto incluirá capacitación y soporte en español, con documentación clara y videos tutoriales para facilitar la adopción.
#### 1.2.2.3. Lean UX Hypothesis Statements.

**Creemos que** los propietarios de gimnasios independientes adoptarán PumpUp si perciben una reducción significativa en el tiempo de gestión administrativa y mayor control operativo. **Sabremos que esto es cierto cuando** al menos el 75% de los usuarios en piloto reporten una reducción del 40% o más en tiempo dedicado a tareas administrativas durante los primeros 2 meses de uso.

**Creemos que** una interfaz de administración intuitiva y dashboards visuales facilitarán que administradores sin experiencia técnica puedan gestionar el sistema sin capacitación extensiva. **Sabremos que esto es cierto cuando** el 80% de los administradores puedan completar las tareas principales (revisar aforo, generar reportes, gestionar miembros) sin soporte técnico durante las pruebas de usabilidad.

**Creemos que** la automatización del control de accesos y monitoreo de equipos mejorará significativamente la experiencia de los miembros del gimnasio. **Sabremos que esto es cierto cuando** el 70% de los miembros reporten mayor satisfacción con su experiencia de entrenamiento y el índice de retención aumente en al menos 25% después de 6 meses de implementación.

**Creemos que** los miembros valorarán tener acceso a sus métricas de progreso y estadísticas de entrenamiento a través de la aplicación móvil. **Sabremos que esto es cierto cuando** al menos el 60% de los miembros usen activamente la app móvil al menos 3 veces por semana y el 40% compartirán sus logros en redes sociales.

**Creemos que** el sistema podrá escalarse fácilmente a diferentes tamaños y tipos de gimnasios sin requerir customizaciones complejas. **Sabremos que esto es cierto cuando** al menos 3 tipos distintos de gimnasios (boutique fitness, gimnasio tradicional y centro de crossfit) implementen el sistema sin requerir modificaciones técnicas significativas.

**Creemos que** un proceso de instalación guiado y soporte en español aumentará la tasa de adopción exitosa sin requerir visitas técnicas frecuentes. **Sabremos que esto es cierto cuando** más del 80% de los gimnasios completen la instalación e integración inicial sin intervención presencial del equipo de soporte técnico.

**Creemos que** los insights y analytics en tiempo real ayudarán a los administradores a tomar mejores decisiones de negocio y optimizar sus operaciones. **Sabremos que esto es cierto cuando** el 65% de los usuarios reporten haber implementado al menos 2 mejoras operativas basadas en los datos proporcionados por PumpUp en los primeros 4 meses de uso.
#### 1.2.2.4. Lean UX Canvas.

<img src="./assets/capitulo-1/lean_ux_canvas/Lean UX Canvas.png">

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

| Competitive Analysis Landscape                          |  |
| ------------------------------------------------------- | -|
| ¿Por qué llevar a cabo este análisis?                   | -- |


| |  | (Nosotros) | Competidor  | Comptdor |
|-|-|-|-|-|
| PERFIL| Overview | lorem | ipsum | lorem |
|| Ventaja competitiva ¿Qué valor ofrece a los clientes? |  ipsu | impuz |
|| Mercado Objetivo                                        | Jeda | asa | asa2 |
| Perfil de marketing                                     | Estrategia de Marketing | Redes Sociales | Redes Sociales | Televisión, Redes Sociales |
| Perfil del producto                                     | Productos y servicios | Elementos Gráficos Interactivos Enseñanza de Matemáticas Lúdica y Autodidacta Educación matemática interactiva Ámbito Freemium | Educación matemática interactiva Mas de 100 cursos en 28 idiomas diferentes | Educación general interactiva Contratos con Movistar |
|| Precios y costos                                        | Freemium (Cuenta Premium permite personalizar los juegos) Gratis | Gratuito | Gratuito |
|| Canales de distribución (Web y/o Móvil)                 | Web y Móvil Web | Móvil Web | Web y móvil Web |
### 2.1.2. Estrategias y tácticas frente a competidores.


|Competidores ->|  | Nosotros | Competidor2| Competidor3|
|-|-|-|-|-|
| Análisis SWOT | Fortalezas | lorem | Lorem | lorem |
|| Debilidades   | lorem | lorem | lorem | lorem | 
|| Oportunidades | lorem | lorem | lorem | lorem | 
|| Amenazas      | lorem | lorem | lorem | lorem |

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


**Segmento 2**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)
{texto}

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

| HU0X | Historia Usuario | "Descripcion"  |
|-|-|-|

## 3.2. Impact Mapping.

![Impact Mapping](image.jpg)

## 3.3. Product Backlog.

| #Orden | User Story ID | Titulo| Descripción| Story Points (1/2/3/5/8) |
| ------ | ------------- | ----- | ---------- | ------------------------ |
| 1      | HU01          | titulo his | desc  | 5                        |

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
{texto}
# Conclusiones y recomendaciones.
{texto}
# Video About-the-Team.
[URL del video about the team](https://www.example.com)

# Bibliografía
qoomon. (2021, 11 enero). Conventional Commit Messages. Gist.
Recuperado 20 de junio de 2022, de [LINK](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

LeaseIN. (2018). Importancia de contar con un equipo de soporte
técnico. [Entrada en blog]. Recuperado de:
[LINK](https://leasein.pe/blog/branding-empresarial-importanciasoporte-tecnico/)
``` 
formato

"Apellido", Ini.Ciales. & "otroAutor", O.A. (año). titulo del articulo.
        "nombre del articulo o lo q sea, Volumen(si es que tiene), numero  de pagina"#-#. https//link.org/eeeseneko

```
# Anexos

datos, gráficos, imágenes, esquemas, mapas o referencias de otros autores

![Imagen de algo no nuestro ](image.jpg)






