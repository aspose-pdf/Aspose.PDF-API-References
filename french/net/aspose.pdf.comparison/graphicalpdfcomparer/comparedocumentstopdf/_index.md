---
title: GraphicalPdfComparer.CompareDocumentsToPdf
second_title: Aspose.PDF for .NET API Reference
description: Méthode GraphicalPdfComparer. Compare les documents graphiquement. Le résultat de la comparaison est placé dans un document PDF
type: docs
weight: 60
url: /fr/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/
---
## Méthode GraphicalPdfComparer.CompareDocumentsToPdf

Compare les documents graphiquement. Le résultat de la comparaison est placé dans un document PDF.

```csharp
public void CompareDocumentsToPdf(Document document1, Document document2, string resultPdfPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document1 | Document | Le premier document à comparer. |
| document2 | Document | Le deuxième document à comparer. |
| resultPdfPath | String | Le chemin du fichier pdf cible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Si les pages comparées sont de tailles différentes. Si resultPdfPath est nul ou une chaîne vide. |

### Voir aussi

* classe [Document](../../../aspose.pdf/document/)
* classe [GraphicalPdfComparer](../)
* espace de noms [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)