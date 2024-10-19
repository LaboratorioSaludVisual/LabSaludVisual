## Ajustes en Website Content

### Cómo agregar más miembros al sitio web

1. Subir alguna foto o imagen a la carpeta [images](https://github.com/LaboratorioSaludVisual/LabSaludVisual/tree/main/WebsiteContent/images) dentro de WebsiteContent.
2. Localizar el código de los miembros actuales:
   * Abrir los archivos [index.html](https://github.com/LaboratorioSaludVisual/LabSaludVisual/blob/main/index.html) y [index_es.html](https://github.com/LaboratorioSaludVisual/LabSaludVisual/blob/main/index_es.html).
   * Navegar a las líneas donde se encuentran las fotos de los miembros actuales del laboratorio, la sección inicia en la línea 172.
3. Agregar un nuevo miembro:

   ```html
   <div class="miembro">
     <img src="images/nombre_del_miembro.jpg" alt="Nombre del miembro">
     <h3>Nombre del miembro</h3>
     <p>Descripción o título del miembro.</p>
   </div>

