---
title: Class XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmlLoadOptions sınıfı. XML dosyasını PDF belgesine yüklemek/içe aktarmak için seçenekleri temsil eder.
type: docs
weight: 11390
url: /tr/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions Sınıfı

XML dosyasını PDF belgesine yüklemek/içe aktarmak için seçenekleri temsil eder.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | XSL verisi olmadan `XmlLoadOptions` nesnesi oluşturur. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | XSL verisi ile `XmlLoadOptions` nesnesi oluşturur. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | XSL verisi ile `XmlLoadOptions` nesnesi oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu yazı tipinin lisansı tarafından yasaklanan yazı tipleriyle işlemleri gerçekleştirmeye izin verir; örneğin, bu yazı tipi için gömme kuralları gömme işlemini devre dışı bırakmış olsa bile bir yazı tipini PDF belgesine gömmeye izin verir. Varsayılan olarak `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı iptal de döndürebilir; bu durumda yükleme işlemi durmalıdır. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | XML'yi PDF belgesine dönüştürmek için XSL verisini alır. |

## Örnekler

Aşağıdaki örnek, XML dosyasını PDF dosyasına dönüştürmeyi göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XML File.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialize XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)