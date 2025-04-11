---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: Metodo TextBuilder. Aggiunge un paragrafo di testo alla pagina Pdf
type: docs
weight: 20
url: /it/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## Metodo TextBuilder.AppendParagraph

Aggiunge un paragrafo di testo alla pagina Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textParagraph | TextParagraph | Oggetto paragrafo di testo. |

## Esempi

L'esempio dimostra come creare un oggetto paragrafo di testo e aggiungerlo alla pagina Pdf.

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

### Vedi Anche

* classe [TextParagraph](../../textparagraph/)
* classe [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)