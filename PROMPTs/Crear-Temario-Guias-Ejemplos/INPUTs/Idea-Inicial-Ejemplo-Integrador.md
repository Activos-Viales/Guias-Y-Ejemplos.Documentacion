
# Idea Inicial - Ejemplo Temático de integración de temas.



## Contexto

  Se plantea el siguiente escenerio donde se necesita realizar relevamientos del estado de las trazas viales comprendido por caminos y puentes.

  El relevamiento consiste en un proyecto que agrupa los relevamientos que cada agente de inspección, cada uno es parte de una cuadrilla, y cada cual aporta a dicho proyecto de relevamiento sus observaciones. Cada observación consta de evidencias descriptivas, fotografia. Todas las observaciones se georeferencian.
  
  El ciclo de vida del proyecto consiste en la creación del proyecto por los agentes o personal del area de planeamiento, la ejecución del proyecto de relevamiento por los agentes de inspección, y la evaluación por parte del area de planeamiento.

  La ejecución del proyecto por parte de la cuadrilla consite en iniciar las tareas de inspección, en la que se iran creando observaciones sobre el estado de la traza vial.
  
  Cada observación consta de fecha/hora, geolocalización, una posible breve descripción y/o fotografias. Así un agente inspector si se observa diferentes baches, por estos basches puede que incluya en una misma observación varias fotos evidenciales, y una descripción general, y en esta observación se incluirá la georeferenciación. No obstante otro agente tambien puede sumar sus observaciones.

  Durante un inicio inspección determinado, recorre y va sumando sus observaciones documentadolas con descripciones y fotografias geolocalizadas. 

---

## Planteo de la necesidad

  Se requiere un sistema compuesto de dos partes principales

  - Gestión de los proyectos. Debe ser un sistema web que permita tanto al persona del planeamiento como al personal de inspección operar el sistema y realizar sus tareas. El personal de planeamiento gestionará las cuadrillas, los proyectos de relevamientos, y las evaluaciones posteriores de dichos proyectos. El persona de inspección podrá cargar de manera ofline sus observaciones según el proyecto que haya relevado. El persona de administración de sistema se encarga de la gestión de alta de personal, tanto de nuevos administradores, como de personal de planeamiento e inspección. Un personal de planeamiento puede cumplir con los tres roles.

  - Dispositivo de capturas. Mediante dispositivos moviles el sistema debe permitir la automatización de las tareas de inspección. Aquí mediante una aplicación movile debe permitir el mejor modo de capturar las observaciones, tanto descrptivas como gráficas (fotografias o albun fotografico), completando posición georeferencial y fecha y hora de realización de la observación.

  El alcance del sistema 

--

## Artefactos 

  Un servicio web api rest para la administración de cada plan de inspección. Aqui participacipan los agentes de inspección de la cuadrilla o inspectores y tambieen los agentes de planeamiento.

  Los agentes de planimiento manejan el ciclo de vida de la inspección, reunir las cuadrillas, con los agentes disponibles

  Los agentes de inspección reportan segun el plan asignado sus observaciones

  Un usuario administrador, para el alta y habilitacion de los agentes.

  Una aplicación movil que permite a cada agente de inspección de la cuadrilla poder 

---  

## Aspectos técnicos.

  Servicio web debe ser realizado con .NET utilizando páginas blazor, Base de datos postgresql. 
  Despliegue en docker, devcontainer e information Server, Al iniciar el servicio inicialmente solicitar la configuración (usuario administrador o root , nombre y clave)

  Aplicación movile, utilizar .NET MAUI con páginas blazor , SQLite, implementar una arquitectura de aplicación que permita sincornizar datos. Manejo de catalogo de fotos, cámara , autentificación de la aplicación mediante seguridad del telefono (pin, patró,n huellas dactilares,reconocimiento de rostro) 

  Mapas open source , open street map -lefft

  Servicio de manejo de archivos tuf para subir los archivos conteneirazado. Debe permitir subir las fotos, 


---

## Conocimientos

IA/IA.Knowledge.Base/Knowledges/Knowledge-Conformacion-Pull-Request-Automatico.md

IA/IA.Knowledge.Base/Knowledges/Knowledge-Red-Movil-Problematica.md

IA/IA.Knowledge.Base/Knowledges/Knowledge-Bundle-JS.md