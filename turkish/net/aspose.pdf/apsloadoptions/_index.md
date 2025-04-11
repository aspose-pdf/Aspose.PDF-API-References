---
title: Class ApsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ApsLoadOptions sınıfı. Sınıf, aps yükleme seçeneklerini tanımlar.
type: docs
weight: 2750
url: /tr/net/aspose.pdf/apsloadoptions/
---
## ApsLoadOptions sınıfı

Sınıf, aps yükleme seçeneklerini tanımlar.

```csharp
public class ApsLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ApsLoadOptions](apsloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu yazı tipinin lisansı tarafından yasaklanan yazı tipi ile işlemleri gerçekleştirmeye izin verir; örneğin, bu yazı tipi için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir yazı tipini PDF belgesine gömmeye izin verir. Varsayılan `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya durdurma belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve Yükleme işlemi devam eder, ancak kullanıcı durdurmayı da döndürebilir; bu durumda Yükleme işlemi durmalıdır. |

## Örnekler

Aşağıdaki örnek, APS dosyasını PDF dosyasına dönüştürmenin nasıl yapılacağını göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your APS File.
	string apsFile = Path.Combine(dataDir, "APS-to-PDF.aps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf");

	// Initialize ApsLoadOptions  	
	ApsLoadOptions apsLoadOptions = new ApsLoadOptions();

	// Initialize Document wiht ApsLoadOptions     
	using (Document pdfDocument = new Document(apsFile, apsLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your APS File.
    Dim apsFile = Path.Combine(dataDir, "APS-to-PDF.aps")
	
    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf")
 
    ' Initialize ApsLoadOptions    
    Dim apsLoadOptions As ApsLoadOptions = New ApsLoadOptions()
 
	' Initialize Document wiht ApsLoadOptions
    Using pdfDocument As Document = New Document(apsFile, apsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)