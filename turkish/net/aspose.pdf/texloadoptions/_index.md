---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXLoadOptions sınıfı. PDF belgesine TeX dosyasını yüklemek/içe aktarmak için seçenekleri temsil eder.
type: docs
weight: 10370
url: /tr/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions sınıfı

PDF belgesine TeX dosyasını yüklemek/içe aktarmak için seçenekleri temsil eder.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Yıl, ay, gün ve zaman gibi tarih/saat primitifleri için belirli bir değeri alır/ayarlar. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm fontlar için lisans kısıtlamalarını devre dışı bırakma bayrağını alır/ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemler gerçekleştirilmesine izin verir, örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | TeX girdi dizinini alır/ayarlar. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | İşin adını alır/ayarlar. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Tüm fontlardaki ligatürleri iptal eden bir bayrağı alır/ayarlar. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | TeX çıktı dizinini alır/ayarlar. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Matematik formüllerini rasterleştirmeye izin veren bir bayrağı alır/ayarlar. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Girdi TeX dosyasında referanslar varsa, TeX işinin iki kez çalıştırılması gerekip gerekmediğini belirten bayrağı alır/ayarlar. Genel olarak, bu davranış, motorun tür düzenleme süreci boyunca bazı verileri topladığı ve bunları yardımcı bir dosyada depoladığı durumlarda faydalıdır, tüm bunlar ilk çalıştırmada gerçekleşir. İkinci çalıştırmada, motor bir şekilde bu verileri kullanır. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | TeX'in gerekli girdi dizinini alır/ayarlar. Gerekli girdi, ana .tex dosyasına bir şekilde dahil edilen dosyalardır, örneğin, yerleşik desteği olmayan paketler. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Konsolda terminal çıktısını gösterip göstermeyeceğini belirten bayrağı alır/ayarlar. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Çıktı dosyasında fontları alt küme yapıp yapmamayı belirten bayrağı alır/ayarlar. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı iptal etme döndürebilir, bu durumda yükleme işlemi durmalıdır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | TeX yükleme ve derleme sonucu alır - her şey sorunsuz mu gitti yoksa herhangi bir yorum/hata mı vardı. |

## Örnekler

Aşağıdaki örnek, TeX dosyasını PDF dosyasına dönüştürmenin nasıl yapılacağını göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)