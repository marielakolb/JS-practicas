## CONSIGNA
1. Cambiar contenido de un elemento: Introducir la manipulación del Document Object Model (DOM) para cambiar el contenido de un elemento HTML. Contexto en un sitio web dinámico: En un sitio real, podrías querer actualizar un mensaje de bienvenida, el estado de un pedido o un contador de notificaciones sin recargar la página. Crea un archivo HTML
con un párrafo (\<p\>) que contenga el texto \"Hola, mundo!\". Añade un botón. Cuando se haga clic en el botón, el texto del párrafo debe  cambiar a \"¡Bienvenido/a a mi sitio web!\".

2. Eventos: Mostrar u ocultar elementos: Practicar el manejo de eventos para controlar la visibilidad de elementos HTML. Contexto en un sitio web dinámico: Esto es fundamental para menús desplegables, modales de confirmación, paneles de información que aparecen/desaparecen al hacer
clic, etc. Crea un HTML con un botón y un \<div\> oculto inicialmente (puedes usar display: none; en CSS). Cuando se haga clic en el botón, el \<div\> debe volverse visible. Un segundo clic en el mismo botón debe ocultarlo de nuevo.

3. Formularios: Validar entrada de usuario (cliente), el objetivo es entender cómo JavaScript puede validar la entrada de datos en un formulario antes de enviarlos. Contexto en un sitio web dinámico: Es crucial para asegurar que los datos enviados a la base de datos sean
válidos y para proporcionar retroalimentación instantánea al usuario, mejorando la experiencia. Crea un formulario simple con un campo de entrada para \"Email\" y un botón de \"Enviar\". Cuando el usuario
intente enviar el formulario, JavaScript debe verificar si el campo de email no está vacío y si contiene un @. Si no cumple las condiciones, debe mostrar una alerta o un mensaje de error debajo del campo.

4. Arrays y bucles: Listado de elementos dinámicos: Usar arrays y bucles para generar listas de contenido dinámicamente en el DOM. Contexto en un sitio web dinámico: Piensa en listas de productos en una tienda online, comentarios de un blog, elementos de un carrito de compras, o resultados
de búsqueda. Estos datos provienen de una base de datos y se renderizan dinámicamente. Crea un array de JavaScript con al menos 3 nombres de frutas. Utiliza un bucle para crear una lista desordenada (\<ul\>) en HTML, donde cada elemento de la lista (\<li\>) sea una fruta del array.

5. Objetos y funciones: Información de producto: Representar datos con objetos y usar funciones para manipularlos y mostrarlos. Contexto en un sitio web dinámico: Cada \"cosa\" en una base de datos (un usuario, un producto, una publicación) puede ser vista como un objeto. JavaScript es
ideal para trabajar con estos objetos en el frontend. Define un objeto JavaScript llamado producto con propiedades como nombre, precio y disponible. Crea una función que reciba este objeto y actualice la información de un \<div\> preexistente en el HTML para mostrar los
detalles del producto. Llama a la función con el objeto producto.

6. Eventos y CSS: Cambio de tema/modo oscuro: Combinar JavaScript y CSS para cambiar dinámicamente la apariencia de un sitio. Contexto en un sitio web dinámico: Funcionalidades como el \"modo oscuro\" son muy comunes. Esto no solo mejora la experiencia del usuario, sino que
también puede reflejar preferencias almacenadas en una base de datos para un usuario específico. Crea un HTML con un botón \"Cambiar Tema\".
Define dos clases CSS, claro y oscuro, que cambien el color de fondo y el color del texto del \<body\>. Cuando se haga clic en el botón, alterna entre estas dos clases en el elemento \<body\>.

7. Temporizadores: Galería de imágenes automática: Usar setInterval o setTimeout para ejecutar código en intervalos regulares o después de un tiempo. Contexto en un sitio web dinámico: Carruseles de imágenes, notificaciones temporales, actualizaciones de datos en tiempo real (por
ejemplo, un contador de visitas), o animaciones que se reproducen automáticamente. Crea un HTML con un elemento \<img\>. Ten un array de URLs de imágenes. Cada 3 segundos, la imagen mostrada en el \<img\> debe cambiar a la siguiente en el array, volviendo a la primera al llegar al
final.

8. Peticiones HTTP (simuladas): Carga de datos asíncrona: Preparar para el concepto de hacer peticiones a un servidor (backend) para obtener datos. Aunque no se usará fetch o XMLHttpRequest directamente en esta fase, la simulación ayuda a entender el flujo asíncrono. Contexto en un
sitio web dinámico: Esta es la base de cómo un frontend obtiene información de una API (desarrollada con PHP, por ejemplo) para mostrarla al usuario, como la carga de productos, publicaciones de blog o datos de perfil. Simula la carga de datos de un \"servidor\". Crea una
función que, después de un retraso de 2 segundos (usando setTimeout), simule devolver un array de objetos (por ejemplo, usuarios con id y nombre). Al \"recibir\" estos datos, imprímelos en la consola y luego muestra cada usuario en una lista HTML.

9. Manipulación avanzada del DOM y datos estructurados: Tabla de datos: Generar una tabla HTML dinámicamente a partir de un array de objetos.
Contexto en un sitio web dinámico: Mostrar listados de datos complejos (productos, pedidos, usuarios, reportes) que provienen de una base de datos es una tarea muy común. Crea un array de objetos, donde cada objeto represente un \"libro\" con propiedades como titulo, autor y año.
Genera una tabla HTML (\<table\>) dinámicamente con JavaScript, donde cada libro sea una fila (\<tr\>) y sus propiedades sean celdas (\<td\>). Añade una fila de encabezados (\<th\>) para la tabla.

10. Interacción compleja: Filtrado de lista: Combinar la entrada del usuario, la manipulación del DOM y la lógica de datos para crear una funcionalidad de búsqueda/filtrado. Contexto en un sitio web dinámico:
Una funcionalidad esencial en casi cualquier sitio web que maneja colecciones de datos (productos, usuarios, artículos de blog). La lógica de filtrado puede ser ejecutada en el frontend (para listas pequeñas) o enviada al backend para grandes volúmenes de datos. Partiendo de la
actividad 4 (lista de frutas), añade un campo de entrada de texto (\<input type=\"text\"\>) y un botón de \"Filtrar\". Cuando el usuario escriba algo y haga clic en \"Filtrar\", solo deben mostrarse las frutas que contengan el texto ingresado (sin distinguir mayúsculas/minúsculas).
Si el campo está vacío, deben mostrarse todas las frutas.

## Tienes acceso a las soluciones ##
