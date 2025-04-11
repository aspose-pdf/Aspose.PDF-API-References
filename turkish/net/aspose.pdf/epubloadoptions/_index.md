---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubLoadOptions sınıfı. EPUB dosyasını pdf belgesine yüklemek/içeri aktarmak için seçenekler içerir
type: docs
weight: 4050
url: /tr/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions sınıfı

EPUB dosyasını pdf belgesine yüklemek/içeri aktarmak için seçenekler içerir.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | EPUB dosyasını pdf belgesine dönüştürmek için varsayılan yükleme seçeneklerini oluşturur. Varsayılan pdf sayfa boyutu - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Belirtilen sayfa boyutu ile yükleme seçenekleri oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Epub belgesi açıldığında uygulanacak özel Css'yi alır veya ayarlar. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosya yüklenirken tüm fontlar için lisans kısıtlamalarını devre dışı bırakacak bayrağı alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemleri gerçekleştirmeye izin verir, örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontu PDF belgesine gömmeye izin verir. Varsayılan `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Margin bilgilerini temsil eden nesneye referans alır. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | İçe aktarma için çıktı sayfa boyutunu alır veya ayarlar. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya durdurma belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve Yükleme işlemi devam eder, ancak kullanıcı durdurmayı da döndürebilir, bu durumda Yükleme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Margin alanının kullanım modunu temsil eder - içe aktarılan belgenin CSS'sinin margin kullanımı ile ilgili talimatlarının (varsa) işlenmesini tanımlar. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | DİKKAT! Özellik uygulanmıştır ancak örnek belgede ortaya çıkan OSHARED katmanındaki engelleyici sorun nedeniyle henüz genel API'ye eklenmemiştir. Dönüşüm sırasında sayfa boyutunun kullanım modunu temsil eder. Formatlar (HTML, EPUB vb. gibi), genellikle akışkan tasarıma sahiptir, bu nedenle gerekli sayfa boyutuna uyum sağlamaya izin verir. Ancak bazen içerik, gerekli sayfa boyutuna yerleştirilmesine izin vermeyen belirli yatay konumlar veya boyutlar içerir. Bu durumda, bu durumda ne yapılması gerektiğini tanımlayabiliriz (yani, içeriğin boyutu, sonuç PDF belgesinin gerekli başlangıç sayfa boyutuna uymadığında). |

## Örnekler

Aşağıdaki örnek, EPUB dosyasını PDF dosyasına dönüştürmenin nasıl yapılacağını göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)