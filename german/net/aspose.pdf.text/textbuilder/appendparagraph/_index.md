---
title: AppendParagraph
second_title: Aspose.PDF für .NET-API-Referenz
description: Hängt einen Textabsatz an die PDF-Seite an.
type: docs
weight: 20
url: /de/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

Hängt einen Textabsatz an die PDF-Seite an.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textParagraph | TextParagraph | Textabsatzobjekt. |

### Beispiele

Das Beispiel zeigt, wie Sie ein Textabsatzobjekt erstellen und es an die PDF-Seite anhängen.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// Textabsatz erstellen
TextParagraph paragraph = new TextParagraph();
           
// setze das Absatzrechteck
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// Optionen für den Wortumbruch festlegen
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// Stringzeilen anhängen
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// Den Absatz mit dem TextBuilder an die Pdf-Seite anhängen
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// Pdf-Dokument speichern
doc.Save(outFile);
```

### Siehe auch

* class [TextParagraph](../../textparagraph)
* class [TextBuilder](../../textbuilder)
* namensraum [Aspose.Pdf.Text](../../textbuilder)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->