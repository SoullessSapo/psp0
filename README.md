# Proyecto PSP0

Este es mi primer proyecto usando Maven y Git.

## Clonar el repositorio

Para descargar el proyecto desde GitHub, ejecuta el siguiente comando en la terminal (CMD):

```bash
git clone https://github.com/SoullessSapo/psp0
```

---

## Pasos para subir el proyecto a un repositorio remoto

1. **Inicializar el proyecto con Maven:**

```bash
mvn archetype:generate -DgroupId=edu.escuelaing.arem -DartifactId=psp0 -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```

2. **Generar documentación básica del proyecto:**

```bash
echo "Mi primer proyecto" > README.txt
echo "TODO: Copiar el texto de la licencia desde http://www.gnu.org/licenses/gpl.html" > LICENSE.txt
echo "# TODO: copiar los contenidos desde https://github.com/github/gitignore/blob/master/Java.gitignore" > .gitignore
```

3. **Inicializar el repositorio Git:**

```bash
git init
```

4. **Agregar archivos al repositorio:**

```bash
git add *.txt pom.xml .gitignore src
```

5. **Conectar con el repositorio remoto:**

```bash
git remote add origin https://github.com/SoullessSapo/psp0.git
```

6. **Hacer el primer commit:**

```bash
git commit -m "Primera versión del proyecto PSP0 de Esteban Valencia"
```

7. **Subir el proyecto al repositorio remoto:**

```bash
git push -u origin master
```

---

## Compilar el proyecto

Una vez clonado, puedes compilar el proyecto con:

```bash
mvn package
```

---

## Ejemplo del proceso

A continuación, se muestran imágenes ilustrativas del proceso:

- ![Paso 1](https://github.com/SoullessSapo/psp0/blob/master/src/site/resources/1.png)
- ![Paso 2](https://github.com/SoullessSapo/psp0/blob/master/src/site/resources/2.png)
- ![Paso 3](https://github.com/SoullessSapo/psp0/blob/master/src/site/resources/3.png)
