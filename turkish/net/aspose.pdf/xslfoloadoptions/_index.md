---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptions sınıfı. PDF belgesine XSLFO dosyasını yüklemek/içeri aktarmak için seçenekleri temsil eder.
type: docs
weight: 11530
url: /tr/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions sınıfı

PDF belgesine XSL-FO dosyasını yüklemek/içeri aktarmak için seçenekleri temsil eder.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Xsl verisi olmadan `XslFoLoadOptions` nesnesi oluşturur. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Xsl verisi ile `XslFoLoadOptions` nesnesi oluşturur. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Xsl verisi ile `XslFoLoadOptions` nesnesi oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Yüklenen SVG dosyasında referans verilen dış kaynaklara (varsa) göre göreceli yolların arandığı temel yol/url. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosyayı yüklerken tüm fontlar için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemler gerçekleştirilmesine izin verir; örneğin, bu font için gömme kuralları devre dışı bırakılmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya durdurma belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve Yükleme işlemi devam eder, ancak kullanıcı durdurmayı da döndürebilir; bu durumda Yükleme işlemi durmalıdır. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | XML'i PDF belgesine dönüştürmek için xsl verisini alır. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | Mevcut xls parametrelerine değer eklemek için XsltArgumentList. XLS dosyasında değeri olmayan 'animal' parametresi var: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); şimdi dönüştürücü, XLS dosyasında 'cat' değerine sahip bir 'animal' parametresi olduğunu varsayıyor. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu hataların işlenmesi için olası stratejileri sıralar. |

## Örnekler

Aşağıdaki örnek, XSL-FO dosyasını PDF dosyasına dönüştürmenin nasıl yapılacağını gösterir.

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [XmlLoadOptions](../xmlloadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)