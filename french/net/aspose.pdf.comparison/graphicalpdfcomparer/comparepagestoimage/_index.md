---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: Méthode GraphicalPdfComparer. Compare les pages graphiquement. Le résultat de la comparaison est placé dans une image
type: docs
weight: 70
url: /fr/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## Méthode GraphicalPdfComparer.ComparePagesToImage

Compare les pages graphiquement. Le résultat de la comparaison est placé dans une image.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page1 | Page | La première page à comparer. |
| page2 | Page | La deuxième page à comparer. |
| resultImagePath | String | Le chemin vers le fichier image cible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Si les pages comparées sont de tailles différentes. Si resultImagePath est nul ou une chaîne vide. Il y a un format d'image de sauvegarde inconnu. |

### Voir aussi

* classe [Page](../../../aspose.pdf/page/)
* classe [GraphicalPdfComparer](../)
* espace de noms [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)