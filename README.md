# repoprueba
Just another test repository to play with git

hghf.
<<<<<<< HEAD
Probando
=======
A ver aqui modifico
>>>>>>> 81d7286a900d79ecf80bf65748293f6baa4445fe

A ver si choca

Pues esto esta asi loco
Vamos a intentar crear un error

jeje
hola a ver esto es una prueba

Probando autoria

<<<<<<< HEAD
 esto q probadno tamquien aqui es hola  choca?ca
=======
 esto ah y aqui q es hola  choca?ca
>>>>>>> 81d7286a900d79ecf80bf65748293f6baa4445fe

Jeje
Y aqui por poner algo
Prueba 2

Va a choca x fin jejee.
hola

No se q

<<<<<<< HEAD
Por supuesto aqui tmbn pruebo
=======
Aqui tambien 

1. En primer lugar, conviene conocer cuando se produce este conflicto, que ocurre cuando dos clientes hacen un _pull_. Posteriormente,
  2. un cliente hace sus modificaciones en las lineas 2 y 3 y realiza un _push_. Por otro lado, el otro cliente modifica las líneas 3 y 4 e intenta realizar un _push_.
  3. En este caso, git le informa que ha habido un problema y no se ha podido (porque otro cliente ha modificado alguna de esas líneas y git no puede unificarlo todo en uno)
  4. Por ello, el segundo cliente deberá hace un _pull_ (a su servidor local que ha modificado él también) para traerse lo que ha modificado el otro cliente.
  5. Ahora, al abrir el fichero en cuestión, el segundo cliente verá algo del siguiente estilo en las líneas conflictivas:
  6. <<<<<<< HEAD
  7. Lo que ha escrito este segundo cliente (el que ha abierto el fichero)
  8. =======
  9. En esta línea, estará lo que hizo el otro cliente en esa misma línea que lo anterior
  10. >>>>>>> Aquí habrá unas letras y números haciendo referencia al cliente que lo modificó.
  11. Una vez que el segundo cliente ve esto, deberá unificar estas dos líneas dejando una con lo apropiado y hacer un _push_.


Pues nada


1. En primer lugar, conviene conocer cuando se produce este conflicto, que ocurre cuando dos clientes hacen un _pull_. Posteriormente, 
un cliente hace sus modificaciones en las lineas 2 y 3 y realiza un _push_. 
Por otro lado, el otro cliente modifica las líneas 3 y 4 e intenta realizar un _push_. 
En este caso, git le informa que ha habido un problema y no se ha podido (porque otro cliente ha modificado alguna de esas líneas y git no puede unificarlo todo en uno).
Por ello, el segundo cliente deberá hace un _pull_ (a su servidor local que ha modificado él también) para traerse lo que ha modificado el otro cliente.
Ahora, al abrir el fichero en cuestión, el segundo cliente verá algo del siguiente estilo en las líneas conflictivas:
  2. "<<<<<<<" HEAD
  3. Lo que ha escrito este segundo cliente (el que ha abierto el fichero)
  4. "======="
  5. En esta línea, estará lo que hizo el otro cliente en esa misma línea que lo anterior
  6. ">>>>>>>" Aquí habrá unas letras y números haciendo referencia al cliente que lo modificó.
  7. Una vez que el segundo cliente ve esto, deberá unificar estas dos líneas dejando una con lo apropiado y hacer un _push_.


>>>>>>> 81d7286a900d79ecf80bf65748293f6baa4445fe
