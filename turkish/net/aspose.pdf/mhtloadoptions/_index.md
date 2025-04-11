---
title: Class MhtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MhtLoadOptions sınıfı. .mht dosyasının pdf belgesine yüklenmesi/içeri aktarılması için seçenekleri temsil eder
type: docs
weight: 6970
url: /tr/net/aspose.pdf/mhtloadoptions/
---
## MhtLoadOptions sınıfı

.mht dosyasının pdf belgesine yüklenmesi/içeri aktarılması için seçenekleri temsil eder.

```csharp
public sealed class MhtLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [MhtLoadOptions](mhtloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm fontlar için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemleri gerçekleştirmeye izin verir, örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontu PDF belgesine gömmeye izin verir. Varsayılan `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | Belge sayfa bilgilerini alır veya ayarlar |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam et veya iptal et belirten ReturnAction enum öğesini döndürür. Devam et varsayılan eylemdir ve Yükleme işlemi devam eder, ancak kullanıcı iptal de döndürebilir; bu durumda Yükleme işlemi durmalıdır. |

## Örnekler

Aşağıdaki örnek, MHT dosyasını PDF dosyasına dönüştürmenin nasıl yapılacağını göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MHT File.
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// Initialize MhtLoadOptions	
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MHT File.
    Dim mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf")
 
    ' Initialize MhtLoadOptions
    Dim mhtLoadOptions As MhtLoadOptions = New MhtLoadOptions()
 
    Using pdfDocument As Document = New Document(mhtFile, mhtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```
	
### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)