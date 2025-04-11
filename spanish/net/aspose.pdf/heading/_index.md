---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Heading. Representa un encabezado
type: docs
weight: 5470
url: /es/net/aspose.pdf/heading/
---
## Clase Encabezado

Representa un encabezado.

```csharp
public sealed class Heading : TextFragment
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Heading](heading/)(int) | Inicializa una nueva instancia de la clase Cell. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Obtiene la posición del texto para el texto, representado con el objeto [`TextFragment`](../../aspose.pdf.text/textfragment/). La YIndent de la estructura Position representa la coordenada de línea base del fragmento de texto. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Obtiene la página de destino. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Obtiene o establece la nota al pie del párrafo. (solo para generación de pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Obtiene o establece la nota al pie del párrafo. (solo para generación de pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Obtiene el objeto de formulario que contiene el TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Obtiene o establece una alineación horizontal del fragmento de texto. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Establece el hipervínculo del fragmento |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Obtiene que el encabezado debe ser numerado automáticamente. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para generación de pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Obtiene que el encabezado debe estar en la lista de contenido. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para generación de pdf) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Obtiene el nivel. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Obtiene la página que contiene el TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Obtiene o establece la posición del texto para el texto, representado con el objeto [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Obtiene el rectángulo del TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Obtiene las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto/largo. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Obtiene los segmentos de texto para el [`TextFragment`](../../aspose.pdf.text/textfragment/) actual. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Obtiene el número de inicio del encabezado. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Obtiene o establece el estilo. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Obtiene o establece el objeto de texto String que representa el objeto [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Obtiene o establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no se puede escribir con la fuente. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Obtiene o establece el estado del texto para el texto que representa el objeto [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Obtiene la página que contiene este encabezado. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Obtiene la parte superior Y de estos encabezados. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Obtiene o establece la etiqueta del usuario. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del fragmento de texto. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Obtiene o establece el conteo de líneas de ajuste para este párrafo (solo para generación de pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Clona el encabezado. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Clona el encabezado con todos los segmentos. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Obtiene los [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) que representan la parte especificada del texto del [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### Ver También

* clase [TextFragment](../../aspose.pdf.text/textfragment/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)