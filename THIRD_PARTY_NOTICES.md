# Avisos de terceros

Esta aplicación incluye o utiliza los siguientes proyectos. Los textos completos
de sus licencias están disponibles en los proyectos originales.
La oferta escrita que acompaña a la aplicación está en `SOURCE-OFFER.txt` u
`OFERTA-DE-CODIGO-FUENTE.txt`, según el paquete.

## Ejecutables incluidos

| Proyecto | Versión | Licencia | Código fuente |
|---|---|---|---|
| yt-dlp | 2026.08.19 | GPL-3.0-or-later | https://github.com/yt-dlp/yt-dlp |
| yt_dlp_ejs (incluido en yt-dlp.exe) | 0.8.0 | (con yt-dlp) | distribución oficial de PyInstaller |
| Deno | 2.9.6 | MIT | https://github.com/denoland/deno |
| FFmpeg / ffprobe (Gyan essentials) | 9.0.1 | GPL-3.0-or-later | https://github.com/GyanD/codexffmpeg |

FFmpeg es una compilación estática con licencia GPLv3 que incluye libx264 y
libmp3lame. El código fuente correspondiente está disponible en la publicación
de la misma versión de GyanD/codexffmpeg.

## Escudo del club

`static/escudo-cai.svg` reproduce sin modificar el escudo del Club Atlético
Independiente, en su aplicación primaria sobre fondo rojo, tal como se publica
en el manual de marca oficial del club
(https://clubaindependiente.com.ar/sitios/identidad/descargas/brandbook-2023.pdf).
El escudo, el nombre y los colores del club son marcas registradas de Club
Atlético Independiente; esta aplicación no está afiliada al club ni cuenta con
su aval.

## Tipografías incluidas

| Proyecto | Versión | Licencia | Código fuente |
|---|---|---|---|
| Barlow / Barlow Condensed | v13 (Google Fonts) | OFL-1.1 | https://github.com/jpt/barlow |

La interfaz incluye los archivos `static/fonts/barlow-*.woff2`, subconjunto
latino de las tipografías Barlow y Barlow Condensed de Jeremy Tribby. El texto
completo de la licencia SIL Open Font License 1.1 se distribuye junto a ellas en
`static/fonts/OFL.txt`.

## Dependencias de Rust y JavaScript

Las licencias de las dependencias de Rust se verifican con `cargo deny check`.
Las licencias de los paquetes de la interfaz se pueden consultar con
`pnpm licenses list`.

## Instalador de Brave

Si no están instalados Firefox ni Brave, la aplicación puede descargar el
instalador oficial estable de Brave para la cuenta de Windows,
`BraveBrowserStandaloneSilentSetup.exe`, desde
https://github.com/brave/brave-browser/releases . Brave se descarga por separado
y no se elimina al desinstalar esta aplicación.
