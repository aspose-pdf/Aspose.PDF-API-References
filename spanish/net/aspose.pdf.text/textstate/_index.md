---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TextState. Representa un estado de texto de un texto
type: docs
weight: 11070
url: /es/net/aspose.pdf.text/textstate/
---
## Clase TextState

Representa un estado de texto de un texto

```csharp
public class TextState
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextState](textstate/#constructor)() | Crea un objeto de estado de texto. |
| [TextState](textstate/#constructor_2)(Color) | Crea un objeto de estado de texto con especificación de color de primer plano. |
| [TextState](textstate/#constructor_1)(double) | Crea un objeto de estado de texto con especificación de tamaño de fuente. |
| [TextState](textstate/#constructor_4)(string) | Crea un objeto de estado de texto con especificación de familia de fuente. |
| [TextState](textstate/#constructor_3)(Color, double) | Crea un objeto de estado de texto con especificación de color de primer plano y tamaño de fuente. |
| [TextState](textstate/#constructor_6)(string, double) | Crea un objeto de estado de texto con especificación de familia de fuente y tamaño de fuente. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Crea un objeto de estado de texto con especificación de familia de fuente y estilo de fuente. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Establece el color de fondo del texto. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Obtiene o establece el espaciado de caracteres del texto. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor de Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor representación del texto. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Obtiene o establece la fuente del texto. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Obtiene o establece el tamaño de fuente del texto. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Establece el estilo de fuente del texto. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Obtiene o establece el color de primer plano del texto. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Obtiene o establece la alineación horizontal para el texto. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Obtiene o establece la escala horizontal del texto. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Obtiene o establece la invisibilidad del texto. Esto refleja básicamente el estado de [`RenderingMode`](./renderingmode/), excepto en algunos casos especiales (como el recorte). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Obtiene o establece el espaciado de líneas del texto. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Obtiene o establece el modo de representación del texto. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Obtiene o establece el tachado para el texto, representado por el objeto [`TextSegment`](../textsegment/) |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Obtiene o establece el color de primer plano del texto. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Obtiene o establece el subíndice del texto. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Obtiene o establece el superíndice del texto. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Obtiene o establece el subrayado para el texto, representado por el objeto [`TextFragment`](../textfragment/) |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Obtiene o establece el espaciado de palabras del texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Aplica configuraciones de otro textState. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Mide la altura del carácter. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Mide la cadena. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valor predeterminado de tabulación en anchos del carácter de espacio de la fuente predeterminada. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Puedes colocar esta etiqueta en el texto para declarar tabulación. |

### Ver También

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)