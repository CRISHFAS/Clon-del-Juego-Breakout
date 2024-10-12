# Breakout Game Clon

Este proyecto es una implementación de un clásico juego tipo "Breakout" utilizando HTML5, JavaScript y el elemento `<canvas>`. El jugador controla una paleta que se mueve a izquierda y derecha para hacer rebotar una pelota y romper ladrillos dispuestos en la parte superior del lienzo. El objetivo es destruir todos los ladrillos sin que la pelota caiga al fondo del lienzo.

## Características

- **Juego interactivo**: Controla la paleta con las flechas del teclado o moviendo el mouse.
- **Elementos gráficos**: El juego se desarrolla en un lienzo de 800x600 píxeles, ofreciendo una mejor experiencia visual con más espacio para jugar.
- **Bricks y colisiones**: Rompe ladrillos de colores al hacer rebotar la pelota. La pelota cambia de dirección cada vez que golpea un ladrillo.
- **Sistema de vidas**: El juego termina cuando la pelota cae al fondo y no puedes devolverla con la paleta.
- **Iniciar partida manualmente**: El juego comienza solo después de hacer clic en un botón de inicio, lo que te da tiempo para prepararte antes de que la pelota empiece a moverse.

## Instrucciones

1. Usa las **flechas izquierda y derecha** del teclado para mover la paleta y hacer rebotar la pelota.
2. También puedes mover la paleta utilizando el **mouse**.
3. **Evita que la pelota caiga** al fondo del lienzo.
4. **Rompe todos los ladrillos** para ganar el juego.

## Funcionalidades

- **Control de movimiento**: La paleta se puede mover utilizando tanto el teclado como el ratón.
- **Detección de colisiones**: El juego detecta colisiones entre la pelota y los ladrillos, eliminando ladrillos cuando son golpeados.
- **Rebotes dinámicos**: El ángulo de rebote de la pelota cambia dependiendo de dónde golpea la paleta, lo que añade un nivel de dificultad.
- **Botón de inicio**: El juego no comienza automáticamente; debes pulsar el botón de "Iniciar juego" para empezar.
- **Lienzo de mayor tamaño**: El lienzo tiene un tamaño de 800x600 píxeles, ofreciendo más espacio para mover la pelota y los ladrillos.

## Cómo jugar

1. **Clona** este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/CRISHFAS/Clon-del-Juego-Breakout

2. Abra el archivoindex.html en su navegador web para comenzar a jugar.

3. Haz clic en el botón de "Iniciar juego" y disfruta del reto.

## Tecnologías utilizadas

- HTML5 Canvas para renderizar el juego en el navegador.

- JavaScript para la lógica del juego y las físicas de colisión.

- jQuery para la gestión de eventos del teclado y del ratón, mejorando la interactividad.

### Futuras mejoras

- Niveles avanzados : Se agregarán más niveles con mayor dificultad, brindando una experiencia más desafiante.

- Sistema de puntuación : Implementar una puntuación que muestre cuántos ladrillos han destruido.

- Efectos de sonido : Incorporar sonidos para las colisiones y el avance de nivel.

- Poderes especiales : Añadir elementos como bolas dobles, disparos desde la paleta o ladrillos especiales.

#### Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar o encuentras algún error, no dudes en crear un problema o hacer una solicitud de extracción.

¡Gracias por jugar! Si te gusta el juego, no olvides darle una estrella a este repositorio.

