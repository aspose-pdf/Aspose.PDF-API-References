---
title: "الفئة PdfToImageOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Plugins.PdfToImageOptions class. يمثل الخيارات لملحق PdfToImage"
type: docs
weight: 9280
url: /ar/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

يمثل الخيارات لملحق [`PdfToImage`](../pdftoimage/) plugin.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | يحصل على وضع تحويل الصورة. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | يعيد مجموعة بيانات الملحق [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | يرجع اسم العملية. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | يحصل أو يعيّن قيمة الدقة للصور الناتجة. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | يحصل أو يعيّن قائمة الصفحات للعملية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات الملحق [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | يعيّن مصدر حفظ بيانات جديد. لا يمكن أن يكون إلا . إذا كنت تريد حفظ الصور في تدفقات الذاكرة، مرّر null كمعامل. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | يحدد أوضاعًا مختلفة يمكن استخدامها أثناء التحويل من مستند PDF إلى صورة Jpeg. راجع فئة [`JpegOptions`](../jpegoptions/). |

## ملاحظات

الفئة PdfImageOptions تحتوي على وظائف أساسية لإضافة البيانات (ملفات، تدفقات) التي تمثل مستندات PDF المدخلة.

### انظر أيضًا

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


