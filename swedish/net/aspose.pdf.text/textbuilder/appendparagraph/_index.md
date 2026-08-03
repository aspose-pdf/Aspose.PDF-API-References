---
title: "TextBuilder.AppendParagraph"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextBuilder-metod. Lägger till textparagraf till Pdf-sida"
type: docs
weight: 20
url: /sv/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

Lägger till textparagraf på Pdf-sida.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textParagraph | TextParagraph | Textparagraf-objekt. |

## Exempel

Exemplet visar hur man skapar ett textparagrafobjekt och lägger till det på Pdf-sidan.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// skapa textparagraf
TextParagraph paragraph = new TextParagraph();
           
// ange paragrafens rektangel
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// ange alternativ för radbrytning
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// lägg till strängrader
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// lägg till paragrafen på Pdf-sidan med TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// spara Pdf-dokument
doc.Save(outFile);
```

### Se även

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


