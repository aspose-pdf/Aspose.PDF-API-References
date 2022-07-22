---
title: Heading
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa rumbo.
type: docs
weight: 3360
url: /es/net/aspose.pdf/heading/
---
## Heading class

Representa rumbo.

```csharp
public sealed class Heading : TextFragment
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Heading](heading)(int) | Inicializa una nueva instancia de la clase Cell. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Obtiene la posición del texto, representada con[`TextFragment`](../../aspose.pdf.text/textfragment) object. El YIndent de la estructura Position representa la coordenada de línea base del fragmento de texto. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage) { get; set; } | Obtiene la página de destino. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Obtiene o establece la nota final del párrafo (solo para generación de PDF) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Obtiene o establece la nota al pie del párrafo (solo para generación de pdf) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Obtiene el objeto de formulario que contiene el TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Obtiene o establece una alineación horizontal del fragmento de texto. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Establece el fragmento hipervínculo |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence) { get; set; } | Obtiene el encabezado que debe numerarse automáticamente. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtiene o establece que un párrafo está en línea. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInList](../../aspose.pdf/heading/isinlist) { get; set; } | Obtiene el encabezado que debe estar en la lista toc. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtiene o establece un valor booleano que obliga a generar este párrafo en una nueva página. El valor predeterminado es falso. (para la generación de PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el párrafo siguiente. El valor predeterminado es falso. (para la generación de PDF) |
| [Level](../../aspose.pdf/heading/level) { get; set; } | Obtiene el nivel. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para la generación de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Obtiene la página que contiene el TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Obtiene o establece la posición del texto para el texto, representado con[`TextFragment`](../../aspose.pdf.text/textfragment) objeto. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Obtiene el rectángulo del TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Obtiene opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por más corto/largo. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Obtiene segmentos de texto para el actual[`TextFragment`](../../aspose.pdf.text/textfragment) . |
| [StartNumber](../../aspose.pdf/heading/startnumber) { get; set; } | Obtiene el número de inicio del rumbo. |
| [Style](../../aspose.pdf/heading/style) { get; set; } | Obtiene o establece estilo. |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Obtiene o estableceString objeto de texto que el[`TextFragment`](../../aspose.pdf.text/textfragment) objeto representa. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Obtiene o establece el estado de texto para el texto que[`TextFragment`](../../aspose.pdf.text/textfragment) objeto representa. |
| [TocPage](../../aspose.pdf/heading/tocpage) { get; set; } | Obtiene la página que contiene este encabezado. |
| [Top](../../aspose.pdf/heading/top) { get; set; } | Obtiene la Y superior de estos encabezados. |
| [UserLabel](../../aspose.pdf/heading/userlabel) { get; set; } | Obtiene o establece la etiqueta del usuario. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Obtiene o establece una alineación vertical del fragmento de texto. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Obtiene o establece el recuento de líneas de ajuste para este párrafo (solo para generación de PDF) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex más grande se colocará sobre el gráfico con ZIndex más pequeño. ZIndex puede ser negativo. El gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone)() | Clonar el encabezado. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments)() | Clonar el encabezado con todos los segmentos. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Obtiene[`TextSegment`](../../aspose.pdf.text/textsegment) (s) que representa una parte especificada de la[`TextFragment`](../../aspose.pdf.text/textfragment) texto. |

### Ver también

* class [TextFragment](../../aspose.pdf.text/textfragment)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
