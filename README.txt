mi primer poryecto 
traer directorio desde cmd usa git clone https://github.com/SoullessSapo/psp0
pasos subir 
pasos para subir proyecto a repositorio remoto desde cmd:
paso 1:
ejecutar comando para inicializar proyecto : mvn archetype:generate -DgroupId=edu.escuelaing.arem -DartifactId=psp0 -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

paso 2:
generar documentacion del proyecto:
echo "mi primer poryecto" > REAADME.txt
echo "TODO: Copiar el texto de la licenica http://www-gnu.org/licenses/gpl.html" > LICENSE.txt
echo "# TODO: copiar los contenidos de https://github.com/github/gitignore/blob/master/Java.gitignore" > .gitignore

paso 3:
inicializar repo : git init

paso 4: 
añadir archivos para el repo: git add *.txt pom.xml .gitignore src

paso 5:
conectar con repositorio remoto: git remote add origin https://github.com/SoullessSapo/psp0.git

paso 6:
hacer primer commit del proyecto: git commit -m "primera version del proyecto PSP0 de esteban valencia"

paso 7:
subir cambios al repo: git push -u origin master

pasos para descargar proyecto en repositorio remoto:
paso 1:
traer directorio desde cmd usa git clone https://github.com/SoullessSapo/psp0

paso 2:
compilar proyecto con el comando mvn package
