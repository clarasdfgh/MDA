# MDA 22/23 - Relación de problemas 3

###### Clara María Romero Lara

## Tema 4: SCRUM

### 1. En el vídeo [“Scrum in 10 minutes”](https://www.youtube.com/watch?v=YFkwhTkrVx8) se comentan las características principales de Scrum. Contesta a las siguientes preguntas: 

#### ¿Faltan en el vídeo conceptos importantes que hemos visto en el Tema 4? 

- Aunque lo describe, no habla del concepto de Planificación del sprint, sino de Release planning.
- No menciona el Sprint Review

#### ¿Alguna idea interesante? 

- Equiparar el product backlog a una wishlist
- Planteamiento de la estimación en horas en vez de History points
- Aunque estrictamente hablando no sea Scrum, el planteamiento de los Release cycles y de sprints de distinta duración

#### ¿Algunos errores? 

- Menciona como roles a los tester, clientes, ejecutivos... Si bien son parte del entorno de desarrollo de un producto, no tienen que ver con Scrum de por sí

- Las priorización de historias de usuario no es un trabajo en equipo, se encarga el PO

- Añade conceptos externos a la terminología Scrum, como la Release

- Scrum plantea sprints de duración cercana a un mes. Todo lo mencionado sobre el ciclo de release, no es Scrum

  - Parafraseando a la guía Scrum:

    > El marco de Scrum, tal y como se describe en este documento, es inmutable. Aunque la implementación de sólo algunas partes de Scrum es posible, el resultado final no es Scrum. Scrum sólo existe en su totalidad y funciona bien como un contenedor para otras técnicas, metodologías y prácticas.

    Por tanto, es incorrecto clasificar lo descrito en el vídeo como Scrum. 

### 2. Contesta a las siguientes preguntas sobre la Pila del producto (Product Backlog): 

#### ¿La Pila del producto contiene todos los requisitos del producto? 

Sí, contiene todo lo que queremos que tenga nuestro producto. No solo eso, también puede incluir cosas como deseos, mejoras...

#### ¿Es una lista ordenada o desordenada? 

Ordenada. La Product Backlog es una lista priorizada.

#### ¿Quiénes crean los requisitos que contiene la Pila del producto? 

La Product Backlog es responsabilidad del PO, pero prácticamente cualquiera puede aportar requisitos: equipo scrum, stakeholders, usuarios...

#### ¿Los requisitos de la Pila del producto son de distintos tipos? 

Si, contiene requisitos funcionales y no funcionales.

### 3. Comenta brevemente las características principales de las técnicas de priorización: 

#### Modelo de Kano

El modelo Kano nos ayuda a entender las necesidades del cliente y su nivel de satisfacción. Para ello, se definen 3 categorías, basadas en dos ejes: la satisfacción del cliente (satisfecho, no satisfecho), y su grado de implementación (implementada, no implementada):

- **Necesidades básicas:** si no están implementadas, generan una gran insatisfacción; pero si están implementadas no generan demasiada satisfacción. Son los mínimos esperados del producto, pero no lo distinguen de sus competidores.
- **Necesidades de performance:** crecimiento lineal entre implementación-satisfacción: a más implementados, mayor satisfacción y viceversa. No son críticos para el producto, pero nos dan ventaja sobre los competidores.
- **Delighters (deslumbrantes, emocionantes):** características inesperadas, su ausencia no genera insatisfacción, pero su presencia da mucha satisfacción. Rasgos definitorios, cosas que nos harán destacar en el mercado, aquí es dónde se toman riesgos

#### Criba de temas 

En la criba de temas, lo primero es identificar los criterios que nos importan a la hora de priorizar, tales como satisfacción del cliente, rentabilidad, productividad... y los asignamos a filas en una tabla.

Seleccionamos una historia o épica base, que debe ser un elemento relevante para el próximo sprint. Debería ser un elemento cuya implementación es importante, pero no garantizada. Si seleccionamos el elemento más relevante de todo el sprint, inevitablemente nos encontraremos que todos los demás elementos son menos relevantes.

Iremos comparando todas las demás historias con esta base, indicando en cada uno de los criterios (filas) si la historia es mejor (+1), peor (-1) o igual (0) en ese aspecto. 

#### Peso relativo

En este método, calificamos del 1 al 9 el beneficio que aporta una cierta funcionalidad y el riesgo que conlleva su ausencia o coste. 

A partir de esta información, podemos calcular el valor total y porcentual de una historia, el cual podremos usar para determinar su prioridad, riesgo, beneficio...

### 4. ¿Cómo crees que los valores de Scrum, que hemos comentado en el Tema 4, mejora el proceso de desarrollo del software? 

- Comunicación con el cliente a través del PO, lo cual nos provee con feedback
- Iterativo
- Genera siempre un producto usable
- Coordinación en el equipo, se trabaja hacia una meta común y todos conocen los objetivos entre sí
- Acepta el cambio como una parte inevitable del desarrollo y fomenta la adaptación como una máxima
- Descriptivista, no prescripcionista. La documentación se genera de forma orgánica según se trabaja sobre los artefactos, en vez de generarse al principio sin tener un marco empírico de referencia.

### 5. Indica que rol o roles de Scrum realizan cada una de las distintas actividades:

- **Actualizar el trabajo en progreso (burndown chart).** 
  - Scrum Master
- **Definir buenas historias de usuario.** 
  - PO, Stakeholders
- **Ordenar y priorizar las historias de usuario del Product Backlog.** 
  - PO
- **Planificar la implantación de Scrum junto con la organización.** 
  - Scrum Master
- **Implementar las pruebas de aceptación.** 
  - Equipo de desarrollo
- **Asegurar y promover buenas prácticas de programación.** 
  - Scrum Master, Equipo de desarrollo
- **Fijar criterios de aceptación para cada historia de usuario.** 
  - PO
- **Dividir las historias de usuario en tareas.** 
  - Equipo de desarrollo
- **Estimar las tareas.** 
  - Equipo de desarrollo
- **Estimar las historias de usuario.**
  -  PO, Scrum Master, Equipo de desarrollo
- **Implementar las pruebas de unidad.** 
  - Equipo de desarrollo
- **Solucionar los posibles impedimentos que pudieran surgir durante el sprint.** 
  - Scrum Master
- **Definir el plan de entregas.** 
  - PO
- **Ayudar al equipo de desarrollo a convertirse en auto-organizado y multifuncional.** 
  - Scrum Master
- **Ayudar a que las posibles mejoras detectadas en la retrospectiva del sprint se lleven a cabo.** 
  - Scrum Master
- **Buscar la excelencia técnica.** 
  - Scrum Master, Equipo de desarrollo
- **Estar disponible y accesible para el equipo de desarrollo.**
  - Scrum Master, PO
- **Gestionar el equipo de desarrollo.**
  - Scrum Master

### 6. Indica que roles de Scrum participan en cada una de las siguientes reuniones:

-  **Reunión de planificación de Sprint Planning.** 
  - Equipo de desarrollo, Scrum master, PO
- **Reunión de planificación detallada de Sprint Planning.** 
  - Equipo de desarrollo, Scrum master
- **Reunión de revisión del Backlog (Backlog grooming).** 
  - PO, Equipo de desarrollo
- **Reunión diaria (Daily meeting).** 
  - Equipo de desarrollo y Scrum master
  - Opcional: PO
- **Reunión de revisión del sprint (Sprint Review).** 
  - Equipo de desarrollo, Scrum master, PO, clientes.
- **Reunión de retrospectiva (Sprint retrospective).**
  - Equipo de desarrollo, Scrum master, PO. 

### 7. ¿Cómo se consigue en Scrum los principios de transparencia, inspección y adaptación? 

Si el equipo de desarrollo y los implicados adoptan Scrum y sus valores (compromiso, enfoque, apertura, respeto y coraje), los artefactos y eventos se ejecutan correctamente, otorgando la transparencia necesaria para ejecutar los otros dos principios.

Los principios se retroalimentan entre sí: no existe inspección sin transparencia, no existe adaptación sin inspección. Y cómo hemos destacado, la transparencia se consigue ejecutando correctamente los eventos y artefactos de Scrum.

### 8. ¿Qué ocurre durante un Sprint si el Product Owner identifica una nueva historia de usuario?

Se debería esperar al final del sprint para añadirla. Añadir historias durante el desarrollo de un sprint no es una buena práctica porque puede afectar al objetivo de éste, además de añadir cargas (consultar con el PO, priorización, estimación...). 

El mejor momento sería en la planificación del sprint.