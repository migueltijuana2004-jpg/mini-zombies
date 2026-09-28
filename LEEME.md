# Mini Zombies Co-op

Juego de zombis por oleadas inspirado en *Call of Mini Zombies* y en el modo zombis de *Call of Duty*. Se juega en el navegador, solo o en cooperativo por internet (hasta 4 jugadores).

**Link del juego:** https://migueltijuana2004-jpg.github.io/mini-zombies/

## Controles

| Tecla | Acción |
|---|---|
| W A S D | Moverte |
| Shift | Correr |
| Ratón | Apuntar |
| Clic izquierdo | Disparar |
| Clic derecho o V | Cuchillo |
| E | Comprar / usar (armas, puertas, máquinas, caja, radios) |
| R | Recargar |
| 1, 2, 3 o la rueda del ratón | Cambiar de arma |
| Enter | Empezar la siguiente oleada ya (solo el anfitrión) |
| Esc | Pausa / soltar el ratón |

## Mapas

- **Ciudad:** calles abiertas, sin puertas. Ideal para empezar.
- **Hospital:** 9 cuartos conectados por puertas que se compran. Empieza sin luz, así que usas tu linterna, y los zombis entran por las ventanas y los ductos de ventilación. Tiene un **easter egg**.
- Próximamente: Escuela, Cárcel, Puente, Pantano y Cementerio.

## Cómo se juega (estilo Call of Duty Zombies)

- **Puntos:** ganas $10 por cada bala que le pega a un zombi y más dinero por cada zombi que matas. Empiezas con $500.
- **Armas en la pared:** acércate a un dibujo de arma y presiona **E**. Si ya la tienes, te vende munición a mitad de precio.
- **Puertas:** cuestan dinero y abren nuevas zonas. Ojo: también salen zombis por ahí.
- **Caja misteriosa ($950):** te da un arma al azar, como el lanzacohetes, la ametralladora o el **Rayo X**.
- **Electricidad:** en el Hospital hay que encenderla en el Cuarto de Máquinas para que funcionen las máquinas de ventajas.
- **Ventajas (máquinas):**
  - **Coraza:** vida 250.
  - **Mano Rápida:** recargas más rápido.
  - **Doble Disparo:** disparas más rápido.
  - **Piernas de Liebre:** corres más rápido.
  - **Resurrección:** en solo te levanta una vez; en equipo revives más rápido.
  - **Tercera Arma:** puedes cargar 3 armas.
  - Las pierdes si te derriban.
- **Máquina de Mejora ($5000):** dobla el daño de tu arma y le da más balas.
- **Power-ups que sueltan los zombis:**
  - **Munición máxima**
  - **Muerte instantánea** (30 s)
  - **Doble puntos** (30 s)
  - **Bomba nuclear** (mata a todos los zombis)
- **Vida:** se recupera sola si no te pegan por unos segundos.
- **Derribado:** puedes seguir disparando. Tu compañero te revive si se queda junto a ti. Si nadie te revive en 30 s, te desangras y vuelves en la siguiente oleada con la pistola.

## Zombis

- **Zombi** y **Corredor:** los normales.
- **Saltador:** brinca hacia ti desde lejos.
- **Escupidor:** te lanza ácido que deja un charco verde. ¡Sal del charco!
- **Explosivo:** tiene la panza naranja. Si se te acerca, parpadea y explota. Si le disparas de lejos, su explosión daña a los otros zombis.
- **Bruto:** ruge y luego te embiste.
- **Jefe:** sale cada 5 oleadas. Da un pisotón (marca un círculo rojo, ¡aléjate!) y llama a otros zombis.

## Easter egg del Hospital: "Paciente Cero"

Escucha las 3 grabaciones de radio (E) para conocer la historia. Si te atoras, el objetivo aparece en la esquina de arriba a la izquierda:

1. Enciende la electricidad.
2. Encuentra las 3 muestras de sangre brillantes (cambian de lugar cada partida).
3. Llévalas a la centrífuga del Laboratorio.
4. Protégela 25 segundos.
5. Mata al Paciente Cero.

Premio: $2500 y se destapa la Máquina de Mejora.

## Jugar juntos

1. Abre el link del juego, elige un mapa y dale a **Crear partida para jugar juntos**.
2. Dale a **Copiar link** y mándaselo a tu hermano.
3. Él abre el link y le da a **Unirme a la partida** (o escribe el código de 5 letras).
4. Tu hermano puede entrar aunque ya hayas empezado. Si pierdes el código, presiona **Esc** para verlo.

Tu computadora es el "anfitrión". Si cierras tu pestaña, la partida se acaba para los dos.

**Si no se conectan:** revisen el código y el internet. Algunas redes bloquean la conexión directa; prueben con otra red o con el hotspot del celular.

## Actualizar el juego en GitHub

1. En tu repositorio de GitHub dale a **Add file → Upload files**.
2. Arrastra el nuevo `index.html` (y `LEEME.md` si cambió) y dale a **Commit changes**.
3. En 1 o 2 minutos el link ya tiene la versión nueva. Si no ves el cambio, recarga con **Ctrl + F5**.

## Cambiar el juego

Todo está en `index.html`. Hasta arriba del código, en la parte de **CONFIGURACIÓN**, puedes cambiar precios, daño de las armas, vida de los zombis, etc.
