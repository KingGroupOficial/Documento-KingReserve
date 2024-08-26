UNIVERSIDAD PERUANA<br>
 DE CIENCIAS APLICADAS



  <img src="https://hackmd.io/_uploads/ryJoz7YcR.png" alt="Logo" />



  **SI730 Apliaciones Web** <br>
    **Sección: WS51**<br>
    **Carrera: Ingeniería de Software**<br>
    **Ciclo: 5-6**<br>
    **Profesor:**<br>
    **Hugo Allan Mori Paiva**<br>
    **"Informe de Trabajo Final"**<br>
    **Tema:Reservas**<br>
    **Producto: KingReserve de KingGroup**<br>
    **Agosto 2024**<br>

**Integrantes:**


- Gómez Vallejos Sergio André - U20221D401
- Rojas Velasquez Maycol Jhordan - U202219984
- Zevallos Linares Alessandro Netto - U202216035


<p style="text-align: center;">
  <strong>Registro de versiones de informe:</strong><br>
</p>



| Entregables  | Fecha | Autor | Descripción de modificación |
|-----------|-----------|-----------|-----------|
| TB1| 03/08/2024 | Sergio André Gómez Vallejos | Implementación de contenido en el Student Outcome <br> Registrar las entrevistas<br> Desarrollo del Contenido II<br> Competidores<br> User Journey Mapping <br> Perfil de integrante <br> Desarrollar el Capitulo IV <br> Implementar en el Capitulo V|
| TP | Fila 2, Columna 2 | Fila 2, Columna 3 | Fila 2, Columna 4 |
| TB2 | Fila 3, Columna 2 | Fila 3, Columna 3 | Fila 3, Columna 4 |
| TF | Fila 4, Columna 2 | Fila 4, Columna 3 | Fila 4, Columna 4 |


**Project Report Collaboration Insights**

### URL del Repositorio 
https://github.com/KingGroupOficial/Documento-KingReserve




<p style="text-align: center; font-weight: bold;">
  Tabla de contenido
  
</p>

1. [CAPÍTULO I: Introducción](#CAPÍTULO-I-Introducción)<br>
      1.1. [Startup Profile](#Startup-Profile)<br>
      1.1.1. [Descripción de la Startup](#Descripción-de-la-Startup)<br>
      1.1.2. [Perfiles de integrantes del equipo](#Perfiles-de-integrantes-del-equipo)<br>
   1.2. [Solution Profile](#Solution-Profile)<br>
      1.2.1. [Antecedentes y problemática](#Antecedentes-y-problemática)<br>
      1.2.2. [Lean UX Process](#Lean-UX-Process)<br>
             1.2.2.1 [Lean UX Problem Statements](#Lean-UX-Problem-Statements)<br>
             1.2.2.2 [Lean UX Assumptions](#Lean-US-Assumptions)<br>
             1.2.2.3 [Lean UX Hypothesis Statements](#Lean-UX-Hypothesis-Statements)<br>
             1.2.2.4 [Lean UX Canvas](#Lean-UX-Canvas) <br>
1.3. [Segmentos objetivo](#Segmentos-objetivo) <br>
2. [CAPÍTULO II: Requirements Elicitation & Analysis](#Capítulo-II-Requirements-Elicitation--Analysis) <br>
   2.1. [Competidores](#Competidores) <br>
      2.1.1. [Análisis competitivo](#Análisis-competitivo) <br>
      2.1.2. [Estrategias y tácticas frente a competidores](#Estrategias-y-tácticas-frente-a-competidores) <br>
   2.2. [Entrevistas](#Entrevistas) <br>
      2.2.1. [Diseño de entrevistas](#Diseño-de-entrevistas) <br>
      2.2.2. [Registro de entrevistas](#Registro-de-entrevistas)<br> 
      2.2.3. [Análisis de entrevistas](#Análisis-de-entrevistas)<br> 
   2.3. [Needfinding](#Needfinding) <br>
      2.3.1. [User Personas](#User-Personas) <br>
      2.3.2. [User Task Matrix](#User-Task-Matrix) <br>
      2.3.3. [User Journey Mapping](#User-Journey-Mapping) <br>
      2.3.4. [Empathy Mapping](#Empathy-Mapping) <br>
      2.3.5. [As-is Scenario Mapping](#As-is-Scenario-Mapping) <br>
   2.4. [Ubiquitous Language](#Ubiquitous-Language) <br>
3. [CAPÍTULO III: Requirements Specification](#Capítulo-III-Requirements-Specification) <br>
   3.1. [To-Be Scenario Mapping](#To-Be-Scenario-Mapping) <br>
   3.2. [User Stories](#User-Stories) <br>
   3.3. [Impact Mapping](#Impact-Mapping) <br>
   3.4. [Product Backlog](#Product-Backlog) <br>
4. [CAPÍTULO IV: Product Design](#Capítulo-IV-Product-Design) <br>
   4.1. [Style Guidelines](#Style-Guidelines) <br>
      4.1.1. [General Style Guidelines](#General-Style-Guidelines) <br>
      4.1.2. [Web Style Guidelines](#Web-Style-Guidelines) <br>
   4.2. [Information Architecture](#Information-Architecture) <br>
      4.2.1. [Organization Systems](#Organization-Systems) <br>
      4.2.2. [Labeling Systems](#Labeling-Systems) <br>
      4.2.3. [SEO Tags and Meta Tags](#SEO-Tags-and-Meta-Tags) <br>
      4.2.4. [Searching Systems](#Searching-Systems) <br>
      4.2.5. [Navigation Systems](#Navigation-Systems) <br>
   4.3. [Landing Page UI Design](#Landing-Page-UI-Design) <br>
      4.3.1. [Landing Page Wireframe](#Landing-Page-Wireframe) <br>
      4.3.2. [Landing Page Mock-up](#Landing-Page-Mock-up) <br>
   4.4. [Web Applications UX/UI Design](#Web-Applications-UX-UI-Design) <br>
      4.4.1. [Web Applications Wireframes](#Web-Applications-Wireframes) <br>
      4.4.2. [Web Applications Wireflow Diagrams](#Web-Applications-Wireflow-Diagrams) <br>
      4.4.3. [Web Applications Mock-ups](#Web-Applications-Mock-ups) <br>
      4.4.4. [Web Applications User Flow Diagrams](#Web-Applications-User-Flow-Diagrams) <br>
   4.5. [Web Applications Prototyping](#Web-Applications-Prototyping) <br>
   4.6. [Domain-Driven Software Architecture](#Domain-Driven-Software-Architecture) <br>
      4.6.1. [Software Architecture Context Diagram](#Software-Architecture-Context-Diagram) <br>
      4.6.2. [Software Architecture Container Diagrams](#Software-Architecture-Container-Diagrams) <br>
      4.6.3. [Software Architecture Components Diagrams](#Software-Architecture-Components-Diagrams) <br>
   4.7. [Software Object-Oriented Design](#Software-Object-Oriented-Design) <br>
      4.7.1. [Class Diagrams](#Class-Diagrams) <br>
      4.7.2. [Class Dictionary](#Class-Dictionary) <br>
   4.8. [Database Design](#Database-Design) <br>
      4.8.1. [Database Diagram](#Database-Diagram) <br>
5. [CAPÍTULO V: Product Implementation, Validation & Deployment](#Capítulo-V-Product-Implementation--Validation--Deployment) <br>
   5.1. [Software Configuration Management](#Software-Configuration-Management) <br>
      5.1.1. [Software Development Environment Configuration](#Software-Development-Environment-Configuration) <br>
      5.1.2. [Source Code Management](#Source-Code-Management) <br>
      5.1.3. [Source Code Style Guide & Conventions](#Source-Code-Style-Guide--Conventions) <br>
      5.1.4. [Software Deployment Configuration](#Software-Deployment-Configuration) <br>
   5.2. [Landing Page, Services & Applications Implementation](#Landing-Page--Services--Applications-Implementation) <br>
      5.2.1. [Sprint 1](#Sprint-1) <br>
         5.2.1.1. [Sprint Planning 1](#Sprint-Planning-1) <br>
         5.2.1.2. [Sprint Backlog 1](#Sprint-Backlog-1) <br>
         5.2.1.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review) <br>
         5.2.1.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review) <br>
         5.2.1.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review) <br>
         5.2.1.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review) <br>
         5.2.1.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review) <br>
         5.2.1.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint) <br>
      5.2.2. [Sprint 2](#Sprint-2) <br>
         5.2.2.1. [Sprint Planning 2](#Sprint-Planning-2) <br>
         5.2.2.2. [Sprint Backlog 2](#Sprint-Backlog-2) <br>
         5.2.2.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review-2)<br> 
         5.2.2.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review-2) <br>
         5.2.2.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review-2) <br>
         5.2.2.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review-2) <br>
         5.2.2.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review-2) <br>
         5.2.2.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint-2) <br>
      5.2.3. [Sprint 3](#Sprint-3) <br>
         5.2.3.1. [Sprint Planning 3](#Sprint-Planning-3) <br>
         5.2.3.2. [Sprint Backlog 3](#Sprint-Backlog-3) <br>
         5.2.3.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review-3) <br>
         5.2.3.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review-3) <br>
         5.2.3.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review-3) <br>
         5.2.3.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review-3) <br>
         5.2.3.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review-3) <br>
         5.2.3.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint-3) <br>
      5.2.4. [Sprint 4](#Sprint-4) <br>
         5.2.4.1. [Sprint Planning 4](#Sprint-Planning-4) <br>
         5.2.4.2. [Sprint Backlog 4](#Sprint-Backlog-4) <br>
         5.2.4.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review-4) <br>
         5.2.4.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review-4) <br>
         5.2.4.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review-4) <br>
         5.2.4.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review-4) <br>
         5.2.4.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review-4) <br>
         5.2.4.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint-4) <br>
   5.3. [Validation & Testing](#Validation--Testing) <br>
      5.3.1. [Testing Plan](#Testing-Plan) <br>
      5.3.2. [Quality Assurance](#Quality-Assurance) <br>
      5.3.3. [User Acceptance Testing (UAT)](#User-Acceptance-Testing-UAT) <br>
   5.4. [Product Deployment](#Product-Deployment) <br>
      5.4.1. [Deployment Plan](#Deployment-Plan) <br>
      5.4.2. [Deployment Process](#Deployment-Process) <br>
      5.4.3. [Post-Deployment Review](#Post-Deployment-Review) <br>
6. [CAPÍTULO VI: Appendix](#Capítulo-VI-Appendix) <br>
   6.1. [References](#References) <br>
   6.2. [Glossary](#Glossary) <br>
   6.3. [Acronyms](#Acronyms) <br>
   6.4. [Bibliography](#Bibliography)<br>
   # STUDENT OUTCOME
El curso contribuye al cumplimiento del Student Outcome ABET: 
##### ABET – EAC - Student Outcome 5 
Criterio: Trabaja efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo; crea un entorno colaborativo e inclusivo y establece metas, planifica tareas y cumple objetivos, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5. 

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|-------------------------|------------------------|------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta |                        |                  |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos |   

# CAPÍTULO I: Introducción
## Startup Profile
### Descripción de la Startup
#### Descripción General:
<div style="text-align: justify">
KingReserve es una startup inovadora 
<div/>

Nuestra plataforma principal, **KingReserve**, permite a los hoteles gestionar sus operaciones de manera más eficiente y mejorar la experiencia de sus huéspedes. **KingReserve** no solo es una herramienta para administrar reservas y personal, sino también para ofrecer servicios de manera accesible e intuitiva.

### **Colaboraciones Estratégicas:**
En **KingReserve**, estamos comprometidos a establecer sólidas alianzas con cadenas hoteleras, hoteles boutique, y resorts. Trabajamos en estrecha colaboración con estos socios para garantizar que nuestras soluciones tecnológicas respondan a sus necesidades operativas, facilitando la gestión diaria y mejorando la satisfacción del cliente. Invitamos a los hoteles a integrar nuestras soluciones para optimizar la administración de reservas, la gestión de empleados, y la atención al cliente, creando una experiencia más fluida y eficiente.

### **Innovación y Tecnología:**
Nuestra plataforma utiliza tecnologías avanzadas para ofrecer una experiencia optimizada tanto para el personal hotelero como para los huéspedes. Desde la capacidad de administrar reservas y asignar tareas de manera automatizada hasta la personalización de servicios según las preferencias de los clientes, **KingReserve** busca redefinir la forma en que los hoteles gestionan sus operaciones. Queremos que cada hotel se sienta respaldado por una solución tecnológica que le permita mejorar su eficiencia y ofrecer una atención al cliente excepcional.

### **Comunidad y Funciones Sociales:**
**KingReserve** no es solo una plataforma para la gestión operativa; es también un espacio de colaboración donde los hoteles pueden compartir buenas prácticas y aprender unos de otros. La plataforma incluye funciones que permiten a los administradores conectarse con otros profesionales del sector, intercambiar ideas y estrategias, y mantenerse al día con las últimas tendencias en gestión hotelera. Esta característica fomenta la creación de una comunidad de aprendizaje y mejora continua, donde los hoteles pueden crecer y prosperar juntos.

### **Visión:**
Visualizamos un mundo donde la tecnología y la gestión hotelera se fusionan para crear experiencias excepcionales tanto para los empleados como para los huéspedes. Nuestro objetivo es que **KingReserve** sea sinónimo de innovación en el sector hotelero, un lugar donde las empresas puedan optimizar sus operaciones y elevar la calidad de sus servicios. Aspiramos a construir una industria hotelera más conectada, eficiente y orientada al cliente.

### **Misión:**
Nos esforzamos por proporcionar una plataforma que conecte a los hoteles con herramientas avanzadas de gestión, mejorando la eficiencia operativa y la satisfacción del cliente. Estamos decididos a utilizar la tecnología para generar un impacto positivo en la experiencia de los huéspedes y la eficiencia del personal hotelero. **KingReserve** será símbolo de excelencia en la gestión hotelera, innovación en la administración de servicios, y compromiso con la mejora continua, mientras fomentamos una comunidad activa y colaborativa en torno a la hospitalidad y el servicio.

### **Perfiles de los integrantes del Startup:**

### **Joaquín Andree Pedraza Maldonado:**
Mi nombre es Joaquín Andreé Pedraza Maldonado , tengo 20 años y actualmente me encuentro en 6to ciclo de la carrera de Ingeniería de Software , en la UPC , sede San Miguel. Al terminar mi carrera desearía dedicarme al rubro de desarrollo Web o cyberseguridad.Soy una persona centrada , perseverante , tranquila  , optimista y efectiva.

### Alessandro Zevallos

Soy estudiante de Ingenieria de Software con un fuerte interés en el desarrollo de productos digitales y la tecnología.En mi tiempo libre, me gusta jugar videojuegos. También tengo un interés especial en la música, lo que me ayuda a equilibrar mi vida académica y personal.Cuento con habilidades en gestión de bases de datos. Además, tengo experiencia en análisis de datos, lo que me ayuda a tomar decisiones informadas y crear soluciones efectivas.

### 1.2.1 Antecedentes y Problematica **

En la actualidad se puede evidenciar que la industria turistica a incrementado de manera exponencial estos ultimos años en nuestro país , esto a traido como consecuencia la aparición de más agencias hoteleras debido a la vista de una gran oportunidad de negocio frente a la alta demanda del sector turistico, sin embargo esto ocasiono que la productividad en el sector hotelero disminuya por la falta de eficiencia a la hora de realizar las reservas o la mala desorganización dentro del sector hotelero .

En el Perú el problema de la informalidad en el sector turístico, que también abarca el sector hotelero, es evidente, como lo revela un estudio realizado por el Ministerio de Comercio Exterior y Turismo del Perú (Mincetur, 2019). Según este estudio, en el distrito de Miraflores, el 24% de las agencias de viajes operan de manera informal. Esta situación se traduce en deficiencias en los estándares de servicio, incluyendo la descoordinación en las reservas de restaurantes, excursiones, hoteles y guías de turismo. Además, se presentan errores en la comunicación con las agencias de origen, en la programación de vuelos de llegada y vuelos locales, en la categorización de hoteles, en el tipo de excursión, y en la coincidencia de identidad y fechas en el destino. También se observa una falta de efectividad en la capacidad de respuesta de los sistemas ante solicitudes de los servicios de hotel

Fuente: https://revistasinvestigacion.unmsm.edu.pe/index.php/quipu/article/view/20192





    
### Segmentos Objetivo

#### 1. Empresas Hoteleras:

Este segmento se enfoca en cadenas hoteleras, hoteles boutique y resorts que buscan transformar sus operaciones mediante la implementación de soluciones tecnológicas avanzadas. Estas empresas están comprometidas con la mejora continua de sus procesos operativos y la optimización de la experiencia de sus huéspedes. Su principal objetivo es integrar herramientas que les permitan gestionar reservas, coordinar al personal y ofrecer un servicio al cliente de alta calidad de manera más eficiente. Buscan reducir la carga administrativa mediante la automatización de tareas y mejorar la comunicación interna para una gestión más fluida. Además, valoran las oportunidades de colaborar con otros profesionales del sector, compartir buenas prácticas y estar al tanto de las últimas tendencias en gestión hotelera para mantener un estándar elevado en sus operaciones.

#### 2. Huéspedes:

Este segmento está compuesto por viajeros que buscan una experiencia de alojamiento personalizada y de alta calidad. Los huéspedes valoran una experiencia que se ajuste a sus preferencias individuales, desde la facilidad de reserva hasta la atención personalizada durante su estancia. Están interesados en un proceso de reserva intuitivo que simplifique la planificación de su viaje y en recibir un servicio al cliente eficiente que pueda resolver cualquier inconveniente de manera rápida. Además, aprecian servicios y comodidades que mejoren su confort y hagan su estancia más placentera. La capacidad de personalizar su experiencia y acceder a un servicio excepcional son factores clave para su satisfacción y fidelización.

# Capítulo II: Requirements Elicitation & Analysis
## Competidores
KingReserve se diferencia de competidores como Opera PMS, RoomRaccoon y Mews al combinar la gestión hotelera con una comunidad colaborativa para profesionales del sector. Mientras que Opera PMS es ideal para grandes cadenas pero costoso para pequeños hoteles, RoomRaccoon se centra en hoteles más pequeños con una solución integral, y Mews destaca por su automatización y diseño moderno, KingReserve ofrece una solución versátil que no solo optimiza la operación, sino que también fomenta la interacción y el intercambio de conocimientos entre usuarios, elevando la calidad del servicio y la experiencia del cliente.
## Análisis Competitivo
<table>
   <tr>
      <td align="center" colspan="6"><b>Competitive Analysis Landscape</b></td>
   </tr>
   <tr>
      <td colspan="2"><b>¿Por qué llevar a cabo este análisis?</b></td>
      <td colspan="4">¿Cómo podemos proporcionar una gestión hotelera eficiente que además de optimizar las operaciones, fomente una experiencia personalizada y excelente para los huéspedes?</td>
   </tr>
   <tr align="center">
      <td colspan="2"></td>
      <td><b>KingReserve</b><br><img src="https://hackmd.io/_uploads/rkXwsQdsC.png" alt="KingReserve Logo" style="max-width: 80px;"/></td>
      <td><b>Cloudbeds</b><br><img src="https://acortar.link/SDV6QT" alt="Cloudbeds Logo" style="max-width: 80px;"/></td>
      <td><b>RoomRaccoon</b><br><img src="https://acortar.link/4OQEIk" alt="RoomRaccoon" style="max-width: 80px;"/></td>
      <td><b>Mews</b><br><img src="https://acortar.link/UGgluO" alt="Mews" style="max-width: 90px;"/></td>
   </tr>

   <tr>
      <td rowspan="2"><b>Perfil</b></td>
      <td><b>Overview</b></td>
      <td>KingReserve es una plataforma innovadora que ofrece una solución integral para la gestión hotelera, combinando funciones operativas con un enfoque en la experiencia del cliente. Además de optimizar la administración, se enfoca en crear un entorno que fomente la interacción social y la personalización.</td>
      <td>Cloudbeds es una plataforma moderna para la gestión hotelera que integra PMS, motor de reservas y canal de distribución, destacándose por su facilidad de uso y su enfoque en la automatización y centralización de operaciones para hoteles de distintos tamaños.</td>
      <td>RoomRaccoon es una solución todo-en-uno diseñada para pequeños y medianos hoteles, que combina gestión de reservas, un motor de reservas en línea y herramientas de facturación.</td>
      <td>Mews ofrece una plataforma moderna y flexible que automatiza gran parte de las operaciones hoteleras, enfocándose en mejorar la eficiencia y la experiencia del huésped.</td>
   </tr>
   <tr>
      <td><b>Ventaja competitiva. ¿Qué valor ofrece a los clientes?</b></td>
      <td>KingReserve se diferencia al integrar la gestión hotelera con funciones sociales para crear una comunidad interactiva entre los hoteles y sus huéspedes, mejorando la experiencia del cliente a través de la personalización y comunicación directa.</td>
      <td>Cloudbeds combina gestión, distribución y automatización en una única plataforma, facilitando la administración hotelera desde una interfaz intuitiva y accesible.</td>
      <td>RoomRaccoon ofrece una interfaz intuitiva para pequeños hoteles, con un enfoque en la facilidad de uso y precios accesibles.</td>
      <td>Mews se centra en la automatización y la experiencia del usuario, con un diseño moderno y adaptable, aunque su integración personalizada puede ser limitada.</td>
   </tr>
   <tr>
      <td rowspan="2"><b>Perfil de Marketing</b></td>
      <td><b>Mercado Objetivo</b></td>
      <td>El mercado objetivo de KingReserve incluye hoteles de tamaño mediano y grande que buscan optimizar sus operaciones y mejorar la experiencia del huésped mediante la tecnología. También apunta a cadenas hoteleras que desean mejorar la personalización y el servicio al cliente.</td>
      <td>Hoteles y alojamientos de diversos tamaños que buscan una solución todo-en-uno para centralizar y automatizar su gestión operativa y de reservas.</td>
      <td>Pequeños y medianos hoteles que buscan una solución todo-en-uno con funcionalidades simples y una curva de aprendizaje baja.</td>
      <td>Hoteles que valoran la automatización y buscan mejorar la experiencia del huésped a través de una plataforma moderna y flexible.</td>
   </tr>
   <tr>
      <td><b>Estrategias de Marketing</b></td>
      <td>KingReserve se centrará en campañas digitales dirigidas a hoteles medianos y grandes, promoviendo su capacidad para mejorar la personalización y la experiencia del huésped. Además, se buscarán alianzas estratégicas con grupos hoteleros y eventos del sector.</td>
      <td>Cloudbeds promueve su solución como una plataforma integral que simplifica la gestión hotelera mediante la automatización, dirigida a alojamientos que buscan centralizar y optimizar sus operaciones.</td>
      <td>RoomRaccoon se promociona principalmente a través de campañas en línea, con un enfoque en la facilidad de uso y los precios accesibles para pequeños hoteles.</td>
      <td>Mews invierte en marketing digital y en la creación de una marca que se asocia con la modernidad y la innovación en la gestión hotelera.</td>
   </tr>
   <tr>
      <td rowspan="3"><b>Perfil de Producto</b></td>
      <td><b>Productos & Servicios</b></td>
      <td>Solución integral de gestión hotelera, combinando administración de reservas, comunicación directa con huéspedes, y herramientas para personalizar la experiencia del cliente.</td>
      <td>PMS, motor de reservas, gestor de canales, y herramientas para automatizar operaciones y mejorar la experiencia del huésped.</td>
      <td>Gestión de reservas, motor de reservas en línea, herramientas de facturación y PMS, diseñado para pequeños hoteles.</td>
      <td>Automatización de operaciones, gestión de reservas y experiencias del huésped, todo dentro de una interfaz moderna.</td>
   </tr>
   <tr>
      <td><b>Precios & Costos</b></td>
      <td>Ofreceremos un modelo de suscripción con opciones escalables según el tamaño del hotel y las funciones necesarias, además de herramientas adicionales para personalización y servicios exclusivos.</td>
      <td>Modelo de suscripción escalable según las necesidades del hotel, con opciones de pago mensuales y personalización de funcionalidades.</td>
      <td>Precios accesibles con paquetes todo-en-uno adaptados a pequeños hoteles.</td>
      <td>Suscripción basada en el tamaño del hotel y las funcionalidades necesarias, con opciones adicionales para automatización avanzada.</td>
   </tr>
   <tr>
      <td><b>Canales de Distribución (Web y/o Móvil)</b></td>
      <td>Web y app móvil con sincronización en tiempo real entre dispositivos para una gestión fluida en múltiples plataformas.</td>
      <td>Web y app móvil con sincronización entre todas las herramientas, accesible desde cualquier dispositivo.</td>
      <td>Web y aplicaciones móviles, con una interfaz sencilla y accesible desde cualquier dispositivo.</td>
      <td>Web y móvil, con un diseño adaptable para distintos tipos de dispositivos.</td>
   </tr>

   <tr>
      <td rowspan="5"><b>Análisis SWOT</b></td>
      <td><b>Fortalezas</b></td>
      <td>Enfoque en la experiencia personalizada del huésped, comunidad interactiva, e integración fluida entre funciones operativas y sociales.</td>
      <td>Plataforma integral que centraliza la gestión y distribución, con una interfaz intuitiva y accesible para hoteles de distintos tamaños.</td>
      <td>Interfaz fácil de usar y precios accesibles para pequeños hoteles.</td>
      <td>Automatización avanzada y diseño moderno.</td>
   </tr>
   <tr>
      <td><b>Debilidades</b></td>
      <td>Dependencia inicial de alianzas estratégicas para atraer grandes cadenas hoteleras.</td>
      <td>Dependencia en su modelo SaaS para alojamientos de menor tamaño, lo que puede limitar su adopción en cadenas grandes.</td>
      <td>Limitado a hoteles pequeños y medianos.</td>
      <td>Limitaciones en integraciones personalizadas.</td>
   </tr>
   <tr>
      <td><b>Oportunidades</b></td>
      <td>Expansión en mercados internacionales, adopción de tecnologías emergentes, y crecimiento en la digitalización hotelera.</td>
      <td>Creciente demanda de soluciones automatizadas y centralizadas, expansión a nuevos mercados geográficos.</td>
      <td>Mayor demanda de soluciones accesibles y eficientes para hoteles pequeños y medianos.</td>
      <td>Creciente interés en automatización hotelera y tecnología moderna.</td>
   </tr>
   <tr>
      <td><b>Amenazas</b></td>
      <td>Competencia fuerte en el mercado de gestión hotelera, cambios en las tendencias tecnológicas.</td>
      <td>Aumento de la competencia en soluciones todo-en-uno y herramientas más especializadas para hoteles grandes.</td>
      <td>Aumento en la competencia de otras soluciones todo-en-uno.</td>
      <td>Nuevas plataformas que ofrezcan soluciones más flexibles o especializadas.</td>
   </tr>
</table>
