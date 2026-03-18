#Dynamo


DESCRIPCION

Creacion de proyecto acerca de base de datos principiante,ITE,principalmente el proeycto se centrara en un Taller de Mecanica especializado en Motores de combustion,con el fin de llevar un orden y control de,entradas,salidas,estado del vehiculo,etc


MOTIVACION 

aprender el funcionamiento y creacion de base de datos

NORMALIZACIONES

1-Primera Forma Normal (1FN)

Se aplicó para asegurar que todos los atributos de las tablas fueran atómicos (valores simples) y eliminar datos repetidos.
Cambios realizados:

Se eliminaron campos con múltiples valores.

Cada atributo contiene un solo dato.

Se organizaron los datos en tablas separadas.


2-Segunda Forma Normal (2FN)

Se aplicó para eliminar dependencias parciales, asegurando que todos los atributos dependan completamente de la clave primaria.

Cambios realizados:

Se separaron entidades como Cliente y Carro.

Se evitó mezclar información en una sola tabla.


3-Tercera Forma Normal (3FN)

Se aplicó para eliminar dependencias transitivas, es decir, que ningún campo dependa de otro campo que no sea la clave primaria.

Cambios realizados:

Se creó la entidad Cita/Servicio.

Se separaron Entrada y Salida.

Se ubicó correctamente el campo total_pagar en la tabla Salida.
