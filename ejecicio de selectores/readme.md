📌¿Cuál es el peso de los siguientes selectores de CSS? ¿Cuál pesa más? ¿Cuál pesa menos?
Define el peso de cada uno de estos selectores y ordenadores de más específicos a menos específicos.
Aunque lo ideal es que lo calcules automáticamente mirando los apuntes, puedes comprobar posteriormente si
los resultados son correctos mirando algunos de los TIPS que se detallan más abajo.

- El primero tendria preferencia el ``!important``ya que da prioridad al resto pero si lo metemos dentro de dos estilos cogera el que tenga mayor peso tenga de esos dos.
- Segundo ``#title-1`` con un peso de 1 , 0, 0
es el que tiene mas peso.
- Tercero ``a[href="title-1"]``con un peso de 0 , 1 , 1
- Quarto ``.title-1``con un peso de 0 , 1 , 0
- Quinto ``h1``con un peso de 0 , 0 , 1
- Sexto ``*`` con un peso de 0 , 0 , 0
