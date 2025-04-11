---
title: Class MdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MdLoadOptions sınıfı. Markdown formatı dönüşümü için yükleme seçenekleri
type: docs
weight: 6940
url: /tr/net/aspose.pdf/mdloadoptions/
---
## MdLoadOptions sınıfı

Markdown formatı dönüşümü için yükleme seçenekleri.

```csharp
public class MdLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [MdLoadOptions](mdloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm fontlar için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemler gerçekleştirilmesine izin verir, örneğin, bu font için gömme kuralları devre dışı bırakılmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan `false`. |
| [IsPriorityCssPageRule](../../aspose.pdf/mdloadoptions/isprioritycsspagerule/) { get; set; } | css'de tanımlanan @page kurallarının PageInfo'da tanımlanan değerleri geçersiz kılacağını belirten bayrağı alır veya ayarlar. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [PageInfo](../../aspose.pdf/mdloadoptions/pageinfo/) { get; set; } | Belge sayfa bilgilerini alır veya ayarlar |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam et veya iptal et belirten ReturnAction enum öğesini döndürür. Devam et varsayılan eylemdir ve Yükleme işlemi devam eder, ancak kullanıcı iptal de döndürebilir, bu durumda Yükleme işlemi durmalıdır. |

## Örnekler

Aşağıdaki örnek, MD dosyasını PDF dosyasına dönüştürmenin nasıl yapılacağını göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MD File.
	string mdFile = Path.Combine(dataDir, "MD-to-PDF.md");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf");

	// Initialize MdLoadOptions	
	MdLoadOptions mdLoadOptions = new MdLoadOptions();
		
	using (Document pdfDocument = new Document(mdFile, mdLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MD File.
    Dim mdFile = Path.Combine(dataDir, "MD-to-PDF.md")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf")
 
    ' Initialize MdLoadOptions  
    Dim mdLoadOptions As MdLoadOptions = New MdLoadOptions()
 
    Using pdfDocument As Document = New Document(mdFile, mdLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)