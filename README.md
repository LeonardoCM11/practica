# Comandos Básicos

- En la clase de hoy vamos a ejecutar diferentes comandos de git

## Git Clone

El comando `git clone` se utiliza para crear una copia local de un repositorio que se encuentra en un servidor remoto (como GitHub o GitLab).

A diferencia de una descarga común, este comando descarga **todo el historial de versiones** y configura la conexión con el servidor de origen.

![Git Clone](img/git-clone.png)

### Línea de comando

Para clonar un repositorio en tu computadora, ejecuta:

```bash
git clone [https://github.com/usuario/nombre-del-proyecto.git](https://github.com/usuario/nombre-del-proyecto.git)

```
# Ejercicio
- haz lo anterior con lo siguiente (colocando una captura de pantalla en cada comando):



- git init Inicia git en la ubicacion actual
- git add . agrega todos los cambios al area de preparacion
- git commit crea un comentario en todos los cambis
- git branch gh-pages crea una rama
- git checkout gh-pages se cambia a la rama seleccionada 
- git remote add origin https://github.com.... conecta un repositorio
- git push origin se suben los cambios
