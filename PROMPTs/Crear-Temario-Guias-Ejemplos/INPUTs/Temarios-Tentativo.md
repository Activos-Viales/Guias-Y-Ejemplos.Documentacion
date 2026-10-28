

# Temario tentativo

## Introducción

  Este documento trata sobre el temario de temas tentativos que debe server de guía para estructurar guías de estudios por temas, ejemplos y ejemplo demostrativo de soportes para la bibliografia generada.

  Todo el material, incluido parte de las necesidades que se deben cubrir para desarrollar en el sistema por parte de un grupo de estudiantes bajo los siguientes planes de trabajos:
    - Plan de trabajo completo: `/GROUPs/Activo-Viales/Group-Activos-Viales-Media/Documentacion-Proyecto.Documentacion/PROMPTs/01-Redaccion-Plan/ARTIFACs/Final-Plan-Trabajo.md` 
    - Plan de trabajo reducido, requerido por la institución educativa: `/GROUPs/Activo-Viales/Group-Activos-Viales-Media/Documentacion-Proyecto.Documentacion/PROMPTs/01-Redaccion-Plan/ARTIFACs/Plan-Trabajo-PPS-UTN.md`


## Temas:

  - **Aspectos teóricos de .NET**
    Inyección de dependencias (DI) e inversión de control (IoC), ciclo de vida de los servicios que administra el contenedor de dependencias. Ejemplos minimalistas y prácticos de uso según el caso. 

  - **Acceso a datos - ORM**: .NET EntityFramework, Estrategias, base de datos primero, clase primero, script de migración, Planteo de diferentes situaciones según en que caso. Situaciones ante mapeo de jerarquías de clases y objetos, estrategías.  

  - **Aplicaciones web y RestAPI**: Páginas blazord interactive server.

  - **Arquitectura en .NET** - Arquitectura de depedencias clean según el estandar de .NET, modelo de capas, definición desarrollo práctico, como identificar que escribir en cada una, ejemplificar que clase va en donde y que lleva. 

  - **Pruebas**: E2E, Pruebas unitarias, y de integración. Todas dentro del entorno .NET. Que pretende cada una, ejemplos. 

  - **Devops**, despliegue, diferentes estrategias.
     Contenedores docker, devcontainer, desarrollo en visualcode, visual studio, 

  - **Bases de datos**: principios básicos, y avanzados, procedimientos almacenado , script, DDL, DML, etc. Georeferenciación.
     a. Postgresql para uso en servicios web y API.
     b. SQLite para uso en aplicaciones móviles

  - **Mapas y geolocalización**: 
    - Bases de datos PostGIS
    - Librerias OpenStreet Leaflet


  - **Integración con IA, agentes**: AI Layer: LLM/Generative Models RAG Pipeline, AI Services & Agentes, Embeddings, Vector DB

  - **Integración con sistema de documentación**

  Actualmente hay formas de estructurar la documentacion con metodlogias `DocsAsCode`. Métodologías de desarrollo y ciclo de vida de desarrollo de la documentación.
  Referencia actual: `/LAB/Lab-Documentos/Lab-Documentos/Guides/Documentacion-Tecnica/` una guía de resumen, ejemplos y demostración en .net. 

  - Desarrollo de aplicaciones móviles en .NET. MAUI .NET, MAUI .NET Blazor hibridas, integración con sqlite. Modelo de aplicación sin conexión. Modelo de aplicación

  - **Manejo de proyectos, Requerimientos y Diseño**: Metodologías agiles, metodlogía Scrum, Canvas, otras. En que caso se aplica cada una.
  Ciclo de desarrollo del sofware: Lenguage Modelo Unificado, Casos de usos, 
  
  - **Herramientas de georeferenciación**, QGis, postgresq. Ejemplos prácticos, definiciones, aplicaciones.

- Unidad integradora: Desarrollo de un ejemplo completo que sirva de debate, discusión, referencia y apoyo 

## Metodologia

  Por cada unidad temática crear guías practicas con dos o tres ejercicios minimalistas y prácticos. Generar criterio de diseño e implementación mediante preguntas, respuestas explicativas y ejemplos.

  Por cada unidad temática se desarrolla las guías de estudios, ejemplos que se referencia en dichas guias de estudio. De estos ejemplos deben ser pensado de tal forma que permitan en las guías de estudio citar e incluir partes de estos ejemplos, snipped de código con explicaciones, por lo tanto estos ejemplos deben servir de soporte para ilustrar  el marco conceptual de definiciones que conforme la guía.

  Para la demo integradora a desarrollar: `<raíz del workspace>/GROUPs/Activo-Viales/Guias-Y-Ejemplos/Guias-Y-Ejemplos.Documentacion/PROMPTs/Crear-Temario-Guias-Ejemplos/INPUTs/Idea-Inicial-Ejemplo-Integrador.md` sería interesante utilizarla para desarrollar por completo la unidad integradora mediante este flujo `/GROUPs/Activo-Viales/Guias-Y-Ejemplos/Guias-Y-Ejemplos.Documentacion/PROMPTs/Crear-Temario-Guias-Ejemplos/INPUTs/mapa-simple.bmp` en la que se integra todas las metodlogias de forma organica, incluso como propuesta se pueden integrar. Debe servir para dar ejemplo de como se parte del nacimiento de la idea, las preguntas que forman que dan origen a cada conceptualización de los elementos que van conformando la piezas de requerimientos, postreior piezas de diseño y por ultimo código funcional y de prueba. Ademas debe servir para generar los ejemplos ilustrativos y adaptados orientados a focoalizar cada tema del temario a desarrollar.

   


