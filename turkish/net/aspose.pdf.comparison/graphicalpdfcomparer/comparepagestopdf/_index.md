---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer metodu. Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir.
type: docs
weight: 80
url: /tr/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page1 | Page | İlk sayfa. |
| page2 | Page | İkinci sayfa. |
| resultPdfPath | String | Hedef pdf dosyasının yolu. |

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentException | Karşılaştırılan sayfalar farklı boyutlardaysa. resultPdfPath null veya boş bir dizeyse. |

### Ayrıca Bakınız

* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [GraphicalPdfComparer](../)
* ad alanı [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* derleme [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Sayfaları grafiksel olarak karşılaştırır. Karşılaştırma sonucu bir PDF belgesine yerleştirilir.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page1 | Page | İlk sayfa. |
| page2 | Page | İkinci sayfa. |
| pdfDocument | Document | PDF belge örneği. |

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentException | Karşılaştırılan sayfalar farklı boyutlardaysa. |

### Ayrıca Bakınız

* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [GraphicalPdfComparer](../)
* ad alanı [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* derleme [Aspose.PDF](../../../)