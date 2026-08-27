---
title: "فئة TiffOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Plugins.TiffOptions. يمثل خيارات تحويل Pdf إلى Tiff للملحق Tiff."
type: docs
weight: 9570
url: /ar/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

يمثل خيارات تحويل Pdf إلى Tiff للملحق [`Tiff`](../tiff/).

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffOptions](tiffoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | احصل أو عيّن حد قيمة لتحويل الألوان بين الأبيض والأسود. يمكن تطبيق هذا المعامل مع EncoderValue.CompressionCCITT4، EncoderValue.CompressionCCITT3، EncoderValue.CompressionRle أو ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | احصل أو عيّن نوع الضغط. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | يحصل على وضع تحويل الصورة. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | احصل أو عيّن نوع إحداثيات الصفحة (صناديق Media/Crop). تُستخدم قيمة CropBox افتراضيًا. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | احصل أو عيّن عمق اللون. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | يعيد مجموعة بيانات الملحق [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | يرجع اسم العملية. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | يحصل أو يعيّن قيمة الدقة للصور الناتجة. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | يحصل أو يعيّن قائمة الصفحات للعملية. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | احصل وعين العلامة التي تسمح بحفظ جميع الصفحات في ملف tiff متعدد الصفحات. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | احصل أو عيّن نوع الشكل. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | احصل أو عيّن قيمة تشير إلى ما إذا كان يجب تخطي الصفحات الفارغة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات الملحق [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | يعيّن مصدر حفظ بيانات جديد. لا يمكن أن يكون إلا . إذا كنت تريد حفظ الصور في تدفقات الذاكرة، مرّر null كمعامل. |

### انظر أيضًا

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


