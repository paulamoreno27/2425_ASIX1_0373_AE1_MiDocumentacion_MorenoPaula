# 2425_ASIX1_0373_AE1_MiDocumentacion_MorenoPaula

## Apuntes Github:
* git init --> reinicia el repositorio

* git branch -->  crear diferentes ramas de desarrollo que pueden converger en el mismo repositorio

* git add --> añade contenido del directorio de trabajo al área de ensayo

* git commit -m "Añadida una linea de cógido" --> hacer commits con mensaje

* git push origin main --> "Sincronizar" repositorio

* git remote add origin "url" --> sincroniza el repositorio local con el web

* git pull --> Coger los cambios del GitHub web y pasarlos al repositorio local

## Apuntes Markdown:
### Encabezados:
Tenemos encabezados de diferentes tamaños, para hacerlos utilizamos el "#" contra más "#" pongamos más pequeño se vuelve.

# ENCABEZADO DE PRIMER NIVEL (RESULTADO)
* Para hacer un encabezado de **primer nivel** deberemos de poner un unico "#", un espacio y a continuación el encabezado que deseamos. 
### **Ejemplo:** 
"# ENCABEZADO DE PRIMER NIVEL"
**Podemos ver como quedaria arriba de la explicación**

## ENCABEZADO DE SEGUNDO NIVEL (RESULTADO)
* Para hacer un encabezado de **segundo nivel** deberemos de poner dos "#", es decir lo que tendriamos que hacer es, "##", un espacio y a continuación el encabezado que deseamos. 
### **Ejemplo:** 
"## ENCABEZADO DE SEGUNDO NIVEL"
**Podemos ver como quedaria arriba de la explicación**

### ENCABEZADO DE TERCER NIVEL (RESULTADO)
* Para hacer un encabezado de **tercer nivel** deberemos de poner tres "#", es decir lo que tendriamos que hacer es, "###", un espacio y a continuación el encabezado que deseamos. 
### **Ejemplo:** 
"### ENCABEZADO DE TERCER NIVEL"
**Podemos ver como quedaria arriba de la explicación**

#### ENCABEZADO DE CUARTO NIVEL (RESULTADO)
* Para hacer un encabezado de **cuarto nivel** deberemos de poner cuatro "#", es decir lo que tendriamos que hacer es, "####", un espacio y a continuación el encabezado que deseamos. 
### **Ejemplo:** 
"#### ENCABEZADO DE CUARTO NIVEL"
**Podemos ver como quedaria arriba de la explicación**

##### ENCABEZADO DE QUINTO NIVEL (RESULTADO)
* Para hacer un encabezado de **quinto nivel** deberemos de poner cinco "#", es decir lo que tendriamos que hacer es, "#####", un espacio y a continuación el encabezado que deseamos. 
### **Ejemplo:** 
"##### ENCABEZADO DE QUINTO NIVEL"
**Podemos ver como quedaria arriba de la explicación**

###### ENCABEZADO DE SEXTO NIVEL (RESULTADO)
* Por ultimo para hacer un encabezado de **sexto nivel** deberemos de poner seis "#", es decir lo que tendriamos que hacer es, "######", un espacio y a continuación el encabezado que deseamos. 
### **Ejemplo:** 
"###### ENCABEZADO DE SEXTO NIVEL"
**Podemos ver como quedaria arriba de la explicación**


## Estilos de letra
En Markdown tenemos diferentes estilos de letra como:
* *ítalica* 
* _cursiva_
* **negrita**
* ~~tachada~~

También tenemos estilos que se anidan, como por ejemplo:
* **palabra1 _palabra2_** (itálicas pero la segunda además negrita)


### Estilo *ítalica* o _cursiva_:
* Para poner el estilo *ítalica* o _cursiva_ utilizaremos o " * " (asterisco) o " _ " (barrabaja) utilizemos el que sea de los dos ya que obtendemos el mismo resultado, lo unico que deberemos de hacer es poner " * " (asterisco) o " _ " (barrabaja) al inicio de la palabra o frase, escribiremos lo que queremos y al finalizar colocaremos otro * (asterisco) o _ (barrabaja), dependiendo que hemos usado. Si usamos asterisco, pondremos uno al principio y uno al final y si hemos usado barrabaja pues al principio y al final.
### **Ejemplo:** "* ítaliza/cursiva *", " _ítalica/cursiva _ "
### *Resultado:** *Ítaliza/Cursiva*, _Ítalica/Cursiva_


### Estilo **negrita**:
* Para poner el estilo **negrita** utilizaremos dos " * " (asteriscos), lo que deberemos de hacer para que nuestra letra o frase se vea en negrita es poner " ** " (asteriscos) al inicio de la palabra o frase, escribiremos lo que queremos y al finalizar colocaremos otros dos " ** " (asteriscos).
### **Ejemplo:** "** Negrita **"
### **Resultado:** **Negrita**


### Estilo ~~tachado~~:
* Para poner el estilo ~~tachado~~ utilizaremos dos "~" (virgulillas, se encuentra haciendo "alt gr + num 2/3/4"), lo que deberemos de hacer para que nuestra letra o frase se vea tachada es poner dos "~ ~" (virguelillas) al inicio de la palabra o frase, escribiremos lo que queremos y al finalizar colocaremos otras dos "~ ~" (virguelillas).
### **Ejemplo:** "~ ~ Tachada ~ ~" (las virguelillas van juntas sin espacio)
### **Resultado:** ~~Tachada~~


### Estilo anidado **palabra1 _palabra2_**:
* Por ultimo para hacer el estilo anidado **palabra1 _palabra2_** lo que debemos de hacer es utilizar el "*" y la "_", primero colocaremos dos " * " (asteriscos) la frase o palabra que queremos, una " _ " (barrabaja) la siguiente frase o palabra y finalizamos con una " _ " (barrabaja) y dos " * " (asteriscos). Si hacemos esto la primera palabra nos quedara en negrita y la siguiente en negrita y cursiva.
### **Ejemplo:**  "* * palabra1 _ palabra2 _ * *" (tanto los asteriscos como las barrabajas van pegadas a la palabra)
### **Resultado:** **palabra1 _palabra2_**


## Listas
### Como hacer una lista ordenada:
Para crear una lista numerada en Markdown como esta:
1. Primer punto de la lista
2. Segundo punto de la lista
3. Tercer punto de la lista

Lo unico que deberemos de hacer es poner "1.", esapcio y lo que queramos escribir, al hacer enter nos pasara al siguiente punto de la lista lo cual ya se pondra automaticamente el siguiente punto que seria "2.", es importante despues de poner el "1." poner el espacio, ya que si no, no se ejecutará. 

### **Ejemplo:** " 1. Punto uno de la lista "

### **Resultado:**
1. Punto uno de la lista


### Como hacer una lista con subpuntos:
En caso que queramos crear una lista con subpuntos como esta:
* 1. Primer punto de la lista
    1. Primer elemento de la sublista 1
    2. Segundo elemento de la sublista 1
* 2. Segundo punto de la lista
    * Primer elemento de la sublista 2
    * Segundo elemento de la sublista 2
* 3. Tercer punto de la lista

Lo que debemos de hacer es hacer una lista normal, como la anterior pero cuando queramos poner un subpunto lo que haremos sera, tabulador, y entonces nos aparecera un subpunto con otro "1.", si no queremos poner el "1." podemos cambiarlo por "*", "-", "+".
**Ejemplo:** 
" 1. Punto uno de la lista "
    " 1. Subpunto de la lista "

" 1. Punto uno de la lista "
    " * Subpunto de la lista "

" 1. Punto uno de la lista "
    " - Subpunto de la lista "

" 1. Punto uno de la lista "
    " + Subpunto de la lista "

### **Resultado:**
1. Punto uno de la lista
   1. subpunto de la lista

1. Punto uno de la lista
   * subpunto de la lista

1. Punto uno de la lista
   - subpunto de la lista

1. Punto uno de la lista
   + subpunto de la lista

### Como hacer una lista desordenada:
Tenemos diferentes puntos para la lista desordenada en Markdown desde un "*" (asterisco), "-" (guion) y incluso "+" (más), para utilizar estos puntos solo tenemos que poner " * ", " - ", " + ", un espacio y lo que queramos poner.

**Ejemplo:**
" * Primer punto de la lista "
" - Segundo punto de la lista "
" + Tercer punto de la lista "

### **Resultado:**
* Primer punto de la lista
- Segundo punto de la lista
+ Tercer punto de la lista

## Enlaces
Para crear un enlace tenemos que realizar la siguiente estructura: "["textoclicable" ]"(URL "Titulo opcional")" (sin comillas)
### **Resultado:**[Página repositorio GitHub](https://github.com/paulamoreno27/2425_ASIX1_0373_AE1_MiDocumentacion_MorenoPaula "Link GitHub Paula")

## Imagenes
Para insertar una imagen en Markdown debemos debemos de descargar la imagen primero de todo y colocarla en la carpeta donde se encuetra el archivo README.md, una vez la tenemos en la carpeta, lo que deberemos de hacer es  irnos a GitHub web y pegar la URL donde se encuentra la imagen. Luego debemos de escribir la siguiente ruta en nuestro archivo README.md "!"[" TextoAlternativo "]"(UbicaciónDeLaImagen "Titulo opcional")" (sin comillas)
### **Resultado:**
![Foto GitHub](https://github.com/paulamoreno27/2425_ASIX1_0373_AE1_MiDocumentacion_MorenoPaula/blob/main/imagengithub.png "Foto GitHub")

## Tablas
Para hacer una tabla en Markdown debemos de hacer lo siguiente:
* "|Titulo 1|Titulo 2|Titulo 3|
   |---------|**:**-----------**:**|----------------**:**|
   |SMX2 |Curso 2324|25|
   |ASIX1|Curso 2425|33| 
   |DAW2|Curso 2425|32|

* Los dos puntos resaltados en negrita se usan para alinear las columnas (izquierda, centrado, derecha).
* No es necesario que estén alineadas verticalmente. Solo a nivel visual para claridad del código.
* Se han de poner al menos tres guiones para separar cada encabezado (los guiones son los "-")

### Resultado:
|Titulo 1|Titulo 2|Titulo 3|
|---------|:-----------:|----------------:|
|SMX2 |Curso 2324|25|
|ASIX1|Curso 2425|33| 
|DAW2|Curso 2425|32|