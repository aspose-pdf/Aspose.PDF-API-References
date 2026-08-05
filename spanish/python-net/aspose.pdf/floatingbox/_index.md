---
title: "FloatingBox"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: 
type: docs
weight: 370
url: /es/python-net/aspose.pdf/floatingbox/
---

## FloatingBox class



El tipo FloatingBox expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| FloatingBox(width, height) | Inicializa una nueva instancia de la clase FloatingBox |
| FloatingBox() | Inicializa una nueva instancia de la clase [FloatingBox](/pdf/python-net/aspose.pdf/floatingbox/). |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| vertical_alignment | Obtiene o establece una alineación vertical del párrafo |
| horizontal_alignment | Obtiene o establece una alineación horizontal del párrafo |
| margen | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| is_first_paragraph_in_column | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_kept_with_next | Obtiene o establece un valor bool que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_in_new_page | Obtiene o establece un valor bool que fuerza que este párrafo se genere en una nueva página.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_in_line_paragraph | Obtiene o establece si un párrafo es inline.<br/>            El valor predeterminado es false. (para generación de pdf) |
| hipervínculo | Obtiene o establece el hipervínculo del fragmento (para generador de pdf). |
| z_index | Obtiene o establece un valor entero que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor <br/>            se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo <br/>            se colocará detrás del texto en la página. |
| column_info | Obtiene o establece la información de una columna |
| ancho | Obtiene o establece un valor de tipo float que indica el ancho del cuadro flotante. |
| alto | Obtiene o establece un valor de tipo float que indica la altura del cuadro flotante. |
| is_need_repeating | Obtiene o establece un valor booleano que indica si el párrafo debe repetirse en la página siguiente.<br/>            El valor predeterminado es false. El atributo solo es válido cuando tanto el propio párrafo como el objeto al que se refiere su ReferenceParagraphID están incluidos en RepeatingRows. |
| paragraphs | Obtiene o establece una colección de [paragraphs](/pdf/python-net/aspose.pdf/floatingbox/) que indica todos los párrafos en la celda. |
| border | Obtiene o establece un objeto [BorderInfo](/pdf/python-net/aspose.pdf/borderinfo/) que indica la información del borde del cuadro flotante. |
| background_color | Obtiene o establece un objeto [Color](/pdf/python-net/aspose.pdf/color/) que indica el color de fondo del cuadro flotante. |
| background_image | Obtiene o establece la imagen de fondo para la página (solo para el generador, no se rellena al leer el documento). |
| padding | Obtiene o establece un objeto [MarginInfo](/pdf/python-net/aspose.pdf/margininfo/) que indica el relleno del cuadro flotante. |
| left | Obtiene o establece la coordenada izquierda de la tabla. |
| top | Obtiene o establece la coordenada superior de la tabla. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Clona un nuevo objeto [FloatingBox](/pdf/python-net/aspose.pdf/floatingbox/). Los párrafos en el cuadro flotante no se clonan. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

