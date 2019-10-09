'Titulos'
'Modifica la letras del titulo, con los comandos `#` cuantos mas pongas mas pequeño es.'


# Alex
## Alex
### Alex

'Negrita/italica/tachado'
'Caracteristicas de los caracteres. `_ITALICA_` o `*ITALICA*` - `__NEGRITA__` - `**NEGRITA  _ITALICA Y NEGRITA_**` - `~~TACHADO.~~`

_Alex_

__Alex__

**Alex _Perez Garcia_**

~~Alex Perez Garcia~~

'Listas'

'Enumeracion de oraciones con numeros. `1. - 2. - 3.`'

'Enumeracion de oraciones con un punto. `* - +`

1. Primera enumeracion

2. Segunda enumeracion

* Enumeracion con un punto.

- Enumeracion con un punto.

+ Enumeracion con un punto.


'Enlaces'

'De esta manera se ponen los enlaces, primero va el nombre del link y despues el enlace `[Nombre del enlace](https://www.google.com)`

[Google](https://www.google.com)

'Imágenes'

'Manera de insertar imagenes. `"Texto" ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
`

Veras una imagen:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")



'Resaltado de código y sintaxis'

Al poner los dos accentos "`" con texto dentro queda resaltado y si es un codigo no se ejecutara ``#``

'Tablas'
' Para hacer tablas hay que construirlas como si hicieras unas tabla normal con los simbolos ` | (columnas) y con ---(filas) `


| Hola | Alex | Perez | Garcia
| --- | --- | --- | ---
| *Still* | `renders` | **nicely** | ~~Huola~~
| 1 | 2 | 3 | 5 



'Blockquotes'

> Resalta las oraciones marcadas con el simbolo delante de la oracion `>`



'HTML en línea'
'Se pueden utilizar comandos de HTML'

``` 
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>



'Regla horizontal'
' 3 o mas `...` `---` `***` `___` hace una linea debajo de la frase

3 o mas...

---

Guiones

***

Asteriscos

___

Barra bajas



'Saltos de línea'




Esta línea está separada de la anterior por dos líneas nuevas, por lo que será un *párrafo separado*.

Esta línea también comienza un párrafo separado, pero ...
Esta línea solo está separada por una nueva línea, por lo que es una línea separada en el *mismo párrafo* .



### Qué codificación de caracteres tiene este archivo de texto? Contesta el mismo documento Markdown.

'Codificacion ``UTF-8``'

### Tienes que explicar la función de las principales instrucciones de git (clone, add, commit, push, pull) y poner algún ejemplo


`git clone <url>` Crea una copia de un repositorio remoto.

 > Ejemplo:  `git clone <https://github.com/Aleeex98/PerezGarciaAlex_Tasca11>`

`git add [-u] [Nombre del Archivo|.|Ruta]` Hace una instantánea de los archivos para versionarlos, añadiéndolos al Index (staged)
-u añade ficheros al Index que se han de borrar

 > Ejemplo: `git add -u ejercicio1.md`

`git commit [-m "Mensaje"]` Guarda las instantáneas de los archivos permanentemente al historial de versiones (Index -> HEAD)

 > Ejemplo: `git commit -m "Hola mundo" `

`git push origin master` Carga todos los archivos validados de la rama local al repositorio remoto


`git pull origin master` Descarga e incorpora los cambios desde el repositorio remoto
