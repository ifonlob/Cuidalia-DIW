# CHANGELOG — Órbita 1

## 14/10/2026 — Uso de inteligencia artificial

### 1. Hipótesis y brief

**Herramienta**: ChatGPT.

**Uso**: Solicité ayuda para estructurar y mejorar la redacción de la hipótesis, el problema, el MVP, los criterios de éxito y las restricciones.

**Decisión**: Utilicé las propuestas como apoyo y adapté el contenido a las entrevistas, los requisitos de la asignatura y el alcance que decidí para el proyecto.

### 2. Fichas de las personas

**Herramientas**: ChatGPT e IA de generación de imágenes.

**Uso**: Solicité ayuda para organizar los perfiles y generar propuestas visuales de las tres fichas.

**Decisión**: Conservé la estructura visual y adapté los contenidos a las necesidades identificadas en las entrevistas.

**Criterio personal**

La IA se utilizó como herramienta de apoyo para organizar información, explorar alternativas y mejorar la presentación.
No obstante, la selección de propuestas y las decisiones finales corresponden a mi criterio.

## 15/10/2026 — Uso de inteligencia artificial

### 1. Organización de las entrevistas

*+Herramienta**: ChatGPT.

**Qué pedí**: Ayuda para estructurar la información de las entrevistas que ya había recopilado, manteniendo las preguntas y respuestas de los perfiles de coordinación, familiar y cuidador/a.

**Qué devolvió la IA**: Una propuesta de formato común para las tres entrevistas, organizada en objetivo, preguntas y respuestas.

**Qué conservé**: La estructura común y la síntesis de necesidades principales de cada perfil.

**Qué cambié**: Adapté la redacción para facilitar la lectura, mantuve el contenido procedente de mis notas y distinguí los hallazgos de las funcionalidades que finalmente entran en el MVP

### 2. Análisis de referentes

**Herramienta**: ChatGPT.

**Qué pedí**: Ayuda para organizar y comparar el análisis de Gesad, CIBERSAD y Birdie.

**Qué devolvió la IA**: Una estructura común para analizar los tres referentes y una síntesis de sus características.

**Qué conservé**: La organización por producto y la comparación de las funciones destinadas a coordinación, familiares y cuidadores.

**Qué cambié**: Revisé las conclusiones para distinguir las características descritas en fuentes públicas de los problemas que todavía no he comprobado directamente.De la misma forma, evité presentar las hipótesis de usabilidad como defectos demostrados y relacioné los aprendizajes con las necesidades identificadas en mis entrevistas.


## 16/10/2026 — Definición del MVP

### 1. Organización y priorización de funcionalidades

**Herramienta**: ChatGPT.

**Qué pedí**: Ayuda para organizar las funcionalidades de CUIDALIA y decidir cuáles incluir en el MVP y cuáles dejar fuera, teniendo en cuenta las necesidades de los usuarios, la viabilidad técnica y el tiempo disponible.

**Qué devolvió la IA**: Una propuesta estructurada de funcionalidades para coordinación, trabajadores y familiares, junto con justificaciones para las funciones incluidas y descartadas.

**Qué conservé**: La organización del panel principal de coordinación, la gestión básica de ausencias, las fichas contextuales de los usuarios, las recomendaciones de sustitución mediante reglas y puntuaciones, y la confirmación manual por parte del coordinador. También conservé las funciones de consulta y registro previstas para trabajadores, la consulta de información por parte de los familiares y el acceso diferenciado según el perfil.

**Qué cambié**: Delimité el alcance excluyendo funcionalidades que aumentarían la complejidad sin ser imprescindibles para validar el proceso principal, como la mensajería en tiempo real, las notificaciones push, la optimización automática de rutas, la gestión administrativa avanzada y los algoritmos predictivos o basados en modelos avanzados de inteligencia artificial. 

# CHANGELOG - Órbita 2

## Rediseño de wireframes con Google Stitch

### Trabajador

#### Pantalla de login

La propuesta generada por Stitch se ajusta bastante a la idea que tenía para esta pantalla. He decidido conservar su diseño general, ya que me parece más acogedor, sencillo y minimalista. Únicamente he eliminado el mensaje de protección, porque considero que no aporta información relevante para el proceso de inicio de sesión y ocupa un espacio innecesario.

#### Pantalla de resumen general

En esta pantalla he optado por eliminar los emoticonos y la fotografía de perfil, ya que considero que ambos elementos son prescindibles y no aportan información relevante para la tarea principal del usuario.

Además, he reorganizado la distribución de los elementos para aprovechar mejor el espacio disponible y evitar la presencia de demasiados huecos en blanco. Con estos cambios busco conseguir una pantalla más equilibrada, ordenada y fácil de consultar.

#### Pantalla de mis turnos

En este caso, he mantenido la estructura general propuesta por Stitch, pero he realizado algunos ajustes para simplificar la interfaz. He eliminado iconos redundantes y recuadros que no consideraba necesarios, además de reorganizar los elementos para conseguir una distribución más limpia y aprovechar mejor el espacio.

Mi intención ha sido facilitar la consulta de los turnos, dando mayor protagonismo a la información realmente importante.

#### Pantalla de detalle del turno

En primer lugar, he cambiado el nombre de la pantalla de «Detalle del turno» a «Detalle visita», para mantener la coherencia con la denominación establecida en el resto del proyecto.

También he eliminado algunos iconos redundantes y los últimos recuadros correspondientes al contacto con coordinación y las observaciones, puesto que estos elementos no estaban contemplados en mi diseño original. De esta manera, he conseguido simplificar la interfaz y mantener únicamente la información necesaria.

Por último, he decidido conservar la propuesta de barra de navegación inferior de Stitch, ya que me parece más limpia, minimalista e intuitiva que la distribución que tenía inicialmente.

### Familiar

En este caso he optado por rediseñar de forma exclusiva la pantalla de 'Ficha del cuidador' puesto que las mejoras ofrecidas por Stitch no me han parecido lo suficiente
notorias ni que aportaran mejoras en cuanto a jerarquía visual.

#### Ficha del cuidador

En esta pantalla he decidido conservar la estructura general propuesta por Stitch, pero he realizado varios ajustes para conseguir una interfaz más compacta y organizada.

En primer lugar, he reorganizado la tarjeta del cuidador asignado, reduciendo el tamaño de su imagen de perfil y agrupando mejor la información del nombre y el horario. También he incorporado dos acciones de contacto diferentes, por una parte la que permite enviar un mensaje y por otra, la que realiza una llamada telefónica, facilitando el acceso a ambas opciones sin tener que depender de una única acción.

Por otro lado, he simplificado las tarjetas correspondientes a los demás cuidadores, reduciendo su altura y reorganizando la información para aprovechar mejor el espacio disponible. También he incorporado un pequeño icono de horario para identificar más rápidamente los turnos de cada cuidador.

En general, he buscado conseguir una pantalla más limpia, compacta y funcional, dando mayor protagonismo al cuidador asignado y facilitando la consulta de las alternativas disponibles.

### Coordinador (Desktop)

#### Pantalla de login

En esta pantalla he optado por reorganizar la distribución del formulario de inicio de sesión, concentrando sus elementos en un contenedor central para conseguir una interfaz más ordenada y equilibrada.

También he mejorado la identificación de los campos de correo electrónico y contraseña mediante etiquetas visibles e iconos que facilitan reconocer su función. He mantenido la opción de recordar la sesión y la posibilidad de solicitar la generación de credenciales, diferenciando claramente la acción principal del resto de opciones.

En general, he buscado simplificar el proceso de acceso y establecer una jerarquía visual más clara, dando protagonismo al formulario sin perder la identidad de la aplicación.

#### Pantalla de resumen general

En esta pantalla he decidido mantener una estructura basada en una barra lateral de navegación y una zona principal de contenido, ya que considero que permite acceder a las diferentes secciones de la plataforma de forma más organizada y aprovechar mejor el espacio disponible en escritorio.

He reorganizado la información del resumen general mediante tarjetas mejores estructuradas, como los usuarios activos, los trabajadores, los turnos del día y las incidencias. De esta manera, coordinación puede obtener una visión general de la actividad de la plataforma de un solo vistazo.

Además, he organizado la parte inferior en dos bloques diferenciados: por un lado, los turnos del día, mostrando los horarios y los trabajadores correspondientes; y, por otro, las alertas, que permiten identificar rápidamente las incidencias pendientes de resolver.

También he mantenido la barra superior con el buscador, el acceso a las notificaciones y la información del perfil, separando estas opciones de la navegación principal.

Con esta distribución busco ofrecer a coordinación una visión general más clara de la actividad diaria, facilitando la localización de la información relevante y evitando que los distintos bloques de contenido compitan entre sí.
