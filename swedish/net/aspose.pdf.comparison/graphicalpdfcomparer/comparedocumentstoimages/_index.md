---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer-metod. Jämför dokument grafiskt. Jämförelseresultatet placeras i bilder
type: docs
weight: 50
url: /sv/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages metod

Jämför dokument grafiskt. Jämförelseresultatet placeras i bilder.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Document | Det första dokumentet att jämföra. |
| document2 | Document | Det andra dokumentet att jämföra. |
| targetDirectory | String | Katalogen för att spara jämförelsens resultat. |
| fileNamePrefix | String | Prefix för bildnamn. |
| imageFormat | ImageFormat | Bildformatet för att spara. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Om sidorna som jämförs har olika storlekar. Om targetDirectory är null eller en tom sträng. Om fileNamePrefix är null eller en tom sträng. |

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [GraphicalPdfComparer](../)
* namnrymd [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)