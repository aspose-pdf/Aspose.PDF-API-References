---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfProducer. تمثل فئة لإنتاج PDF من تنسيقات أخرى. يوضح هذا المثال كيفية إنتاج ملف Pdf من ملف CGM
type: docs
weight: 4610
url: /ar/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

تمثل فئة لإنتاج PDF من تنسيقات أخرى. يوضح هذا المثال كيفية إنتاج ملف Pdf من ملف CGM.

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
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | إنتاج تدفق PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج تدفق Pdf من تدفق CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | إنتاج ملف PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج ملف Pdf من تدفق CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | إنتاج ملف PDF باستخدام خيار الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج تدفق Pdf من تدفق CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | إنتاج ملف PDF باستخدام خيار الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج ملف Pdf من تدفق CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | إنتاج تدفق PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج تدفق Pdf من ملف CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | إنتاج ملف PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج ملف Pdf من ملف CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | إنتاج تدفق PDF باستخدام خيار الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج تدفق Pdf من ملف CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | إنتاج ملف PDF باستخدام خيار الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج ملف Pdf من ملف CGM. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)