# BRIEF DEL PROYECTO [Enlace al brief en FigJam](https://www.figma.com/board/bmj5okPQBjTse368s8NVrZ/Ideas-proyecto-DIW?node-id=103-675&t=TuTAvgNBjkPNDd40-4)

## El problema detectado

Las empresas de ayuda a domicilio tienen dificultades para coordinar los servicios, asignar cuidadores y mantener actualizada la información sobre las personas mayores atendidas.

Actualmente, la planificación depende de hojas de cálculo, mientras que la comunicación se realiza mediante llamadas telefónicas, WhatsApp y documentos en papel. Por lo que este caos a la hora de manejar la información provoca pérdidas de tiempo, dificulta la gestión de cambios de última hora y complica el seguimiento de las visitas y las tareas realizadas.

Las entrevistas realizadas a coordinación, una familiar y una cuidadora me han permitido identificar tres necesidades principales:

* **Mejorar la coordinación:** gestionar horarios, sustituciones y asignaciones teniendo en cuenta la disponibilidad, los desplazamientos y las necesidades de cada usuario.
* **Centralizar la información:** facilitar el acceso a las rutinas, tareas, indicaciones y datos relevantes para garantizar la continuidad de los cuidados.
* **Mejorar la comunicación y el seguimiento:** registrar las visitas y las tareas realizadas, comunicar incidencias y permitir que las familias consulten información relevante sin depender constantemente de llamadas a la oficina.

El problema afecta tanto al trabajo administrativo de coordinación como a la experiencia de los cuidadores y a la tranquilidad de las familias.

Asimismo, algunas evidencias que me han permitido identificar el problema, las he obtenido gracias a la entrevista realizada a cada una de las users personas, algunas son:

* Coordinación: "Hago cuadrantes enormes a principios de mes y se los mando por foto de WhatsApp a los cuidadores".
* Familiar: "Me paso el día trabajando y no sé si mi padre ha comido, si se ha tomado la pastilla de la tensión o si lo han duchado".
* Cuidadora: "Que vas totalmente a ciegas" cuando tiene que sustituir a otro trabajador.

Finalmente, cabe destacar que aunque la investigación ha identificado otras necesidades, como gestionar sustituciones, registrar visitas y comunicar incidencias, estas funciones quedan fuera del MVP, ya que la primera versión se centrará en facilitar la consulta de la información esencial para cada perfil de usuario.

## Objetivo del MVP

Desarrollar una plataforma web que permita a coordinadores, familiares y cuidadores consultar la información más relevante sobre los servicios de ayuda a domicilio, adaptando las funcionalidades disponibles al perfil de cada usuario.

**Funcionalidades incluidas**

**1. Inicio de sesión**
Todos los usuarios podrán iniciar sesión para acceder a la plataforma o en su contraparte, pedir la regeneración de las credenciales.

**2. Coordinador/a**
* Consultar un resumen general de la información relevante para la coordinación del servicio.
* Consultar los cuadrantes de horarios de los servicios y cuidadores.
* Acceder a la ficha de cada usuario para consultar su información.

**3. Familiar**
* Consultar la lista de tareas realizadas a su familiar.
* Consultar un resumen general de la información relevante sobre los cuidados de su familiar.

**4. Cuidador/a**
* Consultar un resumen general de los turnos asignados para ese día.
* Identificar el próximo turno.
* Acceder a los detalles de un turno para consultar las tareas que debe realizar durante el servicio.

**Alcance de la primera versión**
El MVP se centrará en el inicio de sesión y en la consulta de información adaptada a cada perfil. No permitirá editar cuadrantes, asignar cuidadores, registrar la realización de tareas ni gestionar incidencias.

## Restricciones

* **Alcance funcional:** el MVP se limitará al inicio de sesión y a la consulta de información correspondiente a cada perfil. Las funciones adicionales identificadas durante la investigación quedarán fuera de esta versión.
* **Restricciones tecnológicas:** la implementación deberá respetar las tecnologías, herramientas y requisitos de integración establecidos para el proyecto y su coordinación con DWEC y DWES. Las funcionalidades que no puedan desarrollarse dentro de esas condiciones no se incluirán en esta versión.
* **Tiempo y recursos:** el desarrollo se ajustará al calendario de la asignatura y a los recursos disponibles, priorizando las funciones esenciales
* **Condiciones de uso:** la interfaz deberá ser comprensible para usuarios con distintos niveles de competencia digital y permitir consultar la información desde móviles y ordenadores. Se priorizarán textos claros, navegación sencilla y controles fáciles de identificar.
* **Privacidad:** los datos personales y de salud de las personas mayores solo deberán estar disponibles para los perfiles autorizados.
* **Sostenibilidad ambiental:** se optimizarán las imágenes y se reutilizarán mediante caché los recursos estáticos que no hayan cambiado. Como objetivo inicial, se establece un peso máximo de 1 MB para la carga inicial de cada página, medido sin caché. Este límite deberá comprobarse durante las pruebas de rendimiento y ajustarse si las necesidades reales del proyecto lo justifican.

## Users Personas

La plataforma está dirigida a tres perfiles de usuario: coordinadores de empresas de ayuda a domicilio, familiares de personas mayores y cuidadores.

Cada perfil tiene necesidades específicas, por lo que la plataforma adaptará la información y las funcionalidades disponibles a sus responsabilidades.

**Persona principal: Coordinador/a**
Es la persona encargada de organizar y supervisar los servicios de ayuda a domicilio. Necesita consultar los cuadrantes de horarios, tener una visión general del servicio y acceder a las fichas de los usuarios para conocer sus necesidades. Actualmente, la gestión mediante hojas de cálculo, llamadas y documentos dispersos dificulta su trabajo y le hace perder tiempo.

**Persona secundaria 1: Familiar**
Es un familiar responsable que necesita conocer cómo se está atendiendo a su ser querido cuando no puede estar presente. Busca consultar las tareas realizadas y disponer de un resumen general de los cuidados para reducir la incertidumbre y evitar tener que llamar continuamente a la empresa.

**Persona secundaria 2: Cuidador/a**
Es el profesional que atiende a las personas mayores en sus domicilios. Necesita consultar los turnos asignados para el día, identificar cuál es su próximo servicio y acceder a los detalles de cada turno para conocer las tareas que debe realizar. La información debe ser clara y accesible para facilitar la preparación de cada visita.

Acceso a las fichas de personas
* Persona principal: https://www.figma.com/board/bmj5okPQBjTse368s8NVrZ/Ideas-proyecto-DIW?node-id=77-987&t=519FI3YClUYGlSZD-4
* Persona secundaria 1: https://www.figma.com/board/bmj5okPQBjTse368s8NVrZ/Ideas-proyecto-DIW?node-id=78-1519&t=519FI3YClUYGlSZD-4
* Persona secundaria 2: https://www.figma.com/board/bmj5okPQBjTse368s8NVrZ/Ideas-proyecto-DIW?node-id=79-1705&t=519FI3YClUYGlSZD-4

Cabe destacar que las fichas individuales recogen con mayor detalle el contexto de uso, los objetivos y las frustraciones de cada perfil, a partir de los datos obtenidos en las entrevistas.

## Criterios de éxito

**Coordinador/a:**
* Encuentra el cuadrante solicitado sin ayuda.
* Localiza la ficha de una persona usuaria y encuentra la información que necesita.
* Consulta el resumen general e identifica la información relevante.

**Familiar:**
* Encuentra la lista de tareas realizadas a su familiar.
* Localiza y comprende la información principal del resumen de cuidados.

**Cuidador/a:**
* Consulta los turnos asignados para el día.
* Identifica correctamente cuál es su próximo turno.
* Abre un turno concreto e identifica las tareas previstas para ese servicio.

**Acceso:**
* Cada participante inicia sesión y accede a la sección correspondiente a su perfil.

Método de evaluación:
Se pedirá a participantes representativos de los tres perfiles que completen estas tareas sin recibir instrucciones sobre cómo utilizar la interfaz. Se registrarán las tareas completadas, el tiempo empleado, los errores y las solicitudes de ayuda.

Meta propuesta: al menos el 80 % de los participantes completa las tareas principales de su perfil sin ayuda y comprende correctamente la información mostrada.

## Hipótesis inicial adaptada

Creo que las personas que coordinan servicios de ayuda a domicilio necesitan organizar y consultar la información de los servicios de atención a personas mayores, pero pierden tiempo y tienen dificultades para encontrar información fiable porque está repartida entre hojas de cálculo, WhatsApp, llamadas telefónicas y documentos en papel.
