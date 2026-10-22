# Ficha del proyecto: Aroma Café

## 1. Datos generales

- **Nombre del proyecto:** Aroma Café
- **Tipo de sitio web:** Página web de una cafetería local
- **Estudiante:** Cristina Loja
- **Asignatura:** Estándares Web
- **Tecnologías utilizadas:** HTML5 y CSS3
- **Enlace del sitio web:** [Aroma Café](https://cristinaelilo.github.io/Practica---Est-ndares-HTML--LC/)

## 2. Descripción del proyecto

Aroma Café es una página web creada para una cafetería local, con el propósito de presentar sus productos, mostrar sus precios y permitir que los visitantes preparen un pedido mediante un formulario. La información está organizada en diferentes secciones para que sea fácil encontrar lo que se busca.

Para desarrollar la página se utilizaron HTML y CSS. Con HTML se estructuró el contenido y se añadieron elementos como el menú de navegación, la tabla de precios y el formulario. Por su parte, CSS se utilizó para definir los colores, los espacios, la distribución de los elementos y la apariencia general del sitio.

## 3. Características implementadas

### 3.1. Estructura semántica

Se utilizaron etiquetas como `header`, `nav`, `main`, `section`, `article`, `aside` y `footer` para organizar el contenido. También se añadieron títulos y etiquetas descriptivas para identificar las diferentes partes de la página.

Además, se incluyó un enlace al inicio que permite saltar directamente al contenido principal, lo que facilita la navegación.

### 3.2. Diseño y presentación visual

Se definió una combinación de colores inspirada en el café, utilizando tonos marrones, crema y blanco. También se establecieron estilos para las imágenes, la tabla de precios, los botones y el formulario.

Para distribuir los elementos se utilizaron Flexbox y CSS Grid. Asimismo, se crearon variables CSS para reutilizar los colores y mantener una presentación uniforme.

### 3.3. Diseño adaptable

Se incorporó una media query para pantallas de hasta 640 píxeles de ancho. En este tamaño se ajustan el menú de navegación, los espacios del contenido, las celdas de la tabla y los botones.

Con estos cambios se busca que la página sea más cómoda de consultar desde teléfonos móviles y otros dispositivos con pantallas pequeñas.

### 3.4. Formulario y validaciones

La sección de pedidos incluye campos para ingresar el nombre, el correo electrónico, el número de celular y los detalles del pedido. También permite seleccionar el tamaño de la bebida, agregar ingredientes adicionales y elegir el producto, la cantidad y la fecha.

Se utilizaron atributos como `required`, `minlength`, `pattern`, `min`, `max` y `maxlength` para establecer condiciones en los campos. Además, mediante CSS se diferencian los estados válidos e inválidos y se resaltan los grupos que contienen campos inválidos utilizando `:has()`.

### 3.5. Accesibilidad y navegación

Se añadieron textos alternativos a las imágenes, etiquetas asociadas a los campos del formulario y un enlace para saltar al contenido principal. También se definieron estilos de foco visible para enlaces, botones y campos del formulario, con el fin de facilitar la navegación mediante teclado.

En la tabla de precios se utilizaron encabezados para identificar los productos, sus descripciones y sus valores.

## 4. Aspectos que se revisarán

Para comprobar la calidad de la página, se revisarán los siguientes puntos:

- La estructura y la validez del código HTML.
- La presencia de errores en el CSS.
- La adaptación del contenido a diferentes tamaños de pantalla.
- La navegación mediante teclado y la visibilidad del foco.
- La asociación entre las etiquetas y los campos del formulario.
- El comportamiento de las validaciones.
- La visualización de las imágenes y la tabla de precios.

## 5. Evidencias

En la carpeta `docs/evidencias/` se guardarán las capturas de los resultados obtenidos al validar el HTML y el CSS, así como las pruebas realizadas con las herramientas de desarrollo del navegador.

Las evidencias se añadirán conforme se realicen las comprobaciones correspondientes.

## 6. Estado del proyecto

La página Aroma Café está publicada mediante GitHub Pages y puede consultarse desde el enlace incluido en esta ficha. Como parte de la actividad, se revisarán los aspectos mencionados para identificar posibles errores y determinar si es necesario realizar mejoras.