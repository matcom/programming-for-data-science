# Tutorial para instalar y configurar Git en Linux

## 1. Actualizar la lista de paquetes

Antes de instalar Git, debemos asegurarnos de que la lista de paquetes de nuestro sistema esté actualizada. Podemos hacerlo ejecutando el siguiente comando en la terminal:

```bash
sudo apt update
```

## 2: Instalar Git

Para instalar Git, simplemente ejecuta el siguiente comando en la terminal:

```bash
sudo apt install git
```

Esto instalará la versión más reciente de Git en tu sistema.

## 3: Verificar la instalación de Git

Después de instalar Git, podemos verificar si se ha instalado correctamente ejecutando el siguiente comando en la terminal:

```bash
git --version
```

Este comando mostrará la versión de Git instalada en tu sistema.

## 4: Configurar Git

Antes de comenzar a usar Git, es importante configurarlo con tu nombre de usuario y dirección de correo electrónico. Puedes hacerlo ejecutando los siguientes comandos en la terminal:

```bash
git config --global user.name "Tu nombre de usuario"
git config --global user.email "tu@correo.com"
```

Reemplaza `"Tu nombre de usuario"` y `"tu@correo.com"` con tus propios datos.

## 5: Configurar Git para el manejo de lineas de fin de línea (EOL)

El manejo de los caracteres de fin de línea (EOL) puede causar problemas de compatibilidad en diferentes sistemas operativos. Para evitar estos problemas, se puede configurar Git para que maneje automáticamente los caracteres de fin de línea. Se puede hacer ejecutando el siguiente comando en la terminal:

```bash
git config --global core.autocrlf input
```

Con esta configuración, Git convertirá automáticamente los caracteres de fin de línea en el formato Unix (LF) cuando los archivos se agreguen al repositorio.

## 6: Verificar la configuración de Git

Para verificar la configuración de Git, puedes ejecutar el siguiente comando en la terminal:

```bash
git config --list
```

Este comando mostrará la configuración de Git en tu sistema.

¡Eso es todo! Ahora has instalado y configurado Git en tu sistema Linux. Puedes comenzar a utilizar Git para controlar versiones de tus proyectos.
