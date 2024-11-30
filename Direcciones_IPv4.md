# Direcciones IPv4:

- La longitud máxima es de 4 bytes (32 bits).
  
- Está formado por un sistema de numeración decimal, separados por puntos (**x.y.z.v**).
  
Las direcciones IPv4 están formadas por dos partes:

- Una parte es el **identificador de red** (netid). Todas las máquinas pertenecientes a la misma red tiene el mismo
valor de netid.

- Otra parte es el **identificador de host** (hostid). Cada host tiene un valor distinto dentro de la red.
  
Se pueden clasificar en dos grupos basándonos en los esquemas de direccionamiento:

- **Basado en Clases (classfull)**: están divididas en 5 clases (A, B, C, D y E). Cada clase contiene unos números
para netid y otros números de bits para hostid. Es poco eficiente ya que se agotan y está en desuso.

- **Sin Clases (classless)**: Es más eficiente, es el más empleado en la actualidad y viene determinada por el CIDR.
