---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo sınıfı. HtmlSaveOptions'ın SplitToPages özelliği varsa, PDF'den HTML'ye dönüştürme sırasında birden fazla HTML dosyası oluşturulur. Bu sınıf, PDF'den HTML'ye dönüştürme sırasında bir HTML sayfasının işaretlemesinin özel olarak kaydedilmesiyle ilgili veri kümesini temsil eder.
type: docs
weight: 5670
url: /tr/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo sınıfı

HtmlSaveOptions'ın SplitToPages özelliği varsa, PDF'den HTML'ye dönüştürme sırasında birden fazla HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu sınıf, PDF'den HTML'ye dönüştürme sırasında bir HTML sayfasının işaretlemesinin özel olarak kaydedilmesiyle ilgili veri kümesini temsil eder.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Alanlar

| Ad | Açıklama |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Dönüştürücü tarafından ayarlanır. Kaydedilen HTML'yi akış olarak temsil eder. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Gerekli olduğunda özel kodda ayarlanmalıdır. Bu bayrak, bazı nedenlerden dolayı sağlanan HTML işaretlemesinin özel kodla değil, dönüştürücünün kendi koduyla standart bir şekilde işlenmesi gerekiyorsa özel kodda "true" olarak ayarlanmalıdır. Yani, bu bayrağın özel kodda ayarlanması, özel kodun referans dosyayı işlemediği ve dönüştürücünün bunu kendisinin ele alması gerektiği anlamına gelir. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlandığında, dönüştürme sırasında birden fazla HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, kaydedilen HTML sayfasının dosyasının sırasını içerir. Bu özellik, özel kodun HTML sayfasını nasıl işleyeceğine veya nereye kaydedeceğine karar vermek için kullanılabilir ve sayfaların bölünmesi kapatıldığında bu değer her zaman '1' içerir, çünkü bu durumda tüm kaynak belge için yalnızca bir büyük HTML sayfası üretilir. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlandığında, dönüştürme sırasında birden fazla HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, özel koda kaydedilen HTML işaretlemesinin hangi orijinal PDF sayfasından oluşturulduğunu bildirir. Orijinal sayfa numarası bazı nedenlerden dolayı bilinmiyorsa veya SplitOnPages=false ise, bu özellik her zaman '0' içerir; bu, dönüştürücünün sağlanan HTML işaretleme dosyası için kesin orijinal PDF sayfa numarasını sağlayamayacağını gösterir. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel yöntem koduna giden varsayılan dosya adı. İçeriği nasıl işleyeceğine veya nereye kaydedeceğine karar vermek için özel kodda kullanılabilir. |

### Ayrıca Bakınız

* sınıf [HtmlSaveOptions](../htmlsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)