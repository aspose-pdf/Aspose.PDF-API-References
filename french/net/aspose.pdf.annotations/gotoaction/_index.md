---
title: Class GoToAction
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.GoToAction. Représente une action de saut qui change la vue vers un emplacement de page de destination spécifié et un facteur de grossissement
type: docs
weight: 1830
url: /fr/net/aspose.pdf.annotations/gotoaction/
---
## Classe GoToAction

Représente une action de saut qui change la vue vers une destination spécifiée (page, emplacement et facteur de grossissement).

```csharp
public class GoToAction : PdfAction
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GoToAction](gotoaction/#constructor_1)(ExplicitDestination) | Constructeur. |
| [GoToAction](gotoaction/#constructor_3)(Page) | Constructeur pour la classe GoToAction. |
| [GoToAction](gotoaction/#constructor_2)(Document, string) | Action liée à une destination nommée. |
| [GoToAction](gotoaction/#constructor_4)(Page, ExplicitDestinationType, params double[]) | Constructeur pour la classe GoToAction. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [Destination](../../aspose.pdf.annotations/gotoaction/destination/) { get; set; } | Obtient ou définit la destination vers laquelle sauter. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Actions suivantes dans la séquence. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Obtient la chaîne pour l'action ECMAScript. |

### Voir aussi

* classe [PdfAction](../pdfaction/)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)