1. Creación del Repositorio en GitHub
  1. Inicien sesión en GitHub y creen un nuevo repositorio llamado taller-git-python (público).
  Para esto nos ubicamos en el menú principal de GitHub, donde vamos a ubicar este botón verde que dice New o Nuevo y la vamos a presionar, al presionarlo nos encontramos con diversas opciones y le vamos a dar el nombre al repositorio.
  2. No seleccionen la opción de inicializar con README, para hacerlo manualmente después.
  Simplemente no presionamos la casilla de README, después presionamos el botón verde para crear el repositorio.
  3. Copien la URL del repositorio.
  En cuanto terminemos la creación nos encontramos con otro menú, donde nos vamos a ir a este apartado para copiar los comandos que nos permiten clonar el repositorio a nuestro cmd.
2. Clonación del Repositorio y Creación de Archivos
  1. En su terminal o línea de comandos, clonen el repositorio en su computadora.
  En nuestro cmd nos movemos a la carpeta que vamos a trabajar con “cd” y ya en ella pegamos el comando anteriormente mencionado.
  2. Dentro del repositorio clonado, creen un directorio llamado app y dentro de él, creen tres archivos Python con el nombre y contenido que desee.
3. Seguimiento y Confirmación de Cambios (Commits)
  1. Verifiquen el estado del repositorio:
  Se utilizó el comando después de añadir los archivos
  2. Agreguen los archivos al seguimiento de Git.
  Se usó el “add .” para agregar todos los archivos no rastreados y después el commit para confirmarlos
  3. Realicen un commit con un mensaje descriptivo.
  4. Suban los cambios al repositorio remoto.
4. Creación y Uso de Ramas
  1. Creen una nueva rama para agregar una nueva funcionalidad.
  2. En la rama nueva-funcionalidad, modifiquen dos de los scripts Python.
  Se cambio a la rama con “git checkout”
  3. Confirmen los cambios y súbanlos a GitHub:
  Se agregan los archivos al área de preparación, después se realiza el commit y para finalizar lo subimos a github con el push pero lo modificamos para que se suba a la rama en la que nos encontramos. 
5. Fusionar Ramas y Mantener el Repositorio Sincronizado
  1. Fusion nueva-funcionalidad con main.
  Primero nos movemos a la rama main con “Checkout” y con “Merge” las fusionamos.
  2. Confirme que la fusión fue realizada.
  3. Actualicen el repositorio con los cambios de main.
6. Cambios en GitHub y Sincronización Local
  1. Desde GitHub, editen directamente uno de sus archivos del repositorio
  Nos metemos a GitHub y entramos a la carpeta “app”, dentro de ella seleccionamos el archivo a modificar, y al seleccionar el campo a modificar se nos abre otro apartado, donde continuamos la modificación.
  2. Guarden los cambios y confirmen la edición en GitHub.
  Después de la anterior modificación presionamos el botón verde que dice Commit changes, en la ventana emergente le agregamos un mensaje al commit y nuevamente presionamos el botón verde.
  3. En su computadora, actualicen el repositorio con los cambios remotos.
  4. Verifiquen que el archivo modificado en GitHub ahora contiene la nueva versión del archivo.
