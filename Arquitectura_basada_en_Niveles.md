# Arquitectura basada en Niveles:

Es un conjunto de protocolos y niveles que dan una solución completa a los sistemas de telecomunicaciones o
teleinformática.

El **diseño** de un sistema de comunicación requiere la resolución de muchos y complejos **problemas**:

- **Encaminamiento**: existen diferentes rutas entre el origen y el destino.

- **Direccionamiento**: se requiere un mecanismo para que un proceso en una máquina especifique con quién quiere
comunicarse.

- **Acceso al medio**: es necesario algún mecanismo que controle el orden de transmisión de los interlocutores.

- **Saturación del receptor**: un emisor rápido puede saturar a un receptor lento.

- **Mantenimiento del orden**: algunas redes desordenan los mensajes que envían, por lo que se necesita crear un
mecanismo que le permita volver a ordenador los mensajes en el destino.

- **Control de errores**: debido a que los medios de transmisión son imperfectos, las redes de comunicación de
datos tienen una tasa de error.

- **Multiplexación**: la red puede tener tramos en los que exista un único medio de transmisión.

Para resolver estos problemas, las redes se organizan en capas o niveles para reducir la complejidad del diseño.
Cada capa o nivel se construye sobre su predecesor y cada nivel es responsable de ofrecer servicios al nivel
superior. Con esto tenemos que cada capa tiene su propio protocolo que es homólogo tanto en origen como
destino.
