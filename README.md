# Laboratorio-03---WEB

Pregunta 10.
 ¿Porqué cambia el posicionamiento de las cajas internas al div principal?, ¿Qué pasa si me solicitan hacer
un cambio en el orden de los elementos pero sin tocar los archivos html y js, será que puedo lograrlo a traves de CSS?
Respuesta: El cambio en el posicionamiento de las cajas internas se debe al uso de Flexbox en el contenedor .box, que por defecto organiza los elementos en fila horizontal, pero al aplicar flex-direction: column, los acomoda verticalmente. Además, es totalmente posible modificar el orden visual de los elementos sin tocar el html y el js, solo con el css se puede, gracias a la propiedad order, que permite reorganizar los hijos del contenedor flex de forma dinámica y precisa, ideal para adaptaciones visuales o requerimientos de diseño sin alterar la estructura original del código.
