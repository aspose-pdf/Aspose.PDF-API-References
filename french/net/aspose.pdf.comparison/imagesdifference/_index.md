---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.ImagesDifference. Représente la classe de résultat de la comparaison de deux pages PDF
type: docs
weight: 3230
url: /fr/net/aspose.pdf.comparison/imagesdifference/
---
## Classe ImagesDifference

Représente la classe de résultat de la comparaison de deux pages PDF.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Obtient le tableau des différences. Ce tableau est similaire au tableau de données d'image original obtenu à la suite de la méthode LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | La hauteur de la différence. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Obtient l'image de la première page comparée. L'image a un format de pixel de 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | Le pas des données d'image de différence. |

## Méthodes

| Nom | Description |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Convertit le tableau des différences en une image bitmap en utilisant les couleurs spécifiées. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Effectue toutes les opérations de nettoyage nécessaires avant que l'objet ne soit détruit. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Renvoie un nouveau bitmap représentant l'image de destination en appliquant le tableau des différences à l'image source. |

### Voir aussi

* espace de noms [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)