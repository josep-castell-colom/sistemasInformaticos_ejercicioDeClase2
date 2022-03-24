# EJERCICIO DE CLASE 2

## SISTEMAS INFORMÁTICOS - DAW1

### JOSEP M CASTELL COLOM

---

## EJERCICIO 1

### Indica en cada caso las órdenes utilizadas:

### 1. Crea la siguiente estructura de carpetas:

```powershell
md apli, prog, varios
cd apli
md word, access, excel
cd word
md textos, notas
cd ../excel
md tablas, info
...
```

### 2. Sitúate en la carpeta TABLAS

```powershell
cd apli/excel/tablas
```

### 3. Vuelve a la carpeta raíz

```powershell
cd ../../..
```

### 4. Muestra el contenido de la carpeta PROG

```powershell
dir ./prog/
```

### 5. Borra la carpeta PASCAL

```powershell
del prog/pascal
```

### 6. Sitúate en la carpeta VARIOS y desde allí crea una nueva carpeta dentro de WORD llamada PRACT

```powershell
cd varios

md ../apli/word/pract
```

### 7. Sitúate en PRACT y desde allí muestra el contenido de la carpeta EXCEL

```powershell
cd ../apli/word/pract

dir ../excel
```

### 8. Desde TABLAS muestra el listado de archivos y carpetas de la carpeta raíz

```powershell
cd ../excel/tablas

dir ../../..
```

### 9. Sitúate en la carpeta APLI y desde allí crea una subcarpeta llamada AGENDA dentro de VARIOS

```powershell
cd ../..

dir ../varios/agenda
```

### 10. Borra la carpeta EXCEL

```powershell
deltree excel
```

### 11. Desde la carpeta raíz, crea en ella una subcarpeta llamada NUEVO

```powershell
cd ..

md nuevo
```

### 12. Desde PRACT muesta el contenido de WORD

```powershell
cd apli/word/pract

dir ..
```

---

## EJERCICIO 2

### Indica en cada caso las órdenes utilizadas:

### 1. Utilizando el editor de textos de MS-DOS, crea un archivo de texto denominado EJER.TXT, con el siguiente contenido, y almacénalo dentro de la carpeta TEXTOS (dentro de la estructura del ejercicio anterior)

```powershell
---
```

### 2. Copia el archivo EJER.TXT en AGENDA

```powershell
copy apli/word/textos/ejer.txt ./agenda/ejer.txt
```

### 3. Borra el archivo almacenado en la carpeta TEXTOS

```powershell
del apli/word/textos/ejer.txt
```

### 4. Añade el siguiente párrafo al archivo EJER.TXT

```powershell
echo 'Cada archivo tiene un nombre y una extensión que los distingue del resto de archivos' >> agenda/ejer.txt
```

### 5. Copia el archivo EJER.TXT en la carpeta BASIC

```powershell
copy agenda/ejer.txt prog/basic/ejer.txt
```

### 6. Cambia el nombre del archivo almacenado en AGENDA por FICHERO.TXT

```powershell
ren agenda/ejer.txt agenda/fichero.txt
```

### 7. Mueve el archivo FICHERO.TXT a la carpeta BASIC

```powershell
move agenda/fichero.txt prog/basic/fichero.txt
```

### 8. Abre el archivo EJER.TXT y borra la primera frase; almacena el nuevo archivo con el nombre NUEVO.TXT dentro de la carpeta BASIC

```powershell
---
```

### 9. Copia el archivo NUEVO.TXT en la carpeta NOTAS

```powershell
copy prog/basic/ejer.txt apli/word/notas/ejer.txt
```

### 10. ¿Cuántos archivos hay en la carpeta BASIC? ¿Y en NOTAS?

En la carpeta BASIC hay dos archivos, y en la carpeta NOTAS hay uno.

## EJERCICIO 3

### Indica en cada caso las órdenes utilizadas:

### 1. Borra la carpeta ACCESS y en su lugar crea una nueva carpeta llamada ASTRO

```powershell
rmdir apli/access

md apli/astro
```

### 2. Crea la siguiente estructura de subcarpetas dentro de la carpeta ASTRO

```powershell
cd apli/astro

md historia,ciencia

cd historia

md datos1,datos2

cd ../../ciencia

md astro1,astro2

```

### 3. Sitúate en la carpeta CIENCIA y desde allí muestra el listado de archivos y subcarpetas de la carpeta HISTORIA

```powershell
dir ../historia
```

### 4. Utilizando el editor de MS-DOS crea el siguiente archivo de texto y guárdalo con el nombre TYCHO.TXT dentro de la carpeta DATOS1

```powershell
---
```

### 5. Utilizando de nuevo el editor de textos de MS-DOS crea el siguiente archivo de texto, y guárdalo con el nombre KEPLER.TXT dentro de la carpeta DATOS2

```powershell
---
```

### 6. Copia los archivos TYCHO.TXT y KEPLER.TXT en la carpeta CIENCIA

```powershell
copy ../historia/datos1/tycho.txt .

copy ../history/datos2/kepler.txt .
```

### 7. Cambia de lugar los archivos almacenados en DATOS1 y DATOS2 de forma que TYCHO.TXT quede guardado dentro DATOS2 y KEPLER.TXT en DATOS1

```powershell
move ../history/datos1/tycho.txt ../history/datos2/tycho.txt

move ../history/datos2/kepler.txt ../history/datos1/kepler.txt
```

### 8. Crea un nuevo archivo formado por la unión de los dos anteriores (sin volver a escribir el texto) y guárdalo dentro de la carpeta HISTORIA con el nombre TOTAL.TXT

```powershell

```

### 9. Abre el archivo KEPLER.TXT almacenado en la carpeta CIENCIA y añade el siguiente texto

```powershell
---
```

### 10. Cambia el nombre del archivo anterior por el de GALILEO.TXT

```powershell
ren ../history/datos1/kepler.txt ../history/datos1/galileo.txt
```

## EJERCICIO 4

### Indica en cada caso las órdenes utilizadas:

### 1. Crea en la carpeta raíz de la unidad A: una carpeta denominada TECINFO

```powershell
---
```

### 2. Crea dentro de TECINFO el siguiente archivo de texto y llámalo HARD.TXT

```powershell
---
```

### 3. Crea dentro de TECINFO el siguiente archivo de texto y llámalo SOFT.TXT

```powershell
---
```

### 4. Mueve el contenido de TECINFO a la carpeta APLI del disquete A utilizado para realizar los ejercicios anteriores

```powershell
---
```

### 5. Crea un nuevo archivo formado por la unión de HARD.TXT y SOFT.TXT, sin volver a escribir el texto, y guárdalo en la carpeta AGENDA con el nombre ORDER.TXT

```powershell
---
```

### 6. Elimina la carpeta TECINFO

```powershell
---
```

### 7. Copia a la vez los archivos HARD.TXT y SOFT.TXT en la carpeta VARIOS

```powershell
---
```

### 8. Cambia la extensión de los archivos contenidos en AGENDA por .TYP

```powershell
---
```

### 9. Cambia la primera letra del nombre de todos los archivos del directorio APLI que empiecen por la letra C y tengan extensión DOC de forma que empiecen con la letra S

```powershell
---
```

### 10. Copia los archivos contenidos en la carpeta APLI que tengan extensión DOC en la carpeta AGENDA

```powershell
---
```
