# EquipoKBI
Proyecto Tienda

## Integrantes:
|-|-|-|
| Ivana Rocha Campos |1222100460|
| Kevin Conejo Salazar |  |1222100714| 
| Brayan Yohani Morales Narváez| |1222100518|

Carta de liberación del proyecto (Esta parte no ha sido realizada pues aun no hemos liverado el producto)
Dirigida al Docente
Debe de expresar las funcionalidades que tiene el proyecto
Nombres de los integrantes que participaron en el proyecto
Es una imagen jpg o png.
Firmada por el empresario o docente ageno a la UTNG, agradeciendo la contribución de la UTNG.
Hoja membretada (Logo de la empresa, dirección y contacto)

###Lista del Hardware utilizado
| ID  | Componente                                              | Descripción                                                  | Imagen | Cantidad | Costo total |
|-----|---------------------------------------------------------|--------------------------------------------------------------|--------|----------|-------------|
| 1   | Raspberry Pi 4B (o superior) con adaptador de corriente | Mini ordenador de una sola placa con adaptador de corriente | () | 1        | $XX         |
| 2   | Sensor de Sonido                                        | Sensor para detectar la presencia de sonidos en su entorno    | (https://avsuwzdjuo.cloudimg.io/v7/_cs_/2021/05/60aba2b80453c/ABX00019.png?w=400&org_if_sml=1) | 4| $118      |
| 3   | Sensor de  Proximidad                                   | Sensor para  detectar la presencia o la cercanía de objeto    | (https://tiendadeelectronica.mx/wp-content/uploads/2022/06/sensor-de-proximidad-por-infrarrojo.jpg) | 4 | $70 |
| 4   | Sensor de  Alejamiento                                  | Sensor para detecta la distancia entre el sensor y un objeto | (https://m.media-amazon.com/images/I/311mU7DJggL._AC_.jpg) | 4        | $108         |
| 5   | Sensor de movimiento                                    | Sensor para detectar movimiento                              | (https://m.media-amazon.com/images/I/41yzyHkyT6L._SY445_SX342_QL70_ML2_.jpg) | 4        | $243         |
| 6   | LED                                                     | Dispositivo de iluminación                                   | [(https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/LEDES.jpg/300px-LEDES.jpg) | 4        | $60|
| 7   | Motor                                                   | Dispositivo para generar movimiento                           | (https://www.steren.com.mx/media/catalog/product/cache/bb0cad18a6adb5d17b0efd58f4201a2f/image/20367551d/mini-motor-de-corriente-directa.jpg) | 4| $25|
| 8 | ESP32 (o módulo compatible)                            | Microcontrolador para comunicación inalámbrica               | [(https://avsuwzdjuo.cloudimg.io/v7/_cs_/2021/05/60aba2b80453c/ABX00019.png) | 1 | $120         |
| 9  | Cables, resistencias y otros componentes                | Componentes necesarios para conexiones                        | (https://framad.es/wp-content/uploads/2021/03/componentes-cables-electricos.jpeg) |2| $289|



###Lista de Software utilizado
| ID  | Software    | Versión | Tipo        |
|-----|-------------|---------|-------------|
| 1   | Node-RED    | -       | Entorno de programación visual |
| 2   | MQTT        | -       | Protocolo de mensajería ligero |
| 3   | MicroPython | -       | Lenguaje de programación optimizado para microcontroladores |
| 4   | Raspbian    | -       | Sistema operativo compatible con Raspberry Pi |
| 5   | Thonny      | -       | IDE compatible con ESP32 y MicroPython |
| 6   | uPyCraft    | -       | IDE compatible con ESP32 y MicroPython |

Conexiones:
- Sensores y actuadores conectados a la Raspberry Pi a través de los puertos GPIO.
- ESP32 conectado a la Raspberry Pi a través de una conexión inalámbrica (Wi-Fi o Bluetooth).
- Configuración de los dispositivos para la comunicación a través del protocolo MQTT.


###Visión de Producto 
##Público:
El público objetivo para el producto de la tienda de zapatos son los consumidores de calzado, 
que pueden incluir hombres, mujeres y niños de diversas edades y gustos. Además, también 
puede abarcar a personas interesadas en regalar calzado, así 
como a compradores que buscan una amplia variedad de estilos y opciones.

##Problema o necesidad:
La problemática que enfrenta la tienda de zapatos es la seguridad, específicamente 
el riesgo de robo de inventario y la intrusión no autorizada en el establecimiento.
Esta situación genera preocupación tanto para los propietarios como para los clientes, ya que 
la falta de medidas de seguridad adecuadas puede resultar en pérdidas materiales y afectar la 
sensación de seguridad en el lugar de compra. Además, la falta de seguridad puede impactar negativamente 
la reputación de la tienda y disminuir la confianza de los clientes en el establecimiento. Por lo tanto,
la necesidad de implementar medidas efectivas para proteger el inventario y garantizar la seguridad tanto 
de la propiedad como de los clientes es una prioridad clave para el negocio.

##Solución:
la seguridad es una prioridad clave para proteger el inventario y garantizar 
la tranquilidad de los propietarios y clientes. El proyecto de sistema de alarma 
antirrobo con cámara integrada ofrece una solución innovadora y efectiva para abordar 
estas preocupaciones en una tienda de zapatos.

El sensor de movimiento es capaz de detectar cualquier movimiento no autorizado 
dentro del área protegida de la tienda, la presencia visible del sistema de alarma
 y la cámara de seguridad actúa como un disuasivo efectivo contra los ladrones potenciales. 
Sabiendo que están siendo monitoreados y que sus acciones están siendo registradas, 
es menos probable que los delincuentes se arriesguen a cometer un robo en la tienda.

Con este sistema de seguridad en su lugar, los propietarios de la tienda y los clientes pueden
 tener la tranquilidad de saber que se están tomando medidas proactivas para proteger el establecimiento
 y sus pertenencias. Esto fomenta un entorno de compra seguro y confiable, lo que a su vez puede mejorar
 la satisfacción del cliente y la reputación de la tienda.{

### Visión
PARA el comprador de calzado que valora la experiencia de compra en una tienda física,
QUIEN busca encontrar el par perfecto que refleje su estilo y ajuste cómodamente,
EL "Zapatería ComfortFit" QUE ES UNA tienda de calzado física,
QUE ofrece un servicio personalizado y experto para garantizar el ajuste perfecto y la satisfacción del cliente,
A DIFERENCIA DE las grandes cadenas de tiendas donde la atención personalizada puede ser limitada,
NUESTRO PRODUCTO se destaca por nuestro enfoque en la atención al cliente, donde nuestros expertos en calzado brindan asesoramiento 
individualizado y se aseguran de que cada cliente salga con un par de zapatos que se adapte a sus necesidades y preferencias específicas.


### Conexión y Funcionalidad 
| ID  | Historia de Usuario                            | Prioridad | Estimación | Como Probarlo   | Responsable |
|-----|-----------------------------------------------|-----------|------------|-----------------|-------------|
| 1   | Conexiones del circuito utilizando Wokwi    | Alta      | 2 horas    | Verificar las conexiones visuales en el software y confirmar que coinciden con el diseño del circuito. | [Nombre del Responsable] |
| 2   | Configuración de la Raspberry Pi y ESP32 para la comunicación inalámbrica | Alta | 3 horas | Verificar la conexión entre la Raspberry Pi y el ESP32 a través de la comunicación inalámbrica. | [Nombre del Responsable] |
| 3   | Implementación de funcionalidades específicas en Raspberry Pi y ESP32 | Media | 5 horas | Verificar que las funcionalidades diseñadas se ejecuten correctamente en ambas plataformas. | [Nombre del Responsable] |

Nota: Las estimaciones de tiempo son aproximadas y pueden variar según la complejidad de cada tarea y la experiencia del responsable.


##Prototipo dibujo
