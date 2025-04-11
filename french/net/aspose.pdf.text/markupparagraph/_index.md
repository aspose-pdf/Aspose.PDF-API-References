---
title: Class MarkupParagraph
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.MarkupParagraph. Représente un paragraphe
type: docs
weight: 10630
url: /fr/net/aspose.pdf.text/markupparagraph/
---
## Classe MarkupParagraph

Représente un paragraphe.

```csharp
public sealed class MarkupParagraph
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Liste des numéros de page sur lesquels le paragraphe est continué. Cela correspondra à la page où le paragraphe a commencé s'il continue dans la colonne suivante sur la même page. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Collection d'objets [`TextFragment`](../textfragment/) non vides du paragraphe. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Lignes du paragraphe. Chaque ligne est représentée par une liste de fragments de texte. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Points du polygone qui décrit le paragraphe. Le point de départ est le coin inférieur gauche du paragraphe. Et les points suivants sont dans une séquence antihoraire. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Points du polygone secondaire décrivant la continuation du paragraphe. Il ne sera pas nul si le paragraphe est continué dans la colonne ou la page suivante. Le point de départ est le coin inférieur gauche du paragraphe. Et les points suivants sont dans une séquence antihoraire. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Obtient ou définit le texte du paragraphe. |

### Voir aussi

* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)