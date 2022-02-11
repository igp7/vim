# Comandos vim

## Configuracion
El fichero de configuración de vim es `.vimrc` y suele estas ubicado en `$HOME`.

## Modos
- **INSERT:** En este modo se permite insertar y editar ficheros. Para establecer el modo `insert` presionar la tecla `i` o `a` y se pasara a estar en modo `insert`.
- **VISUAL:** En este modo se permite seleccionar texto del fichero.  Para establecer el modo `visual` presionar la tecla `v` y se pasara a estar en modo `visual`.

**Nota:** Para salir de cualquier modo presionar `ESC`.

## Comandos Básicos
### Configuración visual
|Comando|DESCRIPCIÓN|
|---|---|
|:set nu|Muestra el numero de cada linea|
|:set nu!|Quita el numero de cada linea|
|:set background <color>|Cambia colores de visualización|

### Desplazamiento
|Comando|DESCRIPCIÓN|
|---|---|
|h|Moverse un carácter a la izquierda|
|j|Moverse una fila a bajo|
|k|Moverse una fila a arriba|
|l|Moverse un carácter a la derecha|
|w|Moverse al inicio de la siguiente palabra|
|b|Moverse al principio anterior de la palabra|
|e|Moverse al final de la palabra|
|W|Moverse al inicio de la siguiente palabra después de un espacio en blanco|
|B|Moverse al principio de la palabra anterior antes de un espacio en blanco|
|E|Moverse al final de la palabra antes de un espacio en blanco|
|gg|Moverse al inicio del fichero|
|G|Moverse al final del fichero|

### Guardado y salir de ficheros
|Comando|DESCRIPCIÓN|
|---|---|
|:q|Salir del fichero sin guardar|
|:q!|Salir del fichero sin guardar y sin preguntar|
|:w|Guarda cambios del fichero, pero no sale del fichero|
|:wq|Guarda los cambios y sale del fichero|
|:x|Guarda los cambios y sale del fichero|


## Edición de un fichero
|Comando|DESCRIPCIÓN|
|---|---|
|d|Corta la linea seleccionada previamente|
|dd|Selecciona y cortar la linea sobre la que esta el cursor|
|p|Pegar la linea debajo de la linea en la que esta el cursor|
|y|Copia la linea seleccionada previamente|
|yy|Selecciona y copiar linea sobre la que esta el cursor|
|o|Crea una linea vaciá debajo de la linea en la que esta el cursor y entra en modo insert|
|d<numero>d|Corta un <numero> de lineas por debajo|
|y<numero>y|Copiar un <numero> de lineas por debajo|
|u|Deshacer un cambio|
|<Ctrl> + r|Rehacer un cambio|


## Buscar
|Comando|DESCRIPCIÓN|
|---|---|
|/<texto>|Busca <texto> en el fichero|
|n|Desplazamiento a la siguiente coincidencia|
|N|Desplazamiento a la anterior coincidencia|
