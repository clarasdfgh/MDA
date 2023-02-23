# MDA 22/23 - Relación de problemas 2

###### Clara María Romero Lara

## Tema 3: Métodos de desarrollo ágiles

### 1. Comenta las diferencias principales entre las metodologías ágiles y las metodologías tradicionales. 

- **Participación del cliente:** en las metodologías tradicionales, se invierte una buena cantidad de tiempo al inicio de la planificación en determinar qué quiere exactamente el cliente. Una vez planificado, el cliente no aporta mucho más. En las metodologías ágiles, en cambio, el tiempo inicial de planificación se reduce, a cambio de mantener al cliente mucho más involucrado en el desarrollo de las iteraciones, recibiendo su feedback y aportando ideas.
- **Desarrollo lineal vs. iterativo:** las metodologías tradicionales trabajan en cascada: se pasa por cada etapa de desarrollo una única vez. Las metodologías ágiles trabajan iterando todas las fases hasta que se completa el producto. Esto hace el desarrollo mucho más flexible, puesto que se podrán corregir cosas en iteraciones futuras.
-  **Equipos autodirigidos:** en las metodologías ágiles existe la figura del *Proyect Manager*, una jerarquía superior dentro del proyecto que organiza y dirige al equipo de desarrollo. Los equipos ágiles no cuentan con esta figura, todos desarrollan y participan en la organización del proyecto equitativamente. Puede existir la figura de *Scrum Master* o equivalentes, pero este rol nunca es un superior en el desarrollo, sino más bien un nodo de conexión entre los devs y el cliente.

### 2. Lee el documento sobre *15th Annual State of Agile Survey* que podéis encontrar en Prado, y contesta a las siguientes preguntas: 

#### 2.1. ¿Cuál es el método ágil más utilizado? 

Scrum, con un 66% de los encuestados.

#### 2.2. ¿Cuáles son las 5 técnicas ágiles más usadas? 

1. Scrum
2. ScrumBan
3. Híbrido de Scrum/XP
4. Kanban
5. Iterativo

#### 2.3. Comenta algunas de las causas principales qué hacen que los proyectos ágiles fallen. 

1. Procesos y prácticas poco consistentes entre equipos
2. La cultura de la empresa no coincide con los valores ágiles
3. Resistencia al cambio

#### 2.4 Comenta algunos de los obstáculos que impiden que se adopten los métodos ágiles.

1. Procesos y prácticas poco consistentes entre equipos
2. La cultura de la empresa no coincide con los valores ágiles
3. Resistencia al cambio
4. Falta de experiencia o práctica con métodos ágiles



## Seminario 2: Historias de usuario

### 3. Comenta las diferencias principales entre escenarios, casos de uso e historias de usuario. 

- **Escenarios**: descripción **narrativa** de una interacción entre el usuario y el sistema, incluyendo contexto como su formación, situación actual, sentimientos...
- **Casos de uso**: descripción **técnica** de una tarea, describiendo en profundidad su funcionalidad: entradas, salidas, procesos...
- **Historias de usuario**: definidas por los mismos usuarios. Frases cortas en lenguaje **simple**, que definen una necesidad de interacción específica entre el usuario y el sistema, sin detallar salidas, entradas, procesos, contexto, opiniones...

### 4. ¿Por qué se especifican las pruebas de aceptación antes de desarrollar las Historias de usuario por parte del Equipo de desarrollo? 

Porque sirven como guía a los desarrolladores a la hora de implementar las HU. Hacen que sea mucho más fácil determinar si la HU está acabada, porque dictan características necesarias para el sistema. Además sirven para dar profundidad a las HU, especificaciones de PO sobre éstas.

### 5. Describe las historias de usuario de una aplicación web que permita la compra de entradas de cine, así como la consulta de las películas que se ofrecen en un lugar concreto. Prioriza las historias de usuario, y para las 5 primeras escribe las pruebas de aceptación y divídelas en sus tareas. 

- Como usuario, quiero ver la lista completa de ubicaciones ofertadas
- Como usuario, quiero ver la lista completa de películas ofertadas
- Como usuario, quiero poder ver la cartelera de un cine concreto
- Como usuario, quiero poder acceder a la página de una película 
- Como usuario, quiero que la página de la película contenga información relevante (ubicaciones, horarios, duración, calificación por edades...)
- Como usuario, quiero poder comprar entradas para una película en una ubicación
- Como usuario, quiero poder registrarme en la aplicación
- Como usuario, quiero poder ver mi perfil
- Como usuario, quiero poder modificar mi perfil
- Como usuario, quiero poder eliminar mi perfil
- Como usuario, quiero recibir algún tipo de bonificación por ser usuario registrado en la aplicación
- Como administrador, quiero poder añadir ubicaciones
- Como administrador, quiero poder añadir películas
- Como administrador, quiero poder asociar películas a ubicaciones
- Como administrador, quiero poder eliminar ubicaciones
- Como administrador, quiero poder eliminar películas
- Como administrador, quiero poder modificar la información de una ubicación
- Como administrador, quiero poder modificar la información de una película
- Como administrador, quiero poder eliminar un usuario de la aplicación



1. Como usuario, quiero ver la lista completa de ubicaciones ofertadas
   - Prioridad: 1
   - Pruebas de aceptación:
     - Aparece la lista completa de ubicaciones
     - Al hacer click en una ubicación, nos redirige a la cartelera específica a esa ubicación
     - Las ubicaciones aparecen ordenadas por proximidad
   - Subtareas:
2. Como usuario, quiero ver la lista completa de películas ofertadas
   - Prioridad: 1
   - Pruebas de aceptación:
     - Aparece la lista completa de películas
     - Las películas aparecen en orden alfabético
     - Al hacer click en una película, nos redirige a la página de la misma
3. Como usuario, quiero poder ver la cartelera de un cine concreto
   - Prioridad: 1
   - Pruebas de aceptación:
     - Aparece la lista completa de películas asociadas a la ubicación
     - Al hacer click en una película, nos redirige a la página de la misma
     - La página de la película es específica para la ubicación seleccionada, mostrando sólo los horarios de ésta.
4. Como usuario, quiero poder acceder a la página de una película 
   - Prioridad: 1
   - Pruebas de aceptación:
     - Si se viene desde la cartelera de una ubicación, sólo se muestran sus horarios
5. Como usuario, quiero que la página de la película contenga información relevante (ubicaciones, horarios, duración, calificación por edades...)
   - Prioridad: 2
   - Pruebas de aceptación:
     - Se lista la información completa de la película
     - Se listan horarios
     - Existe diferenciación entre los horarios-ubicaciones disponibles y los completos
     - Se lista la clasificación por edades
     - Se lista la duración
     - Se lista el género

### 6. ¿Por qué los usuarios escriben las historias de usuario?

Porque lo importante es que se describa la interacción real entre usuario y sistema, ver las necesidades reales del usuario. Sólo los propios usuarios saben lo que es importante para su experiencia de uso. Las historias de usuario deben servir a los desarrolladores y PO como método de comunicación y negociación.