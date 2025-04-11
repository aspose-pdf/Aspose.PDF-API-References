---
title: Class XpsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XpsLoadOptions sınıfı. XPS dosyasını PDF belgesine yüklemek/içeri aktarmak için seçenekleri temsil eder.
type: docs
weight: 11510
url: /tr/net/aspose.pdf/xpsloadoptions/
---
## XpsLoadOptions sınıfı

XPS dosyasını PDF belgesine yüklemek/içeri aktarmak için seçenekleri temsil eder.

```csharp
public sealed class XpsLoadOptions : LoadOptions, IPipelineOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [XpsLoadOptions](xpsloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpsloadoptions/batchsize/) { get; set; } | Kaynak ve hedef format çiftine toplu dönüşüm uygulanabilir ise toplu boyutunu tanımlar. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakmak için bayrağı alır veya ayarlar. `true` olduğunda, bu yazı tipinin lisansına göre yasaklanan yazı tipi ile işlemleri gerçekleştirmeye izin verir, örneğin, bu yazı tipi için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir yazı tipini PDF belgesine gömmeye izin verir. Varsayılan olarak `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşturulan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam et veya iptal et belirten ReturnAction enum öğesini döndürür. Devam et varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı iptal de döndürebilir, bu durumda yükleme işlemi durmalıdır. |

## Örnekler

Aşağıdaki örnek, XPS dosyasını PDF dosyasına dönüştürmeyi göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XPS File.
	string xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf");

	// Initialize XpsLoadOptions	
	XpsLoadOptions xpsLoadOptions = new XpsLoadOptions();
		
	using (Document pdfDocument = new Document(xpsFile, xpsLoadOptions)){
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XPS File.
    Dim xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf")
 
    ' Initialize XpsLoadOptions
    Dim xpsLoadOptions As XpsLoadOptions = New XpsLoadOptions()
 
    Using pdfDocument As Document = New Document(xpsFile, xpsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* arayüz [IPipelineOptions](../ipipelineoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)