# MDA 22/23 - Relación de problemas 4

## Introducción: rúbrica de trabajo

Cada uno de los ejercicios cuenta con el nombre de la persona que se responsabiliza de éste. Aunque todos los ejercicios han sido revisados en pareja y cuentan con feedback del compañero, su redacción inicial proviene de la persona responsable.

El documento ha sido revisado conjuntamente, para añadir puntualizaciones y corrección de errores; además de para pasarlo a LaTeX.

## Tema 5: eXtreme Programming

### 1. El problema básico del desarrollo del software es el riesgo, algunos ejemplos de situaciones de riesgo son: 

- Retrasos de planificación: llega el día de la entrega, y le decimos al cliente que el software no estará disponible. 
- Proyecto cancelado: después de numerosos retrasos, el proyecto se cancela sin haber entrado nunca en producción. 
- El sistema se deteriora: el software se pone satisfactoriamente en producción, pero después de un par de años, los costes de hacer cambios o la tasa de defectos crecen tanto que el sistema debe ser reemplazado. 
- Tasa de defectos: el software se pone en producción, pero la tasa de defectos es tal alta que no se usa. 
- Requisitos mal comprendidos: el software se pone en producción, pero no resuelve el requisito planteado inicialmente. 
- Cambios en el negocio: el software se pone en producción, pero el problema de negocio para el que se diseñó la solución inicial fue reemplazado hace seis meses por otro problema más acuciante. 
- Falsa riqueza de características: el software tiene un montón de características potencialmente interesantes, todas las cuales fueron divertidas de programar, pero ninguna hace que el cliente gane dinero. 
- Cambios de personal: después de dos años, todos los buenos programadores del proyecto comienzan a odiar el programa y se marchan. 

**¿Cómo trata XP el riesgo que hemos comentado anteriormente?**

- Retrasos de planificación - XP lidia con los retrasos mediante una planificación flexible y adaptativa. Las estimaciones no son planes de futuro, sino el mejor escenario posible. Además, los sprints de pequeño tamaño también ayudan a evitar esta situacion
- Proyecto cancelado - No sucederá a no ser que se cancele en etapas extremadamente tempranas. XP genera en cada sprint de corta duración contenido apto para producción. 
- El sistema se deteriora - Una de las máximas de XP es el énfasis en las pruebas. El contenido nuevo se añade al programa en un proceso de producción e integración continua, lo cual genera un sistema estable.
- Tasa de defectos - De nuevo, las pruebas son muy importantes en XP, así como las revisiones de código en parejas y un diseño sólido y revisado diariamente. 
- Requisitos mal comprendidos - En XP se acepta el cambio como una realidad. Durante la vida de un proyecto, los requisitos cambiarán, se malinterpretarán, se volverán innecesarios... La planificación es un diálogo continuo y, si algo cambia, nos adaptamos a ello y continuamos.
- Cambios en el negocio - Mismo planteamiento que la anterior: el cambio es parte del proceso de desarrollo. Pero gracias a la metodología de XP, sabemos que no pasarán 6 meses hasta que nos demos cuenta de este problema, ya que el diálogo continuo y los sprints cortos nos permitirán implementar los cambios necesarios mucho antes.
- Falsa riqueza de características - En XP se premia la simplicidad: hay que hace lo más sencillo que funcione. Esto requiere invertir tiempo previo en diseño, pero como máxima nos garantiza que este riesgo no va a darse.
- Cambios de personal - El código pertenece a todo el equipo, y nos apoyamos los unos a los otros. Si tras un tiempo los programadores más veteranos del programa deciden marcharse, el resto del equipo debería conocer el código tan bien como ellos. Todos los miembros del equipo deberían sentirse cómodos con todo el código del programa.

### 2. Comenta brevemente las diferencias principales entre XP y Scrum. 

La diferencia más notable es que Scrum no determina metodologías de desarrollo, sino un marco de trabajo que adaptar a nuestro entorno de trabajo. En XP, se recomiendan técnicas específicas (como la programación en parejas). Esto nos permite aplicar XP directamente a un equipo, cuando para aplicar Scrum tendríamos que completar el marco de trabajo con otras metodologías de desarrollo.

Otra diferencia sería la duración del sprint y su flexibilidad: en Scrum, los sprints duran un mes; y el tiempo no es negociable. En XP, los sprints son mucho más cortos (de una a tres semanas), y si hay problemas, se puede repetir la reunión de planificación y reestimar.

Finalmente, Scrum se centra mucho más en prácticas enfocadas a la auto-organización; mientras que XP se dedica más a reforzar las buenas prácticas de desarrollo.

### 3. Compara los roles de XP con los roles de Scrum. 

- **Programador VS. Equipo de desarrollo:**
  - El rol del equipo de programadores en XP y equipo de desarrollo en Scrum es prácticamente el mismo. Se encargan del apartado técnico, estiman las historias y hacen las pruebas de unidad. Además, pese a su nombre, no es un rol limitado a los programadores: se incluyen todos los roles necesarios para el desarrollo del producto (diseñadores, programadores...)
- **Cliente VS. Product Owner:**
  - Es el mismo rol. Se encarga de ser el nexo entre el producto y los desarrolladores, es parte del equipo y como tal tiene ciertas responsabilidades con ellos: se encarga de las historias de usuario y su priorización, así como de las pruebas funcionales, ya que es la persona encargada de dar el visto bueno a lo producido en la iteración.
- **Entrenador, Gestor, Rastreador VS. Scrum Master:**
  - *Similitudes*:
    - Entrenador: responsable del proceso y su llegada a buen puerto. Aunque está formado en su campo, a la hora de la programación queda en un segundo plano, ya que su trabajo se centra más en garantizar que los procesos se cumplen correctamente y el equipo funciona.
    - Gestor: nexo entre el cliente y los programadores.
    - Rastreador: ambos son encargados de llevar seguimiento del proyecto, reflejarlo en gráficos, interpretar los datos y aplicar cambios acordes a éstos. 
  - *Diferencias*:
    - Los roles de Entrenador y Gestor tienen una carga jerárquica, se ubican encima de los desarrolladores. En Scrum, el Scrum Master no puede considerarse un superior del equipo de desarrollo.

- **Probador VS. Stakeholder:**
  - *Similitudes*:
    - El rol de probador se corresponde en parte con el de stakeholder, puesto que son los que proveen feedback sobre el producto y lo testean.
  - *Diferencias*:
    - Los stakeholders son normalmente un grupo de directivos y otros implicados. Un probador podría ser cualquiera.

El rol de consultor no existe en Scrum como tal, pero es responsabilidad del Scrum Master contactar consultores cuando nos encontramos con un obstáculo.

### 4. Relacionar los 14 principios de XP2 con las prácticas propuestas en XP.



### 5. Clasifica las prácticas de XP que hemos comentado en el tema 5 en las siguientes categorías: 

- **Planificación y análisis de requisitos.** 
  - 
- **Factores humanos y equipo.** 
  - 
- **Diseño.**
  - 
- **Codificación del software y entrega.**
  - 




## Seminario 3: tableros Kanban

### 6. ¿Para qué se utiliza WIP (Work in progress) en Kanban? 

Limitación y visualización de la carga de trabajo del equipo. Es decir: si una tarea bloquea el desarrollo porque han surgido problemas, el avance se para hasta que se solucione y la tarea problemática salga de WIP. 

Teniendo un número limitado de tareas en WIP podemos permitir que el equipo completo se centre en las tareas más complejas cuando nos dan problemas.

### 7. Lee “La Guía oficial del Método Kanban” (disponible en Prado) y comenta los principios y métricas principales de Kanban. 



### 8. Comenta brevemente las diferencias entre Kanban y Scrum.

Primero mencionar que Scrum es un marco de trabajo, una metodología; y Kanban es una técnica específica. Esto quiere decir que dentro de Scrum existe espacio para la implementación de Kanban. Realmente sus similitudes a nivel de principios e ideales son más que sus diferencias.

La mayor diferencia reside en el flujo de trabajo. Kanban cuenta con un esquema de desarrollo continuo; mientras que Scrum se organiza en Sprints y distintas etapas. En general, el flujo de trabajo de Kanban es mucho más flexible que el del Sprint de Scrum, que se rige por temporizaciones estrictas y diversas prácticas (reuniones, artefactos...).

En Scrum determinamos la carga del Sprint según ciertas métricas, normalmente la velocidad del equipo y los puntos de historia, que asignamos al sprint. En kanban, optamos por las columnas WIP en cada punto del proceso, que tienen capacidad limitada. De esta forma, el trabajo concurrente se limita de forma natural, ya que cuando surge un problema que se alarga en el tiempo, eventualmente el equipo completo estará trabajando en él hasta que se solucione. 

En Kanban se destaca mucho el uso de elementos físicos visibles (tableros, pizarra, post-it...). En Scrum no se menciona su uso como parte de la metodología, pero son compatibles e incluso recomendables.





