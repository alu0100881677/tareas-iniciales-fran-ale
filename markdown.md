Markdown
==
**Markdown** es un lenguaje de marcado ligero creado por John Gruber
que trata de conseguir la máxima legibilidad y facilidad de publicación
tanto en su forma de entrada como de salida.

**Cabeceras:** Se usan poniendo # al principio de la linea.
* h1 #
* h2 ##
* h3 ###
Y así sucesivamente.

# Cabecera 1
## Cabecera 2
### Cabecera 3             

**Titulos**: Se usan poniendo almenos 2 simbolos '=' en la linea siguiente
<pre>
  Titulo
  ==
</pre>

Titulo
==
 -----

**Tipos de texto**: *italic*,  **negrita**, and `codigo()`.
<pre>
*italic*,  **negrita**, and `codigo()`.
</pre>

---

**Citas**: Puedes citar textos y anidarlos con '>'
<pre>
> cita
>> cita2
</pre>

> cita
>> cita2

---

**Listas**: Se pueden hacer listas con `'*','-','+'` o enumeradas '1.','2.'
<pre>
* e1
- e2
+ e3
</pre>

1. primero
2. segundo

---
**Codigo**: Tambien se puede hacer cógido multilinea con ~~~ al principio y al final.

<pre>
~~~
if (code == true &&) {
    func();
}
~~~
</pre>


~~~

if (code == true &&) {
    func();
}

~~~

--------------------------

**Tablas**: Creacion de tablas

<pre>
| Header | Header | Right  |
| ------ | ------ | -----: |
|  Cell  |  Cell  |   $10  |
|  Cell  |  Cell  |   $20  |
</pre>

| Header | Header | Right  |
| ------ | ------ | -----: |
|  Cell  |  Cell  |   $10  |
|  Cell  |  Cell  |   $20  |


---

**Enlaces e imagenes**
<pre>
[enlace](www.enlace.es)
![Titulo alt](URL "Título de la imagen")
</pre>
[enlace](www.enlace.es)

![Texto alternativo](http://pngimg.com/upload/cat_PNG1635.png)
