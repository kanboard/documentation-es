Tareas
======

Creación de tarea
-----------------

Desde el tablero, haga clic en el signo más **plus** al lado del nombre
de la columna

.. figure:: /_static/task-creation-board.png
   :alt: Creación de tarea desde el tablero

   Creación de tarea desde el tablero

A continuación, aparece el formulario de creación de tareas:

.. figure:: /_static/task-creation-form.png
   :alt: Formulario de creación de tareas

   Formulario de creación de tareas

Descripción de campos:

-  **Titulo**: El título de su tarea, que se podrá ver en el tablero.
-  **Descripción**: Descripción que usa el formato Markdown.
-  **Tags**: Lista de etiquetas asociadas a las tareas
-  **Crear otra tarea**:Marque esta casilla si desea crear una tarea
   similar (serán pre-llenados algunos campos)..
-  **Color**: Escoger el color de la tarjeta.
-  **Asignado**: Persona que trabajara en la tarea.
-  **Categoría**: Sólo una categoría puede ser asignado a una tarea
   (visibles sólo si los proyectos tienen categorías).
-  **Columna**: La columna en la que se creó la tarea, su tarea se
   coloca en la parte inferior.
-  **Prioridad**: AL Prioridad de la tarea, el intervalo se puede
   definir en la configuración del proyecto, los valores por defecto son
   P0 a P3.
-  **Complejidad**: Se utiliza en la gestión de proyectos ágiles
   (Scrum), los puntos de complejidad o de la historia es un número que
   le dice al equipo lo difícil es la historia. A menudo, las personas
   utilizan la serie de Fibonacci.
-  **Referencia**: ID externo para la tarea, por ejemplo, puede ser el
   número de entradas que provienen de otro sistema
-  **Estimación original** : Estimación de horas para completar la
   tarea.
-  **Tiempo transcurrido** : El tiempo dedicado a trabajar en la tarea.
-  **Fecha de Inicio** : Se trata de un campo de fecha y hora.
-  **Fecha de vencimiento** : Las tareas vencidas se tiene una fecha de
   vencimiento próxima rojo y las fechas de vencimiento será de color
   negro en el tablero. Varios formato de fecha se aceptan además del
   selector de fecha.

Con el enlace de vista previa, se puede ver la descripción de la tarea
convertiendo la sintaxis de Markdown.

Agregar screenshots
-------------------

Tu puedes copiar y pegar imagenes directamente en Kanboard y salvarlo al
mismo tiempo. Estas imágenes se cargan como archivos adjuntos a la tarea
.

Esto es especialmente útil para tomar capturas de pantalla para
describir un problema, por ejemplo.

Puede agregar imágenes directamente desde el tablero haciendo clic en
menú desplegable o en la página de vista de tareas.

.. figure:: /_static/dropdown-screenshot.png
   :alt: Drop-down screenshot menu

Para añadir una nueva imagen, coloque su captura de pantalla y pegar
CTRL+V or Command+V:

.. figure:: /_static/task-screenshot.png
   :alt: Screenshot page

En Mac OS X, puede utilizar los atajos para tomar screenshots:

-  Command-Control-Shift-3: Tome una screenshot de la pantalla, y
   guardarlo en el portapapeles
-  Command-Control-Shift-4, a continuación, seleccione un área: Tome una
   captura de pantalla de la zona y la guarda en el portapapeles
-  Command-Control-Shift-4, entonces el espacio, a continuación, haga
   clic en una ventana : Tome una captura de pantalla de una ventana y
   guardarlo en el portapapeles

También hay varias aplicaciones de terceros que pueden ser utilizados
para tomar capturas de pantalla con anotaciones y formas.

Nota: Esta función no funciona con todos los navegadores

No funciona con Safari, debido a este error :
https://bugs.webkit.org/show_bug.cgi?id=49141

Etiquetas
---------

Con kanboard, tu puedes asociar una o mas tags a una tarea. Tu puedes
definir etiquetas globalmente para todos los proyectos o solo para unos
proyectos en especifico.

.. figure:: /_static/tags-board.png
   :alt: Tags en el tablero

Desde el formulario de tarea, tu puedes caputarar las tags deseadas:

.. figure:: /_static/tags-task.png
   :alt: Tags form

La auto-completacion se forma para mostrar ó sugerir etiquetas
disponibles.

También puede crear etiquetas directamente desde el formulario de tareas.
Por defecto, al crear etiquetas de un formulario de tarea que están
asociados al proyecto actual :

.. figure:: /_static/tags-projects.png
   :alt: Project Tags

Todas las tags pueden ser manejadas en configuración del proyecto.

Para definir tags globalmente para todos los proyectos, ve a la
configuración de la aplicación :

.. figure:: /_static/tags-global.png
   :alt: Global Tags

Para buscar tareas basadas en etiquetas, solo use el atributo “tag”:

.. figure:: /_static/tags-search.png
   :alt: Search Tags

Análisis para tareas
--------------------

Cada tarea tiene una sección de análisis disponible en el menu izquierdo
en la vista de tarea.

Espera y tiempo de ciclo
~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: /_static/task-lead-cycle-time.png
   :alt: Lead and cycle time

-  El tiempo de espera es el tiempo entre la creacion de la tarea y la
   fecha de finalización (Tarea cerrada).
-  El tiempo de ciclo es el tiempo entre la fecha de inicio y la fecha
   de finalización.
-  Si la tarea no esta cerrada el tiempo actual es usado en lugar de la
   fecha de finalización.
-  Si la fecha de inicio no es especificada, el tiempo de ciclo no es
   calculado.

Nota: Puede configurar una accion automatica para definir la fecha de
inicio automaticamente cuando se mueve una tarea a la columna de su
eleccion.

El tiempo invertido en cada columna
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: /_static/time-into-each-column.png
   :alt: Time spent into each column

-  Esta gráfico muestra el total de tiempo invertido en cada columna
   para la tarea.
-  El tiempo invertido es calculado hasta que la tarea es cerrada.
