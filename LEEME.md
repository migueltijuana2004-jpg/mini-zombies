# Mini Zombies Co-op

Juego de zombis por oleadas inspirado en *Call of Mini Zombies*. Se juega en el navegador, solo o en cooperativo por internet (hasta 4 jugadores).

## Jugar en tu PC (solo)

Dale doble clic a `index.html`. Se abre en tu navegador (Chrome o Edge) y ya puedes jugar.
Necesitas internet porque el juego baja las librerías 3D la primera vez.

## Controles

| Tecla | Acción |
|---|---|
| W A S D | Moverte |
| Shift | Correr |
| Ratón | Apuntar |
| Clic izquierdo | Disparar |
| R | Recargar |
| 1, 2, 3, 4 o la rueda del ratón | Cambiar de arma |
| B | Abrir la tienda (solo entre oleadas) |
| Enter | Empezar la siguiente oleada ya |
| Esc | Pausa / soltar el ratón |

## Publicarlo en GitHub Pages (para jugar con tu hermano)

Esto se hace una sola vez y es gratis:

1. Entra a https://github.com y arriba a la derecha dale a **+ → New repository**.
2. Nombre: `mini-zombies`. Déjalo en **Public**. Dale a **Create repository**.
3. En la página del repo, dale clic al link **uploading an existing file**.
4. Arrastra `index.html` y `LEEME.md` y dale a **Commit changes**.
5. Ve a **Settings → Pages**. En *Branch* elige **main** y **/(root)**, y dale a **Save**.
6. Espera 1 o 2 minutos. Tu juego queda en:
   `https://TU-USUARIO.github.io/mini-zombies/`

## Jugar juntos

1. Tú abres tu link de GitHub Pages y le das a **Crear partida para jugar juntos**.
2. Dale a **Copiar link** y mándaselo a tu hermano por WhatsApp.
3. Él abre el link y le da a **Unirme a la partida**.
4. Otra opción: él abre el juego y escribe el **código de 5 letras** que te aparece.

Tu hermano puede entrar aunque ya hayas empezado. Si pierdes el código, presiona **Esc** para verlo.

**Cómo funciona:** tu computadora es el "anfitrión" y corre la partida. Si cierras tu pestaña, la partida se acaba para los dos.

### Si no se conectan

- Revisen que los dos tengan internet y que el código esté bien escrito.
- Algunas redes (escuelas, oficinas, datos móviles de ciertas compañías) bloquean la conexión directa. Prueben con otra red o compartiendo datos desde un celular.

## Cómo se juega

- Sobrevive a las oleadas de zombis. Cada 5 oleadas aparece un **JEFE**.
- Tipos de zombi: normal, **corredor** (rápido), **gordo** (aguanta mucho) y **jefe**.
- Ganas dinero por cada zombi que matas y un bono al terminar cada oleada. Los tiros a la cabeza hacen el doble de daño.
- Entre oleadas presiona **B** para comprar escopeta, AK-47, lanzacohetes, munición y botiquines.
- Los zombis a veces tiran **munición** (caja amarilla) o **vida** (caja con cruz roja).
- En cooperativo, si te derriban, tu compañero puede revivirte si se queda junto a ti unos segundos. Si derriban a todos, se acaba el juego.

## Cambiar el juego

Todo está en `index.html`. Hasta arriba del código, en la parte de **CONFIGURACIÓN**, puedes cambiar el daño y el precio de las armas o la vida y velocidad de los zombis. Después de cambiarlo, vuelve a subir el archivo a GitHub.
