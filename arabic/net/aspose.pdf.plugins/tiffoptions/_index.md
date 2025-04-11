---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.TiffOptions. تمثل خيارات تحويل Pdf إلى Tiff لملحق Tiff
type: docs
weight: 9420
url: /ar/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

تمثل خيارات تحويل Pdf إلى Tiff لملحق [`Tiff`](../tiff/) .

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | يحصل أو يحدد قيمة حدود تحويل الألوان إلى الأبيض والأسود. يمكن تطبيق هذا المعامل مع EncoderValue.CompressionCCITT4، EncoderValue.CompressionCCITT3، EncoderValue.CompressionRle أو ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | يحصل أو يحدد نوع الضغط. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | يحصل على وضع تحويل الصورة. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | يحصل أو يحدد نوع إحداثيات الصفحة (Media/Crop boxes). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | يحصل أو يحدد عمق اللون. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | يعيد مجموعة بيانات ملحق [`PdfToImage`](../pdftoimage/) . |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | يعيد اسم العملية. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | يحصل أو يحدد قيمة دقة الصور الناتجة. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | يحصل أو يحدد قائمة الصفحات للعملية. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | يحصل ويحدد علامة تسمح بحفظ جميع الصفحات في ملف tiff متعدد الصفحات. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | يحصل أو يحدد نوع الشكل. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كان يجب تخطي الصفحات الفارغة. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات ملحق [`PdfToImage`](../pdftoimage/) . |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | يحدد مصدر بيانات الحفظ الجديد. يمكن أن يكون فقط . إذا كنت ترغب في حفظ الصور في تدفقات الذاكرة، مرر null كمعامل. |

### See Also

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)