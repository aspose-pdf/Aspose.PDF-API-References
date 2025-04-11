---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.PdfToImageOptions. تمثل خيارات ملحق PdfToImage
type: docs
weight: 9130
url: /ar/net/aspose.pdf.plugins/pdftoimageoptions/
---
## فئة PdfToImageOptions

تمثل خيارات ملحق [`PdfToImage`](../pdftoimage/) .

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | يحصل على وضع تحويل الصورة. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | يعيد مجموعة بيانات ملحق [`PdfToImage`](../pdftoimage/) . |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | يعيد اسم العملية. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | يحصل على أو يحدد قيمة دقة الصور الناتجة. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | يحصل على أو يحدد قائمة الصفحات للعملية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات ملحق [`PdfToImage`](../pdftoimage/) . |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | يحدد مصدر بيانات الحفظ الجديد. يمكن أن يكون فقط . إذا كنت تريد حفظ الصور في تدفقات الذاكرة، مرر null كمعامل. |

## أعضاء آخرون

| الاسم | الوصف |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | يحدد أوضاع مختلفة يمكن استخدامها أثناء التحويل من مستند PDF إلى صورة Jpeg. انظر فئة [`JpegOptions`](../jpegoptions/) . |

## ملاحظات

تحتوي فئة PdfImageOptions على وظائف أساسية لإضافة بيانات (ملفات، تدفقات) تمثل مستندات PDF المدخلة.

### انظر أيضًا

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)