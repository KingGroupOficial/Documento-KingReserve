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
