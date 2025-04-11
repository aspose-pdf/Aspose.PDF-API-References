---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlLoadOptions sınıfı. HTML dosyasını PDF belgesine yüklemek/içeri aktarmak için seçenekleri temsil eder.
type: docs
weight: 5530
url: /tr/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions Sınıfı

HTML dosyasını PDF belgesine yüklemek/içeri aktarmak için seçenekleri temsil eder.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Boş bir temel yol ile HTML'yi PDF belgesine dönüştürmek için yükleme seçenekleri oluşturur. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Tanımlı bir temel yol ile HTML'yi PDF belgesine dönüştürmek için yükleme seçenekleri oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | HTML dosyası için temel yol/url. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Dosya yüklenirken tüm fontlar için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. `true` olduğunda, bu fontun lisansı tarafından yasaklanan fontlarla işlemleri gerçekleştirmeye izin verir, örneğin, bu font için gömme kuralları devre dışı bırakılmış olsa bile bir fontun PDF belgesine gömülmesine izin verir. Varsayılan olarak `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | İşleme sırasında kullanılan olası medya türlerini alır veya ayarlar. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Bu belgenin ayrıştırma sırasında kullanılan kodlamayı belirten niteliği alır veya ayarlar. Bu nitelik null ise, kodlama belge karakter seti niteliğinden belirlenecektir. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Sonuç belgesine font gömme durumunu alır veya ayarlar. |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | CSS'de tanımlanan @page kurallarının PageInfo'da tanımlanan değerleri geçersiz kılacağını belirten bayrağı alır veya ayarlar. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Tüm belgeyi tek bir sayfaya render etme durumunu alır veya ayarlar. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) tarafından tanımlanan dosya formatını temsil eder. |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Belge sayfa bilgilerini alır veya ayarlar. |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Düzen seçeneğini alır veya ayarlar. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Oluşan uyarıları işlemek için geri çağırma. WarningHandler, devam et veya iptal et belirten ReturnAction enum öğesini döndürür. Devam et varsayılan eylemdir ve yükleme işlemi devam eder, ancak kullanıcı iptal de döndürebilir; bu durumda yükleme işlemi durmalıdır. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Bazen dış kaynakların (gibi resimler veya CSS'ler) dahili yükleyicisinin kullanımını önlemek ve istenen kaynakları bir yerden almak için özel bir yöntem sağlamak gerekir. Örneğin, Aspose.PDF'nin bulutta kullanımı sırasında referans verilen dosyalara doğrudan erişim mümkün değildir: bu durumda, özel bir kodun özel bir yönteme yerleştirilmesi ve bu niteliğe atanacak bir delege ile referans verilmesi gerekir. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | HTML'de referans verilen dış verilerin yüklenmesi kimlik bilgileri gerektiriyorsa, bunları bu parametreye koyabilirsiniz - dış kaynakların yüklenmesi sırasında kullanılacaktır. |

## Örnekler

Aşağıdaki örnek, HTML dosyasını PDF dosyasına dönüştürmeyi göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)