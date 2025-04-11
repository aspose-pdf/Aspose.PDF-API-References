---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfProducer 类。表示一个从其他格式生成 PDF 的类。此示例展示了如何从 CGM 文件生成 Pdf 文件
type: docs
weight: 4610
url: /zh/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

表示一个从其他格式生成 PDF 的类。此示例展示了如何从 CGM 文件生成 Pdf 文件。

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
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | 使用指定的导入格式生成 PDF 流。此示例展示了如何从 CGM 流生成 Pdf 流。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | 使用指定的导入格式生成 PDF 文件。此示例展示了如何从 CGM 流生成 Pdf 文件。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | 使用指定的导入选项生成 PDF 文件。此示例展示了如何从 CGM 流生成 Pdf 流。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | 使用指定的导入选项生成 PDF 文件。此示例展示了如何从 CGM 流生成 Pdf 文件。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | 使用指定的导入格式生成 PDF 流。此示例展示了如何从 CGM 文件生成 Pdf 流。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | 使用指定的导入格式生成 PDF 文件。此示例展示了如何从 CGM 文件生成 Pdf 文件。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | 使用指定的导入选项生成 PDF 流。此示例展示了如何从 CGM 文件生成 Pdf 流。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | 使用指定的导入选项生成 PDF 文件。此示例展示了如何从 CGM 文件生成 Pdf 文件。 |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)