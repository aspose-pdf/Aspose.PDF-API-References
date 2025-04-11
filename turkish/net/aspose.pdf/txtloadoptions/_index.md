---
title: Class TxtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TxtLoadOptions sınıfı. TXT'den PDF'ye dönüştürme için yükleme seçenekleri
type: docs
weight: 11130
url: /tr/net/aspose.pdf/txtloadoptions/
---
## TxtLoadOptions sınıfı

TXT'den PDF'ye dönüştürme için yükleme seçenekleri.

```csharp
public class TxtLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TxtLoadOptions](txtloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm fontlar için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemler gerçekleştirilmesine izin verir; örneğin, bu font için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan olarak `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya durdurma belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı durdurmayı da döndürebilir; bu durumda yükleme işlemi durmalıdır. |

## Örnekler

Aşağıdaki örnek, TXT dosyasını PDF dosyasına dönüştürmenin nasıl yapılacağını göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TXT File.
	string txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf");

	// Initialize TxtLoadOptions	
	TxtLoadOptions txtLoadOptions = new TxtLoadOptions();
		
	using (Document pdfDocument = new Document(txtFile, txtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TXT File.
    Dim txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf")
 
    ' Initialize TxtLoadOptions
    Dim txtLoadOptions As TxtLoadOptions = New TxtLoadOptions()
 
    Using pdfDocument As Document = New Document(txtFile, txtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)