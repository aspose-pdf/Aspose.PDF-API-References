---
title: MarkupParagraph
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente un paragraphe.
type: docs
weight: 6810
url: /fr/net/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class

Représente un paragraphe.

```csharp
public sealed class MarkupParagraph
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers) { get; } | Liste des numéros de page sur lesquels le paragraphe se poursuit. Il correspondra à la page où le paragraphe a commencé s'il se poursuit dans la colonne suivante sur la même page. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments) { get; } | Collection de non vide[`TextFragment`](../textfragment) objets du paragraphe. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines) { get; } | Lignes de paragraphe. Chaque ligne représentée par une liste de fragments de texte. |
| [Points](../../aspose.pdf.text/markupparagraph/points) { get; } | Points du polygone décrivant le paragraphe. Le point de départ est le coin inférieur gauche du paragraphe. Et les points suivants sont dans le sens inverse des aiguilles d'une montre. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints) { get; } | Les points du polygone secondaire décrivent la suite du paragraphe. Il ne sera pas nul si le paragraphe se poursuit dans la colonne ou la page suivante. Le point de départ est le coin inférieur gauche du paragraphe. Et les points suivants sont dans le sens inverse des aiguilles d'une montre. |
| [Text](../../aspose.pdf.text/markupparagraph/text) { get; } | ObtientString objet texte que le[`MarkupParagraph`](../markupparagraph) l'objet représente. |

### Voir également

* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
