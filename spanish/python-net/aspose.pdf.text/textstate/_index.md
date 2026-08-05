---
title: "TextState"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un estado de texto"
type: docs
weight: 490
url: /es/python-net/aspose.pdf.text/textstate/
---

## TextState class

Representa un estado de texto

El tipo TextState expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| TextState() | Crea un objeto de estado de texto. |
| TextState(font_size) | Inicializa una nueva instancia de la clase TextState |
| TextState(foreground_color) | Inicializa una nueva instancia de la clase TextState |
| TextState(foreground_color, font_size) | Inicializa una nueva instancia de la clase TextState |
| TextState(font_family) | Inicializa una nueva instancia de la clase TextState |
| TextState(font_family, bold, italic) | Inicializa una nueva instancia de la clase TextState |
| TextState(font_family, font_size) | Inicializa una nueva instancia de la clase TextState |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| character_spacing | Obtiene o establece el espaciado de caracteres del texto. |
| line_spacing | Obtiene o establece el espaciado de líneas del texto. |
| horizontal_scaling | Obtiene o establece el escalado horizontal del texto. |
| subscript | Obtiene o establece el subíndice del texto. |
| superscript | Obtiene o establece el superíndice del texto. |
| word_spacing | Obtiene o establece el espaciado de palabras del texto. |
| invisible | Obtiene o establece la invisibilidad del texto. Esto básicamente refleja el estado de [rendering_mode](/pdf/python-net/aspose.pdf.text/textstate/), excepto en algunos casos especiales (como recorte). |
| rendering_mode | Obtiene o establece el modo de renderizado del texto. |
| font_size | Obtiene o establece el tamaño de fuente del texto. |
| font | Obtiene o establece la fuente del texto. |
| foreground_color | Obtiene o establece el color de primer plano del texto. |
| stroking_color | Obtiene o establece el color de primer plano del texto. |
| underline | Obtiene o establece el subrayado del texto, representado por el objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) |
| strike_out | Establece el tachado del texto, representado por el objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) |
| background_color | Establece el color de fondo del texto. |
| font_style | Establece el estilo de fuente del texto. |
| horizontal_alignment | Obtiene o establece la alineación horizontal del texto. |
| TAB_TAG | Puedes colocar esta etiqueta en el texto para declarar tabulación. |
| TABSTOP_DEFAULT_VALUE | Valor predeterminado de la tabulación en anchuras del carácter de espacio de la fuente predeterminada. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| apply_changes_from(text_state) | Aplica configuraciones desde otro textState. |
| measure_string(str) | Mide la cadena. |

### Ver también

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

