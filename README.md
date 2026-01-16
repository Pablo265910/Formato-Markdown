# Formato-Markdown
Ejercicio Formato Markdown

1. [Encabezados](#encabezados)
2. [Cambios tipográficos](#cambios-tipográficos)
3. [Listas](#listas)
4. [Snippets de código](#snippets-de-código)
5. [Citas](#citas)
6. [Enlaces](#enlaces)
7. [Imágenes](#imágenes)
8. [Tablas](#tablas)
9. [Líneas horizontales](#líneas-horizontales)
10. [Saltos de línea](#saltos-de-línea)
11. [Lista de tareas](#lista-de-tareas)
12. [Emojis](#emojis)
13. [Fórmulas matemáticas](#fórmulas-matemáticas)
14. [Referencias](#referencias)

# Encabezados
Los encabezados se utilizan para organizar el contenido de un documento y establecer una jerarquía visual. En Markdown, se crean utilizando el símbolo `#` seguido de un espacio. Cuantos más símbolos `#` pongas, menor será el nivel del encabezado (siendo 1 el más importante y 6 el más pequeño).

## Encabezado de Nivel 2
Este es un ejemplo de un encabezado de segundo nivel, ideal para secciones principales dentro de un tema.

### Encabezado de Nivel 3
Usamos el nivel 3 para profundizar en subapartados específicos del nivel anterior.

#### Encabezado de Nivel 4
El nivel 4 permite añadir anotaciones o puntos muy específicos manteniendo la estructura organizada.
# Cambios tipográficos
En Markdown, podemos enfatizar el texto de diferentes maneras para mejorar la legibilidad y resaltar conceptos clave. A continuación, se muestran los estilos más comunes:

* **Negrita**: Se utiliza para resaltar palabras importantes. Se escribe entre dos asteriscos o dos guiones bajos: `**texto**` o `__texto__`. Ejemplo: **Este texto es importante.**
* *Cursiva*: Ideal para enfatizar de forma suave o para términos técnicos. Se escribe entre un asterisco o un guion bajo: `*texto*` o `_texto_`.
* ***Negrita y cursiva***: Para un énfasis máximo, combinamos ambos estilos usando tres asteriscos: `***texto***`. Ejemplo: ***Este texto es extremadamente importante.***
* ~~Tachado~~: Útil para indicar correcciones o tareas completadas. Se escribe entre dos virgulillas: `~~texto~~`. Ejemplo: ~~Este concepto ya no es válido.~~
* `Remarcados`: Para resaltar términos específicos, fragmentos de código en línea o comandos, usamos la comilla simple invertida: `` `texto` ``.

# Listas
Las listas permiten agrupar elementos relacionados de forma estructurada. En Markdown, podemos crear listas con viñetas o numeradas, e incluso combinarlas en diferentes niveles.

### Listas sin orden (varios niveles)
Se crean usando asteriscos `*`, guiones `-` o signos más `+`. Para crear subniveles, basta con añadir una sangría (espacios o tabulador):

* Elemento 1
    * Subelemento 1
    * Subelemento 2
        * Subelemento 3
* Elemento 2

### Listas ordenadas (varios niveles)
Se utilizan números seguidos de un punto. Markdown ajusta la numeración automáticamente aunque no pongas los números en orden correlativo:

1. Elemento 1
2. Elemento 2
    1. Subelemento 1
    2. Subelemento 2
3. Elemento 3

# Snippets de código
# Snippets de código

Para mostrar bloques de código extensos y facilitar su lectura, utilizamos los Snippets de código. Estos se crean envolviendo el texto con tres comillas simples invertidas (```) tanto al inicio como al final.

```java
    public class Saludo {
    public static void main(String[] args) {
        System.out.print("Hola mundo")
    }
}
```
# Citas

Las citas se utilizan para indicar que un bloque de texto proviene de otra fuente o para dar un énfasis visual diferente a una frase importante. Para crearlas, se utiliza el símbolo mayor que `>` al principio de la línea.

> Este es un ejemplo de cita

También es posible anidar citas dentro de otras para indicar respuestas o niveles de referencia:

> Este es el nivel principal de la cita.
> > Este es un nivel anidado (se usan dos símbolos `>>`).
> > > Y este es un tercer nivel de profundidad.

# Enlaces

Markdown permite crear vínculos de forma sencilla para conectar tu documento con otros recursos o con secciones del propio archivo.

### Enlaces externos
Para enlazar a una página web externa, se escribe el texto que se verá entre corchetes `[]` y la URL entre paréntesis `()`:

* Visita [Google](https://www.google.com) para buscar información.
* Documentación oficial de [Markdown Guide](https://www.markdownguide.org).

### Enlaces internos
Puedes crear enlaces que te lleven directamente a un encabezado de este mismo documento. El "ID" del encabezado suele ser el nombre del título en minúsculas, sustituyendo los espacios por guiones:

* Volver al apartado de [Encabezados](#encabezados).
* Ir a la sección de [Snippets de código](#snippets-de-código).

*Nota: Los enlaces internos son ideales para crear índices de contenidos interactivos.*

# Imágenes

Las imágenes ayudan a ilustrar conceptos y hacer el documento más atractivo visualmente. 

### Imágenes externas
Para insertar una imagen, usamos la sintaxis `![Texto alternativo](Directorio de la imagen)`. El texto alternativo es lo que aparece si la imagen no carga o lo que leen los lectores de pantalla.

![Logo de Google](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Google_%22G%22_logo.svg/960px-Google_%22G%22_logo.svg.png)

### Imágenes con enlace
A veces queremos que, al hacer clic en una imagen, esta nos lleve a una página web. Para lograrlo, envolvemos la sintaxis de la imagen dentro de la sintaxis de un enlace: `[![Texto](URL_Imagen)](URL_Destino)`.

[![Accede a markdown desde esta imagen](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)](https://www.markdownguide.org)

# Tablas

Las tablas nos permiten organizar información de manera estructurada en filas y columnas. 

Para crearlas, separamos las columnas con el símbolo `|`. La segunda línea debe contener guiones `---` para separar los títulos del contenido. Además, podemos usar dos puntos `:` para definir la alineación del texto.

| Nombre del Atributo | Descripción | Alineación |
| :--- | :---: | ---: |
| Izquierda | Se alinea a la izquierda con `:---` | Izquierda |
| Centro | Se centra con `:---:` | Centro |
| Derecha | Se alinea a la derecha con `---:` | Derecha |

# Líneas horizontales

Las líneas horizontales se utilizan para crear una separación visual entre bloques de contenido, indicando un cambio de tema o el fin de un apartado.

Para crear una línea, puedes usar tres o más asteriscos (`***`), guiones (`---`) o guiones bajos (`___`) en una línea propia.

Ejemplo con asteriscos:
***

Ejemplo con guiones:
---

Ejemplo con guiones bajos:
___

# Saltos de línea

En markdown el salto de líneas puede ser muy útil para facilitar la lectura de los textos, o para separar la información. El salto de línea se puede hacer de la siguiente forma:

**Doble espacio**: Al final de una frase, añade dos espacios en blanco y luego pulsa Enter.
Este es un ejemplo de línea con dos espacios al final.  
Aquí continúa el texto justo debajo.

# Lista de tareas

Las listas de tareas permiten crear una serie de elementos con casillas de verificación. Se basan en la sintaxis de las listas desordenadas, pero añadiendo corchetes `[ ]`.

* `[ ]` seguido de un espacio crea una casilla vacía.
* `[x]` seguido de un espacio crea una casilla marcada.

### Ejemplo de lista de compra:
- [x] Ejemplo 1.
- [x] Ejemplo 2.
- [ ] Ejemplo 3.
- [ ] Ejemplo 4.

# Emojis

Los emojis ayudan a enfatizar mensajes y mejorar la comunicación visual en un documento. Dependiendo de la plataforma que uses para leer el Markdown, puedes insertarlos de dos maneras:

### 1. Copiar y pegar
La forma más sencilla es copiar el emoji directamente desde un selector (como el de tu móvil o el atajo `Win + .` en Windows) y pegarlo en el texto:
* 👋
* 🚀
* ⚠️

### 2. Códigos "shortcodes"
Muchas plataformas permiten escribir el nombre del emoji entre dos puntos:
* `:smile:` produce 😄
* `:tada:` produce 🎉
* `:rocket:` produce 🚀


# Fórmulas matemáticas

Para escribir expresiones matemáticas, Markdown utiliza la sintaxis de LaTeX. Para que el editor sepa que debe procesar una fórmula, envolvemos el contenido con el símbolo del dólar `$`.

### Fórmulas en línea
Se escriben entre un solo símbolo de dólar `$fórmula$`. Son ideales para mencionar variables o ecuaciones cortas dentro de un párrafo.
* Ejemplo: El área de un círculo es $A = \pi r^2$.

### Fórmulas en bloque
Se escriben entre dos símbolos de dólar `$$fórmula$$`. Esto coloca la ecuación en una línea nueva y la centra automáticamente.

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$



# Referencias

Las referencias permiten que el texto sea mucho más legible al evitar colocar URLs largas en medio de los párrafos. En su lugar, se utiliza una etiqueta que se define en otra parte del documento.

### Cómo funcionan
Se define el enlace con dos pares de corchetes: `[Texto del enlace][etiqueta]`. Luego, en cualquier otra parte del archivo (normalmente al final), se define la etiqueta.

**Ejemplo en el texto:**
Puedes consultar más información en el [sitio oficial de Markdown][Markdown] o buscar en [Google][Google].

[Markdown]: https://www.markdownguide.org "Guía de Markdown"
[Google]: https://www.google.com "Buscador de Google"

---