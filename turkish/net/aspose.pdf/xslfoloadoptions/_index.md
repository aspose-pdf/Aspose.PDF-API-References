---
title: XslFoLoadOptions
second_title: Aspose.PDF for .NET API Referansı
description: XSL-FO dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini temsil eder.
type: docs
weight: 7580
url: /tr/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

XSL-FO dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini temsil eder.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions#constructor)() | Oluşturur[`XslFoLoadOptions`](../xslfoloadoptions) xsl verisi olmayan nesne. |
| [XslFoLoadOptions](xslfoloadoptions#constructor_1)(Stream) | Oluşturur[`XslFoLoadOptions`](../xslfoloadoptions) xsl verili nesne. |
| [XslFoLoadOptions](xslfoloadoptions#constructor_2)(string) | Oluşturur[`XslFoLoadOptions`](../xslfoloadoptions) xsl verili nesne. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath) { get; set; } | Yüklenen SVG dosyasında başvurulan harici kaynaklara (varsa) göreli yolların arandığı temel yol/url. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat) { get; } | Hangi dosya biçimini temsil eder?[`LoadOptions`](../loadoptions) tanımlar. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler) { get; set; } | Oluşturulan uyarıları işlemek için geri arama. WarningHandler, Continue veya Abort'u belirten ReturnAction numaralandırma öğesini döndürür. Devam, varsayılan eylemdir ve Yükleme işlemi devam eder, ancak kullanıcı ayrıca Durdur'a da dönebilir, bu durumda Yükleme işlemi sona ermelidir. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream) { get; } | xml'yi pdf belgesine dönüştürmek için xsl verilerini alır. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist) { get; set; } | Var olan xls parametrelerine değer eklemek için XsltArgumentList  XLS dosyası, değeri olmayan 'animal' parametresine sahip: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); artık bir dönüştürücü olduğunu varsayar ' parametre XLS dosyasında 'cat' değerine sahip. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype) | Kaynak XSLFO belgesi, biçimlendirme hataları içerebilir. Bu numaralandırma, bu hataların olası dağıtım stratejilerini sıralar |

### Ayrıca bakınız

* class [XmlLoadOptions](../xmlloadoptions)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->