---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TextParagraph. Representa párrafos de texto como un objeto de texto multilinea
type: docs
weight: 10990
url: /es/net/aspose.pdf.text/textparagraph/
---
## Clase TextParagraph

Representa párrafos de texto como un objeto de texto multilinea.

```csharp
public sealed class TextParagraph
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextParagraph](textparagraph/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Obtiene o establece el valor de sangría de las líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Obtiene o establece las opciones de formato. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Obtiene o establece la alineación horizontal para el texto dentro del [`Rectangle`](./rectangle/) del párrafo. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Obtiene o establece el valor de si el texto está justificado. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Obtiene o establece el relleno. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Obtiene o establece la posición del párrafo. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Obtiene o establece el rectángulo del párrafo. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Obtiene o establece el ángulo de rotación en grados. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Obtiene o establece el valor de sangría de las líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Obtiene el rectángulo del texto colocado en el párrafo. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Obtiene o establece la alineación vertical para el texto dentro del [`Rectangle`](./rectangle/) del párrafo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Agrega una línea de texto |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Agrega una línea de texto con parámetros de estado de texto. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Agrega una línea de texto. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Agrega una línea de texto con parámetros de estado de texto. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Agrega una línea de texto con parámetros de estado de texto. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Agrega una línea de texto con parámetros de estado de texto |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Agrega una línea de texto con parámetros de estado de texto |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Comienza la edición del TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Finaliza la edición del TextParagraph. |

## Ejemplos

El ejemplo demuestra cómo crear un objeto de párrafo de texto y agregarlo a la página del Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### Ver También

* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../)