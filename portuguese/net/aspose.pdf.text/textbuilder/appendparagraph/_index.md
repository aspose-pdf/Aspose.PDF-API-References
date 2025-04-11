---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: Método TextBuilder. Anexa parágrafo de texto à página Pdf
type: docs
weight: 20
url: /pt/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## Método TextBuilder.AppendParagraph

Anexa parágrafo de texto à página Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textParagraph | TextParagraph | Objeto de parágrafo de texto. |

## Exemplos

O exemplo demonstra como criar um objeto de parágrafo de texto e anexá-lo à página Pdf.

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

### Veja Também

* classe [TextParagraph](../../textparagraph/)
* classe [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)