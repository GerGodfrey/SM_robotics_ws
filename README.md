# SM_robotics_ws
## ACT1 - Publicador y subscritor de velocidad

* Luis Gerardo Godfrey Castañeda
* Descripción: Se realizaron 2 nodos (publicador y subscriptor) para ir identificando los cambios que se requieren al agregar nuevos documentos (en este caso .py) que alteraran diferentes valores de nuestro robot o tortuga
* Comandos:
  1. Se ocupo touch y nano para crear y editar el nuevo .py del suscriptor 
  2. Se ocupo nano nuevamente pero ahora con el compilador para que agarre nuestro nuevo documento
  3. Se ocupo source install/setup.bash para actualizar las instancias
  4. ros2 run basics velocity_subscriber
* Complicaciones: Solo para generar el nodo porqué no se actualizaba y corría el ros2 node list y tampoco aparecía nada. Así que tuve que correr source ~/. para ejecutar de nuevo el archivo y cargue las instancias en otra terminal


