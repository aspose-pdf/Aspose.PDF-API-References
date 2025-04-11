---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.GraphicalPdfComparer. Représente une classe pour comparer graphiquement des documents PDF. Doit être utilisée pour rechercher de petits changements principalement d'ordre graphique. Pour comparer les changements de contenu textuel, utilisez d'autres classes de comparaison PDF.
type: docs
weight: 3190
url: /fr/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## Classe GraphicalPdfComparer

Représente une classe pour comparer graphiquement des documents PDF. Doit être utilisée pour rechercher de petits changements, principalement d'ordre graphique. Pour comparer les changements de contenu textuel, utilisez d'autres classes de comparaison PDF.

```csharp
public class GraphicalPdfComparer
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Obtient et définit la couleur du drapeau de changement. La couleur par défaut est rouge. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Obtient et définit la résolution des images résultantes. La valeur par défaut est 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Obtient et définit la valeur de seuil en pourcentage. Cette valeur vous permet d'ignorer les petits changements s'ils ne sont pas significatifs pour vous. La valeur par défaut est 0%. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Compare graphiquement des documents. Le résultat de la comparaison est placé dans des images. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Compare graphiquement des documents. Le résultat de la comparaison est placé dans un document PDF. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Compare graphiquement des pages. Le résultat de la comparaison est placé dans une image. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Compare graphiquement des pages. Le résultat de la comparaison est placé dans un document PDF. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Compare graphiquement des pages. Le résultat de la comparaison est placé dans un document PDF. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Obtient les différences entre les images des pages. Le résultat contient une image de la première page comparée et un tableau de différences. |

### Voir aussi

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)