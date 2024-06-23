# Version del curso
version Actual:  v1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- letra *italica* de la primer forma.
- letra _italica_ de la primer forma.
- formato **bold o strong** 1re forma
- formato __bold o strong__ 2da forma
- formato ~~tachado~~. formato normal.
- aqui podemos usar *formato italico*, pero tambien **bold** y ~~tacahdo~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item.
3. Esto es un item.

- Esto es un item de lista desordenada.
- Esto es un item.
- Esto es un item.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link MarkDown](http://www.google.com)

# Imagenes
![Logo Github](https://qph.cf2.quoracdn.net/main-qimg-729a22aba98d1235fdce4883accaf81e)

# Code Snippets
codigo en JSON
```` JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
````

codigo en Javascript
```` Javascript
[
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}
]
````

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Pepe | Perez | 34234234 |
| Juan | García | 34234234 |

# Citas
Esto es un ertxto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior
>Esto es otra cita

# Lineas divisoras
Esto es un texto que sera dividido por guiones medios

---
Esto es otro texto dividido por asteriscos

***

Esto es otro texto dividido por guiones bajos

___

# Saltos de linea
Esto es nuestro priemer parrafo.

Esto es nuestro segundo parrafo.

Esto es un tercer parrafo
- lista

