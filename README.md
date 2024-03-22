<h1>Animation Css</h1>

Propiedades básicas de la animación en css:

- animation-name: indica el nombre de la animación,
ex:

````````````````````````````````````````````````````````
div {
  animation-name: mymove;}
@keyframes mymove {
  from {top: 0px;}
  to {top: 200px;}
}
````````````````````````````````````````````````````````

- animation duration: indica la duración de la animación,
ex:

````````````````````````````````````````````````````````
div {
  animation-name: mymove;
  animation-duration: 3s;//indica que la animación durará 3 segundos.
}
@keyframes mymove {
  from {top: 0px;}
  to {top: 200px;}
}
````````````````````````````````````````````````````````


- animation-direction: indica la dirección de la animación,
ex:

````````````````````````````````````````````````````````
div {
  animation-name: mymove;
  animation-duration: 3s;
 animation-direction: alternate;//la animación cambiará de dirección de forma alternativa
}
@keyframes mymove {
  from {top: 0px;}
  to {top: 200px;}
}
````````````````````````````````````````````````````````

-  animation-timing-function: indica el comportamiento de la animación.

````````````````````````````````````````````````````````
div {
  animation-name: mymove;
  animation-timing-function: linear//La animación tiene la misma velocidad de principio a fin.
 animation-timing-function: ease//Valor por defecto.  La animación tiene un comienzo lento, luego rápido, antes de terminar lentamente.
animation-timing-function: ease-in//La animación tiene un comienzo lento.
animation-timing-function: ease-out//La animación tiene un final lento.
animation-timing-function: ease-in-out//La animación tiene un comienzo lento y un final lento.
}
@keyframes mymove {
  from {top: 0px;}
  to {top: 200px;}
}
````````````````````````````````````````````````````````


Pincha aquí para ver una prueba: http://77766352w.com/josetrujillosilva/animation2/animation.html




