# Glosario del Multiworld

Este es un glosario de terminos comunmente usados jugando multiworld. Mucho de estos son terminos en ingles que se
usan igual en español. 

## Item
Itemes son lo que es puesto al azar en tu mundo y en el de otros jugadores en un multiworld. Esto pueden ser espadas,
mejoras de status, hechizos, dinero o cualquier otro potencial objeto o mejora para tu juego.

## Location
Locations son donde los items son puestos en cada juego en un multiworld. Cuando interactuas con una locations tu 
o otro jugador va a recibir un item. Las locations podrian ser cofres, recompensas por matar enemigos, objetos en tiendas,
logros o cualquier otra interaccion en tu juego que contiene un item.

## Check
Un check es un termino comun para "checkear" o obtener el item de una location. Es comun mezclar locations y checks.

## Slot
Un slot corresponde al nombre que se le da a cada juego del multiworld. No es tan usado.

## World

World o mundo es un termino que en el context de multiworld puede significar distintas cosas. Suele usarse para
referirse a la informacion e itemes contenidos en cierto slot. World tambien se ocupa para referirse
al codigo usado para integrar cierto juego al multiworld.

## RNG

Acronimo para "Random Number Generator" o generador de numero aleatorio.

## Seed

Una seed o semilla es el numero usado por el RNG para generar la aleatoria del mulwitorld. Cada vez que se genera un
nuevo multiworld una nueva semilla es usada para decider donde van los itemes. Usar la misma semilla resulta
en exactamente el mismo juego siendo generado.

## Room

Un room o cuarto es una pagina que contiene la informacion para conectarse a un juego de multiworld y bajar
archivos externos en caso de ser necesario. Notar que una misma semilla puede generar distintos rooms, de forma
que una misma semilla puede jugarse muchas veces o incluso compartirse con otras personas en caso de ser deseado.

## Logic

Logic o logica es la serie de reglas que determina las locations factibles para ciertos itemes en el multiworld. Es
decir, es el codigo que determina como posicionar de itemes de forma que todos los juegos puedan ser terminados. Tambien
decimos que una location esta en logica o "in logic" se puede ser alcanzada con los itemes que se tienen en cierto momento
del multiworld. Notar que ciertos itemes "out of logic" o fuera de logica pueden ser obtenidos con el uso de glitches o trucos.

## Progression

Ciertos itemes desbloquean mas locations, asi que permiten progresar la semilla. Estos itemes son llamados "progression"
o necesarios para el progreso.

## Trash

Trash/Filler/Basura/Relleno son todos terminos usados para itemes que no son realmente importantes para progresar el multiworld.

## Burger King / BK Mode

Termino usado cuando cierto jugador no puede seguir progresando en su juego y necesita que alguien le mande algun item para seguir.

El termino viene de un jugador que al no poder seguir fue a comer a Burger King, volvio y aun no podia seguir jugando.

## Sphere

Archipelago calcula como el juego progresa usando una heuristica de "sphere"/esferas. El conjunto de todas las locations
que pueden ser alcanzados con cierto estado del juego es referido como una esfera/sphere, y desbloquear los itemes
que se encuentran esas locations abre el progreso a la sphere/esfera siguiente.

## Scouts / Scouting

En ciertos juegos hay locations que se puede ver que contienen antes de desbloquearlas (como objetos en la tienda de Hades).
Esto es un hint gratuito para el juego y permite planificar si esas locations son importantes o no.
