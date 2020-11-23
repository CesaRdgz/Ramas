# Ramas
## Carpeta Casa
Con git init inicias en carpeta casa un repositorio en el que previamente tienes un archivo como puede ser un documento de texto. La añades y haces un primer commit 
( yo lo llame "Primera Version Master") y lo pusheas. Tras esto creas la rama en la que quieres hacer la prueba o la version alternativa con el comando git branch 
+ el nombre que le quieras dar a esta rama ( en mi caso la llame Ramas-experimental) y con el comando git checkout + el nombre de la rama para situarse en la nueva rama.
Tras todo esto haces cambios en el archivo y lo añades y pusheas en la rama nueva. Para volver a la rama master solo tienes que poner git checkout master para situarse
en esta rama y si abres el archivo veras que al estar en la rama master esta sin modificar.
##Carpeta Instituto
Con git init inicias el repositorio y con git clone te "copias" el repositorio de carpeta casa a carpeta instituto y situandote en la rama master usas el comando git merge 
+ el nombre de la rama alternativa y con esto consigues que se junten los archivos de la rama master y los de la rama alternativa. Luego esto lo añades, haces el commit y 
por ultimo lo pusheas a tu repositorio online
