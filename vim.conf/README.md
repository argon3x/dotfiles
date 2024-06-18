# Archivo de configuración vim o neovim

## Descripción

Este archivo contiene las configuraciónes basicas para el uso de vim o neovim, también contiene algunos shortcuts
de utilidad, el unico punto importante a tener en cuenta es la instalación.

### Instalacion para **vim**

* Copiar o Mover el archivo al HOME

```bash
 $ cp $PWD/vim $HOME/.vimrc

 $ mv $PWD/vim $HOME/.vimrc
```

* Hacer un enlace simbolico

```bash
 $ ln -svf $PWD/vim $HOME/.vimrc
```

### Instalacion para **neovim**

* Crear el directorio **nvim**

```bash
 $ mkdir -m 700 -p $HOME/.config/nvim
```

```bash
 $ cp $PWD/vim $HOME/.config/nvim/init.vim

 $ mv $PWD/vim $HOME/.config/nvim/init.vim
```

* Hacer un enlace simbolico

```bash
 $ ln -svf $PWD/vim $HOME/.config/nvim/init.vim
```

#### Shortcuts

* pulsar doble `Esc` para limpiar los resultados de las busquedas al usar `/busqueda`

* desplasarse con `ctrl` **+** `h`,`j`,`k`,`l` en modo `INSERT`
