---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer metodu. Belgeleri grafiksel olarak karşılaştırır. Karşılaştırma sonucu görüntülere yerleştirilir.
type: docs
weight: 50
url: /tr/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages metodu

Belgeleri grafiksel olarak karşılaştırır. Karşılaştırma sonucu görüntülere yerleştirilir.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document1 | Document | Karşılaştırılacak ilk belge. |
| document2 | Document | Karşılaştırılacak ikinci belge. |
| targetDirectory | String | Karşılaştırma sonuçlarını kaydetmek için dizin. |
| fileNamePrefix | String | Görüntülerin ad ön eki. |
| imageFormat | ImageFormat | Kaydedilecek görüntü formatı. |

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentException | Karşılaştırılan sayfalar farklı boyutlardaysa. targetDirectory null veya boş bir dizeyse. fileNamePrefix null veya boş bir dizeyse. |

### Ayrıca Bakınız

* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [GraphicalPdfComparer](../)
* ad alanı [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* derleme [Aspose.PDF](../../../)