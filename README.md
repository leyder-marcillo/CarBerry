# CarBerry
Proyecto final Digitales III
Carberry
Objetivo: El objetivo de este proyecto es diseñar y construir un dispositivo móvil  capaz de seguir una línea trazada en el suelo y resolver un laberinto dibujado con cinta negra de manera autónoma. Además, el dispositivo será capaz de recorrer una pista trazada con cinta en el menor tiempo posible. También contara con una interfaz con el usuario utilizando el modulo bluetooth o wifi para manejar el carro de manera manual.
Componentes:
Raspberry Pi Pico W, sensores de Reflexión Infrarrojos, micromotores, batería, chasis , ruedas etc.
Funcionamiento: El dispositivo utilizará los sensores de reflexión infrarrojos para seguir la línea trazada en el suelo. Mediante un algoritmo de control, el Raspberry Pi Pico W procesará la información de los sensores y ajustará la velocidad y dirección de los motores para mantener el dispositivo en la línea.
Para resolver el laberinto, se implementará un algoritmo de búsqueda que permita al dispositivo explorar las diferentes rutas disponibles y encontrar la salida del laberinto además de descartar rutas erráticas. Los sensores de reflexión infrarrojos se utilizarán también para detectar las paredes del laberinto y tomar decisiones sobre la dirección a seguir.
Requisitos funcionales:
Velocidad de Procesamiento: El dispositivo debe procesar los datos de los sensores y ejecutar los algoritmos de control y búsqueda con una velocidad adecuada para mantener un seguimiento fluido de la línea y resolver el laberinto de manera eficiente.
Optimización de Algoritmos y Control: Los algoritmos de búsqueda utilizados para resolver el laberinto deben estar optimizados para minimizar el tiempo de resolución y la cantidad de recursos computacionales requeridos. El algoritmo de control de velocidad para la pista debe ajustar la velocidad del dispositivo de manera precisa y paulatina, manteniendo un movimiento constante y evitando cambios bruscos que puedan afectar la estabilidad del dispositivo.
Interfaz de Usuario y Conectividad: La interfaz de usuario a través de Bluetooth o WiFi debe proporcionar una conexión estable entre el dispositivo móvil y el dispositivo remoto (como un teléfono o una computadora) además la interfaz  debe permitir al usuario controlar fácilmente el dispositivo, iniciar o detener la operación, ajustar la velocidad y acceder a la información relevante del estado del dispositivo, todo ello a través de una interfaz intuitiva y fácil de entender.
Eficiencia energética: El dispositivo debe administrar eficientemente el consumo de energía para maximizar la duración de la batería durante la operación autónoma.




Requisitos no funcionales:
Rendimiento del sistema: El dispositivo debe ser capaz de procesar datos de sensores y ejecutar algoritmos de control y búsqueda de manera eficiente, sin retrasos significativos.
Consumo de recursos del procesador: El sistema debe administrar eficientemente los recursos del procesador y minimizar el uso de la CPU y la memoria para mantener el sistema embebido dentro de las capacidades del MCU.
Tolerancia a errores y robustez del sistema: El sistema debe ser capaz de manejar de manera adecuada y recuperarse de situaciones de error o fallo, como lecturas inconsistentes de sensores, interrupciones temporales de la comunicación inalámbrica.
Consumo de energía: El sistema debe operar con un consumo de energía no superior a 5 vatios.
Escenario.
El escenario será una pista que consiste en dibujar una trayectoria o el laberinto con cinta negra en el caso del laberinto para facilitar el montaje de este escenario la cinta negra representara los pasillos o corredores todos los caminos deben ir sobre una superficie plana como el suelo de un color blanco o similar  para facilitar la lectura de los sensores infrarrojos.  
Costos:
Raspberry Pi Pico W:  $44'000
Sensores de reflexión infrarrojos: $12'000
Micromotores y controlador: $20'000
Chasis y estructura del carro: $20'000 
Batería recargable: $15'000 
Placa de circuito impreso (PCB): $15'000
Componentes electrónicos adicionales (resistencias, capacitores, etc.): $10'000
Herramientas y equipos de prototipado (multímetro, soldador, impresora 3D, etc.): $0
Software de desarrollo (IDE, software de diseño PCB, etc.): $0 
Estimación de costos total: $136'000 pesos colombianos
