---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextParagraph. Représente des paragraphes de texte en tant qu'objet de texte multiligne
type: docs
weight: 10990
url: /fr/net/aspose.pdf.text/textparagraph/
---
## Classe TextParagraph

Représente des paragraphes de texte en tant qu'objet de texte multiligne.

```csharp
public sealed class TextParagraph
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextParagraph](textparagraph/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Obtient ou définit la valeur d'indentation des lignes suivantes. Si défini sur une valeur non nulle, il a un avantage sur la valeur FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Obtient ou définit les options de formatage. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Obtient ou définit l'alignement horizontal pour le texte à l'intérieur du [`Rectangle`](./rectangle/) du paragraphe. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Obtient ou définit la valeur indiquant si le texte est justifié. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Obtient ou définit le rembourrage. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Obtient ou définit la position du paragraphe. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Obtient ou définit le rectangle du paragraphe. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Obtient ou définit l'angle de rotation en degrés. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Obtient ou définit la valeur d'indentation des lignes suivantes. Si défini sur une valeur non nulle, il a un avantage sur la valeur FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Obtient le rectangle du texte placé dans le paragraphe. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Obtient ou définit l'alignement vertical pour le texte à l'intérieur du [`Rectangle`](./rectangle/) du paragraphe. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Ajoute une ligne de texte |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Ajoute une ligne de texte avec des paramètres d'état de texte. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Ajoute une ligne de texte. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Ajoute une ligne de texte avec des paramètres d'état de texte. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Ajoute une ligne de texte avec des paramètres d'état de texte. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Ajoute une ligne de texte avec des paramètres d'état de texte |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Ajoute une ligne de texte avec des paramètres d'état de texte |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Commence l'édition du TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Termine l'édition du TextParagraph. |

## Exemples

L'exemple démontre comment créer un objet de paragraphe de texte et l'ajouter à la page Pdf.

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

* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)