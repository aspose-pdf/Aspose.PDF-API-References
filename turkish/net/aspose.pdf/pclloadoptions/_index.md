---
title: Class PclLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PclLoadOptions sınıfı. PDF belgesine PCL dosyasını yüklemek için seçenekleri temsil eder.
type: docs
weight: 8300
url: /tr/net/aspose.pdf/pclloadoptions/
---
## PclLoadOptions sınıfı

PDF belgesine PCL dosyasını yüklemek için seçenekleri temsil eder.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | Kaynak ve hedef format çiftine toplu dönüşüm uygulanabilir ise toplu boyutunu tanımlar. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm fontlar için lisans kısıtlamalarını devre dışı bırakacak bayrağı alır veya ayarlar. `true` olduğunda, bu fontun lisansının yasakladığı fontlarla işlemler gerçekleştirilmesine izin verir, örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı iptal etmeyi de döndürebilir; bu durumda yükleme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | Dönüşüm için kullanılacak dönüşüm motorunu tanımlar. |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | Dönüşüm hatalarının listesi. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | PCL dönüşüm hatalarının bastırılıp bastırılmayacağını belirten boolean değerini alır veya ayarlar. |

## Örnekler

Aşağıdaki örnek, PCL dosyasını PDF dosyasına nasıl dönüştüreceğinizi gösterir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PCL File.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* arayüz [IPipelineOptions](../ipipelineoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)