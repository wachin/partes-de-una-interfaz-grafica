# partes-de-una-interfaz-grafica

De la siguiente interfaz gráfica:

![](imagenes/01-lc-Inventario-partes-de-la-interfaz.png)


están las siguientes partes:

![](imagenes/02-lc-Inventario-partes-de-la-interfaz-con-indicaciones.png)

  - El separador horizontal debajo de la tabla permite ampliar o reducir verticalmente su espacio.
  - Los límites de las columnas pueden arrastrarse hacia la izquierda o derecha, como en Excel
  

• En este tipo de tabla puede ser necesario que crezca y que toda la página inferior sea empujada hacia abajo, aumentando la altura total desplazable, es necesario poner allí una barra de arrastre propia que cambie directamente la altura de la tabla y haga crecer la página completa.


• Corregí el comportamiento cambiando completamente el mecanismo anterior.

  Ahora, al mantener presionado el clic izquierdo sobre la barra horizontal y arrastrarla:

  - La altura de la tabla cambia directamente.
  - Al arrastrar hacia abajo, todos los recuadros inferiores se desplazan hacia abajo.
  - Los paneles inferiores ya no se comprimen.
  - El movimiento se muestra mientras arrastras.
  - La altura permanece donde sueltas el clic.
  - La tabla puede ajustarse entre 180 y 1400 píxeles.
  - La página completa conserva su barra de desplazamiento.

  También actualicé la traducción y los manuales. Las 197 pruebas pasan y no se requiere migración.
