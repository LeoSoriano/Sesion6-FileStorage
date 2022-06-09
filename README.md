# DATOS Y ALMACEN

**Storage: Proporciona servicios de almacenamiento de archivos y objetos.**

### Cuenta de Almacenamiento de Azure

![Almacenamiento de Azure](Imagenes/azurealmacenamiento1.png)

- **Modelo de servicio:** IaaS.
- **Caracteristicas:** Seguridad, alta, disponibilidad, durabilidad y escalabilidad.

La cuenta de almacenamiento de es la que contiene todos los objetos de los demas servicios.

-----------------------------------------------------------------------------------

## Azure File Storage

![Azure File Storage](Imagenes/azureFileStorage1.png)

Almacena archivos mas pequeños, controla mejor su acceso, archivos mas privados o tambien para migrar de un ambiente local a Azure.

Controla mejor los archivos, funciona como disco duro de todas las maquinas virtuales.

- **Modelo de servicio:** IaaS.
- **Funcion:** Para compartir archivos y controlar su acceso.
- **Funcion:** Facilita la migracion de local a Azure.
- **Funcion:** Acceso de archivos desde varias maquinas virtuales.
- **cuando usar:** Compartir datos a traves del mundo.

---------------------------------------------------

#### Pasos para crear un File Storage

1.- Abrimos el [Portal Azure](https://portal.azure.com/)

2.- Nos vamos al almacen que tenemos creado

3.- Nos vamos a la parte de recursos compartidos de archivos

![Recursos Compartidos](Imagenes/recursoscompartidos.JPG)

4.- Creamos un recurso compartido de Archivos

![Creamos un Recurso Compartido](Imagenes/creamosunrecursocompartido.JPG)

5.- Entramos al recurso llamado *glosario*

![Entrar al Recurso](Imagenes/glosario.JPG)

6.- Una ves dentro del recurso, subiremos un archivo 

![Subir Archivo](Imagenes/subirarchivoaGlosario.JPG)

7.- Iremos subido el archivo y tambien, podremos cambiar el nivel en caso de necesitarlo.

![Podremos Cambiar el nivel](Imagenes/cambiodenivel.JPG)

8.- Si queremos conectar el recurso desde  windows osea nuestra propia maquina, debemos darle en conectar y copiar ese comando que nos da.

![Conecta](Imagenes/conectarawindows.JPG)

9.- Ahora abrimos PowerShell Windows.

![PowerShell](Imagenes/windowsPowerShell.JPG)

10.- Copiamos el codigo y le damos enter

![Codigo](Imagenes/codigoenpowershell.JPG)

11.- Para que esto funcione, debes de tener activada tu sesion en tu computadora y en azure, debe ser la misma.

![Ahi esta](Imagenes/ahiestaelarchivo.JPG)

12.- Podemos crear carpetas, eliminar, agregar,etc.

13.- Desde aqui podemos contralar cada uno de los recursos,controlar el acceso,podemos modificar o  conectarnos a este recurso de file storage.

-----------------------------------------------------------------------------------
