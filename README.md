# RandomLab

Editor de equipos Pokémon para **Randomlocke**. Un solo archivo HTML, sin instalación ni servidor: ábrelo en el navegador y listo.

![Demo de RandomLab](demo.gif)

## Funciones

- Una partida por run, con nombre de personaje y cartucho (de Rojo/Azul a Escarlata/Púrpura).
- Equipo de 6, 8 cajas de 30, cementerio de caídos y arrastrar y soltar.
- Pokédex, ataques y objetos filtrados por la generación del juego elegido.
- Registro de capturas por ruta.
- Calculadora de EVs, IVs y naturaleza.
- Copia de seguridad y restauración en archivo `.json`.

## Uso

Descarga `RandomLab.html` y ábrelo en tu navegador. Necesita conexión a internet la primera vez, para descargar los datos y los sprites. Los datos se guardan en caché en tu navegador.

## Privacidad

Todo se guarda en el `localStorage` de tu navegador. No hay servidor ni cuentas, y no se envía nada a ningún sitio. Si borras los datos del navegador pierdes las partidas, así que usa **Guardar copia** de vez en cuando.

## Limitaciones conocidas

- En los juegos de Switch (Leyendas Arceus, Diamante/Perla Reinventados, Espada/Escudo) el filtrado se hace por generación, no por el contenido exacto del juego. Puede aparecer algún ataque u objeto que ese juego no tiene.
- Unos ~25 stats base cambiados en gen 6 no se guardan por generación.
- Rotom, Giratina Origen y Shaymin Cielo salen desde cualquier juego de gen 4 (en realidad desde Platino).

## Carpetas opcionales

`cartuchos/` (imágenes de cartuchos), `musica/` e `intros/` (vídeos) no se incluyen en el repositorio. Si no existen, la app usa sus gráficos por defecto y la consola muestra errores 404, que son normales.

## Créditos y aviso legal

RandomLab es un **proyecto de fans, sin ánimo de lucro y sin ninguna relación con** Nintendo, Game Freak, Creatures Inc. ni The Pokémon Company. Pokémon y todos los nombres, sprites y marcas asociados son propiedad de sus respectivos dueños.

- Datos: [PokéAPI](https://pokeapi.co/) (CSV y sprites).
- Sprites de entrenadores: [Pokémon Showdown](https://play.pokemonshowdown.com/).
- Fuente: [Pixelify Sans](https://fonts.google.com/specimen/Pixelify+Sans) (SIL Open Font License).

## Licencia

El código se publica bajo licencia [MIT](LICENSE). La licencia **no** cubre los datos, sprites ni marcas de Pokémon.

---

Hecho por **Claude Code**.
