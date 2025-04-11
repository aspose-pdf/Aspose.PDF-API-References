---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: Méthode TextBuilder. Ajoute un paragraphe de texte à la page Pdf
type: docs
weight: 20
url: /fr/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## Méthode TextBuilder.AppendParagraph

Ajoute un paragraphe de texte à la page Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| textParagraph | TextParagraph | Objet paragraphe de texte. |

## Exemples

L'exemple démontre comment créer un objet paragraphe de texte et l'ajouter à la page Pdf.

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

### Voir aussi

* classe [TextParagraph](../../textparagraph/)
* classe [TextBuilder](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)