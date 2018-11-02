# Tema para Lakka

* Tema basado en monochrome para la distribución [Lakka](http://www.lakka.tv/) [(Retroarch)](https://www.retroarch.com/).
* Este hack cambia la [fuente a Baloo Bhaijaan](https://fonts.google.com/specimen/Baloo+Bhaijaan) y añade iconos para la playlist **Cochi**
* RetroArch versión 1.7.3

## Playlist y miniaturas


* [Playlist](storage/playlists/)
* [Thumbnails](storage/thumbnails/)

Cada rom de una playlist está compuesta por 6 lineas:

* Path absoluto a la ROM
* Nombre de la ROM a mostrar
* Path absoluto al core para cargar la ROM. Se puede usar DETECT
* Nombre del core (deprecado)
* Link a la entrada de la base de datos. Se puede usar DETECT
* El nombre de esta playlist (con la extensión .lpl)

Ejemplo:

```bash
/storage/roms/Nintendo Entertainment System/Bubble Bobble (USA).nes
Bubble Bobble (NES)
/tmp/cores/nestopia_libretro.so
Nintendo - NES / Famicom (Nestopia UE)
D3A91B41|crc
Nintendo - Nintendo Entertainment System.lpl
```

Las miniaturas (thumbnails) deben tener el mismo nombre que la línea 2 (Nombre de la ROM a mostrar). [Más información sobre playlist en libreto](https://docs.libretro.com/guides/roms-playlists-thumbnails/)

## Iconos

El formato de los iconos debe ser:

* png
* 256x256 de tamaño

### Icono de Lakka

![](tmp/assets/xmb/custom/png/lakka.png)

### Icono para la playlist

Debe tener el mismo nombre que la playlist

![](tmp/assets/xmb/custom/png/Cochi.png)

### Icono para los juegos

Debe tener el mismo nombre que la playlist+"-content.png"

![](tmp/assets/xmb/custom/png/Cochi-content.png)

### Fondo de pantalla (opcional)

El fondo de pantalla se configura a parte.

![](tmp/assets/wallpapers/5YK43U9.jpg)