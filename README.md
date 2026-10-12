# Mi Cancionero

Visor de canciones con acordes para celular y PC: la letra se adapta al ancho de la pantalla, con cambio de tono, tamaño de letra, columnas y desplazamiento automático. Se puede instalar como app y usar sin conexión.

Abrir: https://jonatanquiro.github.io/cancionero/

## Agregar canciones para todos los dispositivos

1. Subí el `.txt` del tema a la carpeta `canciones/`.
2. Agregá su entrada en `canciones.json`:

```json
{ "titulo": "…", "artista": "…", "archivo": "canciones/nombre.txt", "tono": "C", "capo": 0, "genero": "Rock" }
```

Los temas cargados con «Nueva canción» quedan solo en ese dispositivo; el botón «Archivos para GitHub» de cada tema arma el `.txt` y la entrada para subirlos acá.
