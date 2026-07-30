---
title: "Classe MarkupParagraph"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.MarkupParagraph. Représente un paragraphe"
type: docs
weight: 10810
url: /fr/net/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class

Représente un paragraphe.

```csharp
public sealed class MarkupParagraph
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Liste des numéros de page sur lesquels le paragraphe se poursuit. Elle correspondra à la page où le paragraphe a commencé s'il continue dans la colonne suivante sur la même page. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Collection d'objets [`TextFragment`](../textfragment/) non vides du paragraphe. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Lignes du paragraphe. Chaque ligne est représentée par une liste de fragments de texte. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Points du polygone qui décrit le paragraphe. Le point de départ est le coin inférieur gauche du paragraphe. Les points suivants sont dans l'ordre anti-horaire. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Points du polygone secondaire décrivant la continuation du paragraphe. Il ne sera pas nul si le paragraphe se poursuit dans la colonne suivante ou sur une autre page. Le point de départ est le coin inférieur gauche du paragraphe. Les points suivants sont dans l'ordre anti-horaire. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Obtient ou définit le texte du paragraphe. |

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


