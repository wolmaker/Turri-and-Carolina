# Turri and Carolina

**Turri** (para la PC con Windows) y **Carolina** (para el televisor o el celular con Android) son dos programas para jugar en la tele los juegos de tu PC por la red de tu casa, usando un mando. Se manejan totalmente en español.

| | Turri | Carolina |
|---|---|---|
| Dónde se instala | PC con Windows (el anfitrión) | Android TV, TV box o celular |
| Basado en | [Apollo](https://github.com/ClassicOldSong/Apollo) (que viene de [Sunshine](https://github.com/LizardByte/Sunshine)) | [Artemis](https://github.com/ClassicOldSong/moonlight-android) (que viene de [Moonlight](https://github.com/moonlight-stream/moonlight-android)) |
| Qué hace | Captura la pantalla, el sonido y los juegos de la PC y los envía | Recibe la imagen y el sonido y envía el mando a la PC |

---

## Por qué nace este proyecto

Todo empezó con un problema muy común: jugar en un televisor Philips Android TV con un mando GameSir T7 conectado por USB, pero sin vibración. En internet la respuesta era siempre la misma: "no tiene solución".

En vez de aceptarlo, tomamos dos proyectos libres muy buenos, **Apollo** y **Artemis**, y los adaptamos a lo que de verdad necesita alguien que juega desde el sofá:

- Todo en español, con nombres claros. Por ejemplo, "Salir de la sesión de Carolina" y "Desconectar totalmente de la PC".
- **Modo PC**: el mando funciona como mouse y teclado, con un teclado en pantalla que tiene ñ y acentos. Así puedes manejar Windows sin levantarte.
- **Botones configurables**: puedes cambiar lo que hace cada botón desde una guía con el dibujo del mando.
- Un menú por columnas, con efecto de vidrio, que se abre manteniendo presionado el botón Menú.
- El monitor de la PC vuelve a la normalidad cuando cierras la sesión.
- Fondos, logos, música y sonidos propios.

La vibración del T7 sigue bloqueada por el firmware de ese televisor. Este proyecto nació de esa limitación y la convirtió en algo mejor.

---

## Por qué se llaman Turri y Carolina

A comienzos del siglo XIX, en Italia, la condesa **Carolina Fantoni da Fivizzano** perdió la vista. Ya no podía escribir sus cartas a mano sin ayuda.

Su amigo, el inventor **Pellegrino Turri** (1765–1828), construyó para ella una máquina para escribir, entre 1801 y 1808 según la fuente. Fue **una de las primeras máquinas de escribir de la historia**. Para que la máquina tuviera tinta, Turri inventó además el **papel carbón**.

Todavía se conservan cartas que Carolina escribió con esa máquina. En ellas lo llama "mi querido amigo" y le cuenta cómo va aprendiendo a usarla. La tradición, y hasta una novela, los recuerdan como enamorados. Sea amistad o amor, lo que queda es lo mismo: **alguien inventó algo imposible para acortar la distancia con otra persona.**

De esa necesidad tan humana nacieron algunas bases de la comunicación moderna: el teclado, la escritura a máquina y las copias. Sobre ellas se construyó después la tecnología que hoy nos conecta.

Este proyecto quiere honrar eso:

- **Turri** es el que construye y envía, como la máquina que él hizo.
- **Carolina** es la que recibe y responde, como las cartas que ella escribía.

Dos partes que, juntas, reducen la distancia entre la PC y la tele.

---

## Cómo se compila

Ambos se compilan solos con **GitHub Actions** (pestaña *Actions*):

- **Carolina**: aplica `carolina.patch` sobre Artemis y genera el APK (artefacto *Carolina-APK*). En televisores usa el **armeabi-v7a**.
- **Turri**: aplica `turri.patch` sobre Apollo v0.4.6 y genera el instalador para Windows (artefacto *Turri-instalador*).

## Apoya el proyecto

Turri y Carolina son gratuitos y siempre lo serán. Si te sirvieron y quieres ayudar a que sigan mejorando, tienes dos formas de hacerlo:

**💜 Apoyo mensual en Patreon** (desde 1 dólar al mes)

[![Apoyar en Patreon](https://img.shields.io/badge/Apoyar-Patreon-F96854?logo=patreon&logoColor=white&style=for-the-badge)](https://www.patreon.com/c/jordan861/membership)

**📚 O compra un libro de arte restaurado**

Si prefieres no suscribirte, puedes apoyar comprando uno de los libros de dibujo restaurados de mi tienda. Ayudas al proyecto y te llevas un libro de arte.

[![Visitar la tienda](https://img.shields.io/badge/Tienda-Libros%20de%20arte-F96854?logo=patreon&logoColor=white&style=for-the-badge)](https://www.patreon.com/c/jordan861/shop)

Cualquier aporte ayuda. Gracias de corazón.

Si quieres apoyar también a quienes hicieron posible la base, visita las páginas de [Apollo/Artemis](https://github.com/ClassicOldSong), [Sunshine](https://github.com/LizardByte/Sunshine) y [Moonlight](https://moonlight-stream.org).

## Créditos y licencia

Turri y Carolina son trabajos derivados y se distribuyen bajo la misma licencia que sus originales, **GPL-3.0**. Todo el mérito del motor de streaming es de sus autores:

- [Apollo](https://github.com/ClassicOldSong/Apollo) y [Artemis](https://github.com/ClassicOldSong/moonlight-android): ClassicOldSong
- [Sunshine](https://github.com/LizardByte/Sunshine): LizardByte
- [Moonlight](https://github.com/moonlight-stream): el equipo de Moonlight

Las imágenes, los logos y la música de Turri y Carolina son del autor de este proyecto.
