 # Tool-Prompt — Iniciar Temario

> **Invocación**:
> - Leer y ejecutar `/GROUPs/Activo-Viales/Guias-Y-Ejemplos/Guias-Y-Ejemplos.Documentacion/PROMPTs/Crear-Temario/Crear-Temario-Y-Definir-Guias-Estudio-y-Ejemplos.md`
>
> **Overview**: Crear temario

---

## Contexto


  Leer `/GROUPs/Activo-Viales/Group-Activos-Viales-Media/Documentacion-Proyecto.Documentacion/PROMPTs/01-Redaccion-Plan/ARTIFACs/Final-Plan-Trabajo.md`, es un `Plan de trabajo final` pensado para que sea ejecutado por un grupo de estudiantes de la facultad a fin de que puedan cumplir con sus prácticas supervisadas.

  Leer `/GROUPs/Activo-Viales/Group-Activos-Viales-Media/Documentacion-Proyecto.Documentacion/PROMPTs/01-Redaccion-Plan/ARTIFACs/Plan-Trabajo-PPS-UTN.md`, es el formulario con el `Plan de trabajo final` adecuado al formato que pide la institución educativo y es un resumen del `Plan de trabajo final`.

  Leer `/GROUPs/Activo-Viales/Guias-Y-Ejemplos/Guias-Y-Ejemplos.Documentacion/PROMPTs/Iniciar-Temario/INPUTs/Temarios-Tentativo.md` , es un `Temario tentativo` e inicial, sujeto a mejoras,de tecnologías en la que los estudiantes deben introducirse y servirles como referencias para el desarrollo del sistema conforme al `Plan de trabajo final`. 

  Leer `/GROUPs/Activo-Viales/Guias-Y-Ejemplos/Guias-Y-Ejemplos.Documentacion/PROMPTs/Iniciar-Temario/INPUTs/Base-Documental-Y-Ejemplos-Existente.md`, son ejemplos, guias de estudios, desarrollos, que aunque aún muchos de los temas que se estan trabajando estan en curso deberia servir para los objetivos que se proponen luego.


---

## Objetivos

  Elaborar una un temario con las tecnologías que los estudiantes deben trabajar y describir los contenidos de cada uno de estos temas, ejemplos que son los que se deben acompañar.

---

## Solicituedes

  Lo que se debe desarrollar.
  1- una guía de temas , con sus unidades, descripción de cada tema, cada unidad debe agruparse por su tema nucleo conceptual. Se puede partir desde el `Temario tentativo` 


  Crea una mesa basado en el conocimiento: `<repo privado>/Prompts/Conocimientos/Knowledge-Mesa-De-Expertos-A-Pedido.md` con expertos en devops, analistas en sistemas, un especialista en analisis el cúal se le pida criterios de decisión y analisis de las decisiones, QAs, y desarrolladores .NET . A la mesa presentale el contexto, objetivos y las soliticitudes junto con las reglas dadas. La mesa debería abrir los expedientes si se requiere tal seguimiento.


---

## Reglas

  - Vos y toda la mesa y sus subagentes debe seguir el concepto a apliciar como estrategia de descomposición conceptual sobre la totalidad del prompt. 

    Identifica y agrupa las ideas que presenten una relación temática, semántica o de  dependencia fuerte, formando núcleos conceptuales coherentes. No fragmentes el  contenido únicamente por extensión o por párrafos: la unidad de segmentación debe
    estar determinada por la afinidad y dependencia entre las ideas.

    Aborda el análisis y la planificación por estos núcleos conceptuales o ejes  temáticos, documentando cada uno en un documento Markdown independiente. Mantén además un documento de cohesión global que describa las relaciones, dependencias, referencias y vínculos existentes entre los distintos núcleos.

    La segmentación debe permitir trabajar cada eje con mayor precisión sin perder  contexto ni relaciones con los demás. Cada núcleo debe poder analizarse, planificarse y validarse de manera relativamente independiente, pero debe conservarse la trazabilidad necesaria para integrarlo posteriormente en una solución global.

    Una vez abordados los distintos núcleos conceptuales, realiza una fase de integración en la que se consoliden sus resultados, se resuelvan dependencias o contradicciones entre ellos y se reconstruya el modelo completo.

    El objetivo de esta estrategia es transformar un prompt de gran volumen y alta  complejidad en un conjunto de unidades conceptuales manejables, manteniendo entre ellas una estructura de cohesión, dependencia y trazabilidad que permita presentar cada eje a la mesa evaluadora y planificadora y, finalmente, integrarlos en un todo coherente.
    
    Para poder cumplir con esta regla aproyate en ir generando registros que puedas retomar y evaluar markdowns en `<repo privado de documentación>/PROMPTs/DEVs/Fixs/<fix>/OUTPUTs/01-Bitacora`

  - No inventar información. 

  - Toda afirmación debe estar respaldada por evidencia verificable.

