---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: Méthode GraphicalPdfComparer. Compare les documents graphiquement. Le résultat de la comparaison est placé dans des images
type: docs
weight: 50
url: /fr/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## Méthode GraphicalPdfComparer.CompareDocumentsToImages

Compare les documents graphiquement. Le résultat de la comparaison est placé dans des images.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document1 | Document | Le premier document à comparer. |
| document2 | Document | Le deuxième document à comparer. |
| targetDirectory | String | Le répertoire pour enregistrer les résultats de la comparaison. |
| fileNamePrefix | String | Le préfixe du nom des images. |
| imageFormat | ImageFormat | Le format d'image à enregistrer. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Si les pages comparées sont de tailles différentes. Si targetDirectory est nul ou une chaîne vide. Si fileNamePrefix est nul ou une chaîne vide. |

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)