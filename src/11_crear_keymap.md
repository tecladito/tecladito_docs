# Creando tu keymap

Para cambiar el keymap, tenes que ir al siguiente directorio:

```shell
    ...piosic/keymaps/
```

Dentro del mismo, hay 3 directorios que funcionan como base para el layout de cada teclado.


```shell
    keymaps/
    ├─ large
    ├─ medium
    └─ small
```

Tomemos como ejemplo el tecladito large, para cambiar el layout tenemos que modificar el archivo keymap.c

Dentro de este archivo, hay una lista de caracteres, delimitados con comas.
Como habras notado, estos caracteres no tienen nombres 100% equivalentes a las teclas que buscas, para encontrar el 'alias' de QMK para cada tecla, podes usar [esta parte de la documentacion](https://docs.qmk.fm/keycodes).

# Capas

{wip}


