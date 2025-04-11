---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: Método TextBuilder. Agrega un párrafo de texto a la página Pdf
type: docs
weight: 20
url: /es/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## Método TextBuilder.AppendParagraph

Agrega un párrafo de texto a la página Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textParagraph | TextParagraph | Objeto de párrafo de texto. |

## Ejemplos

El ejemplo demuestra cómo crear un objeto de párrafo de texto y agregarlo a la página Pdf.

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

* clase [TextParagraph](../../textparagraph/)
* clase [TextBuilder](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)