# Capítulo III: Solution UI/UX Design

## 3.1. Product design

### 3.1.1. Style Guidelines

#### 3.1.1.1. General Style Guidelines

### 3.1.2. Information Architecture

En base a nuestra aplicación, hemos decidido que nuestro diseño y organización visual será jerárquico, para que los usuarios puedan distinguir claramente la importancia de cada funcionalidad de la app. Al mismo tiempo, utilizamos un sistema moderno y sencillo para atraer a los usuarios.

#### 3.1.2.1. Organization Systems

**Landing Page**

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;"> 
    <tr> 
        <th>Tópico</th> 
        <th>Descripción</th>   
    </tr> 
    <tr> 
        <td>Home</td> 
        <td>La página de inicio muestra una vista general del servicio y destaca las características clave de EduSpace.</td> 
    </tr> 
    <tr> 
        <td>About Us</td> 
        <td>En esta sección, EduSpace explica nuestro compromiso con la gestión eficiente de espacios educativos. También proporcionamos ejemplos de la información detallada que la app mobile ofrece, como el control de inventario, la automatización de cálculos salariales, y la organización de recursos.</td> 
    </tr> 
    <tr> 
        <td>Packages</td> 
        <td>La página ofrece una descripción detallada de los planes disponibles: un plan para pequeñas infraestructuras y un plan premium para grandes infraestructuras, destacando las funcionalidades avanzadas de cada uno.</td> 
    </tr>  
    <tr> 
        <td>Contact</td> 
        <td>Esta sección proporciona información de contacto para soporte y consultas</td>
    </tr> 
    <tr> 
        <td>Sign In</td> 
        <td>La página para que el usuario ingrese a su cuenta. Aquí se solicitan las credenciales de inicio de sesión y se ofrece la opción de recuperar la contraseña en caso de olvido.</td> 
    </tr> 
    <tr>   
        <td>Sign Up</td> 
        <td>La página para que el usuario se registre en EduSpace. Incluye un formulario para ingresar información básica como nombre, correo electrónico y contraseña, así como la opción de aceptar los términos y condiciones del servicio.</td> 
    </tr> 
</table>

**App mobile**

* Tabla de Organización para Administradores

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;">
  <tr>
    <th>Feature</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>Home</td>
    <td>Página principal con un resumen de datos clave, como informes recientes, estado de espacios, y notificaciones urgentes.</td>
  </tr>
  <tr>
    <td>Registro de Ambientes</td>
    <td>Registro de espacios deportivos, aulas y otros ambientes, incluyendo detalles como el equipamiento y el docente responsable.</td>
  </tr>
  <tr>
    <td>Gestión de Cambios de Aula y Reuniones</td>
    <td>Permite gestionar y registrar cambios de aula o reuniones, notificando a los docentes y otros usuarios afectados.</td>
  </tr>
  <tr>
    <td>Gestión de Datos de Trabajadores</td>
    <td>Acceso y administración de la información de docentes, personal de limpieza y otros trabajadores, incluyendo datos personales y profesionales.</td>
  </tr>
  <tr>
    <td>Gestión del Personal a Cargo</td>
    <td>Asignación y reasignación de personal responsable de cada espacio, con opciones para reasignar en caso de ausencias.</td>
  </tr>
  <tr>
    <td>Notificaciones</td>
    <td>Sistema de notificaciones que alerta sobre cambios en los espacios, reportes pendientes, y actualizaciones importantes.</td>
  </tr>
  <tr>
    <td>Perfil</td>
    <td>Acceso a la información personal y profesional del administrador, con opciones para editar datos y visualizar historial de salarios y bonificaciones.</td>
  </tr>
  <tr>
    <td>Cerrar Sesión</td>
    <td>Opción para cerrar sesión de manera segura.</td>
  </tr>
</table>

* Tabla de Organización para Docentes

<table border="1" cellpadding="10" cellspacing="0">
  <tr>
    <th>Feature</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>Home</td>
    <td>Página principal con un resumen de tareas, notificaciones, y un calendario de actividades asignadas.</td>
  </tr>
  <tr>
    <td>Notificaciones de Cambios de Aula o Reuniones</td>
    <td>Alertas sobre cambios de aula o reuniones, incluyendo detalles del nuevo espacio, hora y participantes.</td>
  </tr>
  <tr>
    <td>Reserva de Espacios Deportivos y Ambientes</td>
    <td>Sistema para reservar espacios deportivos y ambientes compartidos, con información sobre disponibilidad y reglas de uso.</td>
  </tr>
  <tr>
    <td>Reporte de Averías en Equipos</td>
    <td>Herramienta para reportar averías o problemas con equipos o recursos del ambiente, con seguimiento del estado de resolución.</td>
  </tr>
  <tr>
    <td>Visualización de Espacios Disponibles</td>
    <td>Consulta de los espacios libres, ocupados y sus fechas de disponibilidad, facilitando la planificación de actividades.</td>
  </tr>
  <tr>
    <td>Perfil</td>
    <td>Información personal y profesional del docente, con opciones para editar datos y visualizar historial de salarios y otras compensaciones.</td>
  </tr>
  <tr>
    <td>Cerrar Sesión</td>
    <td>Opción para cerrar sesión de manera segura.</td>
  </tr>
</table>

#### 3.1.2.2. Labelling Systems

En esta sección, se explica las estrategias empleadas para etiquetar y organizar la información dentro de la plataforma mobile EduSpace, buscando mantener la simplicidad y evitar la confusión para los visitantes y usuarios. Las etiquetas se diseñan para ser claras y concisas, utilizando el mínimo número de palabras necesario para representar eficazmente los conjuntos de información y sus asociaciones.

Principios de Etiquetado:

- Claridad: Cada etiqueta debe ser fácilmente comprensible por todos los usuarios, independientemente de su rol (administrador o docente).
- Consistencia: Se mantiene un lenguaje uniforme en todas las secciones de la aplicación para evitar confusión.
- Brevedad: Las etiquetas se formulan con el menor número de palabras posibles sin perder claridad o precisión.

Etiquetas para Administradores:

- Home: Resumen y acceso rápido a funciones clave.
- Environments and Equipment: Registro y gestión de ambientes (aulas, deportivos, etc.).
- Classroom Changes and Meetings: Administración de cambios de aulas o reuniones.
- Personal Data: Gestión de datos y roles de trabajadores.
- Personnel Management: Asignación y reasignación de personal responsable de cada espacio. 
- Notifications: Alertas y actualizaciones importantes.
- Profile: Información personal y profesional del administrador.
- Log Out: Opción para cerrar sesión.

Etiquetas para Docentes:

- Home: Resumen de tareas y calendario de actividades.
- Notifications: Notificaciones sobre cambios de aula o reuniones.
- Reservations: Reserva de espacios deportivos y aulas.
- Breakdown Reports: Reporte de averías en equipos o recursos.
- Availability: Consulta de espacios disponibles y ocupados.
- Profile: Información personal y profesional del docente.
- Log Out: Opción para cerrar sesión.


Estas etiquetas están diseñadas para facilitar la navegación y comprensión de la plataforma, asegurando que los usuarios puedan acceder rápidamente a las funciones que necesitan, sin tener que interpretar términos complicados o ambiguos. La simplicidad en el etiquetado también ayuda a minimizar el tiempo de aprendizaje y maximiza la eficiencia en el uso de la aplicación.

#### 3.1.2.3. SEO Tags and Meta Tags

Las meta etiquetas nos permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las leen. Estas etiquetas facilitan el análisis de archivos HTML y ayudan en el mantenimiento del contenido. Además, influyen en el posicionamiento de nuestra página en los motores de búsqueda

- Title: 

<div style="text-align: center;">

```html
<title>EduSpace</title>
```

</div>

- Meta Description: 

<div style="text-align: center;">

```html
<meta name="description" content="Platform that simplifies the management of educational infrastructures."/>
```

</div>


- Meta Keyboard: 

<div style="text-align: center;">

```html
<meta name="keywords" content="Management, platform, optimization, automation, coordination, inventory, reservation, infrastructure, communication"/>
```

</div>

- Meta Author: 

<div style="text-align: center;">

```html
<meta name="author" content="Los ProDevs"/>
<meta name="copyright" content="Copyright EduSpace team" />
```

</div>

#### 3.1.2.4. Searching Systems

EduSpace, el sistema de filtrado ha sido diseñado para proporcionar una experiencia eficiente y fluida a la hora de gestionar reservas de espacios educativos y equipamiento, sin abrumar a los usuarios con el volumen de información disponible.

#### **Opciones de Búsqueda Ofrecidas**

- **Cátegorias de Búsqueda**

Los usuarios pueden navegar por categorías predefinidas según su rol. Para los docentes, las opciones incluyen la búsqueda por "Día", "Hora", y "Lugar", permitiendo encontrar rápidamente aulas disponibles o recursos para sus clases. Estas categorías están organizadas de forma clara, al estilo de un buscador de Google, facilitando el acceso directo a la información más relevante.

Para los administradores, se ofrecen filtros adicionales para la búsqueda de equipamiento y ambientes (como aulas o espacios deportivos), con etiquetas que permiten explorar el inventario de manera eficiente. En el caso de ambientes deportivos, los administradores también tienen la opción de filtrar por tipos específicos como "Voleibol", "Fútbol" o "Básquet".

- **Búsqueda avanzada con filtros**

**Docentes:**

- Día y hora de la reserva.
- Lugar de la búsqueda (aulas, espacios comunes).

**Administradores:**
- Equipamiento: tipo de recursos disponibles en cada aula o ambiente.
- Ambientes: aulas, oficinas, espacios deportivos.
- Ambientes deportivos: tipo de espacio deportivo como voleibol, fútbol, básquet.

#### **Visualización de los Datos Después de la Búsqueda**

**Resultados en forma de Tarjetas**

Los resultados se muestran en tarjetas visualmente organizadas que contienen:

- Nombre del ambiente o del equipo disponible.
- Una imagen del aula, equipo o espacio deportivo.
- Detalles clave como capacidad, disponibilidad de recursos o estado de mantenimiento.

#### **Orden de los Resultados**

Los resultados están ordenados por:

- Relevancia: según los filtros seleccionados por el usuario.
- Disponibilidad: los ambientes y equipamientos disponibles primero.

En conjunto, estas herramientas permiten que el proceso de búsqueda en EduSpace sea intuitivo, rápido y enfocado en satisfacer las necesidades tanto de docentes como de administradores.

#### 3.1.2.5. Navigation Systems

Menú Principal: El menú principal contiene las opciones más importantes de navegación como "Home", "Reservas", "Perfil" y el ícono de "inventario". Dicho menú permite un acceso rápido y directo a las secciones clave desde cualquier página.

Categoría de Ambientes: Los espacios se dividen en varias categorías como "Aulas", "Oficinas", "Ambientes Deportivos". Cada uno está representado con intuitivos íconos, facilitando la navegación para los usuarios.

Visualización de Espacios y Equipamiento: Los espacios y equipos están organizados en tarjetas por filas, con la información necesaria para el usuario como el nombre, la imagen del espacio o equipo, y un botón de "Reservar" o "Solicitar" para hacer una reserva o solicitud de uso de recursos.

### 3.1.3. Landing Page UI Design

#### 3.1.3.1. Landing Page Wireframe

#### 3.1.3.2. Landing Page Mock-up

### 3.1.4. Mobile Applications UX/UI Design

Esta sección comprende apartados internos donde se expondrá y detallará la propuesta de diseño visual e interactivo para las aplicaciones que componen la experiencia del usuario con los productos digitales.

#### 3.1.4.1. Mobile Applications Wireframes

Seguidamente, se presentan los wireframes diseñados para nuestras aplicaciones, los cuales permiten estructurar la interfaz y el flujo de navegación previo al inicio del desarrollo.

##### Login and sign up wireframes

Vista para registro e inicio de sesión en la aplicación móvil.

![Login Wireframes](/assets/chapter3/mobile-applications-wireframes/login-wireframes.png)

##### Menu wireframes

Vista de la pestaña de menu de la aplicación móvil.

![Menu Wireframes](/assets/chapter3/mobile-applications-wireframes/menu-wireframe.png)


##### Classroom wireframes

Vista de la asignacion de aulas en la aplicación móvil.

![Classroom Wireframes](/assets/chapter3/mobile-applications-wireframes/classrooms-wireframes.png)


##### Shared Spaces wireframes

Vista de la reserva de los espacios compartidos en la aplicación móvil.

![Shared Spaces Wireframes](/assets/chapter3/mobile-applications-wireframes/shared-spaces-wireframes.png)

##### Meetings wireframes

Vista de la creación de reuniones en la aplicación móvil.

![Meetings Wireframes](/assets/chapter3/mobile-applications-wireframes/meetings-wireframes.png)

##### Teacher management wireframes

Vista de la gestión de profesores en la aplicación móvil.

![Teacher management wireframes](/assets/chapter3/mobile-applications-wireframes/teacher-management-wireframes.png)

#### 3.1.4.2. Mobile Applications Wireflow Diagrams

A continuación, se presentan los diagramas de flujo que representan las rutas de navegación de los usuarios según sus objetivos (User Goals).


- User goal: Como profesor, quiero iniciar sesión en la aplicación, para acceder a las funcionalidades específicas para docentes.


![login user flow](/assets/chapter3/mobile-applications-wireflow-diagrams/login-wireflows.png)

El usuario ingresa a la aplicación usando sus credenciales (email y contraseña).


- User goal: Como administrador, quiero registrarme en la aplicación mobile, para hacer uso de las características disponibles.


![register user flow](/assets/chapter3/mobile-applications-wireflow-diagrams/register-wireflows.png)

El adminnistrador se registra a la aplicación completando un formulario con sus datos.


- User goal: Como administrador, quiero registrar las información de acceso del docente, para que puedan iniciar sesión en la plataforma mobile.


![teacher management user flow](/assets/chapter3/mobile-applications-wireflow-diagrams/teacher-management-wireflows.png)

El administrador registra la información de los docentes para que inicien sesión.


- User goal: Como administrador, quiero registrar los espacios compartidos, para que puedan ser gestionados en la plataforma mobile.


![shared spaces user flow](/assets/chapter3/mobile-applications-wireflow-diagrams/shared-space-wireflow.png)

El administrador registra espacios compartidos para que puedan ser gestionados.

- User goal: Como administrador, quiero registrar la hora y lugar de la reunión, para asegurar que todos los participantes tengan la información correcta sobre la reunión.

![meetings user flow](/assets/chapter3/mobile-applications-wireflow-diagrams/meetings-wireflows.png)

El administrador registra reuniones con fecha y hora para que los paritcipantes estén informados.


- User goal: Como administrador, quiero asignar aulas a los docentes, para que puedan gestionar sus clases de manera eficiente.

![classrooms user flow](/assets/chapter3/mobile-applications-wireflow-diagrams/classroom-wireflows.png)

El administrador asigna aulas a los docentes para que gestionen sus clases.


#### 3.1.4.3. Mobile Applications Mock-ups

Los mockups constituyen una fase fundamental en el proceso de diseño de las aplicaciones, proporcionando una visualización anticipada de la estética y disposición de los elementos previo al inicio del desarrollo. A continuación, se presenta el enlace a los mockups desarrollados en Figma

link: https://tinyurl.com/2nrus2z8

##### Login and sign up mock-ups

Vista para registro e inicio de sesión en la aplicación móvil.

![Login mock-ups](/assets/chapter3/mobile-applications-mock-ups/login-mock-ups.png)

##### Menu mock-ups

Vista de la pestaña de menu de la aplicación móvil.

![Menu mock-ups](/assets/chapter3/mobile-applications-mock-ups/menu-mock-ups.png)


##### Classroom mock-ups

Vista de la asignacion de aulas en la aplicación móvil.

![Classroom mock-ups](/assets/chapter3/mobile-applications-mock-ups/classrooms-mock-ups.png)


##### Shared Spaces mock-ups

Vista de la reserva de los espacios compartidos en la aplicación móvil.

![Shared Spaces mock-ups](/assets/chapter3/mobile-applications-mock-ups/shared-spaces-mock-ups.png)

##### Meetings mock-ups

Vista de la creación de reuniones en la aplicación móvil.

![Meetings mock-ups](/assets/chapter3/mobile-applications-mock-ups/meetings-mock-ups.png)

##### Teacher management mock-ups

Vista de la gestión de profesores en la aplicación móvil.

![Teacher management mock-ups](/assets/chapter3/mobile-applications-mock-ups/teacher-management-mock-ups.png)

#### 3.1.4.4. Mobile Applications User Flow Diagrams

Seguidamente, se presentan los diagramas de flujo que representan las rutas de navegación de los usuarios según sus objetivos (User Goals).

- User goal: Como profesor, quiero iniciar sesión en la aplicación, para acceder a las funcionalidades específicas para docentes.


![login user flow](/assets/chapter3/mobile-applications-user-flow/login-user-flow.png)

El usuario ingresa a la aplicación usando sus credenciales (email y contraseña).


- User goal: Como administrador, quiero registrarme en la aplicación mobile, para hacer uso de las características disponibles.


![register user flow](/assets/chapter3/mobile-applications-user-flow/register-user-flow.png)

El adminnistrador se registra a la aplicación completando un formulario con sus datos.


- User goal: Como administrador, quiero registrar las información de acceso del docente, para que puedan iniciar sesión en la plataforma mobile.


![teacher management user flow](/assets/chapter3/mobile-applications-user-flow/teacher-management-user-flow.png)

El administrador registra la información de los docentes para que inicien sesión.


- User goal: Como administrador, quiero registrar los espacios compartidos, para que puedan ser gestionados en la plataforma mobile.


![shared spaces user flow](/assets/chapter3/mobile-applications-user-flow/shared-spaces-user-flow.png)

El administrador registra espacios compartidos para que puedan ser gestionados.

- User goal: Como administrador, quiero registrar la hora y lugar de la reunión, para asegurar que todos los participantes tengan la información correcta sobre la reunión.

![meetings user flow](/assets/chapter3/mobile-applications-user-flow/meetings-user-flow.png)

El administrador registra reuniones con fecha y hora para que los paritcipantes estén informados.


- User goal: Como administrador, quiero asignar aulas a los docentes, para que puedan gestionar sus clases de manera eficiente.

![classrooms user flow](/assets/chapter3/mobile-applications-user-flow/classrooms-user-flow.png)

El administrador asigna aulas a los docentes para que gestionen sus clases.

#### 3.1.4.5. Mobile Applications Prototyping
