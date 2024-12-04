---
marp: true
---
![PortadaPresentacion](portada.png)

# - *ÍNDICE* -

- ###  1. Idea de la aplicación.
    - ***-** Describir de manera clara y concisa la idea de la aplicación web y su propósito.*

- ### 2. Audiencia objetivo.
    - ***-** Definir el público para el que está destinada la aplicación, explicando su relevancia y cómo se beneficiarán de la aplicación.*

- ### 3. Análisis de mercado.
    - ***-**  Investigar y analizar aplicaciones similares en el mercado. Identificar características comunes y oportunidades de diferenciación para la nueva aplicación, destacando qué valor añadido ofrecerá.*

- ### 4. Funcionalidades clave.
    - ***-**  Identificar y listar las funcionalidades principales que ofrecerá la aplicación (ej: sistema de autenticación, gestión de usuarios, etc.).*

- ### 5. Modelos de ejecución. 
    - ***-** Investigar y comparar los modelos de ejecución en cliente y servidor, explicando sus diferencias y ejemplos de uso.*

- ### 6. Lenguajes de programación web.
    - ***-** Analizar los lenguajes de programación más utilizados para el desarrollo web en cliente, como JavaScript y TypeScript, explicando sus ventajas y desventajas.*

- ### 7. Tecnologías a utilizar.
    - ***-** Seleccionar las tecnologías (lenguajes de programación, frameworks, herramientas de desarrollo) que se utilizarán para el desarrollo de la aplicación. Justificar la elección en base a la investigación realizada. Asegurarse de incluir.*

- ### 8. Compatibilidad en navegadores.
    - ***-**  Realizar un estudio sobre cómo los diferentes navegadores manejan JavaScript y otros lenguajes utilizados en el desarrollo web, identificando problemas de compatibilidad y soluciones. Incluir un análisis sobre cómo la integración de lenguajes de marcas y lenguajes de programación afecta la compatibilidad y el rendimiento de la aplicación en diferentes navegadores.*

---
### 1. Idea de la aplicación.

- La aplicación consiste en una tienda online llamada Garakohandmade destinada a la venta de productos artesanales hechos por un familiar mío.
- La idea es permitir al público realizar pedidos de productos disponibles en la web y también ofrecer la opción de consultar si una idea personalizada es viable. Esta funcionalidad ampliará la creatividad y conexión entre el cliente y el artesano, proporcionando una experiencia única.

---
### 2. Audiencia objetivo.

- El público objetivo son personas interesadas en productos únicos y hechos a mano, que valoren la personalización y creatividad en regalos y decoraciones.
- Este tipo de cliente prefiere artículos artesanales y exclusivos, como decoraciones para el hogar, regalos especiales y recuerdos personalizados.

---
### 3. Análisis de mercado.

- Plataformas como Etsy o Amazon Handmade ofrecen productos artesanales, pero no brindan una opción directa para que los clientes sugieran ideas personalizadas.
- Esta aplicación se diferenciaría al integrar una herramienta para que los clientes puedan proponer ideas personalizadas, lo que ofrecerá un valor añadido de exclusividad y creatividad.

---
### 4. Funcionalidades clave.

1. **Catálogo de productos**: Sección donde los usuarios podrán explorar los productos disponibles, con detalles sobre precios y materiales.
2. **Sistema de autenticación**: Permite que los usuarios creen cuentas para acceder a funciones avanzadas.
3. **Consulta de ideas personalizadas**: Los clientes podrán enviar ideas, dibujos o descripciones para productos personalizados.
4. **Sistema de presupuesto y aprobación de ideas**: El artesano generará un presupuesto que el cliente deberá aprobar.
5. **Gestión de pedidos y seguimiento**: Los usuarios podrán consultar el estado de sus pedidos y recibir notificaciones.
6. **Pasarela de pago**: Integración con plataformas de pago seguras.
7. **Chat o contacto directo**: Herramienta de mensajería para consultas sobre productos.
8. **Lista de deseos**: Los usuarios podrán guardar productos para compras futuras.

---
### 5. Modelos de ejecución.


- **Cliente**: Inicia las solicitudes hacia el servidor, generalmente a través de un navegador web o aplicación. Su función principal es enviar peticiones y recibir respuestas.
- **Servidor**: Responde a las solicitudes del cliente y gestiona recursos como bases de datos, aplicaciones y archivos.

**Ejemplos de uso:**
- Navegar por una web (cliente web y servidor como Apache o Nginx).
- FTP, SSH, y juegos en línea, donde los clientes se conectan a servidores para interactuar.

**Diferencias clave entre cliente y servidor:**

| Aspecto            | Cliente                                   | Servidor                                |
|--------------------|-------------------------------------------|-----------------------------------------|
| Dependencia de red | Baja                                      | Alta                                    |
| Rendimiento local  | Requiere hardware potente                | Menos exigente para el cliente          |
| Seguridad          | Menos segura (procesamiento y datos locales) | Más segura (datos centralizados)        |
| Ejemplos           | Juegos locales, PWAs, editores de video  | SaaS, videojuegos en la nube, streaming |

---
### 6. Lenguajes de programación web.

- **HTML**: Sirve para estructurar contenido web, utilizado en todas las páginas.
  - **Ventajas**: Despliegue rápido, soportado por todos los navegadores, y archivos pequeños.
  - **Desventajas**: Diseño lento, estático, y etiquetas limitadas.

- **CSS**: Usado junto con HTML para definir la apariencia de la página.
  - **Ventajas**: Mantiene la estructura separada de la presentación, eficiente, flexible.
  - **Desventajas**: Curva de aprendizaje, compatibilidad entre navegadores, limitaciones de maquetación.

- **JavaScript**: Lenguaje dinámico que permite interactividad.
  - **Ventajas**: Interactividad en tiempo real, manipulación sencilla del DOM.
  - **Desventajas**: Compatibilidad entre navegadores, seguridad deficiente, rendimiento limitado en aplicaciones complejas.

- **TypeScript**: Superset de JavaScript con tipado estático.
  - **Ventajas**: Mejora la legibilidad y mantenimiento del código.
  - **Desventajas**: Requiere compilación, curva de aprendizaje.

---
### 7. Tecnologías a utilizar.

Las tecnologías elegidas para el desarrollo de la aplicación son:

- **Frontend**: HTML5, SCSS, JavaScript, Vue.js.
- **Backend**: Node.js.

### 8. Compatibilidad en navegadores.

Los navegadores modernos como Chrome, Firefox, Edge y Safari son compatibles con ECMAScript 6 (ES6) y versiones posteriores, mientras que Internet Explorer presenta problemas con características modernas como las *promesas* y las *funciones flecha*. Utilizar herramientas como **Babel** ayuda a asegurar la compatibilidad en navegadores más antiguos.

Al realizar pruebas de compatibilidad, se observa que los navegadores más modernos tienen una mayor compatibilidad con las API de JavaScript, mientras que navegadores antiguos como Internet Explorer o Opera pueden presentar más dificultades para ejecutar código moderno de manera eficiente.

### Bibliografía.

**Arquitectura Cliente-Servidor**
 - [Arsys](https://www.arsys.es/blog/todo-sobre-la-arquitectura-cliente-servidor#tree-1)
 - [InfraNetworking](https://blog.infranetworking.com/modelo-cliente-servidor/)
 - [Daemon4](https://www.daemon4.com/empresa/noticias/arquitectura-cliente-servidor/)

**Lenguajes mas usados y sus ventajas y desventajas**
 - [General](https://blog.hubspot.es/website/que-es-desarrollo-web#lenguajes)
 - [General](https://keepcoding.io/blog/lenguajes-desarrollo-web/#4_TypeScript)
 - [Ventajas HTML](https://economipedia.com/definiciones/lenguaje-html.html#:~:text=Ventajas%3A%20Permite%20describir%20hipertexto%2C%20tiene,y%20las%20etiquetas%20son%20limitadas.)
 - [Ventajas CSS](https://blog.hubspot.es/website/que-es-css#ventajas)
 - [Ventajas JavaScript](https://blog.hubspot.es/website/ventajas-y-desventajas-de-javascript#ventajas)
 - [Ventajas TypeScript](https://www.mytaskpanel.com/lenguaje-de-programacion-typescript/)

**Análisi de navegadoores**
- [Compatibilidad de navegadores con las API de JavaScript](https://developer.mozilla.org/es/docs/Mozilla/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs)
