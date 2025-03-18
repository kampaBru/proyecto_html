# Proyecto HTML - Academia Conquer
La aventura del Frontend comienza con **HTML**. Este proyecto consiste en la creación de un sitio web que simula una academia llamada Conquer. El objetivo es presentar un sitio web con información de cursos, un blog y una sección de contacto, todo utilizando **HTML puro y duro**.

## Requisitos del Proyecto
El sitio web está compuesto por varias vistas (páginas) que se organizarán según el mapa web proporcionado, con un documento HTML para cada una de las vistas o "cajas de color" (verde o azul). Aquí se describen las vistas y sus requisitos:

## Estructura Común ##
- **Header**: Común en todas las páginas con:
  - Logotipo de la academia (puedes usar el logotipo de la propia página de Conquer).
  - Menú de navegación:
  - Home
  - Quiénes somos
  - Cursos
  - Blog
  - Registro
  - Login
  - Contacto
- **Footer**: Común en todas las páginas con:
  - Texto de copyright.
  - Enlace al aviso legal.
 
    
## Páginas del Proyecto ##
- **Home**
En la página de inicio se incluirán:
   - Una imagen con un texto describiendo el objetivo de la página.
   - Una sección con un pequeño texto resumen sobre la academia y un enlace a la sección "Quiénes somos".
   - Un listado de los dos últimos cursos con enlaces a la página de todos los cursos.
   - Un listado de las dos últimas noticias con enlaces a la página de todas las noticias.
- **Quiénes Somos**
   - Información sobre la academia.
   - Se podrán incluir detalles sobre los miembros del equipo si es necesario.
- **Cursos**
    Vista con el listado de cursos disponibles, con enlaces a las páginas de detalle de cada uno.

- **Detalle de Curso**
   - Cada curso tendrá su propia página con:
   - Imagen principal.
   - Título.
   - Contenido detallado del curso.
- **Blog**
Vista con el listado de noticias disponibles, con enlaces a las páginas de detalle de cada una.

- **Detalle de Noticia**
Cada noticia tendrá su propia página con:
   - Imagen principal.
   - Título.
   - Contenido detallado de la noticia.

- **Registro**
  Formulario de registro con los siguientes campos:
   - Nombre completo.
   - Fecha de nacimiento.
   - Email.
   - Dirección.
   - Página web.
   - Foto.
   - Biografía.
- **Login**
  Formulario de inicio de sesión que pedirá:
   - Email.
   - Contraseña.
- **Contacto**
   - Datos y forma de contacto del negocio.
   - Mapa de Google Maps.
   - Formulario de contacto (sin funcionalidad, solo campos de entrada).
- **Páginas Legales**
   - Aviso legal (archivo estático).
     
## Detalles Técnicos ##
- `index.html`: Página principal (Home).
- `archivos HTML`: Una página HTML por cada sección en cursos.
- `img/`: Carpeta con todas las imágenes.
- `post/`: Carpeta del blog.
  
- **Buenas Prácticas:**
   - Usar enlaces relativos y no absolutos para los recursos.
   - Etiquetas semánticas: Usar etiquetas como <header>, <footer>, <section>, <article>, etc., para mejorar la       
     accesibilidad y SEO.
   - Usar meta tags: Al menos incluir title y description para cada página.
   - Imágenes responsivas: Utilizar imágenes que se ajusten al tamaño de la pantalla con técnicas de CSS como max-  
     width: 100%.
   - Asegurarse de que todos los archivos estén bien organizados en carpetas correspondientes.

- ## Restricciones: ##
   - No usar tecnologías externas no vistas en clase (por ejemplo, no se debe usar JavaScript ni frameworks).
   - Cuidar la semántica y la estructura de los archivos HTML.
   - Nombres de archivos válidos: Sin tildes ni espacios en los nombres de los archivos.

## Instalación y Uso ##

Este proyecto está hecho completamente en HTML. No es necesario ningún entorno de desarrollo adicional para visualizar las páginas. Simplemente descarga o clona el repositorio y abre los archivos .html en tu navegador.

- **Clonar el repositorio:**
git clone https://github.com/tu-usuario/proyecto_html.git

- **Notas Adicionales**
Este proyecto se realizó con el objetivo de practicar el uso de HTML semántico y estructurado. No se incluyó diseño visual avanzado ya que la prioridad fue la correcta organización y estructuración del contenido.
