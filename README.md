# EquipoKBI
Proyecto Tienda

| Nombre                    | Número de control |
|---------------------------|---------------------------|
| Ivana Rocha Campos        | 1222100460                |
| Kevin Conejo Salazar      | 1222100714                |
| Brayan Yohani Morales Narváez | 1222100518            |

Carta de liberación del proyecto (Esta parte no ha sido realizada pues aun no hemos liverado el producto)
Dirigida al Docente
Debe de expresar las funcionalidades que tiene el proyecto
Nombres de los integrantes que participaron en el proyecto
Es una imagen jpg o png.
Firmada por el empresario o docente ageno a la UTNG, agradeciendo la contribución de la UTNG.
Hoja membretada (Logo de la empresa, dirección y contacto)

### Lista del Hardware utilizado

| ID  | Componente                                              | Descripción                                                  | Imagen | Cantidad | Costo total |
|-----|---------------------------------------------------------|--------------------------------------------------------------|--------|----------|-------------|
| 1   | Raspberry Pi 4B (o superior) con adaptador de corriente | Mini ordenador de una sola placa con adaptador de corriente | ![Raspberry Pi](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/24e5d376-8092-4242-99c7-29ab949d88ec) | 1 | $347 |
| 2   | Sensor de Sonido                                        | Sensor para detectar la presencia de sonidos en su entorno  | ![Sensor de Sonido](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/3a0c5bd5-4cbc-4d20-b725-8813c7723cea) | 4 | $118 |
| 3   | Sensor de Proximidad                                   | Sensor para detectar la presencia o la cercanía de un objeto| ![Sensor de Proximidad](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/d356107c-e4c8-4d7d-930f-0b4dcbc8065e) | 4 | $70 |
| 4   | Sensor de Alejamiento                                  | Sensor para detectar la distancia entre el sensor y un objeto| ![Sensor de Alejamiento](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/37629584-e26d-49a4-9c22-b225ca632bc2) | 4 | $108 |
| 5   | Sensor de Movimiento                                   | Sensor para detectar movimiento                              | ![Sensor de Movimiento](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/3003ce48-390d-47e6-84b9-e7ee1aa5e135) | 4 | $243 |
| 6   | LED                                                     | Dispositivo de iluminación                                   | ![LED](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/d1f311c5-ac3a-4c9b-a291-13ba9c4d0113) | 4 | $60 |
| 7   | Motor                                                   | Dispositivo para generar movimiento                           | ![Motor](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/d7b7ff47-11ed-44fb-be7e-1a354dff5761) | 4 | $25 |
| 8   | ESP32 (o módulo compatible)                             | Microcontrolador para comunicación inalámbrica               | ![ESP32](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/352e5ef4-a15d-44ed-9990-08e154238b29) | 1 | $120 |
| 9   | Cables, resistencias y otros componentes                | Componentes necesarios para conexiones                       | ![Componentes](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/54a1bc3f-8833-41eb-a842-2364c2408a1a) | 2 | $289 |




| ID | Software     | Versión | Tipo                               |
|----|--------------|---------|------------------------------------|
| 1  | Node-RED     | 2.1.0   | Entorno de programación visual     |
| 2  | MQTT         | 3.1.1   | Protocolo de mensajería ligero     |
| 3  | MicroPython  | 1.15    | Lenguaje de programación optimizado para microcontroladores |
| 4  | Raspbian     | 11      | Sistema operativo compatible con Raspberry Pi |
| 5  | Thonny       | 3.3.3   | IDE compatible con ESP32 y MicroPython |
| 6  | uPyCraft     | 1.1.0   | IDE compatible con ESP32 y MicroPython |

Conexiones:
- Sensores y actuadores conectados a la Raspberry Pi a través de los puertos GPIO.
- ESP32 conectado a la Raspberry Pi a través de una conexión inalámbrica (Wi-Fi o Bluetooth).
- Configuración de los dispositivos para la comunicación a través del protocolo MQTT.


## Visión de Producto 
## Público:
El público objetivo para el producto de la tienda de zapatos son los consumidores de calzado, 
que pueden incluir hombres, mujeres y niños de diversas edades y gustos. Además, también 
puede abarcar a personas interesadas en regalar calzado, así 
como a compradores que buscan una amplia variedad de estilos y opciones.

## Problema o necesidad:
La problemática que enfrenta la tienda de zapatos es la seguridad, específicamente 
el riesgo de robo de inventario y la intrusión no autorizada en el establecimiento.
Esta situación genera preocupación tanto para los propietarios como para los clientes, ya que 
la falta de medidas de seguridad adecuadas puede resultar en pérdidas materiales y afectar la 
sensación de seguridad en el lugar de compra. Además, la falta de seguridad puede impactar negativamente 
la reputación de la tienda y disminuir la confianza de los clientes en el establecimiento. Por lo tanto,
la necesidad de implementar medidas efectivas para proteger el inventario y garantizar la seguridad tanto 
de la propiedad como de los clientes es una prioridad clave para el negocio.

## Solución:
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

## Visión
Para el cliente que busca una experiencia de compra personalizada y eficiente en una tienda de calzado, "Zapatería ComfortFit" ofrece un enfoque innovador utilizando tecnología IoT. A diferencia de las grandes cadenas de tiendas que pueden carecer de atención personalizada, nuestra solución IoT, "SmartFoot", transforma la experiencia de compra.

SmartFoot integra una red de sensores inteligentes en la tienda y en el calzado mismo. Estos sensores recopilan datos en tiempo real sobre la interacción del cliente con los productos y el entorno de la tienda. Por ejemplo, los sensores en el calzado pueden medir la comodidad y el ajuste, mientras que los sensores en la tienda pueden monitorear el tráfico de clientes y las condiciones ambientales.

Utilizando análisis avanzados de datos, SmartFoot proporciona recomendaciones personalizadas a los clientes basadas en sus preferencias de estilo, tamaño y comodidad. Además, los clientes pueden acceder a información detallada sobre cada producto, incluyendo características, disponibilidad de tallas y precios, a través de una aplicación móvil o una pantalla interactiva en la tienda.

Nuestra plataforma IoT mejora la eficiencia operativa de la tienda al optimizar el inventario, predecir la demanda de productos y mejorar la gestión del personal. En última instancia, "Zapatería ComfortFit" ofrece una experiencia de compra única y satisfactoria, diferenciándose de las tiendas convencionales mediante la integración de tecnología IoT para ofrecer un servicio personalizado y de alta calidad a sus clientes.

## Conexión y Funcionalidad 
| ID  | Historia de Usuario                            | Prioridad | Estimación | Como Probarlo   | Responsable |
|-----|-----------------------------------------------|-----------|------------|-----------------|-------------|
| 1   | Conexiones del circuito utilizando Wokwi    | Alta      | 2 horas    | Verificar las conexiones visuales en el software y confirmar que coinciden con el diseño del circuito. | [Nombre del Responsable] |
| 2   | Configuración de la Raspberry Pi y ESP32 para la comunicación inalámbrica | Alta | 3 horas | Verificar la conexión entre la Raspberry Pi y el ESP32 a través de la comunicación inalámbrica. | [Nombre del Responsable] |
| 3   | Implementación de funcionalidades específicas en Raspberry Pi y ESP32 | Media | 5 horas | Verificar que las funcionalidades diseñadas se ejecuten correctamente en ambas plataformas. | [Nombre del Responsable] |

Nota: Las estimaciones de tiempo son aproximadas y pueden variar según la complejidad de cada tarea y la experiencia del responsable.


## Prototipo dibujo

| Concepto | Prototipo |
|----------|-----------|
| Uso      | ![WhatsApp Image 2024-02-12 at 9 14 12 PM](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/0e9b5acc-e60c-47f5-97bc-aee0f3a0d0a8.png) |
| Aparato  | ![WhatsApp Image 2024-02-12 at 9 32 07 PM](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/1ca3decb-5d76-49ba-8366-4e07bc8e1905.png) |

