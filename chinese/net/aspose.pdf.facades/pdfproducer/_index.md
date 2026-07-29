---
title: "类 PdfProducer"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfProducer 类。表示一个用于从其他格式生成 PDF 的类。此示例展示如何从 CGM 文件生成 Pdf 文件。"
type: docs
weight: 4730
url: /zh/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

表示一个用于从其他格式生成 PDF 的类。此示例展示了如何从 CGM 文件生成 Pdf 文件。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // 成功生成 pdf 文件。
}
catch (InvalidCgmFileFormatException e)
{
    //  执行某些操作...
}
```

```csharp
public abstract class PdfProducer
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | 使用指定的导入格式生成 PDF 流。此示例展示如何从 CGM 流生成 Pdf 流。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | 使用指定的导入格式生成 PDF 文件。此示例展示如何从 CGM 流生成 Pdf 文件。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | 使用指定的导入选项生成 PDF 文件。此示例展示如何从 CGM 流生成 Pdf 流。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | 使用指定的导入选项生成 PDF 文件。此示例展示如何从 CGM 流生成 Pdf 文件。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | 使用指定的导入格式生成 PDF 流。此示例展示如何从 CGM 文件生成 Pdf 流。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | 使用指定的导入格式生成 PDF 文件。此示例展示如何从 CGM 文件生成 Pdf 文件。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | 使用指定的导入选项生成 PDF 流。此示例展示如何从 CGM 文件生成 Pdf 流。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | 使用指定的导入选项生成 PDF 文件。此示例展示了如何从 CGM 文件生成 Pdf 文件。 |

### 另请参见

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


