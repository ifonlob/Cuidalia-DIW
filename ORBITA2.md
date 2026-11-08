# Órbita 2: Sistema visual de CUIDALIA

## 1. Enlaces

| Recurso | Enlace |
|---|---|
| Archivo de Figma | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=737-1697&t=WX9LXnEuDo9igRiq-1 |
| Prototipo interactivo | https://www.figma.com/proto/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=919-1518&t=mtt50dF8KfrP8AEq-1&scaling=scale-down&content-scaling=fixed&page-id=737%3A1697&starting-point-node-id=919%3A1518&show-proto-sidebar=1 |
| Proyecto de Google Stitch Coordinador | https://stitch.withgoogle.com/projects/17974827709597582741 |
| Proyecto de Google Stitch Trabajador |  https://stitch.withgoogle.com/projects/6907625626734045572 |
| Proyecto de Google Stitch Familiar | https://stitch.withgoogle.com/projects/5419180171900256187 |

---

## 2. Dónde está cada cosa en Figma

| Entregable | Página y sección del archivo |
|---|---|
| Inventario de decisiones | https://github.com/ifonlob/Cuidalia-DIW/blob/229bf3c971164249e8aff94580deb0d05f3972fd/CHANGELOG.md?plain=1#L67-L132 |
| Wireframes rediseñados con sus anotaciones | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=735-853 |
| Sistema de componentes | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=524-20 |
| Mockups del happy path | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=737-1697 |
| Home del coordinador - Desktop | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=919-1655&t=WX9LXnEuDo9igRiq-4 |
| Home del coordinador - Tablet | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=940-1210&t=WX9LXnEuDo9igRiq-4 |
| Home del coordinador - Mobile | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=940-1224&t=WX9LXnEuDo9igRiq-4 |
| Guía de estilo | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=683-317 |
| Pantallas en modo oscuro (Coordinador) | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=919-936&t=WX9LXnEuDo9igRiq-4 |
| Pantallas en modo oscuro (Trabajador) | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=772-442&t=WX9LXnEuDo9igRiq-4 |
| Pantallas en modo oscuro (Familiar) | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=772-533&t=WX9LXnEuDo9igRiq-4 |

---

## 3. Lista de comprobación de Figma

### Variables y estilos

- [X] Dos colecciones de variables: primitivas y semánticas.
- [X] Alias entre variables primitivas y semánticas.
- [X] Modos claro y oscuro correctamente configurados.
- [X] Estilos tipográficos vinculados a los textos de los mockups.
- [X] Estilos de efectos y retícula configurados y vinculados a las variables de espaciado cuando corresponda.

### Componentes y mockups

- [X] Componentes configurados con Auto Layout.
- [X] Componentes con propiedades y variantes de estado cuando corresponda.
- [X] Mockups construidos utilizando Auto Layout.
- [X] Espaciados y dimensiones vinculados a las variables correspondientes.
- [X] Uso coherente de componentes reutilizables en las distintas pantallas.

### Responsive y accesibilidad

- [X] Home del coordinador adaptada a Desktop.
- [X] Home del coordinador adaptada a Tablet.
- [X] Home del coordinador adaptada a Mobile.
- [X] Uso de los mismos componentes en las distintas adaptaciones, siempre que su estructura lo permita.
- [X] Comprobación de que no existen solapamientos, cortes de contenido ni desplazamiento horizontal.
- [X] Objetivos táctiles adecuados para dispositivos móviles.

### Modo oscuro y validación

- [X] Modo oscuro aplicado mediante el selector de modo de las variables.
- [X] Contraste adecuado entre textos, superficies y elementos gráficos.

### Prototipo

- [X] Prototipo interactivo configurado.
- [X] Recorrido completo del happy path.
- [X] Navegación y acciones principales comprobadas.

---

# 4. Resumen de decisiones

## 4.1. Rediseño de los wireframes

El rediseño de los wireframes se ha realizado teniendo en cuenta las necesidades de los tres perfiles principales de Cuidalia: trabajadores, familiares y coordinadores.

Se han revisado las propuestas visuales y se han seleccionado los cambios que considero más adecuados para mejorar la organización del contenido, la jerarquía visual y la facilidad de uso de cada pantalla.

### Trabajador

**Pantalla de login**

He decidido conservar la propuesta general de diseño porque me parece más acogedora, sencilla y minimalista. Únicamente he eliminado el mensaje de protección, ya que considero que no aporta información relevante para el proceso de inicio de sesión y ocupa un espacio innecesario.

**Pantalla de resumen general**

He eliminado los emoticonos y la fotografía de perfil, puesto que considero que son elementos prescindibles y no aportan información relevante para la tarea principal del usuario.

Además, he reorganizado la distribución de los elementos para aprovechar mejor el espacio disponible y evitar una presencia excesiva de espacios en blanco. Con estos cambios busco conseguir una pantalla más equilibrada, ordenada y fácil de consultar.

**Pantalla de mis turnos**

He mantenido la estructura general de la propuesta, pero he realizado algunos ajustes para simplificar la interfaz. He eliminado iconos redundantes y recuadros que no consideraba necesarios, además de reorganizar los elementos para conseguir una distribución más limpia.

Mi intención ha sido facilitar la consulta de los turnos, dando mayor protagonismo a la información realmente importante.

**Pantalla de detalle de visita**

He cambiado la denominación de "Detalle del turno" a "Detalle visita", para mantener la coherencia con la terminología establecida en el resto del proyecto.

También he eliminado algunos iconos redundantes y los recuadros correspondientes al contacto con coordinación y las observaciones, puesto que estos elementos no estaban contemplados en mi diseño original.

Por último, he conservado la barra de navegación inferior, ya que considero que proporciona una distribución más limpia, minimalista e intuitiva.

### Familiar

En este perfil he decidido rediseñar exclusivamente la pantalla de "Ficha del cuidador", ya que las mejoras propuestas para las demás pantallas no me parecían lo suficientemente relevantes como para justificar una reorganización.

**Ficha del cuidador**

He conservado la estructura general de la propuesta, pero he realizado varios ajustes para conseguir una interfaz más compacta y organizada.

En primer lugar, he reorganizado la tarjeta del cuidador asignado, reduciendo el tamaño de su imagen de perfil y agrupando mejor la información del nombre y el horario. También he incorporado dos acciones de contacto independientes: una para enviar un mensaje y otra para realizar una llamada telefónica.

Por otro lado, he simplificado las tarjetas correspondientes a los demás cuidadores, reduciendo su altura y reorganizando la información para aprovechar mejor el espacio disponible. También he incorporado un icono de horario para identificar más rápidamente los turnos de cada cuidador.

En general, he buscado conseguir una pantalla más limpia, compacta y funcional, dando mayor protagonismo al cuidador asignado y facilitando la consulta de las alternativas disponibles.

### Coordinador - Desktop

**Pantalla de login**

He reorganizado la distribución del formulario de inicio de sesión, concentrando sus elementos en un contenedor central para conseguir una interfaz más ordenada y equilibrada.

También he mejorado la identificación de los campos de correo electrónico y contraseña mediante etiquetas visibles e iconos que facilitan reconocer su función. He mantenido la opción de recordar la sesión y la posibilidad de solicitar la generación de credenciales, diferenciando claramente la acción principal del resto de opciones.

Con estos cambios busco simplificar el proceso de acceso y establecer una jerarquía visual más clara, dando protagonismo al formulario sin perder la identidad de la aplicación.

**Pantalla de resumen general**

He mantenido una estructura basada en una barra lateral de navegación y una zona principal de contenido, ya que considero que permite acceder a las diferentes secciones de la plataforma de forma organizada y aprovechar mejor el espacio disponible en escritorio.

He reorganizado la información mediante tarjetas de indicadores que muestran los usuarios activos, los trabajadores, los turnos del día y las incidencias, permitiendo a coordinación obtener una visión general de la actividad de la plataforma de un solo vistazo.

Además, he organizado la parte inferior en dos bloques diferenciados: por un lado, los turnos del día, mostrando los horarios y los trabajadores correspondientes; y, por otro, las alertas, que permiten identificar rápidamente las incidencias pendientes de resolver.

También he mantenido la barra superior con el buscador, el acceso a las notificaciones y la información del perfil, separando estas opciones de la navegación principal.

Con esta distribución busco ofrecer a coordinación una visión general más clara de la actividad diaria, facilitando la localización de la información relevante y evitando que los distintos bloques de contenido compitan entre sí.

---

## 4.2. Color

Para construir la identidad visual de Cuidalia he seleccionado una paleta basada en el verde azulado como color principal y el coral como color secundario.

El verde azulado transmite confianza, tranquilidad y profesionalidad, valores especialmente importantes en una plataforma relacionada con el cuidado y la atención a las personas. El coral aporta un contraste más cálido y cercano, evitando que la interfaz tenga una apariencia excesivamente fría o médica.

Además, he definido escalas cromáticas y colores neutros para establecer una jerarquía visual coherente. Los neutros se utilizan principalmente en fondos, superficies, textos y bordes, mientras que los colores de estado permiten identificar situaciones de éxito, error, advertencia e información.

La paleta se ha organizado mediante variables primitivas y semánticas para facilitar su reutilización y mantenimiento, así como la adaptación entre los modos claro y oscuro.

**Contraste y accesibilidad**

He tenido en cuenta los criterios WCAG AA para garantizar una lectura adecuada:

- Texto normal: contraste mínimo de 4,5:1.
- Elementos gráficos y componentes visuales relevantes: contraste mínimo de 3:1.

La combinación de menor contraste identificada en el modo claro es:

- Elemento y color de fondo: teal/50 (#E8F7F6) y coral/50 (#FFF0EA)
- Ratio medido con Stark: https://webaim.org/resources/contrastchecker/?fcolor=E8F7F6&bcolor=FFF0EA

La combinación de menor contraste identificada en el modo oscuro es:

- Elemento y color de fondo: teal/50 (#202B2F) y coral/50 (#332527)
- Ratio medido con Stark: https://webaim.org/resources/contrastchecker/?fcolor=202B2F&bcolor=332527

---

## 4.3. Tipografía

Para la identidad tipográfica de Cuidalia he seleccionado dos familias pertenecientes al sistema tipográfico IBM Plex: IBM Plex Sans como tipografía principal e IBM Plex Mono como tipografía secundaria.

He elegido IBM Plex Sans porque buscaba una tipografía clara, moderna y fácil de leer en una interfaz donde se consulta constantemente información como horarios, tareas, turnos y datos de los usuarios. Su diseño sans serif facilita una lectura cómoda en pantalla y permite mantener una apariencia profesional sin resultar demasiado seria o distante.

Como tipografía secundaria he escogido IBM Plex Mono, puesto que contrasta con la tipografía principal y aporta una apariencia más técnica y estructurada. He decidido utilizarla en elementos concretos, como horarios y códigos, evitando aplicarla en párrafos extensos para no dificultar la lectura.

La elección de ambas tipografías también responde a la búsqueda de coherencia visual, ya que pertenecen al mismo sistema tipográfico y mantienen una identidad común.

### Escala tipográfica y jerarquía visual

He definido una escala tipográfica de siete niveles para establecer una jerarquía clara y consistente en todas las pantallas de mi aplicación.

| Token | Tamaño | Altura de línea | Peso | Uso |
|---|---:|---:|---|---|
| display | 48 px | 56 px | Bold (700) | Títulos de gran protagonismo y pantallas de bienvenida. |
| heading-1 | 40 px | 48 px | Bold (700) | Títulos principales de las páginas. |
| heading-2 | 32 px | 40 px | Bold (700) | Encabezados de secciones principales. |
| heading-3 | 28 px | 36 px | Bold (700) | Subtítulos y encabezados de tarjetas. |
| body | 20 px | 28 px | Regular (400) | Textos descriptivos e información principal. |
| label | 16 px | 24 px | Bold (700) | Etiquetas de formularios, botones y elementos interactivos. |
| caption | 16 px | 22 px | Regular (400) | Información complementaria, fechas, direcciones y detalles de los turnos. |

Los tamaños se han seleccionado teniendo en cuenta la importancia de cada elemento y la necesidad de consultar información de forma rápida, especialmente en pantallas con numerosos datos.

### Correspondencia con las etiquetas HTML

Al definir la escala, he tenido en cuenta que el nivel tipográfico determina la apariencia visual del texto, mientras que la etiqueta HTML debe responder a su significado dentro de la estructura de la página.

| Nivel tipográfico | Etiquetas HTML posibles | Uso en CUIDALIA |
|---|---|---|
| display | `<h1>` | Título principal de una portada o sección de presentación. |
| heading-1 | `<h1>` | Título principal de una página. |
| heading-2 | `<h2>` | Títulos de las secciones principales de una pantalla. |
| heading-3 | `<h2>` / `<h3>` | Subtítulos de bloques, tarjetas y apartados. |
| body | `<p>` | Textos descriptivos y contenido informativo. |
| label | `<label>` / `<button>` / `<a>` | Etiquetas de campos de formulario, botones y enlaces, según su función. |
| caption | `<span>` / `<time>` | Fechas, horarios y datos complementarios. |

No he asociado cada nivel a una única etiqueta HTML de manera inamovible, ya que un mismo elemento puede utilizar diferentes estilos tipográficos dependiendo de su importancia visual, siempre respetando la jerarquía del documento.

### Legibilidad y accesibilidad

He tenido en cuenta la accesibilidad durante la selección de las familias y la definición de la escala tipográfica. En Cuidalia se manejan numerosos datos que necesitan consultarse de forma rápida y comprensible, por lo que la claridad de los textos es especialmente importante para los perfiles de usuarios: coordinación, trabajadores y familiares.

La diferenciación entre títulos, contenido principal y datos secundarios permite localizar la información con mayor facilidad y reduce el esfuerzo necesario para interpretar cada pantalla.

Mi objetivo con este sistema tipográfico es conseguir una interfaz coherente, legible y funcional, que permita consultar información de forma eficiente sin perder la personalidad profesional y cercana que quiero transmitir con Cuidalia.

---

## 4.4. Espaciado y retícula

Para mantener una distribución coherente entre los diferentes elementos de la interfaz he utilizado una escala de espaciado basada en una unidad de 4 píxeles, empleando principalmente múltiplos de 8 para establecer las separaciones entre componentes, tarjetas y secciones.

Esta escala permite mantener una distribución consistente, facilitando la organización de los contenidos y la adaptación de las pantallas a diferentes resoluciones.

### Configuración de la retícula

He establecido una retícula adaptada a los diferentes tamaños de pantalla, utilizando un número de columnas, márgenes y medianiles adecuados al espacio disponible.

| Propiedad | Desktop | Tablet | Mobile |
|---|---:|---:|---:|
| Resolución de referencia | 1280 px | 768 px | 360 px |
| Columnas | 12 | 8 | 4 |
| Medianil | 24 px | 16 px | 16 px |
| Márgenes | 32 px | 24 px | 16 px |

La versión Desktop constituye la referencia principal de la interfaz, mientras que las retículas de Tablet y Mobile permiten reorganizar los contenidos manteniendo una estructura ordenada y proporcional.

Además, he utilizado la misma escala de espaciado en los diferentes mockups mediante variables, favoreciendo la coherencia visual y facilitando el mantenimiento del sistema de diseño.

---

## 4.5. Componentes

He creado un sistema de componentes reutilizables con el objetivo de mantener la coherencia visual y facilitar el mantenimiento de la interfaz.

Los componentes permiten centralizar los elementos que aparecen repetidamente en las distintas pantallas, evitando tener que modificar cada instancia de manera independiente.

**Componentes principales**

| Componente | Variantes o propiedades |
|---|---|
| [Sidebars] | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=951-1872&t=WX9LXnEuDo9igRiq-4 |
| [Botones] | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=810-769&t=WX9LXnEuDo9igRiq-4 |
| [Campos de formulario] | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=751-218&t=WX9LXnEuDo9igRiq-4 |
| [Tarjetas] | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=763-449&t=WX9LXnEuDo9igRiq-4 |
| [Navegación inferior] | https://www.figma.com/design/F48oSLoyWxhvqBHM8RNxfD/Cuidalia?node-id=763-342&t=WX9LXnEuDo9igRiq-4 |

Los componentes utilizan Auto Layout, propiedades y variantes cuando corresponde, permitiendo mantener una estructura consistente y facilitar su reutilización en los diferentes mockups.

---

## 4.6. Responsive y modo oscuro

### Adaptabilidad responsive

He adaptado la pantalla principal del coordinador a tres resoluciones diferentes, con el objetivo de garantizar que la información siga siendo accesible y que la interfaz mantenga su funcionalidad en distintos tamaños de pantalla.

Las tres propuestas son:

| Versión | Resolución | Características |
|---|---|---|
| Desktop | 1440 × 1024 px | Sidebar completa, indicadores distribuidos horizontalmente y paneles de contenido organizados en columnas. |
| Tablet | 768 × 800 px | Sidebar compacta, indicadores reorganizados y distribución adaptada al menor espacio disponible. |
| Mobile | 360 × 800 px | Navegación inferior, indicadores compactos y contenido organizado verticalmente. |

El principal cambio realizado al adaptar la pantalla ha sido reorganizar la navegación y la distribución de los bloques de información, evitando reducir simplemente el tamaño de los elementos de escritorio.

También he tenido en cuenta la facilidad de interacción en dispositivos táctiles, procurando que los elementos interactivos dispongan de un área de pulsación adecuada.

### Modo oscuro

He desarrollado una adaptación de la interfaz al modo oscuro utilizando el sistema de variables de Figma, de manera que los cambios de apariencia se gestionan mediante el selector de modo y no modificando manualmente cada elemento.

Durante esta adaptación he revisado especialmente los colores de las superficies, los textos y los bordes, buscando mantener una jerarquía visual clara y evitar que los elementos pierdan visibilidad.

También he tenido en cuenta que las superficies del modo oscuro no deben utilizar necesariamente el negro absoluto, por lo que he empleado los colores neutros de la paleta para mantener una apariencia coherente con la identidad visual de Cuidalia.


El objetivo ha sido conservar la identidad visual de la aplicación en ambos modos, garantizando que la información y los elementos interactivos sigan siendo reconocibles.

---

# 5. Uso de IA

He utilizado Google Stitch como herramienta de apoyo durante el proceso de exploración de propuestas visuales para las pantallas de Trabajador, Familiar y Coordinación. Las propuestas se analizaron para valorar posibles mejoras en la distribución, la jerarquía visual y la organización de los contenidos.

Las decisiones tomadas, los elementos conservados y los cambios realizados en cada pantalla se describen en el apartado de rediseño y se detallan en el archivo `CHANGELOG.md`, destacando que solo se especifican las pantallas que han sido rediseñadas, ya que consideré que algunas pantallas de mis wireframes estaban bien construidas y no era necesario su rediseño.

---

# 6. Lo que ha quedado pendiente

Aunque he diseñado las tres versiones de la pantalla principal del coordinador (Desktop, Tablet y Mobile), ha quedado pendiente conseguir que la interfaz se adapte automáticamente al reducir progresivamente el tamaño de la ventana desde la versión Desktop.

Actualmente, las tres resoluciones están representadas mediante Frames independientes en Figma. Por tanto, cada una muestra correctamente la distribución prevista para su tamaño de pantalla, pero no se produce una transición automática entre ellas al modificar el ancho del Frame Desktop.

Por ejemplo, todavía no he conseguido que la barra lateral de navegación pase automáticamente de su versión completa a la compacta al alcanzar el breakpoint de Tablet, ni que se sustituya por la navegación inferior al llegar al tamaño Mobile.

Aunque he trabajado con Auto Layout y he definido las tres adaptaciones visuales, queda pendiente perfeccionar este comportamiento. La limitación se debe a que Figma no permite establecer puntos de ruptura con cambios estructurales automáticos como los que se implementan mediante media queries en CSS, ya que sólo he encontrado un plugin que lo permite pero es de pago, por lo que figma no lo incluye de forma nativa.

Por tanto, las tres versiones están diseñadas, pero la adaptación automática entre ellas queda pendiente de implementarse durante el desarrollo de la aplicación.
