[![en](https://img.shields.io/badge/lang-en-red.svg)](https://tiredprogrammer70.github.io/Porfolio)

Hola a todos, este es mi porfolio donde muestro todos los proyectos de videojuegos que he realizado durante mis estudios y experiencia laboral.

He realizado un ciclo superior de Desarrollo de Aplicaciones Multiplataforma y Ocio centrado en la programación de videojuegos, he trabajado mayoritariamente con Unity durante el curso, aprendiendo diferentes estilos de juegos que crear con el motor.

### Slay The Corrupted

<p align="center">
<img src="https://github.com/TiredProgrammer70/Portfolio/assets/109514725/39036217-cdae-4a69-8648-878d05aede3d" width="50%" height="50%">
</p>

Slay the Corrupted fue el proyecto de final de curso, tuvimos entre 2 y 3 meses para desarrollarlo con el equipo de 3 compañeros que éramos, yo fui decidido como el líder del proyecto porque la idea la propuse y explique yo, la idea de este proyecto era crear la base de un juego que fuese comercializable y divertido, para lograr ese fin, decidí añadirle elementos RogueLike de aleatoriedad en cada partida con código complejo de creación automática de mapas.

<img src="https://github.com/TiredProgrammer70/Porfolio/assets/109514725/3e591f37-ddb5-4143-9cf5-948fc2d5dd4f" width="30%" height="30%">
<img src="https://github.com/TiredProgrammer70/Porfolio/assets/109514725/b9384db1-1cbe-4bff-bb21-4d404de3904f" width="30%" height="30%">
<img src="https://github.com/TiredProgrammer70/Porfolio/assets/109514725/e430fcf2-9d75-4a5f-8a08-b08809d78969" width="30%" height="30%">

El mapa se genera de forma aleatoria siguiendo un algoritmo que cree yo, permitiéndome también asignar X número de habitaciones especiales que tiene que incluir durante la generación del mapa.

Para facilitar la generación del mapa, utilicé pensamiento creativo y lógico para simplificar el código, creando una función que se llama cuando se genera el mapa y las salas que, convirtiendo cada una de las posibles puertas de la sala de una forma binaria, les asigna potencias de 2, de esa forma, cada una de las 15 combinaciones posibles tenía un número fácilmente reconocible asignado.

```
public int DoorTypes() {
   int valueDoors = 0;

   if (doorUp) valueDoors +=1;
   if (doorBot) valueDoors +=2;
   if (doorLeft) valueDoors +=4;
   if (doorRight) valueDoors +=8;

   return valueDoors;
}
```


Además de trabajar con un algoritmo de aleatoriedad automática, también trabajamos con la creación de GameManagers para controlar el entorno del juego, y clases heredadas para facilitar el uso del código en múltiples instancias.

Mi parte del proyecto fue la creación de los mapas y la inteligencia del enemigo final, hecho con un algoritmo de fases y diferentes ataques de forma limpia y reutilizable para poder crear más enemigos a futuro si se quisiese.

[Descargar](https://drive.google.com/file/d/1O50YXRgjCIfhkQlTCcRi0NL4QlLtnIg5/view?usp=drive_link)

### Space Shooter para Android
<p align="center">
<img src="https://github.com/TiredProgrammer70/Porfolio/assets/109514725/5eb7fc15-aa08-4495-bbd4-4caae1196e50" width="50%" height="50%">
</p>

Primer juego del segundo año del ciclo, estilo arcade con rejugabilidad, nació de la necesidad de aprender programación y modelaje en 3D, aplicando físicas a los disparos, el spawn de enemigos, y movimiento del personaje jugable.

Se aplicó un sistema de mejoras permanente en el juego, desbloqueando las mismas con la moneda del juego, estas mejoras se mantienen aún que cierres y abres el juego.

<p align="center">
<img src="https://github.com/TiredProgrammer70/Porfolio/assets/109514725/558a1839-6f29-4398-b97b-a5ec7cdc1831" width="50%" height="50%">
</p>

Una vez empiezas una partida, el juego es estilo arcade, teniendo un límite de tiempo para disparar a los diferentes objetivos que van apareciendo, algunos objetivos dando bonuses para mejorar o facilitar la partida.

<!--- Cambiar enlace a ejecutable del Android shooter --->
[Descargar](https://drive.google.com/file/d/1wiRNdZfgetoRrpQHFs_arkirY8-vLujm/view?usp=drive_link)

### SpaceScape

SpaceScape fue mi proyecto de final del primer año del ciclo, se creó durante la pandemia en un mes.

SpaceScape lo cree como un videojuego plataformas 2D para practicar las físicas de gravedad 2D, aprendiendo todas las diferentes configuraciones que se le pueden aplicar a las físicas para hacer diferentes estilos de saltos, gravedad, movimiento, etc.

En este proyecto también aprendí a crear parallax con código, la funcionalidad de que los objetos del fondo se muevan a diferentes velocidades mientras avanzas por el juego.

[Descargar](https://drive.google.com/file/d/1bnfME8W120nxHo1SxYzcIU6zgQTkQrlQ/view?usp=drive_link)

### Torre de desafiós
<p align="center">
<img src="https://github.com/TiredProgrammer70/Porfolio/assets/109514725/6a42bb26-7b33-43e1-8f58-18da6c716648" width="50%" height="50%">
</p>

La torre de desafíos fue mi primer proyecto de programación en todo el curso, sirvió para aprender las bases de Unity y aprender a programar diferentes funciones, notoriamente aprendí de eventos, corrutinas, y fue el inicio de aprender de importe y configuración de animación dentro de Unity.

<p align="center">
<img src="https://github.com/TiredProgrammer70/Porfolio/assets/109514725/f8b45d3a-f88b-4c19-b0ce-c647033bc4f4" width="50%" height="50%">
</p>


Mi aportación en el proyecto fue un poco más de la mitad, ya que lo cree con un compañero de ciclo, me ayudo a mejorar mi trabajo en equipo a la hora de programar.

[Descargar](https://drive.google.com/file/d/1wiRNdZfgetoRrpQHFs_arkirY8-vLujm/view?usp=drive_link)

![telefono](https://github.com/TiredProgrammer70/Portfolio/assets/109514725/5c35fc08-1b9b-48b0-b1f0-e84662a5a98f)
 667 96 94 15
 ![correo](https://github.com/TiredProgrammer70/Portfolio/assets/109514725/669e52b0-1ace-4890-96ec-4e1729ec2414) jsellares01@gmail.com

[![LinkedIn](https://github.com/TiredProgrammer70/Portfolio/assets/109514725/54f8e276-28b3-4f53-a695-94c3d372c22b)](https://www.linkedin.com/in/jordi-sellares-0ba95b235/?locale=es_ES) [LinkedIn](https://www.linkedin.com/in/jordi-sellares-0ba95b235/?locale=es_ES)
