# PreEntrega2_ArribillagaMarcos
Pre-entrega del proyecto final para curso JavaScript


# Proyecto final
El proyecto final será sobre la compra de pasajes de aviones, en el mismo se darán las distintas opciones al usuario, con el lugar de partida y lugar de destino.
Los distintos métodos de pago (efectivo, débito o crédito), y el costo final del mismo. También se darán detalles de la compra como el impuesto país y demas detalles
que se mostrarán a la hora de emitirse el "precio final" del producto adquirido.

# PreEntrega1
Esta preentrega constará de un simulador interactivo en el que el usuario podrá elegir entre 3 destinos con 3 precios diferentes, según la elección del usuario se mostrará un menú con los métodos de pago. En el caso de que el usuario ingrese una elección incorrecta, se volverá a mostrar las opciones hasta que elija una que sea correcta. Los menúes se muestran al usuario por medio de la herramienta Console.log() y la solicitud de datos se adquiere mediante prompts. A lo ultimo se colocó una opción para permitirle volver a comprar pasajes al usuario, en caso de que no quiera, pulsará 'N' en caso de que quiera comprar pasajes nuevamente pulsará 'S', en caso de que sea otra letra se volverá a solicitar este menú al usuario advirtiendo por console.log() que la opción ingresada fue incorrecta. Si el usuario accede a comprar pasajes nuevamente, el precio no se acumulará con los pasajes comprados anteriormente (en esta primera versión de la preentrega).



# PreEntrega2
Esta pre-entrega constará de el mismo simulador anteriormente presentado, con el agregado de que el usuario podrá agregar su nombre, apellido, fecha de nacimiento, nacionalidad y DNI. Luego de esto, se le solicitará la cantidad de pasajes a comprar y una lista de origenes y destinos posibles. En función del origen y destino elegido, será el precio del vuelo, el cual tendrá su valor en dolares, y se le aplicará el impuesto país del 30% y la percepción de ganancias del 35%. A su vez, tendrá la opción de pagar con tarjeta, el mismo tendrá un interés distinto según la cantidad de cuotas que se paguen, este interés se formará por numeros aleatorios en determinado rango. Los objetos creados serán el objeto cliente, que tendrá la información personal correspondiente a cada persona, el objeto viaje que tendrá los origenes y destinos que se podrán solicitar así como su precio final según el tipo de pago, y por ultimo el objeto tarjeta, que tendrá los datos asociados a la tarjeta de crédito o débito correspondiente (no se podrá pagar en efectivo, ni $ ni USD).