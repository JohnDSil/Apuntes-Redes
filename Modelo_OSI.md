# Modelo OSI:

[Modelo](img/modelo osi.png)

Es el marco de referencia para la definición de arquitecturas de interconexión de sistemas de comunicaciones.
La mayoría de los fabricantes relacionan sus productos con este modelo ya que permite que los usuarios vean las
funciones de red que se producen en cada capa.

Este modelo está formado por **siete capas** (aplicación, presentación, sesión, transporte, red, enlace y física) y cada
capa tiene su propia función. Con este modelo la comunicación se divide en partes más pequeñas y sencillas,
normaliza los componentes de la red. Podemos entenderlo como que los problemas de la comunicación se divide
en siete problemas más sencillos de solucionar.

Cada capa individual del modelo OSI tiene un conjunto de **funciones** que debe realizar para que los paquetes
puedan viajar de origen a destino.

- **Interfaz**: cada nivel o capa se relaciona con la inmediatamente superior e inferior mediante el concepto de
interfaz.

- **Encapsulamiento**: es el proceso que hace que cada capa añada su informe a los datos que mande a la siguiente
capa.

- **Segmentación**: es el proceso contrario al encapsulamiento. Se divide una red en varios segmentos, cada uno
funciona como pequeña red propia.

Las funciones de las capas o niveles del modelo OSI son:

- **Nivel Físico**: se encarga de la transición de bits por un medio de transmisión, ya sea un medio guiado (cables) o
no guiado (inalámbrico). Esta capa define el medio de transmisión ,no interpreta la información, solo transmite
ceros (0) y unos (1).
**PDU: bits**.
  
- **Nivel Enlace**: envía tramas de datos entre estaciones de una misma red. Trabaja en la capa de red local. Su
función es conseguir que exista una transmisión fiable solventando los problemas de ruido que pueda haber en la
red a nivel de bits. Otra función es el control de flujo para evitar la saturación el equipo receptor. Sistema sencillo
(para y espera; emisor envía una trama y espera que el receptor confirme la recepción para enviar otra).
**PDU: trama**.

- **Nivel Red**: se encarga del encaminamiento de paquetes entre el origen y el destino atravesando tantas redes
intermedias como sean necesarias. Los datos se fragmentan en paquetes y cada uno de ellos se envía de manera
independiente. Este nivel se encarga de mandar los paquetes por el camino mas adecuado para que lleguen en el
menor tiempo posible y evitando a la vez que las redes se lleguen a saturar. El router es el que se encarga de estas
tareas. Esta capa ofrece como servicio a los niveles superiores la identificación de la procedencia y el destino de
los paquetes de datos y utiliza el nivel inferior para que los organice de manera efectiva.
**PDU: paquete**.
  
- **Nivel Transporte**: corazón del modelo OSI, ofrece mecanismo fiables para el intercambio de datos.
   - Servicio de detección de errores que aseguran la integridad de datos así como los niveles de calidad de los
servicios.

   - Ordenar la información , se encarga de eliminar las tramas repetidas y ponerlas todas en el orden correcto. Se
encarga de subsanar posibles diferencias en la red.

   - Realiza una conexión de extremo a extremo entre los niveles de transporte origen y destino.
     
**PDU: datagrama o segmento**.

- **Nivel Sesión**: proporciona funciones de organización para que las aplicaciones dialoguen entre sí. El diálogo se
realiza a través de una conexión que se llama sesión. **PDU: datos**.
  
- **Nivel Presentación**: se encarga de la presentación de los datos y de traducir a un formato universal como por
ejemplo el **ASCII**. **PDU: datos**.

- **Nivel Aplicación**: enlazadirectamente con el usuario.
**PDU: datos**.
