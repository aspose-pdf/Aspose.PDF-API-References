---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptions sınıfı. SVG formatına dışa aktarma için kaydetme seçenekleri
type: docs
weight: 10230
url: /tr/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions sınıfı

SVG formatına dışa aktarma için kaydetme seçenekleri

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps sayfaları hazırlanırken font gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesi performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belge yanıt olarak kaydedildikten sonra Yanıt nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için görüntü veya metin çıkarmak için işlevselliği etkinleştirir. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Verilerin kaydedileceği format. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve kaydetme işlemi devam eder, ancak kullanıcı iptal etmeyi de döndürebilir; bu durumda kaydetme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Çıktının tek bir zip arşivi olarak oluşturulup oluşturulmayacağını belirtir. Çok sayfalı kaynak belgesi için svg dosyalarının adlandırma kurallarını görmek için 'TreatTargetFileNameAsDirectory' seçeneklerine bakınız; bu kurallar ziplenmiş çıktı dosyaları setine de uygulanır. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Bu alan, kaydedilen SVG'ye gömülü BMP veya JPEG gibi referanslı dış resim dosyalarının özelleştirilmiş işlenmesi sırasında kullanılacak kaydetme stratejisini içerebilir (varsa). Bu strateji, kaynakları işlemesi ve oluşturulan SVG'de kaydedilen kaynağın istenen URI'sini temsil eden bir dize döndürmesi gerekir. Bu veya başka bir dosya için işlem nedeniyse dönüştürücünün kodu tarafından yapılması gerekiyorsa, lütfen özel kodda 'imageSavingInfo' parametresinin değişkeninde 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde yapılması gerektiğini belirtir; sanki dış bir özel kod yokmuş gibi. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Sayfaları birkaç iş parçacığında işleyin. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Çıktı belgesinin tipografik noktalarından piksellere ölçeklenip ölçeklenmeyeceğini belirtir. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Bu seçenek, istenen çıktı dosyası yerine aynı isimde bir hedef dizininin (henüz yoksa) oluşturulup oluşturulmayacağını tanımlar. Eğer öyleyse, bu dizin, tüm çıktı SVG sayfalarının görüntülerini içerecektir (aşağıda açıklandığı gibi). Eğer hayırsa, ilk sayfadan farklı sayfa çıktı dosyaları tam olarak istenen dizinde ana çıktı dosyası olarak oluşturulacak, ancak dosya adında _[2...n] ekini içerecektir; bu, sayfa numarası ile tanımlanır, örneğin, çıktı dosyasını "C:\AsposeTests\output.svg" olarak tanımlarsanız ve çıktı birden fazla svg sayfa dosyası içeriyorsa, sayfa dosyaları "C:\AsposeTests\" dizininde de oluşturulacak ve 'output.svg', 'output_2.svg', 'output_3.svg' vb. adlarını alacaktır. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Bazen PDF'ler, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri içerir (sayfalar veya tablo hücreleri için). Bu durumda, hedef formatların (örneğin, DOCS formatı için MsWord) renderleyicileri bazen arka plan görüntülerinin parçaları arasında görünür sınırlar oluşturur; çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Eğer dışa aktarılan belgede aynı arka plan görüntülerinin parçaları arasında görünür sınırlar varsa, bu ayarı kullanarak istenmeyen etkiden kurtulmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu nedenle lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

## Örnekler

Aşağıdaki örnek, PDF dosyasını SVG dosyasına dönüştürmeyi göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### Ayrıca Bakınız

* sınıf [UnifiedSaveOptions](../unifiedsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)