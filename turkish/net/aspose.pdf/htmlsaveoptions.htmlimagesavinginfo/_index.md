---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo sınıfı. Bu sınıf, PDF'den HTML'ye dönüşüm sırasında dış kaynak görüntü dosyalarının kaydedilmesi ile ilgili veri kümesini temsil eder.
type: docs
weight: 5640
url: /tr/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo sınıfı

Bu sınıf, PDF'den HTML'ye dönüşüm sırasında dış kaynak görüntü dosyasının kaydedilmesi ile ilgili veri kümesini temsil eder.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel yöntem koduna giden varsayılan dosya adı. Bu, özel kodda dosyanın nasıl işleneceğine veya nereye kaydedileceğine karar vermek için kullanılabilir. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Dönüştürücü tarafından ayarlanır. Kaydedilen dosyanın ikili içeriğini temsil eder. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Bu bayrak, özel kodda "true" olarak ayarlanmalıdır; eğer bazı nedenlerden dolayı önerilen dosya, özel kodla değil, dönüştürücünün kendi koduyla standart bir şekilde işlenmelidir. Yani, true olarak ayarlanması, özel kodun referans alınan dosyayı işlemediği ve dönüştürücünün bunu kendisinin (her iki anlamda - bir yere kaydetme ve referans dosyasında adlandırma) ele alması gerektiği anlamına gelir. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Özel koda, kaydedilen görüntünün hangi HTML sayfa dosyasına ait olduğunu söyler. Sayfalar arasında bölme kapatıldığında, bu değer her zaman '1' içerir; çünkü bu durumda yalnızca bir HTML sayfası oluşturulur. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | HTML'de referans verilen kaydedilen görüntünün türünü temsil eder. Dönüştürücü tarafından ayarlanır ve özel kodda ne yapılması gerektiğine karar vermek için kullanılabilir. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | Kaydedilen görüntü, HTML'ye ait olabilir veya HTML'ye gömülü SVG'den çıkarılabilir. Bu özellik, özel koda işlenen görüntünün ebeveyn türünün ne olduğunu söyleyebilir. Dönüştürücü tarafından ayarlanır ve özel kodda bu görüntü ile ne yapılması gerektiğine karar vermek için kullanılabilir (örneğin, özel kod görüntünün nereye kaydedileceğine veya ebeveyn içeriğinde nasıl referans alınacağına karar verebilir). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Özel koda, kaydedilen görüntünün orijinal PDF belgesinin hangi sayfasına ait olduğunu söyler. Orijinal belgenin tüm sayfalarının kaydedilmeyeceği durumlarda, bu değer bize orijinal PDF'deki ana sayfa numarasını bildirir. Orijinal sayfa numarası herhangi bir nedenle bilinmiyorsa, her zaman '1' döner. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel yöntem koduna giden varsayılan dosya adı. Bu, özel kodda dosyanın nasıl işleneceğine veya nereye kaydedileceğine karar vermek için kullanılabilir. |

### Ayrıca Bakınız

* sınıf [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* sınıf [HtmlSaveOptions](../htmlsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)