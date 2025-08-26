# Semaforo2
Diseño de una base de datos relacional
Due today at 6:30 PM
•
Closes today at 6:30 PM
Instructions
Un semáforo inteligente es un sistema de control de tráfico vehicular conectado a Internet, capaz de adaptar el comportamiento del semáforo basándose en la información recopilada por sensores, dispositivos periféricos y sistemas de vídeo.


En la intersección, los semáforos inteligentes tienen el mismo aspecto que los semáforos convencionales, salvo por elementos de hardware adicionales como sensores IoT o cámaras de CCTV conectadas. En el back end, los sistemas de semáforos inteligentes están conectados a una plataforma de gestión de tráfico basada en algoritmos predictivos para ajustar dinámicamente las señales de tráfico [1].


Como parte de la iniciativa de campus inteligente de la Universidad de Sonora, nos estamos enfocando en la implementación de semáforos inteligentes en intersecciones clave del campus. El objetivo principal de este proyecto es abordar la congestión del tráfico durante las horas pico y garantizar que se priorice la movilidad peatonal y la accesibilidad para las personas con discapacidades. Se propone la implementación de un sistema para prueba de concepto basado en la arquitectura propuesta por Zantout [2]. 


Su contribución consistirá en diseñar el esquema de una base de datos relacional qué permita almacenar los datos generados por los semáforos inteligentes para qué la plataforma de gestión de tráfico pueda:

Priorizar la movilidad peatonal, ciclistas y transporte público.

Proporcionar controles especiales para los vehículos de servicios de emergencia.

Gestión de los espacios de estacionamiento.

Analizar los movimientos de los vehículos en las intersecciones para detectar accidentes o infracciones.

Prevención temprana de congestionamiento.


Considerar qué la base de datos se va implementar en un servidor Postgresql. Como referencia para el diseño de bases de datos relacionales puede consultar [3]. 


Definir los requerimientos.

Identificar elementos de datos clave: Enumerar los tipos de datos que generarán los semáforos inteligentes.

Determinar relaciones: Considerar cómo estos elementos de datos se relacionan entre sí. Por ejemplo, ¿cómo se relaciona el estado de una señal de tráfico con el recuento de vehículos o los movimientos de peatones?

Crear un diccionario de datos. Este permite documentar que representa cada objeto que se va almacenar en la base de datos.

Diseñar el esquema relacional

Crear un diagrama: Utilice alguna herramienta como draw.io, Lucidchart, Miro, MS Visio para representar visualmente las tablas y sus relaciones. Esta actividade es opcional, pero consideramos que le puede ser de utilidad como actividad de aprendizaje.

Definir claves primarias y externas: identifique claramente las claves principales para cada tabla y establezca relaciones de claves externas para mantener la integridad de los datos.

Implementar el esquema en PostgreSQL

Crear tablas: Escribir un script de comandos SQL para crear las tablas basadas en su esquema o bien utilizar la interfaz de PgAdmin. Asegúrese de definir los tipos de datos adecuados para cada atributo.

Establecer relaciones: use restricciones de clave externa para aplicar relaciones entre tablas.
