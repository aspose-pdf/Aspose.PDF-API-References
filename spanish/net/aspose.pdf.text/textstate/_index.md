---
title: TextState
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa un estado de texto de un text
type: docs
weight: 7230
url: /es/net/aspose.pdf.text/textstate/
---
## TextState class

Representa un estado de texto de un text

```csharp
public class TextState
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextState](textstate#constructor)() | Crea objeto de estado de texto. |
| [TextState](textstate#constructor_2)(Color) | Crea un objeto de estado de texto con especificación de color de primer plano. |
| [TextState](textstate#constructor_1)(double) | Crea un objeto de estado de texto con especificación de tamaño de fuente. |
| [TextState](textstate#constructor_4)(string) | Crea un objeto de estado de texto con especificación de familia de fuentes. |
| [TextState](textstate#constructor_3)(Color, double) | Crea un objeto de estado de texto con especificación de color de primer plano y tamaño de fuente. |
| [TextState](textstate#constructor_6)(string, double) | Crea un objeto de estado de texto con la familia de fuentes y especificación de tamaño de fuente. |
| [TextState](textstate#constructor_5)(string, bool, bool) | Crea un objeto de estado de texto con familia de fuentes y especificación de estilo de fuente. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor) { get; set; } | Establece el color de fondo del texto. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing) { get; set; } | Obtiene o establece el espaciado entre caracteres del texto. |
| virtual [Font](../../aspose.pdf.text/textstate/font) { get; set; } | Obtiene o establece la fuente del texto. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize) { get; set; } | Obtiene o establece el tamaño de fuente del texto. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle) { get; set; } | Establece el estilo de fuente del texto. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor) { get; set; } | Obtiene o establece el color de primer plano del texto. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment) { get; set; } | Obtiene o establece la alineación horizontal del texto. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling) { get; set; } | Obtiene o establece la escala horizontal del texto. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible) { get; set; } | Obtiene o establece la invisibilidad del texto. Esto refleja básicamente la[`RenderingMode`](./renderingmode) estado, excepto en algunos casos especiales (como recorte). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing) { get; set; } | Obtiene o establece el interlineado del texto. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode) { get; set; } | Obtiene o establece el modo de representación del texto. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout) { get; set; } | Establece el tachado del texto, representado por el[`TextFragment`](../textfragment) objeto |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor) { get; set; } | Obtiene o establece el color de primer plano del texto. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript) { get; set; } | Obtiene o establece el subíndice del texto. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript) { get; set; } | Obtiene o establece el superíndice del texto. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline) { get; set; } | Obtiene o establece el subrayado del texto, representado por el[`TextFragment`](../textfragment) objeto |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing) { get; set; } | Obtiene o establece el espaciado entre palabras del texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom)(TextState) | Aplica la configuración de otro estado de texto. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring)(string) | Mide la cuerda. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | Valor predeterminado de tabulación en anchos de carácter de espacio de fuente predeterminada. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | Puede colocar esta etiqueta en el texto para declarar la tabulación. |

### Ver también

* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->