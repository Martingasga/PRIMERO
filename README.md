# Sistema de registro
- Primer repositorio para registro de proyectos

Para ejecutar el sistema, debes poner:

```npm install react```

# Comandos para MINGW64 o Git Bash
Para iniciar utilizando el Git Bash, es necesario declarar el usuario y correo electrónico. (Es importante recordar que el email debe ser el mismo que el repositorio a trabajar).
- **pwd**: Para ver las carpetas y archivos de la computadora.
- **ls**: Para ver la lista del directorio.
- **cd**: Para entrar a las carpetas.
- **git clone**: Se utiliza para clonar los repositorios.

Con el git clone también puedes clonar el repositorio para una carpeta específica:

```git clone <repositorio> <mi-proyecto-clone>```

El repositorio localizado en repositorio es clonado para una carpeta llamada:

```mi-proyecto-clone```

También puedes configurar el git clone y clonar el repositorio desde una branch específica, diferente a la original, de esta manera:

```git clone -branch new_feature <repositorio>```

- **git log**: Se utiliza para ver el historial del repositorio, quién ha editado archivos, etc.

Podemos visualizar todos los commits, uno en cada línea con el comando:

```git log –oneline```

Si, en lugar de menos informaciones, queremos ver más, como las alteraciones del commit, podemos usar:

```git log -p```

Y buscar informaciones por fecha:

```git log --since=1.month.ago --until=1.day.ago```

Tu también puedes formatear la visualización de las informaciones del commit con el comando:

```git log --pretty="format:%h %s"```
