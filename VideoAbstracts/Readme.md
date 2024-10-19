## Cómo subir videos a la carpeta VideoAbstracts

- ** Subir los videos con extensión mp4 a esta carpeta **
- Editar las rutas en las paginas que se subieron a las carpetas locales:
  * En la versión en inglés:
      1. Entrar al archivo [index.html](https://github.com/LaboratorioSaludVisual/LabSaludVisual/blob/main/index.html) 
      2. Ir a la línea 364 del código, donde empieza la sección de Video Abstracts (sección de videos).
      3. Buscar la línea 377, que tiene el siguiente código:
     ```html
         <iframe width="80%" height="450" src="VideoAbstracts/nombre_del_video.mp4" frameborder="0" allowfullscreen></iframe>
      ```
      4. Cambiar nombre_del_video.mp4 por el nombre del video, asegurándo de que esté en la carpeta VideoAbstracts. Así, el video será visible en la página web.
      
  * En la versión en español:
      1. Entrar al archivo [index_es.html](https://github.com/LaboratorioSaludVisual/LabSaludVisual/blob/main/index_es.html)
      2. Ir a la línea 364 del código, donde empieza la sección de Video Abstracts (sección de videos).
      3. Buscar la línea 377, que tiene el siguiente código:
      ```html
      <iframe width="80%" height="450" src="VideoAbstracts/nombre_del_video.mp4" frameborder="0" allowfullscreen></iframe>
      ```
      4. Cambiar nombre_del_video.mp4 por el nombre del video, asegurándo de que esté en la carpeta VideoAbstracts.
      
- Editar las rutas en las paginas de los videos de Internet:
  * En la versión en inglés:
      1. Entrar al archivo [index.html](https://github.com/LaboratorioSaludVisual/LabSaludVisual/blob/main/index.html) 
      2. Ir a la línea 364 del código, donde empieza la sección de Video Abstracts (sección de videos).
      3. Buscar la línea 381, que tiene el siguiente código y descomentarlo, es decir eliminar <!--   -->:
      ```html
      <iframe width="80%" height="450" src="https://www.youtube.com/embed/tu-video-id" frameborder="0" allowfullscreen></iframe>
      ```
      4. Obtener el código de inserción desde YouTube:
          * En YouTube, buscar el video que se desea agregar.
          * Hacer clic en Compartir debajo del video.
          * En las opciones que aparecen, selecciona Incorporar.
          * Copiar el código que aparece en el cuadro de texto (será un código <iframe>).
       5. Reemplaza la ruta del video en el código del iframe:
          * Pegar el código completo que se copio de YouTube.
          * Reemplaza toda la ruta https://www.youtube.com/embed/tu-video-id por la que copiaste en el paso anterior.
      
  * En la versión en español:
      1. Entrar al archivo [index_es.html](https://github.com/LaboratorioSaludVisual/LabSaludVisual/blob/main/index_es.html)
      2. Ir a la línea 364 del código, donde empieza la sección de Video Abstracts (sección de videos).
      3. Buscar la línea 381, que tiene el siguiente código y descomentarlo, es decir eliminar <!--   -->:
      ```html
      <iframe width="80%" height="450" src="https://www.youtube.com/embed/tu-video-id" frameborder="0" allowfullscreen></iframe>
      ```
      4. Obtener el código de inserción desde YouTube:
          * En YouTube, buscar el video que se desea agregar.
          * Hacer clic en Compartir debajo del video.
          * En las opciones que aparecen, selecciona Incorporar.
          * Copiar el código que aparece en el cuadro de texto (será un código <iframe>).
       5. Reemplaza la ruta del video en el código del iframe:
          * Pegar el código completo que se copio de YouTube.
          * Reemplaza toda la ruta https://www.youtube.com/embed/tu-video-id por la que copiaste en el paso anterior.
      


   
