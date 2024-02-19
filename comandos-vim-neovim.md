# Comando VIM / NEOVIM

## Modos Principales

1. MODO NORMAL : tecla `Esc`
    - las teclas insertadas se intermpretan como comandos para la navegacion, edicion y manipulacion del texto
      se puede mover, copiar, pegar, borrar, buscar, reemplazar y ejecutar acciones.

2. MODO INSERCION : tecla `i`
    - Se puede insertar el texto y editarlo, el texto que se inserta se interpretaran como caracteres.

3. MODO COMANDO : caracter `:`
    - Se utiliza para ejecutar comandos especificos utlizando el prefix `:` seguido del comando.

**Como moverse en el editor**

- Tecla `h` se mueve a la izquierda.
- Tecla `l` se mueve a la derecha.
- Tecla `k` se mueve hacia arriba.
- Tecla `j` se mueve hacia abajo.

**Como insertar texto**

- Tecla `i` inserta a la izquierda donde se encuentra el cursor.
- Tecla `a` inserta a la derecha donde se encuentra el cursor.
- Tecla `I` inserta al principio de la linea.
- Tecla `A` inserta al final de la linea.

**Como moverse entre palabras**

- Tecla `w` avanza por palabra con el cursor al principio de cada palabra.
- Tecla `e` avanza por palabra con el cursor al final de cada palabra.
- Tecla `b` retrocede por palabra con el cursor al principio de la palabra.

### *Esta es una lista de comandos que utilizan los editores de texto vim / neovim*

- Abrir un archivo con `vim` / `neovim`.

```bash
 vim archivo
```

```bash
 nvim archivo
```

- Guardar cambios.

```bash
 :w
```

- Guardar cambios de forma forzada.

```bash
 :w!
```

- Salir del editor.

```bash
 :q
```

- Salir del editor de forma forzada.

```bash
 :q!
```

- Guardar y Salir.

```bash
 :wq
```

- Guardar y Salir de forma forzada.

```bash
 :wq!
```

- Eliminar caracater por caracter

```bash
 # usar Esc (modo normal)
 # pulsar `x` 
```

- Elimnar todo lo que este despuede del cursor

```bash
 # usar Esc (modo normal)
 # pulsar `D`
```

- Eliminar una linea completa o X cantidad de lineas hacia abajo

```bash
 # usar Esc (modo normal)
 # pulsar `dd` o `d10d`
```

- Deshacer o Rehacer

```bash
 # usar Esc (modo normal)
 # deshacer pulsar `u` 
 # rehacer pulsar `ctrl+r`
```

- Eliminar el contenido desde la lina actual hasta la linea final

```bash
 # usar Esc (modo normal)
 # pulsar `dG`
```

- Eliminar palabra por palabra

```bash
 # usar Esc (modo normal)
 # pulsar `dw` o `db`
```

- Copiar una linea o varias lineas

```bash
 # usar Esc (modo normal)
 # pulsar `yy` o `y10y`
```
 
- Avanzar palabra por palabra

```bash
 # usar Esc (modo normal)
 # pulsar `w` o `e`
```

- Retroceder palabra por palabra

```bash
 # usar Esc (modo normal)
 # pulsar `b`
```

- Ir al final del Archivo

```bash
 # usar Esc (modo normal)
 # pulsar `G`
```

- Ir al principio del Archivo

```bash
 # usar Esc (modo normal)
 # pulsar `gg`
```

