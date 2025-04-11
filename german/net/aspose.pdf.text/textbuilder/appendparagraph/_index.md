---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder-Methode. Fügt einen Textabsatz zur Pdf-Seite hinzu
type: docs
weight: 20
url: /de/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph-Methode

Fügt einen Textabsatz zur Pdf-Seite hinzu.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textParagraph | TextParagraph | Textabsatzobjekt. |

## Beispiele

Das Beispiel zeigt, wie man ein Textabsatzobjekt erstellt und es zur Pdf-Seite hinzufügt.

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

### Siehe auch

* Klasse [TextParagraph](../../textparagraph/)
* Klasse [TextBuilder](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)