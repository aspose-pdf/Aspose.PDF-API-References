---
title: Class XmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmlSaveOptions sınıfı. Xml formatına dışa aktarma için kaydetme seçenekleri
type: docs
weight: 11400
url: /tr/net/aspose.pdf/xmlsaveoptions/
---
## XmlSaveOptions sınıfı

Xml formatına dışa aktarma için kaydetme seçenekleri

```csharp
public class XmlSaveOptions : SaveOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [XmlSaveOptions](xmlsaveoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps sayfaları hazırlanırken yazı tipi gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesinin performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belge yanıt olarak kaydedildikten sonra Yanıt nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Verilerin kaydedileceği format. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve Kaydetme işlemi devam eder, ancak kullanıcı iptal etme döndürebilir; bu durumda Kaydetme işlemi durmalıdır. |

## Örnekler

Aşağıdaki örnek, PDF dosyasını XML dosyasına dönüştürmeyi göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf");

	// The path to output XML File.
	var xmlFile= Path.Combine(dataDir, "PDF-to-XML.xml");
		
	using (Document pdfDocument = new Document(pdfFile)){
		// Initialize XmlSaveOptions	
		XmlSaveOptions saveOptions = new XmlSaveOptions();
		
		// Save XML file
		pdfDocument.Save(xmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf")

    ' The path to output XML File.
    Dim xmlFile = Path.Combine(dataDir, "PDF-to-XML.xml")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XmlSaveOptions
        Dim saveOptions As XmlSaveOptions = New XmlSaveOptions()
 
        ' Save XML file
        pdfDocument.Save(xmlFile, saveOptions)
    End Using
```

### Ayrıca Bakınız

* sınıf [SaveOptions](../saveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)