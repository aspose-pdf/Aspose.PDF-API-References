---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer metodu. İki belgeyi sayfa sayfa karşılaştırır
type: docs
weight: 40
url: /tr/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

İki belgeyi sayfa sayfa karşılaştırır.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document1 | Document | İlk belge.. |
| document2 | Document | İkinci belge. |
| options | ComparisonOptions | Karşılaştırma seçenekleri. |

### Dönüş Değeri

Sayfa başına değişiklikler listesi.

### Ayrıca Bakınız

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

İki belgeyi sayfa sayfa karşılaştırır. Sonuç bir PDF dosyasına kaydedilir.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document1 | Document | İlk belge.. |
| document2 | Document | İkinci belge. |
| options | ComparisonOptions | Karşılaştırma seçenekleri. |
| resultPdfDocumentPath | String | Karşılaştırma sonuçlarını kaydetmek için PDF dosyasının yolu. |

### Dönüş Değeri

Sayfa başına değişiklikler listesi.

### Ayrıca Bakınız

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)