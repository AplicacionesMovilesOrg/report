# Capítulo IV: Product Implementation & Validation

## 4. Product Implementation & Validation

### 4.1. Software Configuration Management

A continuación, presentaremos el proceso por el cual organizamos, gestionamos y controlamos los cambios en el desarrollo de este proyecto.

#### 4.1.1. Software Development Environment Configuration

Requirements Management

1. Trello: Es una herramienta utilizada para gestionar el flujo de trabajo de proyectos principalmente basados en marcos de
   trabajos ágiles. Será empleado para visualizar y actualizar el estado actual de las tareas e historias de usuario
   pertenecientes al sprint a desarrollar.  
   Ruta de referencia: https://trello.com/es

Product UX/UI Design

1. Figma: Plataforma de elaboración de prototipos y edición gráfica, principalmente utilizado para el diseño digital. En el
   caso del proyecto, será utilizado para el prototipado de la aplicación y sus versiones de Desktop y Mobile Web Browser.

   Ruta de referencia: https://www.figma.com/login

2. Lucidchart: Aplicación para diagramar flujos. Será empleado para el diseño de wireflows, user-flows y el diagrama de
   clases asociado a la aplicación.

   Ruta de referencia: https://www.lucidchart.com/

Software Development

1. WebStorm: Entorno de desarrollo integrado elegido por su soporte completo para tecnologías web como JavaScript, HTML, CSS. Ofrece refactorización avanzada, depuración, integración con Git y la posibilidad de agregar plugins. Es compatible con varios sistemas operativos, facilitando la colaboración en equipo.

   Ruta de referencia: https://www.jetbrains.com/webstorm/
   <br>

2. HTML5: HyperText Markup Language, o por sus siglas HTML, es un lenguaje de etiquetado para páginas web. Será
   empleado en el desarrollo del proyecto para la presentación del contenido en la aplicación.

   Ruta de referencia: https://www.w3schools.com/html/html5_syntax.asp  
   <br>

3. CSS: Cascading Style Sheets es un lenguaje que maneja el diseño y presentación de las páginas web, el cual va de la mano
   con HTML.

   Ruta de referencia: https://google.github.io/styleguide/htmlcssguide.html
   <br>
   <br>

4. JavaScript: Es un lenguaje de programación interpretado y orientado a objetos. Se utilizará para elaborar la interfaz de
   usuario dentro de la aplicación.

   Ruta de referencia: https://developer.mozilla.org/es/docs/Web/JavaScript

 <br>

5. Git: Una herramienta de control de versiones que facilita el registro y la gestión de las distintas versiones del programa. Su propósito es mantener un historial de cambios y simplificar la corrección de errores. Los integrantes del equipo
   accederán a través de la línea de comandos en sus sistemas locales.

Ruta de referencia: https://git-scm.com/
<br>
<br>
Software Documentation and Project Management 6. Github: Una plataforma en la nube que hospedará los repositorios de código del proyecto. Permitirá la colaboración en
tiempo real y la revisión de contribuciones de cada miembro del equipo. Los integrantes del equipo podrán acceder a través de sus navegadores web.

Ruta de referencia: https://github.com/

<br>

Software Deployment

1. Github Pages: GitHub Pages es un servicio de alojamiento web que permite a los usuarios crear y publicar sitios web estáticos directamente desde sus repositorios de GitHub. Es especialmente útil para proyectos personales, portafolios, documentación de proyectos o blogs.

Ruta de referencia: https://pages.github.com/

#### 4.1.2. Source Code Management

El proyecto seguirá las convenciones del flujo de trabajo establecido por el modelo GitFlow para el control de versiones, empleando GitHub como plataforma y sistema de control de versiones. A continuación, se describirá la implementación de GitFlow como un flujo de trabajo para el control de versiones.

Repositorio de GitHub:

- Enlace para acceder a la organización en GitHub: https://github.com/AplicacionesMovilesOrg
- Enlace para acceder al repositorio de la landing Page: https://github.com/AplicacionesMovilesOrg/landing-page
- Enlace para acceder al repositorio del reporte: https://github.com/AplicacionesMovilesOrg/report
- Enlace para acceder al repositorio del back end:

Flujo de trabajo GitFlow

El flujo de trabajo a ser implementado para el desarrollo del proyecto se basará en el modelo propuesto por Vincent Driessen en "A successful Git branching model".

Estructura de branches (Ramas):

1. Main branch (Rama principal): Esta rama servirá como la principal para la aplicación, alojando versiones estables y finales del desarrollo. Únicamente se aceptarán cambios que hayan sido previamente probados y verificados en los features y de ahí en Developer.
2. Develop branch (Rama de desarrollo): El propósito de esta rama es facilitar los avances del proyecto en equipo y mantener los archivos centrales del desarrollo continuo.
3. Feature branch(Ramas de funcionalidad): Cada capitulo desarrollado por el equipo, o separada del enfoque actual del desarrollo, tendrá su propia rama. Una vez que una funcionalidad esté completamente trabajada, se fusionará con la rama de desarrollo del proyecto. Las convenciones para nombrar las ramas de funcionalidad seguirán un patrón descriptivo y único, por ejemplo, "feature/chapter-#".

#### 4.1.3. Source Code Style Guide & Conventions

#### HTML

Algunas de las prácticas que deben seguirse para alcanzar un código coherente, sostenible y ordenado son las siguientes:

1. Cerrar todos los elementos HTML: Por ejemplo, `<p>Esto es un párrafo.</p>`.
2. Siempre declarar el tipo de documento en la primera línea del documento, para HTML es `<!DOCTYPE html>`.
3. Escribir en una línea los comentarios cortos.
4. Utilizar comillas en caso de que los atributos contengan espacios entre sí.
5. Procurar especificar el texto `alt` y las dimensiones `width` y `height` de las imágenes, ya que de esta manera se facilitará la disponibilidad del contenido. Por ejemplo:
6. Se nos recomienda no usar el espacio al momento de utilizar los signos porque es más fácil de leerlo de esta forma.

Referencia: [HTML5 Syntax](https://www.w3schools.com/html/html5_syntax.asp)

#### CSS

Entre las prácticas empleadas se menciona:

1. Se nos recomienda tener una sangría por 2 espacios a la vez, no debemos utilizar tabulaciones ni mezclarlas tabulaciones con espacios para la sangría.
2. Todo el código debe estar en minúscula.
3. Eliminar los espacios en blanco.
4. Usar comentarios para explicar el código.
5. Utilizar nombres de clase significativos o genéricos, nombres que reflejen el propósito de su elemento.

Referencia: [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html)

#### JavaScript

Algunas de las mejores prácticas para programar incluyen:

1. Utilizar nombres de variables claros: Es importante que los nombres reflejen el propósito de la variable.
2. Ser consistente con las comillas: Elegir entre comillas simples o dobles y mantener esa elección a lo largo del código.
3. Incluir comentarios explicativos: Usar comentarios para aclarar bloques de código, especialmente en secciones complejas, facilita la comprensión.
4. Minimizar el uso de variables globales: Limitar el ámbito de las variables para evitar conflictos y mejorar la mantenibilidad del código.
5. Encapsular lógica en funciones: Mantener el código modular y reutilizable mediante el uso de funciones.
6. Seguir un estilo de codificación uniforme: Mantener un formato consistente mejora la legibilidad del código.

Referencia: [JavaScript Best Practices](https://www.w3schools.com/js/DEFAULT.asp)

#### C# (Domain-Driven Design)

Para asegurar que el código en C# siga los principios de Domain-Driven Design (DDD), se recomiendan las siguientes prácticas:

1. Utilizar nombres de dominio significativos: Los nombres de las clases, métodos y variables deben reflejar el lenguaje del dominio.
2. Mantener la lógica de negocio en el dominio: La lógica de negocio debe residir en el modelo de dominio y no en la infraestructura o en la interfaz de usuario.
3. Usar agregados para gestionar la consistencia: Los agregados son entidades que se agrupan para garantizar la consistencia de los cambios en el modelo.
4. Implementar repositorios para el acceso a datos: Los repositorios son responsables de la persistencia y recuperación de los agregados.
5. Aplicar patrones de diseño adecuados: Utilizar patrones de diseño como CQRS, Event Sourcing y DDD para estructurar el código de manera efectiva.
   Referencia: [Domain-Driven Design](https://www.domainlanguage.com/ddd/reference/)

#### 4.1.4. Software Deployment Configuration

#### Landing Page Deployment

La landing page del proyecto se ha desplegado utilizando GitHub Pages, lo que permite alojar el sitio web de manera gratuita y sencilla directamente desde el repositorio de GitHub:

![Captura de pantalla 1](../assets/chapter4/landing-page-deployment/landing-page-deployment-1.png)
![Captura de pantalla 2](../assets/chapter4/landing-page-deployment/landing-page-deployment-2.png)
![Captura de pantalla 3](../assets/chapter4/landing-page-deployment/landing-page-deployment-3.png)
![Captura de pantalla 4](../assets/chapter4/landing-page-deployment/landing-page-deployment-4.png)

Link de la lading page desplegada: https://aplicacionesmovilesorg.github.io/landing-page/

### 4.2. Landing Page & Mobile Application Implementation

#### 4.2.1. Sprint 1

##### 4.2.1.1. Sprint Planning 1

Para este primer sprint nos enfocaremos en los tasks para la
elaboración del producto. Nos dividiremos entre nosotros cada
una de las tareas identificadas para el sprint.

| Sprint #                        | Sprint 1                                                                                                                                                                                                                                                                                                     |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Sprint Planning Background      |                                                                                                                                                                                                                                                                                                              |
| Date                            | 01/10/2025                                                                                                                                                                                                                                                                                                   |
| Time                            | 06:00 PM                                                                                                                                                                                                                                                                                                     |
| Location                        | Servidor de Discord del Equipo                                                                                                                                                                                                                                                                               |
| Prepared By                     | Andres Torres                                                                                                                                                                                                                                                                                                |
| Attendees (to planning meeting) | Andres Torres / Dayro Rios / Vicente Quijandria / Renato Calvo / Antonio Navarro                                                                                                                                                                                                                             |
| Sprint 1 Review Summary         | En esta primera seccion se planteo el desarrollo para el proyecto, se hizo la creacion de la landing page, el diseño de la aplicación movil y del 70% del desarrollo de la API RESTful.                                                                                                                      |
| Sprint 1 Retrospective Summary  | En esta seccion todos los integrantes mencionaron tener aciertos en partes del codigo y en otras partes poder mejorar sus habilidades realizando la Landing Page, aplicacion movil y la API RESTful.                                                                                                         |
| Sprint Goal & User Stories      |                                                                                                                                                                                                                                                                                                              |
| Sprint 1 Goal                   | Desarrollar, desplegar y hacer visible la landing page, aplicacion movil y la API RESTful, integrando todos sus componentes clave y garantizando una apariencia coherente con los mockups de la aplicación. El éxito se logrará cuando la página esté completamente funcional y accesible para los usuarios. |
| Sprint 1 Velocity               | 42 Velocity                                                                                                                                                                                                                                                                                                  |
| Sum of Story Points             | 42 Story Points.                                                                                                                                                                                                                                                                                             |

##### 4.2.1.2. Sprint Backlog 1

| Orden                 | User Story / Technical Story Id | Título                                                                                      | Descripción                                                                                                                                                                                                                                                               | Story Points (1 / 2 / 3 / 5 / 8) | Estimation (hours) | Assigned To        | Status |
| :-------------------- | :------------------------------ | :------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------: | :----------------: | :----------------- | :----- |
| **User Stories**      |
| 1                     | US-01                           | Accesibilidad de la aplicación en diferentes dispositivos                                   | Como visitante, quiero que la aplicación se adapte a diferentes dispositivos para que pueda acceder a la plataforma desde cualquier lugar y en cualquier momento.                                                                                                         |                5                 |         1          | Vicente Quijandria | Done   |
| 2                     | US-02                           | Encontrar información del propósito de la aplicación                                        | Como visitante, quiero saber sobre el propósito de la aplicación para entender qué beneficios y funcionalidades ofrece y decidir si es adecuada para mis necesidades.                                                                                                     |                2                 |         3          | Vicente Quijandria | Done   |
| 3                     | US-03                           | Visualización de imágenes y gráficos relevantes                                             | Como visitante, quiero que las imágenes y gráficos en la landing page sean de alta calidad y relevantes para captar mi interés.                                                                                                                                           |                2                 |         3          | Vicente Quijandria | Done   |
| 4                     | US-04                           | Tipografía cómoda y agradable estéticamente                                                 | Como visitante, quiero que la tipografía en la landing page sea legible y estéticamente agradable para facilitar la lectura y la navegación.                                                                                                                              |                1                 |         2          | Vicente Quijandria | Done   |
| **Technical Stories** |
| 5                     | TS001                           | Añadir administrador a través de un RESTful API                                             | Como desarrollador, quiero que se pueda añadir a un administrador a través de un API, para que el administrador registre a los docentes.                                                                                                                                  |                2                 |         3          | Andres Torres      | Done   |
| 6                     | TS002                           | Añadir un docente a través de un RESTful API                                                | Como desarrollador, quiero que se pueda añadir a un docente a través de un API, para que este pueda interactuar con el administrador.                                                                                                                                     |                3                 |         4          | Andres Torres      | Done   |
| 7                     | TS005                           | Inicio de sesión a través de un RESTful API                                                 | Como desarrollador, quiero implementar la característica de inicio de sesión a través de una API RESTful, para que los usuarios puedan autenticarse y acceder a las funcionalidades del sistema de manera segura.                                                         |                5                 |         6          | Andres Torres      | Done   |
| 8                     | TS007                           | Añadir información de salones a través de un RESTful API                                    | Como desarrollador, quiero implementar la característica de añadir la información de los salones a través de un RESTful API PARA que los usuarios puedan interactuar con su información.                                                                                  |                3                 |         4          | Andres Torres      | Done   |
| 9                     | TS008                           | Añadir información de espacios compartidos través de un RESTful API                         | Como desarrollador, quiero implementar la característica de añadir la información de los espacios compartidos a través de un RESTful API PARA que los usuarios puedan interactuar con su información.                                                                     |                3                 |         4          | Andres Torres      | Done   |
| 10                    | TS010                           | Añadir información de los recursos de un salón a través de un RESTful API                   | Como desarrollador, quiero implementar la característica de añadir la información de los recursos de los salones a través de un RESTful API PARA que los docentes puedan puedan hacer reportes.                                                                           |                3                 |         4          | Andres Torres      | Done   |
| 11                    | TS011                           | Añadir información de hora y lugar de una reunión a través de un RESTful API                | Como desarrollador, quiero implementar la característica de añadir la información de hora y lugar de una reunión a través de un RESTful API PARA que los docentes puedan recibir notificaciones acerca de la reunión.                                                     |                5                 |         6          | Andres Torres      | Done   |
| 12                    | TS012                           | Añadir información de los invitados de una reunión a través de un RESTful API               | Como desarrollador, quiero implementar la característica de añadir la información de los invitados de una reunión a través de un RESTful API PARA que los administradores puedan seleccionar a los participantes de la reunión.                                           |                3                 |         4          | Andres Torres      | Done   |
| 13                    | TS013                           | Obtener notificación de reporte a través de un RESTful API                                  | Como desarrollador, quiero implementar la opción para obtener la notificación de un reporte a través de una API RESTful, PARA que los administradores puedan visualizar los reportes de los docentes.                                                                     |                2                 |         3          | Andres Torres      | Done   |
| 14                    | TS019                           | Actualizar información de la reunión a través de un RESTful API                             | Como desarrollador, quiero implementar la característica de actualizar la información de la reunión a través de un RESTful API PARA que los administradores puedan cambiar la información de la reunión ante cualquier eventualidad.                                      |                3                 |         4          | Andres Torres      | Done   |
| 15                    | TS022                           | Obtener información de la disponibilidad de espacios compartidos a través de un RESTful API | Como desarrollador, quiero implementar la opción para obtener la disponibilidad de espacios compartidos a través de una API RESTful, PARA que los docentes y administradores puedan visualizar si un espacio compartido se encuentra disponible en un momento específico. |                5                 |         6          | Andres Torres      | Done   |
| 16                    | TS023                           | Añadir reserva a un espacios compartido a través de un RESTful API                          | Como desarrollador, quiero implementar la opción para añadir una reserva a un espacio compartidos a través de una API RESTful, PARA que los docentes puedan reservar un espacio compartido que se encuentre disponible en un momento específico.                          |                5                 |         6          | Andres Torres      | Done   |
| 17                    | TS025                           | Añadir información del reporte de avería a través de un RESTful API                         | Como desarrollador, quiero implementar la característica de añadir la información de un reporte a través de un RESTful API PARA que los administradores puedan ver la información del reporte que hizo el docente.                                                        |                3                 |         4          | Andres Torres      | Done   |

##### 4.2.1.3. Development Evidence for Sprint Review

##### 4.2.1.4. Testing Suite Evidence for Sprint Review
A continuación, se presenta una tabla con información del repositorio de las pruebas, y los commits realizados durante el sprint:

| Repository                                                   | Branch | Commit Id                                      | Commit Message                                                      | Commit Message Body | Committed on (Date) |
|--------------------------------------------------------------|---------|------------------------------------------------|---------------------------------------------------------------------|----------------------|---------------------|
| AplicacionesMovilesOrg/AplicacionesMovilesOrg-acceptance-tests | main    | be4fae8973d3f7ee2571b64733e3e0d30cb86f91       | feat: add Gherkin scenarios for administrator login                 | -                    | 08/10/2025          |
| AplicacionesMovilesOrg/AplicacionesMovilesOrg-acceptance-tests | main    | 988b1f5fb8c3e486d3eaf3a59ce2d49437b0717c       | feat: add Gherkin scenarios for teacher personal information registration | -                    | 08/10/2025          |
| AplicacionesMovilesOrg/AplicacionesMovilesOrg-acceptance-tests | main    | 95151a86995fc6431a9e6f49f88dc299bcd74a36       | feat: add Gherkin scenarios for teacher access information registration | -                    | 08/10/2025          |

Enlace del github: [Github Repository](https://tinyurl.com/2dzts67c)

##### 4.2.1.5. Execution Evidence for Sprint Review

Evidencia de ejecución del Landing Page:

![Landing Page Deployed](../assets/chapter4/landing-page-deployment/landingPageMobile.png)
Enlace: [https://tinyurl.com/bdftnb7v](https://tinyurl.com/bdftnb7v)

Evidencia de Ejecución Web Services:

![Backend Deployed](../assets/chapter4/landing-page-deployment/backend.png)
Enlace:[https://tinyurl.com/5aadb5bm](https://tinyurl.com/5aadb5bm)

##### 4.2.1.6. Services Documentation Evidence for Sprint Review

##### 4.2.1.7. Software Deployment Evidence for Sprint Review

##### 4.2.1.8. Team Collaboration Insights during Sprint

### 4.3. Validation Interviews


En la sección **“Validation Interviews”** de nuestro proyecto, nos concentramos en **refinar la plataforma EduSpace**, la cual está orientada a **mejorar la gestión integral de los espacios educativos** en instituciones con **infraestructuras amplias y complejas**. Esta etapa esencial del desarrollo se centra en **realizar entrevistas estructuradas y conversaciones interactivas** con nuestros principales usuarios: **administradores, docentes y auxiliares**.
El propósito de estas entrevistas es **recoger sus percepciones, necesidades y recomendaciones**, garantizando que EduSpace **no solo cumpla con los requerimientos técnicos**, sino que también **se adapte a las dinámicas operativas y expectativas específicas** de cada tipo de usuario.

#### 4.3.1. Diseño de Entrevistas

En esta sección se establece por cada segmento objetivo los elementos a incluir en la sesión de validación, incluyendo el Landing Page y las aplicaciones. Además se especifica cuáles serán los user flows de las aplicaciones, que formarán parte del proceso de validación.

Segmento 1: Administradores de instituciones educativas

Objetivo de la validación: Comprobar si los usuarios entienden el valor de la plataforma para la gestion de la infraestructura educativa.

Elementos a incluir:

- Claridad del mensaje principal en la landing page

- Opiniones sobre testimonios y beneficios listados.

- Visualización de los beneficios sobre las herramientas ofrecidas

- Visualización de planes y precios de la plataforma

- Paneles de errores


Segmento 2: Docentes y auxiliares

Objetivo de la validación: Comprobar si los usuarios entienden el valor de la plataforma para la gestion de los espacios educativos.

Elementos a incluir:

- Claridad del mensaje principal en la landing page

- Opiniones sobre testimonios y beneficios listados.

- Visualización de los beneficios sobre las herramientas ofrecidas

- Visualización de planes y precios de la plataforma


#### 4.3.2. Registro de Entrevistas

#### 4.3.3. Evaluaciones según heurísticas
