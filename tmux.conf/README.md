# Archivo de configuración tmux

## Descripción

Esté es un archivo de configuración para darle un estilo a `tmux`

El `prefix` que usa por defecto es `alt+f` pero puede ser remplazado por cualquier otro, ya sea usando \
`ctrl` o `alt` seguido de cualquier letra, solo se tienen que modificar las lineas `6` `7` y `8` ya que \
son variables que almacenarán el nuevo prefix, y la forma en la que se dividen los paneles ya sea de \
forma horizontal o vertical.

Tomar en cuenta que para usar `ctrl` se usa `C` y para `alt` se utiliza `M` seguido de una letra para configurar
el nuevo prefix.

## Instalación

* puedes copiar o mover el archivo `tmux.conf` a tu home

```bash
 $ cp $PWD/tmux.conf $HOME/.tmux.conf
 
 $ mv $PWD/tmux.conf $HOME/.tmux.conf
```

* o puedes hacer un enlace simbólico

```bash
 $ ln -svf $PWD/tmux.conf $HOME/.tmux.conf
```

> NUEVO FEATURE:
  el archivo de configuración tiene dos estilos, los cuales son (diamante y agnoster) por defecto es agnoster
  para usar uno u otro, se debe comentar las lineas necesarias que estan en la sección 
  **Configuración de la barra de estado**

## Nota

para poder visualizar bien los iconos (`unicode`) se debe tener instalada una fuente de tipo NerdFonts, referencia: [https://www.nerdfonts.com/](https://www.nerdfonts.com/)

## Screenshot

* Estilo agnoster (por default)
![Screenshot-1](screen-1.png)

* Estilo diamante
![Screenshot-2](screen-2.png)
