---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptions sınıfı. Doc formatına dışa aktarma için kaydetme seçenekleri
type: docs
weight: 3750
url: /tr/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions sınıfı

Doc formatına dışa aktarma için kaydetme seçenekleri

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Paragraf veya satır sonu kırılmalarını kullanın |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Gruplandırılmış dönüşümün kaynak ve hedef format çiftine uygulanabilir olup olmadığını tanımlar. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps sayfaları hazırlanırken yazı tipi gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. PDF'den diğer formatlara dönüşümün performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belgenin yanıt içine kaydedildikten sonra Yanıt nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Type3 yazı tipleri için dönüşümü alır veya ayarlar. Type 3 yazı tiplerinde, glifler grafik operatörlerinin akışlarıyla tanımlanmalıdır. Bu, DOC/DOCX çıktısında metin yerine resimler gördüğümüz anlamına gelir. Bu bayrağı true olarak ayarlayın, böylece Type3 yazı tiplerini TTF'ye dönüştürün ve sonuç dosyasında metin elde edin. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Bu özellik, OCR alt katmanına sahip PDF belgeleri için görüntü veya metin çıkarmak için işlevselliği etkinleştirir. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Çıktı formatı |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Dönüştürülen görüntülerin X çözünürlüğü. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Dönüştürülen görüntülerin Y çözünürlüğü. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Bu parametre, metin satırlarını paragraflara gruplamak için kullanılır. İki göreli metin satırının ne kadar uzakta olabileceğini belirler. Metin satırlarının yüksekliğinin yüzdeleri cinsinden belirtilir. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Bellek kaydetme modunda dönüştürme sırasında geçici verileri tutmak için yol (dosya adı veya dizin adı) tanımlar. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Tanıma modu. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Madde işaretlerinin tanınmasını etkinleştir |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | PDF'de kelimeler, harflerini veya hecelerini bağımsız olarak yazdırarak kelimeleri yazdıran operatörlerle içsel olarak temsil edilebilir. Bu nedenle, kelimeleri tespit etmek için bazen aslında kelimeler olan bağımsız karakter gruplarını tespit etmemiz gerekir. Bu ayar, kaynak PDF'deki kelimelerin tanınması sırasında kelimeler arasındaki mesafe olarak ele alınması gereken metin öğeleri (harfler, heceler) arasındaki boşluğun genişliğini tanımlar. (Harfler arasında en az bu genişlikte boşluk bulunması, metinsel öğelerin farklı kelimelere ait olduğunu gösterir). Font boyutuna normlanmıştır - 1.0, varsayılan kelimenin font boyutunun %100'ünü ifade eder. DİKKAT! Bu, kaynak PDF'nin optimal değerinin fonttan hesaplanamayacağı belirli nadir kullanılan fontlar içerdiği durumlarda yalnızca kullanılır. Bu nedenle, çoğu durumda bu parametre sonuç belgesinde hiçbir şeyi değiştirmez. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Yazı tiplerini yeniden kaydetme prosedürünü alır veya ayarlar. true olarak ayarlanırsa, önceki yazı tipi özelliklerinin etkisini önlemek için her sayfada yazı tiplerini yeniden yükleriz ve yeni oluşturulan yazı tipini sıfırdan yükleriz. Performansı artırmak istiyorsanız bu seçeneği false olarak ayarlayın. Varsayılan değer true'dur; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Veri kaydetme formatı. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve kaydetme işlemi devam eder, ancak kullanıcı iptal döndürebilir; bu durumda kaydetme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Bu işleyici, dönüşüm ilerleme olaylarını işlemek için kullanılabilir; örneğin, işleme alınan sayfa sayısı hakkında ilerleme çubuğu veya mesajlar göstermek için kullanılabilir, işleyicinin konsolda ilerlemeyi gösteren kod örneği: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Sayfaları birkaç iş parçacığında işleyin. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Bazen PDF'ler, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri (sayfalar veya tablo hücreleri) içerir. Bu durumda, hedef formatların (örneğin, DOCS formatı için MsWord) renderleyicileri bazen arka plan görüntülerinin parçaları arasında görünür sınırlar oluşturur, çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Eğer dışa aktarılan belgede aynı arka plan görüntülerinin parçaları arasında böyle görünür sınırlar varsa, lütfen bu ayarı kullanarak istenmeyen etkiden kurtulmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu nedenle bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

### Örnekler

Aşağıdaki örnek, PDF dosyasını DOC veya DOCX dosyasına dönüştürmeyi göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### Ayrıca Bakınız

* sınıf [UnifiedSaveOptions](../unifiedsaveoptions/)
* arayüz [IPipelineOptions](../ipipelineoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)