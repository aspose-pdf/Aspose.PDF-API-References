---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfProducer 클래스. 다른 형식에서 PDF를 생성하는 클래스를 나타냅니다. 이 샘플은 CGM 파일에서 PDF 파일을 생성하는 방법을 보여줍니다.
type: docs
weight: 4610
url: /ko/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

다른 형식에서 PDF를 생성하는 클래스를 나타냅니다. 이 샘플은 CGM 파일에서 PDF 파일을 생성하는 방법을 보여줍니다.

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

## Methods

| Name | Description |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | 지정된 가져오기 형식을 사용하여 PDF 스트림을 생성합니다. 이 샘플은 CGM 스트림에서 PDF 스트림을 생성하는 방법을 보여줍니다. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | 지정된 가져오기 형식을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 스트림에서 PDF 파일을 생성하는 방법을 보여줍니다. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | 지정된 가져오기 옵션을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 스트림에서 PDF 스트림을 생성하는 방법을 보여줍니다. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | 지정된 가져오기 옵션을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 스트림에서 PDF 파일을 생성하는 방법을 보여줍니다. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | 지정된 가져오기 형식을 사용하여 PDF 스트림을 생성합니다. 이 샘플은 CGM 파일에서 PDF 스트림을 생성하는 방법을 보여줍니다. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | 지정된 가져오기 형식을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 파일에서 PDF 파일을 생성하는 방법을 보여줍니다. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | 지정된 가져오기 옵션을 사용하여 PDF 스트림을 생성합니다. 이 샘플은 CGM 파일에서 PDF 스트림을 생성하는 방법을 보여줍니다. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | 지정된 가져오기 옵션을 사용하여 PDF 파일을 생성합니다. 이 샘플은 CGM 파일에서 PDF 파일을 생성하는 방법을 보여줍니다. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)