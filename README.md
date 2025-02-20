# Sistema de registro
- Primer repositorio para registro de proyectos

Para ejecutar el sistema, debes poner:

```npm install react```

# Comandos para MINGW64 o Git Bash
Para iniciar utilizando el Git Bash, es necesario declarar el usuario y correo electrónico. (Es importante recordar que el email debe ser el mismo que el repositorio a trabajar).
## Configuración
### ```git config --global user.name <name>```

En primer lugar, utilizamos este comando para establecer el nombre de usuario.

### ```git config --global user.email <email>```

Luego, utilizamos este comando para indicar el correo electrónico. Es importante utilizar el mismo correo que el repositorio a trabajar.

### ```git config --list```

Lo utilizamos para comprobar las configuraciones anteriores.

## Crear
### ```git clone <url>```

Es utilizado para clonar el git o repositorio que vamos a trabajar.

Con el git clone también puedes clonar el repositorio para una carpeta específica:

```git clone <repositorio> <mi-proyecto-clone>```

El repositorio localizado en repositorio es clonado para una carpeta llamada:

```mi-proyecto-clone```

También puedes configurar el git clone y clonar el repositorio desde una branch específica, diferente a la original, de esta manera:

```git clone -branch new_feature <repositorio>```

### ```git init```

Para inicializar el repositorio clonado.

## Verificación
### ```pwd```

Para ver las carpetas y archivos de la computadora.

### ```ls```

Para ver la lista del directorio.

### ```cd```

Para entrar a las carpetas.

### ```git log```

Se utiliza para ver el historial del repositorio, quién ha editado archivos, etc.

Podemos visualizar todos los commits, uno en cada línea con el comando:

```git log –oneline```

Si, en lugar de menos informaciones, queremos ver más, como las alteraciones del commit, podemos usar:

```git log -p```

Y buscar informaciones por fecha:

```git log --since=1.month.ago --until=1.day.ago```

Tu también puedes formatear la visualización de las informaciones del commit con el comando:

```git log --pretty="format:%h %s"```

### ```git status```

Sirve para verificar que se hayan subido a la nube los cambios locales. Se debe utilizar el siguiente código para añadir el archivo que se modificó: 

```git add .``` o ```git add <nombre del archivo>```

### ```git diff <Nombre de archivo>```

Lo utilizamos para ver los cambios realizados a un archivo.

## Agregar

### ```git add .```

Para agregar todos los archivos de una sola vez o de un solo movimiento.

### ```git add <archivo>```

Para agregar un archivo en específico.

## Mover

### ```git commit -m "<Nombre del commit>"```

Lo utilizamos para realizar un commit de los cambios realizados a un archivo.

## Enviar/Actualizar

### ```git push```

Una vez que se ha creado el commit, lo utilizamos para subir los cambios realizados de forma local a la nube.

## Bajar/Actualizar

### ```git pull```

Para verificar si el clon está actualizado. En caso de que no, se descargan los cambios realizados de la nube a la computadora local.

## Cambiar

### ```git branch```

Lo utilizamos para ver las ramas que tenemos actualmente.

### ```git checkout -b <nombre de la rama>```

Nos sirve para crear una nueva rama con su respectivo nombre.

### ```git merge <nombre de la rama>```

Utilizamos este comando para fucionar ambas ramas, cabe mencionar que es necesario realizar un switch a la rama principal o main antes de realizar esta operación.

### ```git switch <nombre de la rama>```

Este comando lo utilizamos para cambiar de ramas.

### ```git restore -source <numero de hash> <nombre de archivo>```

Nos sirve para restaurar un archivo a alguna versión previa. Se tiene que colocar el número de hash correspondiente al commit que se desea hacer la restauración.

### ```git push origin <nombre de la rama>```

Para mandar a github en caso de que se esté utilizando una rama diferente.
