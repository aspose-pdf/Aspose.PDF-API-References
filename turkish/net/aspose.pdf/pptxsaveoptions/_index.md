---
title: Class PptxSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PptxSaveOptions sınıfı. SVG formatına dışa aktarma için kaydetme seçenekleri
type: docs
weight: 9480
url: /tr/net/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions sınıfı

SVG formatına dışa aktarma için kaydetme seçenekleri

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps sayfaları hazırlanırken yazı tipi gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesi performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belge yanıt olarak kaydedildikten sonra Yanıt nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | Bu işleyici, dönüşüm ilerleme olaylarını yönetmek için kullanılabilir; örneğin, işlenen sayfa sayısı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir, ilerlemeyi konsolda gösteren işleyici kodu örneği: |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için resim veya metin çıkarma işlevselliğini etkinleştirir. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | Resim çözünürlüğünü (dpi) alır veya ayarlar. Varsayılan 192 dpi'dir. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | Metin sütunları tanımayı açıp kapatır |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Veri kaydetme formatı. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | Doğru olarak ayarlandığında, resimler tüm diğer grafiklerden ayrılır |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | Doğru olarak ayarlandığında, tüm içerik resim olarak tanınır (sayfa başına bir) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı yönetmek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve kaydetme işlemi devam eder, ancak kullanıcı iptal döndürebilir; bu durumda kaydetme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Sayfaları birkaç iş parçacığında işleyin. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Bazen PDF'ler, yan yana yerleştirilmiş birkaç aynı döşeme arka plan resminden oluşan arka plan resimleri içerir (sayfalar veya tablo hücreleri için). Bu durumda, hedef formatların (örneğin, DOCS formatı için MsWord) işleyicileri bazen arka plan resimlerinin parçaları arasında görünür sınırlar oluşturur, çünkü resim kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Eğer dışa aktarılan belgede aynı arka plan resimlerinin parçaları arasında görünür sınırlar varsa, bu ayarı kullanarak istenmeyen etkiden kurtulmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu nedenle bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

## Örnekler

Aşağıdaki örnek, PDF dosyasını PPT veya PPTX dosyasına dönüştürmeyi göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// The path to your PPT or PPTX File.
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize PptxSaveOptions	
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// Save PPT or PPTX file
		pdfDocument.Save(pptxFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf")
    ' The path to your PPT or PPTX File.
    Dim pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize PptxSaveOptions    
        Dim saveOptions As PptxSaveOptions = New PptxSaveOptions()
 
        ' Save PPT or PPTX file
        pdfDocument.Save(pptxFile, saveOptions)
    End Using
```

### Ayrıca Bakınız

* sınıf [UnifiedSaveOptions](../unifiedsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)