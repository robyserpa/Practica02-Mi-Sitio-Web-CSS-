# Practica02-Mi-Sitio-Web-CSS-
Diseño de páginas con css
| ![](RackMultipart20200423-4-157mbjv_html_f63b2f98374d4bc6.png) | **VICERRECTORADO DOCENTE** | **Código:** GUIA-PRL-001 |
| --- | --- | --- |
| CONSEJO ACADÉMICO | **Aprobación:** 2016/04/06 |
| **Formato:** Guía de Práctica de Laboratorio / Talleres / Centros de Simulación |

| ![](RackMultipart20200423-4-157mbjv_html_b94fd5c8d846e117.png) | **PRÁCTICA DE LABORATORIO** |
| --- | --- |
|
 |
| **CARRERA** : Computación | **ASIGNATURA** : HIPERMEDIAL |
| --- | --- |
| **NRO. PRÁCTICA** : | 2 | **TÍTULO PRÁCTICA** : Resolución de problemas sobre CSS3 |
| --- | --- | --- |
| **OBJETIVO ALCANZADO:** • Entender y organizar de una mejor manera los sitios de web en Internet • Diseñar adecuadamente elementos gráficos en sitios web en Internet. • Crear sitios web aplicando estándares actuales. |
| --- |
| **ACTIVIDADES DESARROLLADAS** |
| --- |
| **1.** Se pide tomar como base el sitio web desarrollado en la práctica 01 - Creación de sitio web usando HTML5. Luego, se pide utilizar estilos CSS con la finalidad de obtener varios diseños como los que se muestran en las siguientes imágenes. ![](RackMultipart20200423-4-157mbjv_html_535a9beed1e981db.png) Figura 1. Diseño de página home del sitio web

**Cabecera** Creación de la cabecera mediante css, su estructura está diseñada en el archivo general.css que se visualiza en todas las demás páginas. Se utilizó la clase &quot;cabecera&quot; para identificar la misma. /\*cabecera\*/ .cabecera { width: 100%; text-align: center; } Se determina el tamaño del logo principal de la cabecera y se lo asigna a la izquierda de la misma manera se interpreta a todas las imagenes.#logo {width: 25%;margin: 3% auto;float: left; }Centrar y alinear el buscador, contiene un borde redondeado y con color de fondo.#buscar {text-align: center;vertical-align: middle;background-color: aqua;border-radius: 10px;width: 50%;margin: 5% 1%;float: left;}#buscar input {width: 80%;margin: 3% auto;float: none; } La navegación contiene un borde redondeado y con un color de fondo.cabecera nav{clear: both;width: 100%;float: left;}.cabecera ul {list-style-type: none;margin: 0;padding: 0;overflow: hidden;background-color: aqua; border-radius: 10px; } Cada vínculo tiene un bode redondeado y se eliminó la decoración para tener un color sólido..cabecera nav a {width: 11%;border-radius: 10px;border: solid;margin: 1% 0.5%;text-decoration: unset;color: black;float: left;}/\*fin cabecera\*/ ![](RackMultipart20200423-4-157mbjv_html_ff5d77e81cbaceff.png) **Primera y segunda sección** Uso de una sección principal que está dividida en dos, uno a la izquierda con float left y otro a la derecha con float right esto está ubicado en index.css. ![](RackMultipart20200423-4-157mbjv_html_e79abe79d10d4f5e.png) **Catálogo de imágenes** Para ordenar las imágenes se utilizó la sección con la clase galería, donde cada imagen tiene un id para poder modificar su posición usando float left y un margen específico que está ubicado en index.css para que se obtenga el siguiente resultado. ![](RackMultipart20200423-4-157mbjv_html_ca3d7c4d850338ac.png) **Sección de votación** Se uso dos asides, el de la izquierda representa al avatar del usuario y una votación de estrellas, el otro aside muestra información del usuario que corresponde al avatar, está ubicado en index.css.El css para las estrellas está en index.css ![](RackMultipart20200423-4-157mbjv_html_673988915331b200.png) **Sección de usuarios** Está dividido en aside con float left cada uno tiene un usuario y su botón respectivo, está ubicado en index.css. ![](RackMultipart20200423-4-157mbjv_html_18add2d97f6f387b.png) **Footer** El footer es de uso general para todas las páginas.Uso de 3 aside, el de la izquierda representa las redes sociales y el correo, el del medio información de la pagina y el de la derecha información de un usuario.Para vincular las redes sociales utilice: \&lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css&quot;\&gt; ![](RackMultipart20200423-4-157mbjv_html_334fb2974c8c66a0.png) |
| --- |
| **2.** Se pide utilizar, en al menos una página HTML, un diseño a dos columnas con cabecera y pie de página, como el que se muestra en la Figura 2. ![](RackMultipart20200423-4-157mbjv_html_9e61b0be7266b9e2.png)Se realizó el diseño propuesto de la siguiente manera, la cabecera y el pie de página es el mismo en todas las paginas lo uso como un estándar, y la parte central lo divido en 2 secciones como pide el diseño la imagen a la izquierda que corresponde a lo que sería menú pero se usa una imagen porque el menú ya está en la cabecera y el texto a la derecha que corresponde a contenidos. ![](RackMultipart20200423-4-157mbjv_html_bca05904fc654e15.png) Así, como también se recomienda utilizar, en al menos una página HTML, un diseño a tres columnas con cabecera y pie de página como se muestra en la Figura 3. En ambos casos se pide tomar como base la página home. ![](RackMultipart20200423-4-157mbjv_html_a2d67bd5ba04165d.png)De la misma manera que el diseño anterior la cabecera y el pie de página son los mismos en todas las páginas, se implementó el diseño de 3 divisiones usando 3 secciones una a la izquierda que contiene imágenes y texto y corresponde al menú que propone el diseño pero se usó todo esto porque el menú ya está en la cabecera, una central que contiene los contenidos, y la sección de la derecha que corresponde al lateral que contiene una tabla. ![](RackMultipart20200423-4-157mbjv_html_b9f899c28c22b977.png)
 |
| --- |
| **3.** De igual manera, se pide que se organice en al menos cuatro archivos CSS los estilos para las diferentes páginas html, estos archivos estarán almacenados en una carpeta llamada css. Un archivo será para el diseño a dos columnas, otro archivo para el diseño a tres columnas, otro archivo para el diseño de la página home. Por último, un archivo para las reglas CSS relacionas a textos, colores, tablas, secciones, artículos, imágenes, etc. **Archivos css**** cuenta.css **Esta plantilla tiene el diseño de la página Cuenta y modifica la estructura de esta.** datos.css **Esta plantilla tiene el diseño de la página Datos Curiosos y modifica la estructura de esta.** evolucion.css **Esta plantilla tiene el diseño de la página Evolución Android y modifica la estructura de esta.** general.css **Esta plantilla tiene el diseño de todas las páginas y modifica la estructura de todas estas.** index.css **Esta plantilla tiene el diseño de la página Información de Android que la página Inicial o Home y modifica la estructura de esta.** paginas.css**Esta plantilla tiene el diseño de las páginas que sobran y modifica la estructura de estas usando un diseño común para todas. |
| --- |
| **4.** Luego, se pide que se personalicen estilos referente a texto tanto en color, tamaño, fuente, decoraciones, etc. Ver más, [https://fonts.google.com/](https://fonts.google.com/) Se descargo 3 estilos Bangers para títulos en h1, Lobster para títulos de h2-6 y IndieFlower para el texto en general como p./\*fuentes\*/@font-face { font-family: &#39;titulos&#39;; src: url(/fuentes/H1/Bangers-Regular.ttf);}

@font-face {font-family: &#39;subtitulos&#39;;src: url(/fuentes/H2-6/Lobster-Regular.ttf);}

@font-face {font-family: &#39;textos&#39;;src: url(/fuentes/P/IndieFlower-Regular.ttf);}

h1 {font-family: &#39;Bangers&#39;, cursive;}

h2, h3 {font-family: &#39;Lobster&#39;, cursive;}

p, label, li {font-family: &#39;Indie Flower&#39;, cursive;}

/\*fin fuentes\*/ |
| --- |
| **5.** Asimismo, se pide que se personalice todos los hipervínculos usando pseudoclases..cabecera nav a:link {color: black; } .cabecera nav a:visited { color: blueviolet; } .cabecera nav a:hover { color: red; } .cabecera nav a:active { color: lime; }

 ![](RackMultipart20200423-4-157mbjv_html_fcc9cf1d05c5b3ed.png) ![](RackMultipart20200423-4-157mbjv_html_e3c6e0ddca9865a6.png) |
| --- |
| **6.** También, se pide que se cree un menú horizontal (navegación) para todas las páginas. Como se puede observar en la Figura 1. ![](RackMultipart20200423-4-157mbjv_html_572e7a1788db103b.png) |
| --- |
| **7.** De igual manera, se pide crear una nueva página HTML, en donde, se muestre un formulario de contacto o crear cuenta que tenga campos como: nombre, mensaje y botón para enviar. Como se muestra en la Figura 4. ![](RackMultipart20200423-4-157mbjv_html_b6dcf3a0edec5866.png) Esta diseñado en el archivo cuenta.html y usa cuenta.css para el diseño de la página, para acceder a esta dar clic en la imagen: ![](RackMultipart20200423-4-157mbjv_html_95ce80532952247e.png) ![](RackMultipart20200423-4-157mbjv_html_95ce80532952247e.png) |
| --- |
| **8.** Asimismo, se pide que se utilice una gama de colores para el desarrollo del sitio web. Ver más, [https://color.adobe.com/es/create](https://color.adobe.com/es/create).Se utilizo colores del sistema y otros del link sugerido para implementar se usó, por ejemplo: background-color: #C292E8; para el fondo de las secciones de algunas páginas. |
| --- |
| **9.** Crear un repositorio en GitHub con el nombre &quot;Practica02 – Mi Sitio Web (CSS)&quot;[https://github.com/robyserpa/Practica02-Mi-Sitio-Web-CSS-](https://github.com/robyserpa/Practica02-Mi-Sitio-Web-CSS-) |
| --- |
| **10.** Realizar un commit y push por cada requerimiento de los puntos antes descritos |
| --- |
| **11.** Al finalizar la práctica se debe validar todas las páginas HTML y hojas de estilos CSS creadas usando el W3C Validator. **audio.html**![](RackMultipart20200423-4-157mbjv_html_79b8481868380704.png) **cuenta.html**![](RackMultipart20200423-4-157mbjv_html_79b8481868380704.png) **datos**** \_curiosos.html**![](RackMultipart20200423-4-157mbjv_html_79b8481868380704.png)**dispositivos.html**![](RackMultipart20200423-4-157mbjv_html_79b8481868380704.png)**evolucion\_android.html**![](RackMultipart20200423-4-157mbjv_html_79b8481868380704.png)**imagenes.html**![](RackMultipart20200423-4-157mbjv_html_79b8481868380704.png)**juegos.html**![](RackMultipart20200423-4-157mbjv_html_79b8481868380704.png)**videos\_youtube.html**![](RackMultipart20200423-4-157mbjv_html_79b8481868380704.png)**videos.html**![](RackMultipart20200423-4-157mbjv_html_79b8481868380704.png) |
| --- |
| **12.** Luego, se debe crear el archivo README del repositorio de GitHub. |
| --- |
| **RESULTADO(S) OBTENIDO(S)**:La modificación del diseño de las paginas según lo pedido. |
| --- |
| **CONCLUSIONES** :El uso de css para el diseño de paginas hace que estas se visualicen de una forma amigable para el usuario. |
| --- |
| **RECOMENDACIONES** :Revisar las imágenes y el link de github. |
| --- |

_ **Nombre de estudiante** _ **: Roberto Serpa**

![](RackMultipart20200423-4-157mbjv_html_5520b8a61bd3af6b.png)

_ **Firma de estudiante** _ **:**

**Resolución CS N° 076-04-2016-04-20**
