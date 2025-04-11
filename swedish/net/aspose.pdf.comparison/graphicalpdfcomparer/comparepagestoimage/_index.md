---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer metod. Jämför sidor grafiskt. Jämförelseresultatet placeras i en bild
type: docs
weight: 70
url: /sv/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## GraphicalPdfComparer.ComparePagesToImage metod

Jämför sidor grafiskt. Jämförelseresultatet placeras i en bild.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page1 | Page | Den första sidan att jämföra. |
| page2 | Page | Den andra sidan att jämföra. |
| resultImagePath | Sträng | Sökvägen till målbildfilen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Om de sidor som jämförs har olika storlekar. Om resultImagePath är null eller en tom sträng. Det finns ett okänt bildformat för sparande. |

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [GraphicalPdfComparer](../)
* namnrymd [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* samling [Aspose.PDF](../../../)