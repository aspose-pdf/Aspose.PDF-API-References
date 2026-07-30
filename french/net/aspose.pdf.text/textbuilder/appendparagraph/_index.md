---
title: "TextBuilder.AppendParagraph"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode TextBuilder. Ajoute un paragraphe de texte à la page Pdf."
type: docs
weight: 20
url: /fr/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

Ajoute un paragraphe de texte à la page Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| textParagraph | TextParagraph | Objet paragraphe de texte. |

## Exemples

L'exemple montre comment créer un objet de paragraphe de texte et l'ajouter à la page Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// créer un paragraphe de texte
TextParagraph paragraph = new TextParagraph();
           
// définir le rectangle du paragraphe
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// définir les options de retour à la ligne
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// ajouter des lignes de chaîne
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// ajouter le paragraphe à la page Pdf avec le TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// enregistrer le document Pdf
doc.Save(outFile);
```

### Voir aussi

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


