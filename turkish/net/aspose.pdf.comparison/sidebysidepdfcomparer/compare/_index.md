---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: SideBySidePdfComparer metodu. İki sayfayı karşılaştırır. Sonuç, ilk sayfanın önce yazıldığı ve ardından ikinci sayfanın yazıldığı bir PDF belgesinde kaydedilir. Değişiklikleri yan yana görmek için Adobe Acrobat'ta İki sayfa görünümünde açabilirsiniz. Silmeler sol sayfada, eklemeler sağ sayfada belirtilir.
type: docs
weight: 10
url: /tr/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

İki sayfayı karşılaştırır. Sonuç, ilk sayfanın önce yazıldığı ve ardından ikinci sayfanın yazıldığı bir PDF belgesinde kaydedilir. Değişiklikleri yan yana görmek için Adobe Acrobat'ta İki sayfa görünümünde açabilirsiniz. Silmeler sol sayfada, eklemeler sağ sayfada belirtilir.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page1 | Page | Karşılaştırılacak ilk sayfa. |
| page2 | Page | Karşılaştırılacak ikinci sayfa. |
| targetPdfPath | String | Karşılaştırma sonucunu kaydetmek için PDF dosyasının yolu. |
| options | SideBySideComparisonOptions | Karşılaştırma seçenekleri. |

### Ayrıca Bakınız

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

İki belgeyi karşılaştırır. Sayfalar birer birer karşılaştırılır. Karşılaştırılan belgelerin sayfaları, sonuç belgesine birer birer kopyalanır. Önce birinci belgeden birinci sayfa, ardından ikinci belgeden birinci sayfa. Sonra birinci belgeden ikinci sayfa ve ardından ikinci belgeden ikinci sayfa, vb. Değişiklikleri yan yana görmek için Adobe Acrobat'ta İki sayfa görünümünde açabilirsiniz. Silmeler sol sayfada, eklemeler sağ sayfada belirtilir.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document1 | Document | Karşılaştırılacak ilk belge. |
| document2 | Document | Karşılaştırılacak ikinci belge. |
| targetPdfPath | String | Karşılaştırma sonucunu kaydetmek için PDF dosyasının yolu. |
| options | SideBySideComparisonOptions | Karşılaştırma seçenekleri. |

### Ayrıca Bakınız

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)