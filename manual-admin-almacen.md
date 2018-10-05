# Manual de Usuario  #
## Rol: Administrador de Almacen ##

Pantalla del Administrador de almacén

![pantalla1](imagenes/principal_adm_almacen.png "Primera Pantalla")

## 1 Alimentos
Elija la opción alimentos para poder con los alimentos que dispone en su almacen.

![menu_alimento](imagenes/menu_alimento.png "Seleccione la opción de Alimentos")

Una vez seleccionada la opción de alimento podrá ver la disposición de los mismos en su almacén.

![listado_alimentos](imagenes/listado_alimentos.png  "Listado de alimentos del almacén")

Dentro de este listado el usuario puede ver el histórico de cada alimento.

![historico_alimento](imagenes/historico_alimento.png  "historico_alimento")

## 2 Notas de ingreso ##

Para introducir alimentos al almacén el usuario, el usuario debe hacer uso de notas de ingreso.

![opcion_notas_ingreso](imagenes/menu_notas_ingreso.png  "Presione la opción notas de ingreso de almacen")

Una vez seleccionada la opción uds. podra ver el listado de todas las notas de ingreso al almacen.

![listado_notas](imagenes/listado_notas_ingreso.png  "Listado de notas de ingreso")

Dentro del listado ud. encontrará la opción de 'ver la nota de ingreso' representada por un botón con un icono de un ojo.

![ver_nota_ingreso](imagenes/ver_nota_ingreso.png  "Ver nota de ingreso")

Dentro del listado también tendrá la opción 'Nueva nota de ingreso' que sirve para crear una nueva nota de ingreso, donde podrá registrar los alimentos que ingresan al almacén, recuerde que para ingresar alimentos debe seleccionar un proveedor y un contrato vigente. El sistema no le permitira introducir alimentos que no esten asociados a un contrato vigente.

![nueva_nota_ingreso](imagenes/nueva_nota_ingreso2.png  "Nueva nota de ingreso")

También el sistema validará que los alimentos que quiere ingresar no sobrepasen el techo presupuestario del contrato. Posteriormente el sistema le asignará un número de nota de ingreso automáticamente.

Una vez que se registren nota de ingreso se veran afectados los stocks de alimentos.

## 3 Solicitudes de salida ##
Para realizar la salida de alimentos, se lo realizará mediante solicitudes de salida, para realizarlo seleccione la opción 'Solicitudes de Salida de Almacén'

![menu_solicitud_salida](imagenes/menu_solicitud_salida.png  "Menu solictudes de salida")

Una vez que seleccionemos la opción, se mostraŕa al usuario el listado de las notas de ingreso generadas por el sistema.

![listado_solicitud_salida](imagenes/listado_solicitudes_salida.png  "Listado de solicitudes de salida")

Dentro de este listado el usuario encontrará una opciónque le permitirá buscar solicitudes en diferentes estados, la opción para ver detalladamente la solicitud de salida y la opción 'Nueva solicitud' que permite crear nuevas solicitudes de salida.

Una vez seleccionada la opción 'Nueva solicitud' el sistema le mostrará un formulario donde debe registrar los alimentos que esta solicitando para la salida.

![nueva_solicitud_salida](imagenes/nueva_solicitud_salida2.png  "Nueva solicitud de salida")

Solo podrá llenar la solicitud de salida con alimentos disponibles en su almacén.

Posteriormente deberá entregar los alimentos solicitados, presionando el botón 'entregar producto' donde se habilitarán las opciones de 'asignar producto' de cada uno de los alimentos solicitados.

![entrega_solicitud_salida](imagenes/entrega_solicitud_salida.png  "Entrega de la solicitud de salida")

![asignar_alimentos](imagenes/asignar_alimentos.png  "Asignar productos")

Una vez concluida la asignación de producto se procederá aceptar la entrega y se consolidará la salida de almacenes.

![entrega_solicitud_salida](imagenes/entrega_solicitud_salida2.png  "Entrega de la solicitud de salida")

## 4 Traspasos ##
Los traspasos son entradas y salidas de alimentos  que se realizan entre almacenes ya sean de la misma distribuidora o de otras distribuidoras.

### 4.1 Solicitud de traspaso ###
Esta se realiza desde el almacén que se quiere que ingresen alimentos de otro almacén es decir del almacén destino.
Para realizar una solictud de traspaso debe elegir la opción traspasos.

![menu_traspasos](imagenes/menu_traspasos.png  "Menu de traspasos")

Una vez presionada la opción de traspasos el sistema mostrará la solicitud de traspaso.

![nuevo_traspaso](imagenes/nuevo_traspaso.png  "Nueva solicitud de traspaso")

El usuario podrá llenar la solicitud de los alimentos que quiere que le traspasen a su almacén.

![ver_traspaso](imagenes/ver_traspaso.png  "Ver solicitud de traspaso")

Posteriormente la solicitud de traspaso será enviada al encardago del almacé a quien se le solicita el traspaso es decir el almacén origen.

### 4.2 Entrega de traspaso ###

El encargado del almacén origen en su bandeja de solicitudes de salida podrá ver las solicitudes que le llegaron.

![listado_traspasos](imagenes/listado_traspasos.png  "Listado de traspasos solicitados")

Una vez seleccionada la solicitud de traspaso que se debe atender se procederá a la entrega del traspaso.

![entrega_traspaso](imagenes/entrega_traspaso.png  "Entrega de alimentos a la solicitud de traspasos")

![entrega_traspaso2](imagenes/entrega_traspaso2.png  "Entrega de alimentos a la solicitud de traspasos")

Finalmente se consolidará la entrega del traspaso.

![ver_traspaso2](imagenes/ver_traspaso2.png  "Ver solicitud de traspasos")

### 5. Peticiones ###

Para la entrega del subsidio a la madre debe elegir la opción 'Peticiones'.

![menu_peticiones](imagenes/menu_peticiones.png  "Menú peticiones")

Una vez seleccionada la opción, el usuario visualizará el listado de madres al que se debe atender. Este listado es alimentado por el sistema de atención a las madres del sistema de subsidios mediante un servicio web.

![listado_peticiones](imagenes/listado_peticiones.png  "Menú peticiones")

En la parte derecha de este listado se encuentra el botón 'atender' de cada una de las personas para atender, para proceder con la atención el usuario debe presionar dicho botón.

![atender_peticion](imagenes/atender_peticion.png  "Atender petición")

En la ventana el usuario deberá registrar los productos que van siendo entregados a la madre. los productos que han sido entregados son marcados con color verde y se actualizará el estado de 'Espera' a 'Listo'.

![entrega_peticion](imagenes/entrega_peticion.png  "Entrega petición")

Una vez concluida la entrega de todos los productos se habilitará el botón 'Guardar Salida'.

![guardar_peticion](imagenes/guardar_peticion.png  "Guardar salida")

El sistema pedirá la confirmación.

![confirmacion_salida](imagenes/confirmacion_salida.png  "Confirmación de salida")

Se debe aceptar la salida para atender a la siguiente persona que esta en espera en el listado de peticiones.
