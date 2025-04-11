---
title: Class ApsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ApsSaveOptions sınıfı. APS XML formatına dışa aktarma için kaydetme seçenekleri
type: docs
weight: 2760
url: /tr/net/aspose.pdf/apssaveoptions/
---
## ApsSaveOptions sınıfı

APS XML formatına dışa aktarma için kaydetme seçenekleri.

```csharp
public class ApsSaveOptions : UnifiedSaveOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ApsSaveOptions](apssaveoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | APS sayfaları hazırlanırken yazı tipi gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesi performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belge yanıt olarak kaydedildikten sonra Yanıt nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için resim veya metin çıkarma işlevselliğini etkinleştirir. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Veri kaydetme formatı. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve kaydetme işlemi devam eder, ancak kullanıcı iptal etmeyi de döndürebilir; bu durumda kaydetme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Sayfaları birkaç iş parçacığında işleme. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Bazen PDF'ler, yan yana yerleştirilmiş birkaç aynı döşeme arka plan resminden oluşan arka plan resimleri içerir (sayfalar veya tablo hücreleri için). Bu durumda, hedef formatların (örneğin, DOCS formatı için MsWord) işleyicileri bazen arka plan resimlerinin parçaları arasında görünür sınırlar oluşturur; çünkü resim kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Eğer dışa aktarılan belgede aynı arka plan resimlerinin parçaları arasında görünür sınırlar varsa, bu ayarı kullanarak istenmeyen etkiden kurtulmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu nedenle bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

## Örnekler

Aşağıdaki örnek, PDF dosyasını APS dosyasına dönüştürmeyi göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-APS.pdf");

	// The path to output APS File.
	var apsFile = Path.Combine(dataDir, "PDF-to-APS.aps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize ApsSaveOptions  	
		ApsSaveOptions saveOptions = new ApsSaveOptions();
		
		// Save APS file
		pdfDocument.Save(apsFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-APS.pdf")

    ' The path to output APS File.
    Dim apsFile = Path.Combine(dataDir, "PDF-to-APS.aps")
 
    Using pdfDocument As Document = New Document(pdfFile)

        ' Initialize ApsSaveOptions    
        Dim saveOptions As ApsSaveOptions = New ApsSaveOptions()
 
        ' Save APS file
        pdfDocument.Save(apsFile, saveOptions)
    End Using
```

### Ayrıca Bakınız

* sınıf [UnifiedSaveOptions](../unifiedsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)