---
title: "Classe GraphicalPdfComparer"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Comparison.GraphicalPdfComparer class. Représente une classe pour comparer graphiquement les Documents PDF. Elle doit être utilisée pour rechercher de petites modifications principalement de nature graphique. Pour comparer les modifications de contenu texte, utilisez d'autres classes de comparaison PDF."
type: docs
weight: 3300
url: /fr/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

Représente une classe permettant de comparer graphiquement des documents PDF. Elle doit être utilisée pour rechercher de petites modifications, principalement de nature graphique. Pour comparer les changements de contenu texte, utilisez d'autres classes de comparaison PDF.

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
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Obtient et définit la couleur du drapeau de modification. La couleur par défaut est rouge. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Obtient et définit la résolution des images résultantes. La valeur par défaut est de 150 dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Obtient et définit la valeur du seuil en pourcentage. Cette valeur vous permet d'ignorer les petites modifications si elles ne sont pas significatives pour vous. La valeur par défaut est de 0 %. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Compare les documents graphiquement. Le résultat de la comparaison est placé dans des images. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Compare les documents graphiquement. Le résultat de la comparaison est placé dans un Document PDF. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Compare les pages graphiquement. Le résultat de la comparaison est placé dans une image. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Compare les pages graphiquement. Le résultat de la comparaison est placé dans un Document PDF. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Compare les pages graphiquement. Le résultat de la comparaison est placé dans un Document PDF. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Obtient les différences entre les images des pages. Le résultat contient une image de la première page comparée et un tableau de différences. |

### Voir aussi

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


