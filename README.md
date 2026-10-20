# Fontana en realidad aumentada

Apuntás el celular a la lámina de Fontana y aparece parado encima. Podés hablarle o escribirle igual que en su página 3D.

## Qué hay en la carpeta
- `index.html`: la página completa (figura 3D, voz y realidad aumentada).
- `lamina-fontana-A4.pdf` y `lamina-fontana.jpg`: la lámina marcadora para imprimir en A4.

## Publicarlo en GitHub Pages
1. Creá un repositorio (por ejemplo `fontana-ra`) y subí `index.html` y la lámina.
2. En **Settings → Pages**, elegí la rama `main` y la carpeta `/ (root)`. Guardá.
3. En uno o dos minutos queda en `https://TU-USUARIO.github.io/fontana-ra/`.

La cámara solo funciona con https, por eso hay que publicarlo: abriendo el archivo suelto en el celular no anda. Tampoco anda dentro de un artefacto de Claude, porque ahí se bloquean la cámara y el micrófono.

## Cómo se usa
1. Imprimí la lámina (o mostrala en otra pantalla).
2. Abrí la página en el celular y tocá **Verlo con la cámara**. Aceptá el permiso de la cámara.
3. Enfocá la lámina: Fontana aparece con un sonido de bienvenida.
4. Tocá **Hablar** para conversar (pide el micrófono) o escribile.
5. Arriba tenés: **Lámina en la mesa / en la pared**, los botones **− +** para el tamaño y **Salir de la cámara**.

Si movés la cámara y se pierde la lámina, Fontana se queda en pantalla y la charla sigue. Al volver a enfocarla se reubica.

## Usar otra imagen
En **Lámina → Usar otra imagen** podés elegir una tapa, afiche o foto con mucho detalle. La página la prepara en el momento y la recuerda en ese navegador.

## A tener en cuenta
- Necesita internet: la voz es un agente de ElevenLabs y cada charla consume créditos.
- Funciona mejor con buena luz, la lámina sin reflejos y un celular de gama media o superior.
- Agente: `agent_6201m4xcywbje6krnz6n8jxatajf`. Si cambiás su prompt o su base en ElevenLabs, también cambia acá.

DIA — Didáctica con IA
