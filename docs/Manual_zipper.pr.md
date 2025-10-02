



# Zipper
  
Módulo para compactar e descompactar arquivos .zip criptografados.  

*Read this in other languages: [English](Manual_zipper.md), [Português](Manual_zipper.pr.md), [Español](Manual_zipper.es.md)*
  
![banner](imgs/Banner_zipper.png)
## Como instalar este módulo
  
Para instalar o módulo no Rocketbot Studio, pode ser feito de duas formas:
1. Manual: __Baixe__ o arquivo .zip e descompacte-o na pasta módulos. O nome da pasta deve ser o mesmo do módulo e dentro dela devem ter os seguintes arquivos e pastas: \__init__.py, package.json, docs, example e libs. Se você tiver o aplicativo aberto, atualize seu navegador para poder usar o novo módulo.
2. Automático: Ao entrar no Rocketbot Studio na margem direita você encontrará a seção **Addons**, selecione **Install Mods**, procure o módulo desejado e aperte instalar.  


## Descrição do comando

### 
  

|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|File |Select the file to encrypt|//Users/User/Path/to/file|
|Compression type |Select the compression type|DEFLATED|
|Bits |Select the number of bits|256 bits|
|Password |Enter the password|s3cre7p4ss|
|Ruta donde guardar el zip |Enter the path where to save the zip|//Users/User/path/to/newzip|
|Atribuir resultado à variável|Variável onde True ou False será armazenado dependendo do sucesso da execução.|Variable|

### 
  

|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|File |Zip file to decrypt|//Users/User/Path/to/file|
|Password |Zip file password|s3cre7p4ss|
|Path where extract zip |Path where extract zip|//Users/User/path/to/folder|
|Atribuir resultado à variável|Variável onde True ou False será armazenado dependendo do sucesso da execução.|Variable|
