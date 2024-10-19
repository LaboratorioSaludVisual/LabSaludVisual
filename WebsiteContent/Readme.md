## Ajustes en Website Content

### Cómo agregar más miembros al sitio web

1. Subir alguna foto o imagen a la carpeta [images](https://github.com/LaboratorioSaludVisual/LabSaludVisual/tree/main/WebsiteContent/images) dentro de WebsiteContent.
2. Localizar el código de los miembros actuales:
   * Abrir el archivo [index.html](https://github.com/LaboratorioSaludVisual/LabSaludVisual/blob/main/index.html) o [index_es.html](https://github.com/LaboratorioSaludVisual/LabSaludVisual/blob/main/index_es.html).
   * Navegar a las líneas donde se encuentran las fotos de los miembros actuales del laboratorio, la sección inicia en la línea 172.
3. Agregar un nuevo miembro:

   ```html
   <div class="miembro">
     <img src="images/nombre_del_miembro.jpg" alt="Nombre del miembro">
     <h3>Nombre del miembro</h3>
     <p>Descripción o título del miembro.</p>
   </div>

### Explicación:

- He utilizado los "triple backticks" \``` para encapsular el bloque de código HTML, lo que permite que se vea resaltado y con fondo oscuro en GitHub.
- Esto te permite copiar y pegar el bloque de código HTML directamente en tu `README.md` para que aparezca bien formateado y fácil de copiar para otros usuarios.

Ahora solo necesitas copiar y pegar este texto directamente en tu archivo `README.md`. ¡Quedará como querías, con el fondo oscuro y formato de código en GitHub!

