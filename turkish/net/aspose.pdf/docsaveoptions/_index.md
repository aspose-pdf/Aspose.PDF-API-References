---
title: DocSaveOptions
second_title: Aspose.PDF for .NET API Referansı
description: Doküman formatına dışa aktarma seçeneklerini kaydedin
type: docs
weight: 1840
url: /tr/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Doküman formatına dışa aktarma seçeneklerini kaydedin

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DocSaveOptions](docsaveoptions)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend) { get; set; } | Paragraf veya satır sonları kullanın |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize) { get; set; } | Kaynak ve hedef biçim çiftine toplu dönüştürme uygulanabilir ise parti boyutunu tanımlar. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Belge yanıta kaydedildikten sonra Response nesnesinin kapatılacağını belirten boole değerini alır veya ayarlar. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için resim veya metin çıkarma işlevini açtı . |
| [Format](../../aspose.pdf/docsaveoptions/format) { get; set; } | Çıktı formatı |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx) { get; set; } | Dönüştürülen görüntüler X çözünürlüğü. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony) { get; set; } | Dönüştürülen resimler Y çözünürlük. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines) { get; set; } | Bu parametre, metin satırlarını paragraflar halinde gruplamak için kullanılır. İki göreli metin satırının birbirinden ne kadar uzakta olabileceğini belirler. Metin satırlarının yüksekliğinin yüzde yüz olarak belirtilir. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath) { get; set; } | Bellek kaydetme modunda dönüştürme sırasında geçici veriyi tutmak için yolu (dosya adı veya dizin adı) tanımlar. |
| [Mode](../../aspose.pdf/docsaveoptions/mode) { get; set; } | Tanıma modu. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets) { get; set; } | Mermilerin tanınmasını açın |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity) { get; set; } | Pdf'de sözcükler, harflerini veya hecelerini bağımsız olarak yazdırarak sözcükleri yazdıran operatörlerle dahili olarak temsil edilebilir. Bu nedenle, bazen sözcükleri algılamak için, aslında sözcükler olan gruplar bağımsız karakter algılamaya ihtiyacımız vardır. Bu ayar, kaynak PDF'de sözcüklerin tanınması sırasında sözcükler arasındaki mesafe olarak ele alınması gereken metin öğeleri (harfler, heceler) arasındaki boşluk genişliğini tanımlar. . (harfler arasında en azından bu genişlikte boşluk olması, metin öğelerinin farklı kelimelere ait olduğu anlamına gelir). Yazı tipi boyutuna göre normlanmıştır - 1.0, varsayılan kelimenin yazı tipi boyutunun %100'ü anlamına gelir. DİKKAT!Sadece durumlarda kullanılır kaynak PDF, en uygun değerin yazı tipinden hesaplanamadığı, nadiren kullanılan belirli yazı tiplerini içerdiğinde. Dolayısıyla, çoğu durumda bu parametre sonuç belgesinde hiçbir şeyi değiştirmez. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Veri kaydetme biçimi. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Oluşturulan uyarıları işlemek için geri arama. WarningHandler, Continue veya Abort'u belirten ReturnAction numaralandırma öğesini döndürür. Devam, varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı ayrıca Durdur'a da dönebilir, bu durumda Kaydetme işlemi sona ermelidir. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler) | Bu işleyici dönüşüm ilerleme olaylarını işlemek için kullanılabilir fe ilerleme çubuğunu veya işlenen sayfaların mevcut miktarı hakkındaki mesajları göstermek için kullanılabilir, işleyicinin konsoldaki ilerlemeyi gösteren kodunun örneği : |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Bazen PDF'ler arka plan görüntülerini (sayfaların veya tablo hücrelerinin) içerir , birbirinin yanına yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşturulmuştur. Bu durumda hedef biçimlerin oluşturucuları (DOCS biçimi için fe MsWord) bazen arka plan görüntülerinin bölümleri arasında görünür sınırlar oluşturur , görüntü kenar yumuşatma (anti-aliasing) tekniklerinin Acrobat Reader'dan farklı olmasına neden olur. Dışa aktarılan belge, aynı arka plan görüntülerinin bölümleri arasında bu tür görünür sınırlar içeriyor gibi görünüyorsa, bundan kurtulmak için lütfen bu ayarı kullanmayı deneyin istenmeyen etki. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü yavaşlatır, bu nedenle, lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

### Ayrıca bakınız

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
