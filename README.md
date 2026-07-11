# MI-TIENDA-VIRTUAL-CON-GEMMINE-
CREACION DE UNA TIENDA VIRTUAL CON LA IA 

Parte 1: Introducción Teórica e Histórica del Desarrollo Web

1.1 ¿Qué es la Programación Web, el Diseño Web y el Maquetado Web?

Programación Web: Es la creación dinámica y funcional de aplicaciones que se ejecutan en servidores o en el propio navegador del usuario. Abarca la lógica de negocio, la manipulación de datos y la interactividad en tiempo real.
Diseño Web: Comprende la planeación visual, la conceptualización estética y la experiencia de usuario (UX/UI). Se enfoca en la psicología del color, la tipografía y la disposición visual óptima para retener al visitante.
Maquetado Web: Es el puente entre el diseño y la programación. Consiste en traducir un boceto gráfico o prototipo visual a código estructurado, organizando el esqueleto lógico para que los navegadores entiendan la distribución del contenido.

1.2 Evolución Cronológica de las Tecnologías Fundamentales
El desarrollo web actual es el resultado de una evolución tecnológica estructurada a lo largo de las últimas décadas. Para comprender el funcionamiento de nuestra aplicación, es necesario analizar el surgimiento histórico de cada componente básico en el orden cronológico en que transformaron la industria digital:

HTML (HyperText Markup Language) – 1991: Creado por el científico Tim Berners-Lee en el CERN. Es el lenguaje de marcado estándar diseñado exclusivamente para definir la estructura, los bloques de información y el esqueleto base de cualquier documento en la World Wide Web. Sin HTML, la información carecería de un orden lógico interpretable por los navegadores y motores de búsqueda.
JavaScript (JS) – 1995: Desarrollado originalmente por Brendan Eich bajo el nombre clave de *Mocha* y posteriormente lanzado con Netscape. Nació con el objetivo de convertirse en el único lenguaje de programación nativo interpretado directamente por los navegadores web. Su llegada rompió con las páginas estáticas, permitiendo manipular el entorno visual (DOM), validar formularios e introducir dinamismo directo sin recargar el sitio.

CSS (Cascading Style Sheets) – 1996: Propuesto inicialmente por Håkon Wium Lie y estandarizado rápidamente por el consorcio W3C. Su aparición histórica respondió a la necesidad crítica de separar la estructura del contenido (HTML) de la capa de presentación visual. CSS introdujo el control absoluto sobre la estética de las páginas: desde la paleta de colores y la tipografía, hasta el espaciado y el diseño adaptativo posterior.

Bootstrap – 2011: Diseñado originalmente por Mark Otto y Jacob Thornton dentro de las oficinas de Twitter como una herramienta interna de estandarización, y posteriormente liberado como código abierto. Se consolidó como el framework de CSS más popular del mundo al introducir un sistema de rejilla inteligente (Grid) basado en clases predefinidas. Su propósito histórico fue masificar el enfoque de diseño adaptativo y dar prioridad absoluta a los dispositivos móviles (Mobile-First).

Font Awesome – 2012: Creado por Dave Gandy como una biblioteca especializada de iconos y vectores tipográficos escalables. Su relevancia histórica radica en que estandarizó el uso de simbología visual moderna de forma limpia y ligera, permitiendo a los desarrolladores incluir iconos vectoriales de alta resolución mediante clases de texto simple, evitando la necesidad de sobrecargar las aplicaciones cargando pesados archivos de imágenes individuales.

1.3 Aplicación Metódica en el Proyecto MenaShop
1.  Estructuración (HTML): Genera las zonas semánticas esenciales: el encabezado de navegación (Navbar), el contenedor dinámico principal (Main Grid) para las prendas, la sección lateral desvanecible (Offcanvas) para el carrito, y el pie de página del documento (Footer).
   
3.  Estilización Personalizada (CSS): Define variables de identidad corporativa (colores azul oscuro y primarios), animaciones fluidas (keyframes) en el logotipo, y efectos de transformación al posar el cursor sobre los artículos de moda.
4.  Consumo de Librerías Estilizadas (Bootstrap y Font Awesome): Otorga una estética profesional instantánea mediante tarjetas de visualización uniforme, ventanas modales interactivas para detalles del producto y pasarelas de pago, junto con simbología intuitiva para cada red social de contacto.
   
6.  Lógica Operativa (JavaScript): Es el motor del ecosistema. Ejecuta una petición asíncrona mediante la interfaz Fetch a la URL de FakeStoreAPI, filtra las colecciones de ropa y joyería, gestiona las variables de memoria interna (LocalStorage) para preservar los artículos elegidos por el usuario, y procesa la biblioteca externa *jsPDF* para generar tickets de compra formateados tipo punto de venta (POS).

directorio raíz.

