# Introduccion a GameMaker

Hola muchachos, para este video daré por hecho que ya vieron la introducción a la programación; así que si empezaron con este váyanse al otro.

Vamos a ver como un funciona un poco este GameMaker Studio 2. Igual también asumiré que ya lo tienen instalado.

Y una aclaración, mi versión de GameMaker se verá diferente a la que ustedes tienen. Esto es porque yo me he tomado el tiempo de personalizarlo a mi gusto porque trabajo mucho con él, pero funciona igual que el que ustedes tienen y no habría porque perderse.

Cuando mencione alguna función particular de GameMaker, voy a dejar un enlace a su entrada en el manual. El manual es de gran ayuda para sacar de dudas y recomiendo mucho revisarlo.

![Proyecto vacio](/images/01NuevoProyecto.png)
Al abrirlo vamos a crear un nuevo proyecto, nos da dos opciones y nosotros elegiremos “GameMaker Language”. El otro modo se parece más al “Scratch” que vimos el otro día en clase, pero está más limitado; además, este modo tiene más sentido con lo que hemos aprendido.

![Modo de GameMaker](/images/02GML.png)
Empezamos con un proyecto vacío y lleno de botones y cosas nuevas. No hace falta sabérselas todas y de hecho hay muchas que ni siquiera voltearemos a ver.

![Lista de recursos](/images/03ListaDeRecursos.png)
A la derecha está nuestra lista de recursos. Aquí se guardan todas las cosas que usaremos para nuestro juego y esta lista ya está separada en los diferentes tipos de recursos que usa el programa.

No hace falta verlos todos y notarás que en mi versión tengo unos de colores; esos son los que más uso y para este vídeo en realidad sólo veremos cuatro.

![Sprites](/images/04Sprites.png)
El primero en rojo está hasta arriba y dice “Sprites”. Este no se refiere al refresco; se le llaman sprites a las imágenes que usa una computadora. Entonces aquí se guarda todo lo relacionado con cosas visuales, dígase, imágenes.

![Sonidos](/images/05ListaDeMusica.png)
El segundo está en color azul y dice “Sounds”, sonidos. Creo que este es bastante claro, cualquier archivo de sonido iría aquí.

![Habitaciones](/images/06Rooms.png)
Voy a saltarme al último que está coloreado con un amarillo cafesoso que dice “Rooms” o habitaciones. Estos son espacios dónde acomodas las cosas para formar tu juego; puedes imaginarlo como los “niveles” por así decirlo.

![Objetos](/images/07Objetos.png)
El último recurso que necesitamos es el que está en verde que dice “Objects” u objetos. Estos son, válgame la redundancia, objetos; cosas que puedes acomodar en las habitaciones y aquí es dónde les escribes el código para que hagan cosas. Cada uno tiene sus propias variables y hace sus propias cosas.

Todos los demás tipos de recursos no son necesarios. En realidad, sólo necesitas imágenes, sonidos (aunque el sonido se podría omitir), código y un lugar dónde ponerlo todo.

![Boton de Play](/images/8BotonDePlay.png)
Y cuando lo tengas todo listo puedes ir acá arriba dónde están todos estos botones y presionar el botón de la flecha verde para darle play y probar lo que hemos hecho.

![Juego vacio](/images/9JuegoVacio.png)
Cómo verás, esto nos da una ventana gris completamente vacía. Esto es porque, efectivamente, no hemos puesto nada en el juego. Así que cerremos esto y comencemos a poner cosas.

![Crear Sprite](/images/10CrearSprite.png)
Empecemos con un Sprite. Hay darle clic derecho en dónde dice “Sprites” y nos saldrán muchas opciones, pero sólo nos interesa la primera, la que dice “crear Sprite”.

![Ventana de Sprite](/images/11NombreDelSprite.png)
Nos abre esta ventana dónde podremos ver y editar el Sprite.
Esta ventana también tiene muchas cosas, pero, cómo de costumbre, muchas de ellas no nos importan y necesitamos sólo unas pocas.

![Cambiar nombre del Sprite](/images/11aNombreDelSprite-Nombre.png)
Arriba a la izquierda está el nombre, podemos ponerle el nombre que queramos (sólo no pongas espacios).

![El tamaño y el botón](/images/12ChecaLaEscala.png)
Abajo del nombre está el tamaño de la imagen. En este caso la imagen mide 32 por 32 pixeles. La W viene de la palabra “width” en inglés que significa ancho y la H viene de la palabra “height” en inglés que significa alto.

![Cambia el tamaño del sprite](/images/13CambiaLaEscala.png)
Si le das clic a este botón, puedes cambiarle el tamaño. Sólo aquí escribe los nuevos números del nuevo tamaño y presiona aplicar. Listo.

![Vista previa del Sprite](/images/13bVistaPrevia.png))
Esto que está abajo a la derecha es una vista previa, para que sepas cómo se ve el Sprite. Ahorita cómo no tenemos nada sólo nos muestra este fondo de cuadros.

![Botones importantes del Sprite](/images/13cEstosBotones.png)
De vuelta a la parte del tamaño hay dos botones, uno que dice “Editar imagen” y otro que dice “Importar”. Si le damos al botón de editarimagen nos manda a otra ventana dónde podemos dibujar a nuestras anchas. Esto es muy parecido a cualquier programa de dibujo, como el Paint que viene incluido con Windows. Eliges un color y usas alguna herramienta. Está el pincel con el que dibujas dónde hagas clic, un borrador, líneas, cuadros y círculos y llenar de color algo. Todo ello. Podremos hacer algo así como una cara feliz.

![Dibujando ando](/images/14Dibujando.gif)
Si no quieres dibujar o al menos no dibujar con GameMaker, puedes usar el botón de importar para traer algún archivo de imagen que tengas en tu computadora.

Ahora vamos a los sonidos.

![Crear sonidos](/images/14CrearSonido.png)
Podemos crear uno de la misma manera. Clic derecho, crear sonido.

Éste no tiene para que hagas música, así sólo puedes traer sonidos de tu computadora.

Aquí arriba le pones algún nombre, como con el Sprite, y a la derecha, en este botón, le ponemos el sonido que queramos.

![Partes de sonido](/images/15CosasDeSonido.png)
Las opciones de abajo no nos importan. Sólo ten en cuenta que puedes ponerle play para asegurarte que sea el sonido correcto y ajustarle el volumen.

![Crear objetos](/images/16CrearObjeto.png)
Los objetos igual se crean dando clic derecho y crear objeto.

![Nombra tus objetos](/images/17CosasObjeto.png)
También puedes ponerle algún nombre.

![Objeto con el sprite ya asignado](/images/18AsignarSprite.png)
Y aquí abajo puedes asignarle algún Sprite. Le puse el que hicimos hace rato, y ahora lo puedes ver aquí.

Vamos a dejar a los objetos así por ahorita para ir a ver los rooms.

Un proyecto nuevo por defecto ya empieza con una habitación, el cuadro gris que vimos cuando le di al botón de play hace rato. Pero si quisiéramos hacer otro… ya saben cómo.

Por lo pronto veamos el que ya está.

![Habitación predefinida](/images/19CosasRoom.png)
Ahora nos abre en una ventana a parte para editar esta habitación. Y ahora tenemos una nueva columna a la izquierda con cosas relacionadas con la habitación.

![Capas en las habitaciones](/images/19aCapas.png)
Lo primero son las capas. Si alguna vez han trabajado con algún programa de imágenes elegantes como Photoshop, es el mismo concepto. Sirve para organizar lo que pongas.

Ya viene con estas dos capas y abajo están botones para hacer nuevas capas.

![Lista de instancias](/images/19bLista.png)
Abajo está la lista de instancias. Es una lista de todo lo que has puesto en la habitación. A parte de decirte eso, no tiene mucha utilidad así que voy a minimizarlo dándole clic a esta flechita.

![Información de la habitación](/images/19cInfoRoom.png)
Lo que sigue es la información de la habitación. Aquí sólo nos interesan estas dos palabras familiares de “width” y “height” que son el ancho y el alto de la habitación. Podemos cambiar estos números y podemos ver que la habitación se hace más pequeña o más grande.

![Acomodando objetos](/images/21AgregaObjetosAlRoom.gif)
Cómo les había dicho, las habitaciones son espacios dónde acomodas objetos, así que vamos a ponerle objetos. Esto es tan fácil como darle clic a alguno de los que hayamos creado y arrastrarlo a la habitación. Podemos hacerlo muchas veces.

Si no nos gustó como quedo algo, podemos moverlo; cambiarlo de tamaño si das clic en el borde; o girarlo si damos clic un poquito más lejos del borde.

![Cuadro gris con objetos](/images/21NuevoRoom.png)
Ahora si le damos play al juego otra vez, veremos el cuadro gris que habíamos visto antes, pero ahora con el nuevo tamaño que le puse y con todas las cosas que le puse.

Ahora sí, regresemos y terminemos de ver a los objetos.

En los ejemplos del vídeo anterior las cosas sólo pasaban cuando algo hacía que pasaran. Como la calculadora, cada cosa que hacía un botón sólo pasaba CUANDO presionas el botón. O el reloj, el segundero cambia CUANDO pasa un segundo. O la persona sólo hace las cosas CUANDO le ordenas que haga algo.

![Eventos del objeto](/images/21bEventos.png)
Igual aquí las cosas que programas sólo pasan cuando cierto evento las activa. Por eso el objeto tiene a la derecha este recuadro que es para los eventos a los que les has creado algo.

![Botón de agregar evento](/images/22CrearEvento.png)
Y el botón de añadir nuevo evento que está debajo nos dará una lista de eventos para elegir cuál es el que tenemos que añadir.

Comencemos con algo sencillo, el evento Step. Puedes elegir cualquier de los tres, no importa cuál.

Este evento se ejecuta todo el tiempo mientras el objeto esté vivo.

Y ahora nos sale un nuevo cuadro. Aquí es dónde escribimos el código. Aquí es dónde sucede la magia.

¿Recuerdas lo de las variables?

Aquí se usan nada más escribiendo su nombre (sin espacios).

![Variables](/images/23Variables.png)
Para asignarles un valor, basta con poner el signo de igual y después poner el valor que quieres asignarles. Si lo que quieres agregar es un texto, tienes que ponerlo entre comillas. E incluso puedes agregar otra variable. Si hago esto, ahora variable4 tiene exactamente lo mismo que variable1.

Pero no necesitamos ninguna de estas variables. En GameMaker, los objetos ya vienen con algunas variables ya definidas y que hacen cosas cuando las modificas.

Como las variables X y Y. Estas variables tienen las coordenadas de dónde está el objeto en la habitación, y si las cambias, el objeto se moverá al nuevo lugar que señalaste.

![Código para seguir al ratón](/images/24CodigoSeguirRaton.png)
Vamos a hacer que X y Y sean iguales a otras variables que ya vienen por defecto, mouse_x y mouse_y. Estas variables tienen las coordenadas de dónde tenga el ratón. Así que haciendo esto, efectivamente estoy diciendo que el objeto se ponga dónde sea que esté el ratón.

![Seguir al ratón](/images/25SeguirRatonJuego.gif)
Deja voy a la habitación y quito todos los objetos menos uno para hacer más fácil el ver esto. Y ahora a darle play. Y ahora vemos que el objeto siempre estará dónde esté el ratón.

Regresemos y vamos a borrar esto para hacer ahora algo diferente.

![Evento de tecla](/images/26EligiendoEventoTecla.gif)
Ahora veremos algo sencillo, el evento de “Key Down”. Este evento es algo que pasa mientras estas presionando alguna tecla. Cómo verás nos da las opciones de las flechas, algunas teclas especiales, los números del teclado numérico, los números que están arriba de las letras, las letras, las teclas que empiezan con la F, u otras especiales.

Por ahora elijamos la tecla de la derecha.

Vamos a modificar otra de las variables predefinidas. Esta vez una que se llama “hspeed”, versión corta de “horizontal speed” o “velocidad horizontal” en español.

Esta variable mientras tenga un valor mayor a 0, hará que el objeto se mueva a la derecha; si tiene una valor menor que 0, hará que el objeto se mueva a la izquierda. Mientras más lejos esté el número del cero, más se moverá. Y si el valor es cero, el objeto NO se moverá horizontalmente.

Vamos a ponerle que sea un 4 y probemos el juego.

![El objeto se mueve a la derecha](/images/27MovimientoInfinito.gif)
En efecto, cuando presionamos la tecla de la derecha, el objeto se mueve a la derecha. Pero hay un problema, el objeto no se detiene y sigue su camino hasta el infinito. Esto es porque hicimos que la variable “hspeed” fuera un cuatro, pero nunca hicimos nada que lo regrese a cero para que se quede quieto. Vamos a ponérselo.

Para eso necesitamos otro evento, esta vez se llama “Key Up”. Este evento funciona cuando sueltas la tecla elegida.

Para este momento puede que ya tengas una idea de qué es lo que tienes que hacer.

Crear un nuevo evento y escribirle hspeed es igual a cero.

![Ahora el objeto se detiene](/images/28MovimientoPausado.gif)
Corramos el juego y funciona. Se detiene, ¡bravo!

![Ahora el objeto se mueve en dos direcciones](/images/29MovimientoHorizontal.gif)
Podemos repetir lo mismo para la tecla de la izquierda y ahora se mueve a los dos lados.

![Ahora el objeto se mueve en todas las direcciones](/images/30MovimientoTotal.gif)
Y por supuesto, también podemos repetirlo para las teclas de arriba y abajo. Sólo que ahora lo que tienes que modificar es una variable que se llama “vspeed” versión corta de “vertical speed” o “velocidad vertical” en español. Sólo considera que aquí es poco intuitivo porque los valores positivos te mueven hacia abajo y los valores negativos te mueven hacia arriba. Contrario a lo que uno pensaría.

Pero ahora se mueve en todas las direcciones. Maravilloso.

También es importante que se detenga al chocar con paredes.

![Agregando la pared](/images/31ParedAgregada.gif)
Vamos a hacer eso. Rápidamente hago un nuevo Sprite para las paredes y un nuevo objeto para la pared y pongo varias paredes en la habitación. Pero si lo notaste, ahora este objeto le puse una palomita en dónde dice “Solid”. Esto marca que ese objeto es, pues, solido; y esto significa que cuando algo intente moverse hacia él se detendrá.

![Poniendo paredes](/images/32AgregandoParedes.gif)
Ahora pongamos las paredes en la habitación.

![Agregando evento de colisión](/images/33EventoDeColision.gif)
Pero falta ir al objeto de nuestro jugador y añadir un evento nuevo. Esta vez será el evento de “Collision” y nos da para elegir una lista de todos los objetos disponibles. Elegiremos la pared que creamos. No hace falta escribir nada, sólo con que exista el evento ya funcionará.

![Las paredes detienen al jugador](/images/34LasParedesMeDetienen.gif)
Si corremos el juego vemos que ahora nuestro objeto se detiene al chocar con las paredes.

![Laberinto](/images/35Laberinto.png)
Ahora, sí quisiéramos, podríamos diseñar un laberinto.

Por ahora solamente hemos usado variables. Pero también están las funciones que no he mencionado.

![Creando sprite y objeto de una moneda](/images/36NuevaMoneda.gif)
Para esto vamos a hacer un nuevo Sprite y un nuevo objeto de una moneda.

Ahora regresaremos al objeto de nuestro protagonista. Y le crearemos un nuevo evento. Esta vez será el evento “Create”. Este evento sucede cuando el objeto es creado y se usa para definir la información con la que empezarán sus variables. No es obligatorio hacer esto, pero es recomendado porque si no, corres el riesgo de que algo salga mal. Además, ayuda para que tengas fresco las variables que has creado.

![Inicializando la variable puntuación](/images/37InicializarPuntuacion.png)
Vamos a crear una variable que se llame “puntuacion” y vamos a ponerle el valor de 0. Porque al inicio empiezas con 0.

Y ahora crearemos otro evento de colisión, pero ahora con el objeto de la moneda.

Hasta ahora hemos visto como ponerle un valor a una variable, pero ahora vamos a cambiarle el que ya tiene, en este caso, le vamos a sumar.

Esto se puede hacer de dos maneras.

Una de ellas es escribir “puntuacion = puntuacion + 100”. ¿Recuerdas que había comentado que puedes ponerle la información de una variable a otra variable? Pues esto lo que hace es ponerle lo que ya tenía antes, más 100. Entonces si tiene 0, cambiará a 100, si tiene 100 cambiará a 200, si tiene 200 cambiará a 300 etc.

La otra manera de hacerlo es escribiendo “puntuacion += 100”, poner el signo de operación antes del signo de igual hace que se haga esa operación en la variable con el número de la derecha. Hace exactamente lo mismo que la versión anterior pero más fácil de escribir.

![Aumentar la puntuación](/images/38AumentarPuntuacion.png)
Y con esto, cada vez que toques una moneda, tu puntuación aumentará en 100. Esto también funciona para restar, multiplicar y dividir.

Pero todavía hay un problema (además de que no hemos usado una función todavía, porque eso de sumar no fue una función). ¿Recuerdas cuando hicimos lo de moverte con las teclas? Si no hacíamos algo para que la velocidad se reinicie, el monito se movería por el infinito.

Pues aquí pasa igual. Mientras estés tocando la moneda te seguirá dando 100 puntos. Puedes quedarte parado en ella y te seguirá dando puntos hasta que te aburras y te quites. Pero no queremos eso, queremos que te de puntos una sola vez y ya.

Creo que en ese caso lo mejor sería hacer desaparecer la moneda.

Para eso usaremos una función.

![Destruye la moneda](/images/39DestruyeLaMoneda.png)
Usaremos una que se llama “instance_destroy(other)”. Las funciones son fáciles de identificar porque siempre tienen al final un par de paréntesis que a veces pueden estar vacíos y a veces puede tener cosas. Esta función lo que hace es destruir algún objeto. Lo que está adentro del paréntesis le dice a la función qué es lo que tiene que destruir.

Si no escribieras nada adentro de estos paréntesis, lo que pasaría sería que tú te destruirías y no la moneda. Podrías poner el nombre de “ObjetoMoneda” pero eso destruiría todas las monedas que haya en la habitación porque no sabe de cual de todas estas hablando. Hay maneras de diferenciar cada una de las monedas en la habitación, pero más bien haremos algo más fácil.

Cuando estás en un evento de colisión, puedes usar la palabra “other” para referirte a la cosa con la que estás colisionando. Entonces escribimos “other” adentro del paréntesis, y listo, ahora sólo desaparecerá la moneda que toques.

![Jugando a conseguir monedas](/images/40ReunamosLasMonedas.gif)
Muy bien, pero estamos consiguiendo puntos sin saber cuántos tenemos.

Ahora crearemos un nuevo evento, el evento “Draw” o evento de “Dibujo” en español. Este evento, al igual que el evento step que vimos al principio, es un evento que sucede todo el tiempo. La diferencia que tiene con el evento step es que este se usa para todo lo que sea de dibujar.

![Eljuego me dijo hola](/images/41ElJuegoMeDijoHola.gif)
Vamos a usar una nueva función que se escribe “draw_text(32,32,”Hola”)”. Sabemos que es una función porque tiene un par de paréntesis al final. Y adentro tiene información que necesita para funcionar. Esta función dibuja algún texto en pantalla. Los dos primeros números son las coordenadas de dónde quedará lo que dibujamos, en este caso en las coordenadas 32 y 32. Lo tercero es el texto que dibujará. Recuerda que te había dicho que el texto se pone entre paréntesis, esto es para evitar confundirlo con alguna variable que se llame “Hola”.

Muy bien. Pero ahora hay un problema. No queremos dibujar la palabra “hola”. Queremos dibujar la puntuación. Y también nuestro objeto desapareció.

Bueno, primero que nada, no desapareció, sólo que ahora es invisible. Todos los objetos automáticamente usan una función para dibujarse a sí mismos. Pero cuando creas un evento de dibujo le estás diciendo a GameMaker: “Oye, ya no te preocupes por dibujar al objeto, ahora yo voy a decidir que se dibuja” y GameMaker te contesta: “Ah ok, ta chido”. Esto se resuelve fácil usando una función que se llama “draw_self()” que lo que hace… creo que el nombre lo explica muy bien.

Ok, eso resuelve un problema, pero aún tenemos otro. En la función de dibujar texto, lo último que pusimos adentro de los paréntesis es lo que escribirá. Pero podemos poner la variable puntuación (así sin comillas, recuerda que las comillas son para que la computadora no piense que le estás poniendo una variable, pero esta vez sí queremos ponerle una variable). Y ya. Le damos correr y ya quedó.

![Mostrando la puntuación](/images/42AhoraSiVeoLaPuntuacion.gif)
Podemos mezclar texto y variables. Sumas cosas con el signo de más, pero tienes que convertir primero la variable a texto. Esto lo haces con la función “string()”, lo que hace esta función es que lo que sea que pongas entre sus paréntesis se convertirá en texto.

Las coordenadas del texto también pueden tener variables y operaciones. Podemos hacer que el texto siga al jugador. Recuerda que los objetos tienen las variables X y Y para decir dónde están. Podemos usar estos. El primer número es la coordenada horizontal. Escribimos x y ahora el texto siempre se dibujará en la misma parte horizontal de dónde esté el objeto.

Hacemos lo mismo con la y. Pero queda muy encimado con tu Sprite. Vamos a ponerlo poquito más arriba de dónde estás tú. Cómo dije, también puedes poner operaciones. Pondremos “y-32”; recuerda que es contraintuitivo y los números negativos son hacia arriba.

![La puntuación te persigue](/images/43LaPuntuacionMeSigue.gif)
Hermoso, ¡Bellizimo! Pero no se ustedes, pero a mí me gusta más que la puntuación esté en un lugar fijo. Voy a regresarlo como estaba antes.

Probemos otra cosa para ver más eventos. En la lista tenemos el evento del “Mouse” para las cosas relacionadas con el ratón. Es muy parecido a lo que vimos del teclado. Tienes para el clic izquierdo, el clic derecho y cuando presionas la ruedita del ratón. Al igual que el teclado puedes elegir cuando el botón del ratón está siendo presionado o cuando lo soltaste. También está el evento “Pressed” que también existe en el teclado, pero no lo mencioné y ese evento es cuando presionas el botón, pero a diferencia del evento normal, este evento sólo sucede una vez y no se vuelve a activar hasta que sueltes el botón y lo vuelvas a presionar. Puedes cambiar el evento que usamos para las teclas por su versión en “Pressed” y todo seguiría funcionando bien.

Cabe aclarar que estos eventos del ratón sólo funcionan si pasan mientras el ratón está encima del objeto. Si quieres que funcionen cuando des clic en cualquier lugar, usas sus variantes de “global”.

Por ahora sólo hagamos un evento de cuando le das clic izquierdo pero el presionado, el que funciona sólo una vez.

Y pongamos que este te de 10 puntos.

Podemos hacer que cambie de Sprite. Creemos otro Sprite.

Y usamos otra de las variables predefinidas. Esta se llama “sprite_index”. Normalmente esta variable tiene el Sprite que le pusimos acá a la izquierda, pero ahora se lo vamos a cambiar al nuevo Sprite que hicimos.

Y hagamos que regrese al Sprite anterior cuando lo sueltes.

![El objeto interactua con el ratón](/images/44SeEnojaSiLePico.gif)
Ahora sólo se enoja cuando le picamos.

Pero recuerda que estos eventos sólo funcionan mientras tienes el ratón encima del objeto. Esto significa que puedes hacer trampa. Puedes dar clic en el objeto para que se enoje, quitar el ratón del objeto, y ya lejos del objeto sueltas el clic. Cuando lo sueltas el ratón no está en el objeto, así que no se activa el evento y no vuelve a calmarse.

Podemos resolver esto haciendo que se calme en el evento de cuando sueltas el clic en cualquier lado.

Ahora vamos a subir un poco más la complejidad.

Crearemos dos Sprites nuevos y dos objetos nuevos.

Haremos unos picos que te hagan daño y una bandera que es tu objetivo final.

Cómo ya te habrás imaginado usaremos eventos de colisión.

Hagamos que los picos te devuelvan al inicio.

Hay dos formas de hacer esto. En una usamos las variables predefinidas “xstart” y “ystart” que guardan las coordenadas en las que empezó el objeto cuando fue creado.

Pongamos unos picos en la habitación y probémoslo.

![Probando los picos](/images/45LosPicosDuelen.gif)
Muy bien. Funciona.

![Los picos reinician todo](/images/46LosPicosReinicianElUniverso.gif)
La otra manera es usando la función “room_restart()”. Esta función lo que hace es reiniciar la habitación a cómo estaba al principio. Esto regresa al jugador al inicio, pero como se reinicia TODO, eso también incluye que reaparecen las monedas que agarraste y pierdes la puntuación que habías conseguido.

Ahora, si queremos hacer niveles ya no nos va a funcionar la manera en que llevamos la puntuación. Esto es porque hicimos que la puntuación sea igual a cero cada vez que el objeto es creado. Y cada vez que cambiemos de habitación se creará otra vez así que se volverá a poner en cero. Y lo que es peor, las variables son únicas de cada objeto, aunque pudiéramos evitar que se reinicie, seguirá siendo cero porque en otra habitación será otro objeto y volverá a poner la puntuación en cero.

Para solucionar esto tenemos que hacer dos cosas. Primero que nada, cambiar el evento, en lugar del evento de creación, lo cambiaremos por el evento de inicio del juego, o “Game Start”. Ahora este evento ya no sucederá cada vez que el objeto se crea sino cada vez que el juego comienza.

Lo segundo que tenemos que hacer es poner la palabra “global” y un punto antes de esta variable. Tenemos que hacerlo en todas las veces que aparezca la variable que estamos cambiando. Esto significa que la variable ya no está “amarrada” al objeto y funcionará en todas partes y para todos por igual.

![La puntuación se mantiene](/images/47YaNoSeReiniciaTodo.gif)
Podemos ver que si reiniciamos la habitación al chocar con picos, nuestra puntuación no se reinicia, porque la variable puntuación ahora es global y no está atada a nada que se reinicie en la habitación.

De paso creemos otra variable local. Esta se llamará vidas y comenzarás con 3.

Haremos que cada vez que toques un pico pierdas una vida, y que cuando pierdas todas tus vidas pierdas el juego.

En la colisión con los picos agregamos este código que hace que le quite uno a la cantidad de vidas. “global.vidas -= 1”

Pero ahora también necesitamos que cuando llegues a cero vidas pase algo especial.

Para esto usaremos una condición.

Hay varias condiciones disponibles, pero la que usaremos se llama “if”. La palabra en inglés para decir “si”. No es el “sí” de “sí señor” sino que es el “si” de “si hubiera clases presenciales, esto sería más fácil”.

Y funciona así.

Escribes la palabra “if” luego la condición que quieres checar, luego un par de llaves y adentro de esas llaves pones lo que quieras que pase cuando se cumpla la condición.

En este caso la condición que estamos esperando es que tus vidas lleguen a cero.

Esto se hace con dos signos de igual. Y eso checa si lo que está a la izquierda del doble signo de igual es igual que lo que está a la derecha. Si son iguales, entonces se hace lo que está entre las llaves.

También puedes checar si es menor que algo, menor o igual a algo, mayor que algo o mayor o igual a algo. Así que también funcionaria si pusieras que si las vidas son menores que uno; o que si son menores o iguales a cero.

![Puedes ir a la pantalla de perdida](/images/48PuedesPerder.gif)
Pero por ahora dejémoslo en lo primero, para no perdernos.

Entonces por ahora cuando tocas unos picos se reiniciará la habitación, perderás una vida y si llegas a cero vidas pasará algo. Pongamos lo que sucede cuando llegas a cero vidas.

Usemos una función que se llama “room_goto(RoomPierdes)”. Esta función te lleva a la habitación que pusiste entre los paréntesis. Actualmente esa habitación que escribí no existe, así que vamos a crearla. Recomiendo que para evitar conflictos la hagas del mismo tamaño.

Está muy aburrida nada más la pantalla gris. Hagamos un nuevo objeto para decirte que perdiste.

Esta vez no necesitamos Sprite porque sólo quiero dibujar texto.

Hagamos un evento de dibujo.

Usemos la función de dibujar texto para decirle al jugador que perdió pero que logró tantos puntos.

De coordenadas pondremos x y y para que cuando pongamos el objeto en la habitación, sepamos dónde se verá el texto.

Y ahora el texto. Como la variable de puntuación es global, este objeto que no tiene nada que ver también la puede usar.

Rayos, es una frase muy larga y se sale de la pantalla.

Cuando escribes texto, puedes escribir un “\n” para pasar a un nuevo renglón.

Pero no dejemos el juego así. Permitamos que si presionas una tecla puedas volver a comenzar.

![Muestra que perdiste](/images/49PuedesPerderMas.gif)
Por supuesto tenemos que añadirle un evento de cuando presionas la tecla R. En este caso la de presionar porque queremos que pase sólo una vez.

Y en el código escribimos la función “game_restart()”. Esta función también reinicia, pero reinicia todo el juego. Te manda de vuelta a la primera habitación y también reinicia las variables globales, en efecto como si hubieras vuelto a comenzar.

![Recuerda poner cosas en las habitaciones](/images/51RecuerdaPonerCosas.gif)
Sólo recuerda poner el objeto de perder en la habitación de perder.

![El juego ahora tiene reinicio](/images/52YaTodoEnMarcha.gif)
Muy bien. Ahora puedes perder, pero también volver a comenzar.

![Dibuja también las vidas](/images/50QueSeVeanTusVidas.png)
Aún no hemos acabado. Regresemos a nuestro objeto del jugador. Ahora que aprendimos esto de hacer una segunda línea entonces también dibujemos las vidas que tienes.

Pero no todo es sobre perder, también hay que ganar y para eso está la bandera.

![Primer intento de programar la colisión con la bandera](/images/53PrimerBandera.png)
En el evento de colisión de la bandera hagamos que vayas al siguiente nivel. Para esto usamos la función “room_goto_next()” que lo que hace es llevarte a la siguiente habitación.

![Segundo intento de programar la colisión con la bandera](/images/54SegundoIntentoBandera.png)
Creo que sería más divertido si sólo puedes pasar el nivel si agarras todas las monedas. Podemos usar otra condición de “if” y usarla con una nueva función que se llama “instance_number(objeto)”; esta función lo que hace es que te dice cuántas instancias del objeto que escribiste entre paréntesis existen actualmente en la habitación. Estamos destruyendo las monedas cuando las tocamos así que sólo hay que esperar a que no haya monedas, es decir a que si “instance_number(ObjetoMoneda) == 0” y ahora sí ponemos la función para cambiar de habitación adentro de las llaves y todo funcionará.

![Ahora también puedes ganar, o algo así](/images/55LaBanderaFunciona.gif)
Y sí, si tocas la bandera sin tener todas las monedas, no pasa nada. Pero a penas la tocas cuando ya tienes todas las monedas te manda a la siguiente habitación. Rayos, la siguiente habitación era la de perder.

No hay problema, crearemos más habitaciones con más niveles y también haremos una última habitación como la de que perdiste, pero para decir que ganaste.

Y por supuesto, ponerle un nuevo objeto parecido al de perder, pero ahora cambiado para que diga que ganaste. Pero a este punto me imagino que ya entiendes cómo hacer lo que falta, así que aquí me detendré.

Creo que esto es lo suficiente para darles una idea de cómo funciona GameMaker. Traté intencionalmente de no incluir cosas relacionadas directamente con los proyectos que me dijeron que quieren hacer para no “hacerles la tarea” y que descubran un poco más de este software. Por supuesto que yo estoy disponible para dudas y aclaraciones; también está el señor internet y papá Google para guiarnos más cuando se tenga alguna duda o inquietud.

Espero esto les haya sido de utilidad y espero ver pronto sus proyectos. Buen día.
