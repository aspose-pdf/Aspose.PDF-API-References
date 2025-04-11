---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfProducer sınıfı. Diğer formatlardan PDF üretmek için bir sınıfı temsil eder. Bu örnek, CGM dosyasından Pdf dosyası nasıl üretileceğini gösterir.
type: docs
weight: 4610
url: /tr/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer Sınıfı

Diğer formatlardan PDF üretmek için bir sınıfı temsil eder. Bu örnek, CGM dosyasından Pdf dosyası nasıl üretileceğini gösterir.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Success produced pdf file.
}
catch (InvalidCgmFileFormatException e)
{
    //  Do something...
}
```

```csharp
public abstract class PdfProducer
```

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Belirtilen içe aktarma formatını kullanarak PDF akışını üretir. Bu örnek, CGM akışından Pdf akışı nasıl üretileceğini gösterir. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Belirtilen içe aktarma formatını kullanarak PDF dosyasını üretir. Bu örnek, CGM akışından Pdf dosyası nasıl üretileceğini gösterir. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üretir. Bu örnek, CGM akışından Pdf akışı nasıl üretileceğini gösterir. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üretir. Bu örnek, CGM akışından Pdf dosyası nasıl üretileceğini gösterir. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Belirtilen içe aktarma formatını kullanarak PDF akışını üretir. Bu örnek, CGM dosyasından Pdf akışı nasıl üretileceğini gösterir. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Belirtilen içe aktarma formatını kullanarak PDF dosyasını üretir. Bu örnek, CGM dosyasından Pdf dosyası nasıl üretileceğini gösterir. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Belirtilen içe aktarma seçeneğini kullanarak PDF akışını üretir. Bu örnek, CGM dosyasından Pdf akışı nasıl üretileceğini gösterir. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üretir. Bu örnek, CGM dosyasından Pdf dosyası nasıl üretileceğini gösterir. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)