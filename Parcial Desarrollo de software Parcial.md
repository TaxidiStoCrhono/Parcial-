# Mateo Mejia Guerra T00061392

## Identificar y listar los requerimientos funcionales, No funcionales, requerimientos de usuario (contemplas las características de UX) y requerimientos del sistema.
### Requerimientos funcionales
- El sistema debe poder permitir el acceso a los recursos literarios virtuales 
- El sistema debe permitir el préstamo bicicletas
- El sistema debe poder permitir pagar la comida sin necesidad de efectivo 
- El sistema debe poder permitir pagar material de papelería sin necesidad de efectivo
- El sistema debe poder permitir prestar computadoras
- El sistema deberá permitir a los estudiantes hacer estas actividades desde cualquier lugar, utilizando dispositivos electrónicos como smartphones
### Requerimientos no funcionales
- El sistema deberá cumplir con estándares de seguridad de la información
- El sistema debe tener un uso de credenciales para su uso
- El sistema debe notificar a los estudiantes cuando su prestamo esta por vencer
- El sistema debe dejar a los estudiantes renovar los artículos hasta cierto numero de veces 
### Requerimientos de usuario 
- El sistema debe poder permitir a los estudiantes buscar libros según el nombre
- El sistema debe mostrar a los estudiantes si hay bicicletas disponibles
- El sistema debe mostrara los estudiantes el inventario disponible de la papelería
- El sistema puede mostrar a los estudiantes si hay computadores disponibles
- El sistema debe poder permitir a los estudiantes pagar comida y papelería por medio de un código QR sin dinero en efectivo 
### Requerimientos de sistema 
- El sistema debe poder manejar los libros agregados a la biblioteca virtual
- El sistema puede manejar los prestamos de bicicletas. Debe poder manejar el tiempo de préstamo, ya sea de varios días u horas, así como su devolución
- El sistema debe mostrar el menú de comida actual, así como sus precios. s. Y al finalizar la compra mostrarles el precio a pagar junto con el QR
- El sistema debe mostrar el inventario actual de la papelería, así como sus precios. Dejar que los estudiantes agreguen utensilios a un carrito de compras. Y al finalizar la compra mostrarles el precio a pagar junto con el QR
- El sistema puede manejar los prestamos de los computadores. Debe poder manejar el tiempo de préstamo, ya sea de varios días u horas, así como su devolución
- El sistema debe ser compatible para vistas tanto en teléfono como en computadora 

## De los anteriores requerimientos, debe escoger tres de cada tipo de requerimientos y describirlos en detalle utilizando la plantilla 
#### Funcionales

| ID          | R1.1                                                                               |
| ----------- | ---------------------------------------------------------------------------------- |
| Nombre      | Prestamos de bicicletas                                                            |
| Descripcion | Los usuarios tiene la capacidad de prestar una bicicleta por un tiempo determinado |
| Entrada     | Nombre, Identificación estudiantil, horas de prestamo, correo                      |
| Salida      | ID de bicicleta asignada, hora o fecha de devolucion                               |
| Excepciones | ninguna                                                                            |
| Autor       | Mat                                                                                |
| Prioridad   | Alta                                                                               |

| ID          | R1.2                                                                                   |
| ----------- | -------------------------------------------------------------------------------------- |
| Nombre      | Prestamos de computadores                                                              |
| Descripcion | Los usuarios tiene la capacidad de prestar una computadora a por un tiempo determinado |
| Entrada     | Nombre, Identificación estudiantil, horas de prestamo, correo                          |
| Salida      | ID de computadora, hora o fecha de devolucion                                          |
| Excepciones | ninguna                                                                                |
| Autor       | Mat                                                                                    |
| Prioridad   | Alta                                                                                   |

| ID          | R1.3                                                                       |
| ----------- | -------------------------------------------------------------------------- |
| Nombre      | Pago de alimentos                                                          |
| Descripcion | Los usuarios tiene la capacidad de pagar sin necesidad de dinero su comida |
| Entrada     | Nombre, Identificación estudiantil, Comida                                 |
| Salida      | Precio a pagar, QR                                                         |
| Excepciones | ninguna                                                                    |
| Autor       | Mat                                                                        |
| Prioridad   | Alta                                                                       |
#### No funcionales
| ID          | R2.1                                                                                    |
| ----------- | --------------------------------------------------------------------------------------- |
| Nombre      | Sistema de credenciales                                                                 |
| Descripcion | Para acceder a la plataforma los usuarios deben ingresar sus credenciales estudiantiles |
| Entrada     | Nombre, Identificación estudiantil, teléfono                                            |
| Salida      | Registro en la plataforma                                                               |
| Excepciones | ninguna                                                                                 |
| Autor       | Mat                                                                                     |
| Prioridad   | Media                                                                                   |

| ID          | R2.2                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------- |
| Nombre      | Sistema de notifciacion                                                                                             |
| Descripcion | Los usuarios deberán recibir una notificación cuando su préstamo esta por vencer, esta notificación será por correo |
| Entrada     | Articulo prestado, horas de prestado, correo                                                                        |
| Salida      | Notificación de correo                                                                                              |
| Excepciones | ninguna                                                                                                             |
| Autor       | Mat                                                                                                                 |
| Prioridad   | Media                                                                                                               |
|             |                                                                                                                     |

| ID          | R2.3                                                                                                 |
| ----------- | ---------------------------------------------------------------------------------------------------- |
| Nombre      | renovación de articulos                                                                              |
| Descripcion | La plataforma debe ser capaz de renovar hasta cierto numero de veces u horas los artículos prestados |
| Entrada     | Nombre, Identificación estudiantil, horas de préstamo                                                |
| Salida      | Nueva fecha de devolución                                                                            |
| Excepciones | ninguna                                                                                              |
| Autor       | Mat                                                                                                  |
| Prioridad   | Alta                                                                                                 |

#### Usuario 

| ID          | R3.1                                                                       |
| ----------- | -------------------------------------------------------------------------- |
| Nombre      | Disponibilidad de bicicletas                                               |
| Descripcion | El sistema debe poder mostrar si hay bicicletas disponibles a los usuarios |
| Entrada     | Numero de bicicletas prestadas                                             |
| Salida      | Disponibilidad o no disponibilidad                                         |
| Excepciones | ninguna                                                                    |
| Autor       | Mat                                                                        |
| Prioridad   | Alta                                                                       |

| ID          | R3.2                                                                         |
| ----------- | ---------------------------------------------------------------------------- |
| Nombre      | Disponibilidad de computadoras                                               |
| Descripcion | El sistema debe poder mostrar si hay computadoras disponibles a los usuarios |
| Entrada     | Numero de computadoras prestada                                              |
| Salida      | Disponibilidad o no disponibilidad                                           |
| Excepciones | ninguna                                                                      |
| Autor       | Mat                                                                          |
| Prioridad   | Alta                                                                         |

| ID          | R3.3                                                                                            |
| ----------- | ----------------------------------------------------------------------------------------------- |
| Nombre      | Disponibilidad de papelería                                                                     |
| Descripcion | El sistema debe poder mostrar que articulos hay en papelería que están disponibles para comprar |
| Entrada     | Inventario de papaleria                                                                         |
| Salida      | Disponibilidad o no disponibilidad de los productos                                             |
| Excepciones | ninguna                                                                                         |
| Autor       | Mat                                                                                             |
| Prioridad   | Alta                                                                                            |
#### Sistema

| ID          | R4.1                                                                                                                                                                                                                                                  |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nombre      | Manejo de prestamos: bicicleta                                                                                                                                                                                                                        |
| Descripcion | El sistema debe poder manejar el préstamo de las bicicletas, cuantas hay disponibles cuantas han sido prestadas, a quien han sido prestadas y por cuanto tiempo, el estado en que fue prestada, así como multas si hay algún daño, ID de la bicicleta |
| Entrada     | Numero de bicicletas disponibles y ocupadas, nombre del prestamista, tiempo de prestación, estado de la bicicleta, ID de la bicicleta                                                                                                                 |
| Salida      | Prestada o no?, ID de la bicicleta prestada, Estado de la bicicleta prestada, tiempo de devolucion                                                                                                                                                    |
| Excepciones | Si la bicicleta esta en mal estado                                                                                                                                                                                                                    |
| Autor       | Mat                                                                                                                                                                                                                                                   |
| Prioridad   | Alta                                                                                                                                                                                                                                                  |

| ID          | R4.2                                                                                                                                                                                                                                                       |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nombre      | Manejo de prestamos: computadoras                                                                                                                                                                                                                          |
| Descripcion | El sistema debe poder manejar el préstamo de las computadoras, cuantas hay disponibles, cuantas han sido prestadas, a quien han sido prestadas y por cuanto tiempo, el estado en que fue prestada, así como multas si hay algún daño, ID de la computadora |
| Entrada     | Numero de computadoras disponibles y ocupadas, nombre del prestamista, tiempo de prestación, estado de la computadora, ID de la computadora                                                                                                                |
| Salida      | Prestada o no?, ID de la computadora prestada, estado de la computadora prestada, tiempo de devolución                                                                                                                                                     |
| Excepciones | Si la computadora esta en mal estado                                                                                                                                                                                                                       |
| Autor       | Mat                                                                                                                                                                                                                                                        |
| Prioridad   | Alta                                                                                                                                                                                                                                                       |

| ID          | R4.3                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------- |
| Nombre      | Manejo de pago por QR                                                                                               |
| Descripcion | El sistema debe poder manejar los pagos de la papelería asi como la comida de la cafetería a través de un código QR |
| Entrada     | Comida, precio                                                                                                      |
| Salida      | QR                                                                                                                  |
| Excepciones | Ninguna                                                                                                             |
| Autor       | Mat                                                                                                                 |
| Prioridad   | Alta                                                                                                                |

## Diagrama de contexto del sistema

![[Diagrama de contexto.png]]

## Diagrama de Casos de Uso
![[Estudiante caso.png]]
## Escoger tres casos de uso y describirlos en detalle tal como la plantilla

| Actores     | Estudiante, Servicio de prestamo de computadora                                                                                                                         |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descripcion | El estudiante puede solicitar el prestamo de una computadora en buen estado para la realización de tareas o para estudiar intensamente durante cierta cantidad de horas |
| Data        | ID de la computadora, estado de la computadora, credenciales del prestador, tiempo de prestacion                                                                        |
| estimulo    | Click en una opcion de la plataforma                                                                                                                                    |
| Respuesta   | Se señala si hay computadoras disponibles y si es asi se procede a preguntar el tiempo de prestamo                                                                      |
| Comentarios | Al final de terminar el tiempo de préstamo y saber las credenciales del estudiante el sistema señala el ID de la computadora a prestar                                  |

| Actores     | Estudiante, Servicio de préstamo de bicicleta                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descripcion | El estudiante puede solicitar el préstamo de una bicicleta en buen estado para la realización de viajes alrededor del campus o para llegar a clases |
| Data        | ID de la bicicleta, estado de la bicicleta, credenciales del prestador tiempo de prestación                                                         |
| estimulo    | Click en una opcion de la plataforma                                                                                                                |
| Respuesta   | Se señala si hay bicicletas disponibles y si es asi se procede a preguntar el tiempo de prestamo                                                    |
| Comentarios | Al final de terminar el tiempo de préstamo y saber las credenciales del estudiante el sistema señala el ID de la bicicleta a prestar                |

| Actores     | Estudiante, Pago QR                                                                                                         |
| ----------- | --------------------------------------------------------------------------------------------------------------------------- |
| Descripcion | El estudiante puede  pagar de forma automática alimentos  u objetos de papelería por medio de la generación de un código QR |
| Data        | Nombre del articulo, Nombre del plato                                                                                       |
| estimulo    | Click en una opción de la plataforma                                                                                        |
| Respuesta   | Se procede a mostrar el codigo QR                                                                                           |
| Comentarios | El QR es un enlace para el pago a una cuenta de dinero especifica de la institución                                         |


