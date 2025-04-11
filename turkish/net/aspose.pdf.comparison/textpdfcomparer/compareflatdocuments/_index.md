---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer metodu. İki belgeyi sayfa sayfa karşılaştırır. Belgeler bir bütün olarak karşılaştırılır. Metinleri karşılaştırmadan önce, belge sayfalarının metinleri bir metin haline getirilir.
type: docs
weight: 50
url: /tr/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

İki belgeyi sayfa sayfa karşılaştırır. Belgeler bir bütün olarak karşılaştırılır. Metinleri karşılaştırmadan önce, belge sayfalarının metinleri bir metin haline getirilir.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document1 | Document | İlk belge. |
| document2 | Document | İkinci belge. |
| options | ComparisonOptions | Karşılaştırma seçenekleri. |

### Dönüş Değeri

Değişiklikler listesi.

### Ayrıca Bakınız

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

İki belgeyi sayfa sayfa karşılaştırır. Sonuç bir PDF dosyasına kaydedilir. Belgeler bir bütün olarak karşılaştırılır. Metinleri karşılaştırmadan önce, belge sayfalarının metinleri bir metin haline getirilir.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document1 | Document | İlk belge. |
| document2 | Document | İkinci belge. |
| options | ComparisonOptions | Karşılaştırma seçenekleri. |
| resultPdfDocumentPath | String | Karşılaştırma sonuçlarını kaydetmek için PDF dosyasının yolu. |

### Dönüş Değeri

Değişiklikler listesi.

### Ayrıca Bakınız

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)