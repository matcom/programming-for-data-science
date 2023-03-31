# Tutorial Básico de Jupyter Lab

Jupyter Lab es un entorno de desarrollo interactivo basado en la web que permite trabajar con cuadernos Jupyter, código y datos. En este tutorial básico, aprenderás cómo utilizar Jupyter Lab.

## Iniciar Jupyter Lab

Para iniciar Jupyter Lab, ejecuta el siguiente comando en tu terminal o línea de comandos:

```bash
jupyter-lab
```

Se abrirá una ventana en tu navegador web con la interfaz de Jupyter Lab.

## Crear un nuevo cuaderno Jupyter

1. En la barra lateral izquierda, haz clic en el icono "+" para abrir el Launcher.
2. Selecciona "Python 3" en la sección "Notebook" para crear un nuevo cuaderno Jupyter con el kernel de Python 3.

## Trabajar con celdas

Los cuadernos Jupyter se componen de celdas que pueden ser de tipo "código" o "markdown".

### Celdas de código

Las celdas de código permiten escribir y ejecutar código Python. Para ejecutar una celda de código, selecciónala y presiona `Shift + Enter` o haz clic en el botón "Run" en la barra de herramientas.

### Celdas de markdown

Las celdas de markdown permiten escribir texto con formato utilizando la sintaxis de Markdown. Para editar una celda de markdown, haz doble clic en ella. Para renderizar el contenido de la celda, presiona `Shift + Enter` o haz clic en el botón "Run" en la barra de herramientas.

## Ejecución de celdas y orden de ejecución

El orden en que ejecutes las celdas en un cuaderno Jupyter puede afectar los resultados. Aunque las celdas se enumeran en un orden secuencial, puedes ejecutarlas en cualquier orden. Al ejecutar una celda, Jupyter asigna un número de ejecución en el margen izquierdo de la celda de código, que indica el orden en que se ha ejecutado. 

Es importante tener en cuenta que las variables y funciones definidas en una celda se almacenan en el kernel y están disponibles para su uso en otras celdas, independientemente de su posición en el cuaderno. Si ejecutas celdas en un orden diferente al secuencial, podrías experimentar resultados inesperados debido a cambios en el estado del kernel.

Si deseas restablecer el estado del kernel y ejecutar todas las celdas en orden, puedes hacer clic en "Kernel" en la barra de menús y seleccionar "Restart Kernel and Run All Cells...".

## Guardar y exportar cuadernos

Para guardar tu cuaderno, haz clic en "File" en la barra de menús y selecciona "Save Notebook" o presiona `Ctrl + S`.

Para exportar tu cuaderno a otro formato, como PDF o HTML, haz clic en "File" en la barra de menús y selecciona "Export Notebook As...".

## Detener el kernel y cerrar Jupyter Lab

Para detener el kernel de un cuaderno, haz clic en "Kernel" en la barra de menús y selecciona "Shutdown Kernel".

Para cerrar Jupyter Lab, cierra la ventana del navegador y, en la terminal o línea de comandos donde
