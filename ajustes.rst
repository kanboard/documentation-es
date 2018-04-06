Ajustes
=======

Configuración del tablero
-------------------------

Ir al menu **Configuraciones**, elije **Ajustes de tablero** a la
izquierda.

.. figure:: /_static/board-settings.png
   :alt: Board settings

Resaltado de tarea
~~~~~~~~~~~~~~~~~~

Esta caracterista muestra una sombra alrededor de la tarea cuando una
tarea se traslado recientemente

Establecer el valor 0 para desactivar esta caracterista, 2 dias por
default (172800 segundos).

Todo lo traslado desde de 2 dias tendra una sombra alrededor de la
tarea.

Recargar el intervalo para la pizarra publica
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Cuando tu compartes un tablero, la pagina se refresca cada 60 segundos
automaticamente por default.

Refrescar el intervalo para un tablero privado
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Cuando su navegador esta abierto un tablero, Kanboard comprueba cada 10
segundos si algo ha sido cambiado por otra persona.

Técnicamente este proceso se lleva a cabo por el Ajax.

Configuración de calendarios
----------------------------

Ir al menu de configuraciones, despues elegir cofiguracion de
calendarios que se encuentra al lado izquierdo

.. figure:: /_static/calendar-settings.png
   :alt: Configuración de calendarios

Existe dos diferentes calendarios en kanboard :

-  Calendarios de projectos
-  Calendario por usuario (disponible desde el dashboard)

Calendario por projectos
~~~~~~~~~~~~~~~~~~~~~~~~

Este calendario visualiza las tareas que se le asignan fechas de
vencimiento y las tareas estan basadas sobre la fecha de creación o el
inicio de fecha

Visualizar tareas basadas en la fecha de creacion
'''''''''''''''''''''''''''''''''''''''''''''''''

-  El inicio de fecha del evento del calendario es la fecha de creacion
   de la tarea
-  El finalización de fecha del evento es cuendo se completa una tarea

Visualizar tareas basadas en las fechas de inicio
'''''''''''''''''''''''''''''''''''''''''''''''''

-  La fecha de inicio del evento del calendario is la fecha de incio de
   la tarea
-  Esta fecha puede ser definida manualmente.
-  La fecha de finalización del evento es la fecha de terminación
-  Si no hay una fecha de inicio de la tarea no aparece en el
   calendario.

Calendarios por usuarios
~~~~~~~~~~~~~~~~~~~~~~~~

Este calendario visualiza solo las tareas asignadas para el usuario y
opcionalmente la información de las subtareas

Visualizar subtareas basadas en el tiempo de tracking
'''''''''''''''''''''''''''''''''''''''''''''''''''''

-  Despliega la información de las subtareas desde el calendario o en el
   registro de la tabla de seguimiento de tiempo
-  La intersección con los usuarios timetable es calculad

Las estimaciones muestran las subtareas (la previsión de los trabajos futuros)
''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''

-  Mostrar la estimación de los trabajos futuros de las subtareas en
   estado de “todo” y con un valor definido "estimación".
