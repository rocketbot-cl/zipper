



# Zipper
  
Módulo para comprimir y descomprimir archivos encriptados .zip.  

*Read this in other languages: [English](Manual_zipper.md), [Português](Manual_zipper.pr.md), [Español](Manual_zipper.es.md)*
  
![banner](imgs/Banner_zipper.png)
## Como instalar este módulo
  
Para instalar el módulo en Rocketbot Studio, se puede hacer de dos formas:
1. Manual: __Descargar__ el archivo .zip y descomprimirlo en la carpeta modules. El nombre de la carpeta debe ser el mismo al del módulo y dentro debe tener los siguientes archivos y carpetas: \__init__.py, package.json, docs, example y libs. Si tiene abierta la aplicación, refresca el navegador para poder utilizar el nuevo modulo.
2. Automática: Al ingresar a Rocketbot Studio sobre el margen derecho encontrara la sección de **Addons**, seleccionar **Install Mods**, buscar el modulo deseado y presionar install.  


## Descripción de los comandos

### Encriptar Zip
  
Crea un zip encriptado
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Archivo |Selecciona el archivo a encriptar|//Users/User/Path/to/file|
|Tipo de compresión |Selecciona el tipo de compresión|DEFLATED|
|Número de bits |Selecciona el número de bits|256 bits|
|Clave |Introduce la clave|s3cre7p4ss|
|Path where save zip |Introduce la ruta donde guardar el zip|//Users/User/path/to/newzip|
|Asignar resultado a Variable|Variable donde se almacenara True o False dependiendo del éxito de la ejecución.|Variable|

### Desencriptar Zip
  
Obtiene archivos de un zip encriptado
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Archivo |Archivo zip a desencriptar|//Users/User/Path/to/file|
|Clave |Clave del archivo zip|s3cre7p4ss|
|Ruta donde extraer el zip |Ruta donde extraer el zip|//Users/User/path/to/folder|
|Asignar resultado a Variable|Variable donde se almacenara True o False dependiendo del éxito de la ejecución.|Variable|
