# -Temario-de-Aplicaciones-Web
Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web  
#1.-Introducción al desarrollo web  
--Historia y evolución del desarrollo web--
La historia del desarrollo web comienza en la década de 1990, cuando Tim Berners-Lee inventó la World Wide Web. Al principio, las páginas web eran simples documentos de texto en HTML, con enlaces para navegar entre ellas 
En los años 2000, llegaron nuevas tecnologías como AJAX, que posibilitó la creación de aplicaciones web interactivas, y surgieron los primeros gestores de contenido y frameworks como PHP y ASP.NET. Más adelante, el desarrollo web se consolidó con la aparición de HTML5, CSS3 y frameworks modernos como React, Angular y Vue.js, que ofrecen experiencias nuevas  
--Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)--
Estáticas:  
Son páginas web que muestran información fija y no permiten interacción más allá de la navegación. Suelen estar hechas solo con HTML y CSS  
Dinámicas:  
Permiten interacción con el usuario y muestran contenido que cambia en función de las acciones del usuario o de datos almacenados en servidores. Utilizan tecnologías como JavaScript, bases de datos y lenguajes de servidor  
PWA (Aplicaciones web progresivas):  
Son aplicaciones web que ofrecen una experiencia similar a las aplicaciones móviles, funcionando offline y permitiendo instalación en dispositivos  
SPA ( Aplicacion de pagina unica):
Es un tipo de aplicación que carga una sola página HTML y actualiza dinámicamente el contenido conforme el usuario interactúa, sin necesidad de recargar la página completa desde el servidor 
<img width="298" height="172" alt="image" src="https://github.com/user-attachments/assets/3300c7ca-eac9-481e-8e89-a69883d6f5fb" />
#2.Arquitectura de aplicaciones web
Cliente-Servidor  
La relación cliente-servidor en la arquitectura web es un modelo donde dos entidades principales interactúan  
Cliente: Es el dispositivo o software que realiza solicitudes de información o servicios. Normalmente, el cliente es un navegador web, una aplicación móvil, o cualquier otro programa que consume servicios web.  
Servidor: Es el sistema que recibe las solicitudes del cliente, procesa esas solicitudes, accede a datos si es necesario, y envía de vuelta una respuesta con la información o el servicio requerido.  
--Arquitectura de tres capas (presentación, lógica, datos)--
La arquitectura en 3 capas del desarrollo web es un modelo de organización para aplicaciones que separa el sistema en tres partes principales  
Capa de Presentación:
Es la encargada de interactuar con el usuario. Incluye la interfaz gráfica, páginas web, formularios, etc. Su función es mostrar la información y recibir entradas del usuario.
Capa de Lógica (o Negocio):
Aquí se procesan las reglas de negocio y la lógica de la aplicación. Recibe solicitudes de la capa de presentación, las procesa (por ejemplo, validaciones, cálculos, decisiones) y gestiona qué datos se deben mostrar o modificar.
Capa de Datos:
Se encarga de almacenar, recuperar y gestionar los datos. Normalmente, incluye bases de datos u otros sistemas de almacenamiento. La lógica de negocio se comunica con esta capa para guardar o consultar información.
--REST y API-first design--  
REST (Representational State Transfer) es un estilo de arquitectura para el diseño de servicios web. Utiliza los métodos estándar de HTTP (GET, POST, PUT, DELETE) para operar sobre recursos representados normalmente en formato JSON o XML  
API-first design (diseño API primero) es una aproximación en la que el desarrollo parte de la definición de la API antes que cualquier implementación. Esto significa que primero se crea una especificación clara y detallada de cómo interactuarán otros sistemas o clientes con tu aplicación (generalmente usando OpenAPI/Swagger), y después se desarrolla el backend y frontend basado en esa especificación.  
#3. -Lenguajes y tecnologías fundamentales
--HTML, CSS, JavaScript, PHP, MySQL--  
HTML (HyperText Markup Language):
Es el lenguaje principal para crear páginas web. Permite estructurar el contenido mediante etiquetas, definiendo elementos como títulos, párrafos, imágenes y enlaces.  
CSS (Cascading Style Sheets):
Se utiliza para diseñar y dar formato a las páginas web creadas con HTML. Permite controlar colores, fuentes, márgenes, posiciones y adaptabilidad de los elementos visuales.  
JavaScript:
Es un lenguaje de programación que añade interactividad y dinamismo a las páginas web. Permite validar formularios, crear animaciones y manejar eventos del usuario directamente en el navegador. 
PHP (Hypertext Preprocessor):
Lenguaje de programación del lado del servidor, usado para crear páginas web dinámicas. Permite procesar información, gestionar bases de datos y generar contenido personalizado en tiempo real.  
MySQL:
Sistema de gestión de bases de datos relacional. Se usa para almacenar, organizar y recuperar información de manera eficiente, generalmente en conjunto con PHP para aplicaciones web dinámicas.  
<img width="268" height="176" alt="image" src="https://github.com/user-attachments/assets/b86a6373-7dbb-4da2-a597-c18406a6f894" />
#4.-Control de versiones
--Git y GitHub--
Git es un sistema de control de versiones distribuido que permite gestionar y registrar los cambios realizados en archivos y proyectos de programación, facilitando el trabajo colaborativo y el seguimiento de la evolución del código  
GitHub es una plataforma web que utiliza Git como sistema de control de versiones y proporciona herramientas para alojar repositorios, colaborar en proyectos, revisar cambios, gestionar incidencias y contribuir con otros usuarios de manera sencilla y segura en la nube  
--Flujo de trabajo con ramas (branching, merge, pull requests)--
El flujo de trabajo con ramas en GitHub se centra en tres conceptos principales: branching (ramas), merge (fusión) y pull requests (solicitudes de extracción). Aquí tienes una explicación clara de cada paso:  
1. Branching (ramas)  
Una rama es una copia aislada del código donde puedes trabajar en nuevas características, arreglos de errores o experimentos sin afectar la rama principal (usualmente llamada main o master).  
Ejemplo: Si quieres añadir una nueva funcionalidad, primero creas una rama llamada, por ejemplo, nueva-funcionalidad a partir de main.  
2. Trabajar en la rama  
Realiza cambios en los archivos, haz commits con mensajes descriptivos y prueba tus modificaciones en la rama creada.  
Esto mantiene tu trabajo separado y seguro, permitiendo colaboración sin conflictos con el código principal.  
3. Pull Requests (solicitudes de extracción)  
Cuando tu trabajo en la rama está listo, creas un pull request para solicitar que tus cambios se integren en la rama principal.  
Otros miembros del equipo pueden revisar, comentar y sugerir cambios antes de aprobar la integración.  
4. Merge (fusión)  
Una vez aprobado el pull request, se realiza el merge. Esto fusiona los cambios de tu rama con la rama principal.  
GitHub se encarga de unir ambos códigos; si hay conflictos, deberás resolverlos antes de completar el merge.
Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
#1.-Diseño e implementación del frontend
--Maquetación/Wireframe/Mockup--
Maquetación: La maquetación es el proceso de organizar y estructurar los elementos visuales de una página web (como textos, imágenes, botones, menús, etc.) para definir cómo se presentarán al usuario. Se realiza normalmente utilizando HTML y CSS, y su objetivo principal es lograr una interfaz clara, atractiva y funcional.  
Wireframe: Un wireframe es un boceto básico, generalmente en blanco y negro, que muestra la estructura y disposición de los elementos principales de una página web o aplicación. No incluye detalles de diseño (colores, imágenes, tipografías), sino que sirve como guía para visualizar la jerarquía de la información y la navegación.  
Mockup: Un mockup es una versión más detallada y realista del diseño de una página web o aplicación. Incluye colores, imágenes, tipografías y otros elementos visuales que representan cómo se verá el producto final. Es útil para presentar el aspecto visual a clientes o equipos antes de empezar la programación.
--API--
Una API  es un conjunto de reglas y definiciones que permiten que diferentes programas o sistemas se comuniquen entre sí. En otras palabras, una API es como un puente que facilita el intercambio de información y funcionalidades entre diferentes aplicaciones, servicios o plataformas.
#2.-Diseño e implementación del backend
--Servidor--
Un servidor es un sistema informático que proporciona servicios, recursos o datos a otros equipos, llamados clientes, a través de una red. Los servidores pueden ser dedicados a funciones específicas, como almacenar archivos, alojar páginas web, gestionar bases de datos o controlar el acceso a aplicaciones. Su característica principal es estar siempre disponibles para responder a las peticiones de los clientes y facilitar la comunicación y el intercambio de información entre diferentes dispositivos en una red.
--Manejo de peticiones y respuestas HTTP--
El manejo de peticiones y respuestas HTTP es el proceso mediante el cual una aplicación web recibe solicitudes (peticiones) desde un cliente (por ejemplo, un navegador) y responde con la información solicitada (respuestas). HTTP (HyperText Transfer Protocol) es el protocolo que define cómo se comunican los clientes y los servidores en la web.
--Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)--
La conexión a bases de datos permite que una aplicación interactúe con la información almacenada en sistemas como MySQL, PostgreSQL y MongoDB
#3.-Bases de datos
-- Modelado de datos y relaciones--
El modelado de datos y relaciones es una técnica utilizada para representar la estructura lógica de los datos en un sistema, así como las conexiones entre diferentes conjuntos de datos. Es fundamental en el diseño de bases de datos y sistemas de información, ya que ayuda a organizar cómo se almacenan, gestionan y relacionan los datos.  
Modelado de datos: Consiste en definir qué información se va a almacenar (por ejemplo, usuarios, productos, pedidos) y cómo se organiza en entidades o tablas. Cada entidad incluye atributos (campos) que describen sus características.  
Relaciones: Son las conexiones entre diferentes entidades. Por ejemplo, una relación puede indicar que un usuario puede realizar varios pedidos, o que un producto pertenece a una categoría.
--ORM (Object Relational Mapping)--
ORM (Object Relational Mapping) es una técnica de programación que permite interactuar con bases de datos relacionales utilizando objetos en el código, en lugar de escribir consultas SQL directamente. El ORM traduce automáticamente las operaciones realizadas sobre los objetos (como crear, leer, actualizar o borrar) en instrucciones SQL que manipulan las tablas de la base de datos.
--CRUD desde el backend--
El CRUD desde el backend se refiere a las operaciones básicas que una aplicación realiza sobre los datos en una base de datos o almacenamiento, gestionadas por el servidor (backend). CRUD son las siglas de:  
Create: Añadir nuevos datos o registros.  
Read: Consultar o recuperar datos existentes.  
Update: Modificar datos existentes.  
Delete: Borrar datos.
#4.-Seguridad básica en aplicaciones web
--Validación de formularios--
La validación de formularios en el desarrollo web es el proceso mediante el cual se comprueba que los datos introducidos por el usuario cumplen ciertos criterios antes de que sean enviados al servidor. Su objetivo principal es garantizar que la información recibida es completa, correcta y segura.
--Autenticación y autorización --
La autenticación es el proceso mediante el cual un sistema verifica la identidad de un usuario. Su objetivo es asegurarse de que quien intenta acceder realmente es quien dice ser.  
La autorización ocurre después de la autenticación y determina qué acciones puede realizar o qué recursos puede ver el usuario autenticado. Es decir, una vez que el sistema sabe quién eres, decide qué permisos tienes dentro de la aplicación.
Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
#1. -Integración de frontend y backend
--Interfaz de usuario Frontend--
La interfaz de usuario frontend es la parte de una aplicación o sitio web con la que interactúa directamente el usuario. Es todo lo que ves en la pantalla: botones, menús, formularios, textos, imágenes y efectos visuales. El frontend se encarga de mostrar la información y de recibir las acciones del usuario, como hacer clic, escribir en campos, o desplazarse por la página.
--Manejo de API--
El manejo de API (Interfaz de Programación de Aplicaciones) se refiere al proceso de interactuar, consumir y gestionar servicios externos a través de interfaces definidas. Una API permite que diferentes aplicaciones se comuniquen entre sí intercambiando datos y funcionalidades.
--Proceso de Solicitud y Respuesta de Backend--
El proceso de solicitud y respuesta de backend es el mecanismo mediante el cual el frontend (interfaz de usuario) se comunica con el servidor (backend) para obtener o enviar información. Este proceso sigue generalmente estos pasos:  
Solicitud: El usuario realiza una acción en la interfaz (por ejemplo, presiona un botón para ver datos). El frontend prepara una solicitud (generalmente HTTP) y la envía al backend, especificando qué información necesita o qué acción desea realizar.

Procesamiento en Backend: El servidor recibe la solicitud, la interpreta y ejecuta la lógica necesaria (consultar una base de datos, procesar datos, validar información, etc.).

Respuesta: Una vez procesada la solicitud, el backend prepara una respuesta (normalmente en formato JSON o XML) y la envía de vuelta al frontend.  
Visualización en Frontend: El frontend recibe la respuesta y la muestra al usuario, actualizando la interfaz según los datos recibidos.  
#2.- Almacenamiento en Servidor
--Tipos de servidores--
Algunos de los tipos de servidores son:  
Servidor web: Aloja sitios web y sirve contenido web (HTML, CSS, JavaScript) a los navegadores de los usuarios a través de HTTP o HTTPS. 
Servidor de archivos: Permite almacenar, administrar y compartir archivos entre varios usuarios o dispositivos en una red.  
Servidor de bases de datos: Gestiona bases de datos y responde a las solicitudes de aplicaciones que necesitan almacenar, recuperar o modificar datos.  
Servidor de correo: Envía, recibe y almacena correos electrónicos. Utiliza protocolos como SMTP, POP3 o IMAP.  
Servidor de aplicaciones: Ejecuta aplicaciones específicas y gestiona la lógica de negocio entre el usuario y la base de datos.  
--Servidores y servicios de hosting--
Los servidores de hosting son computadoras especializadas que almacenan y gestionan los archivos, bases de datos y aplicaciones de sitios web, permitiendo que estos sean accesibles desde cualquier parte del mundo a través de Internet.  
--Proveedores de Servicios de Almacenamiento--
Los Proveedores de Servicios de Almacenamiento son empresas o plataformas que ofrecen espacios y herramientas para guardar, gestionar y acceder a datos o archivos de manera remota, generalmente a través de Internet. Estos servicios permiten almacenar información en la nube, lo que facilita el acceso desde cualquier dispositivo conectado y mejora la seguridad, el respaldo y la colaboración.  
<img width="294" height="170" alt="image" src="https://github.com/user-attachments/assets/64419c71-8bed-4248-affb-297080353936" />
#3.-Optimización y rendimiento
--Optimización de recursos (imágenes, scripts)--
La optimización de recursos, como imágenes y scripts, en desarrollo web se refiere a técnicas y buenas prácticas para reducir el peso y mejorar el rendimiento de estos archivos en una página web. Esto ayuda a que las páginas carguen más rápido y consuman menos ancho de banda.  
--Despliegue de aplicaciones web--
El despliegue de aplicaciones web es el proceso de publicar una aplicación web para que esté disponible y accesible a través de Internet o una red interna. Esto implica mover el código y los archivos de la aplicación desde el entorno de desarrollo local al servidor de producción donde los usuarios pueden acceder a ella.  
--CI/CD básico--
CI/CD básico significa Integración Continua y Entrega/Despliegue Continuo. Es una práctica en desarrollo de software que automatiza los procesos de integración de código, pruebas y despliegue de aplicaciones.  
