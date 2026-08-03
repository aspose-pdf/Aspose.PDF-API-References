---
title: "GraphicalPdfComparer.CompareDocumentsToImages"
second_title: "Aspose.PDF för .NET API‑referens"
description: "GraphicalPdfComparer‑metod. Jämför dokument grafiskt. Jämförelsens resultat placeras i bilder"
type: docs
weight: 50
url: /sv/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages method

Jämför dokument grafiskt. Jämförelsresultatet placeras i bilder.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Dokument | Det första dokumentet att jämföra. |
| document2 | Dokument | Det andra dokumentet att jämföra. |
| targetDirectory | String | Katalogen för att spara jämförelsresultat. |
| fileNamePrefix | String | Bildnamnsprefixet. |
| imageFormat | ImageFormat | Bildformatet att spara. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Om de sidor som jämförs har olika storlekar. Om targetDirectory är null eller en tom sträng. Om fileNamePrefix är null eller en tom sträng. |

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


