---
title: "الفئة XlsConverter"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.XlsConverter. تمثل ملحق XlsConverter"
type: docs
weight: 9600
url: /ar/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

تمثل ملحق `XlsConverter`.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XlsConverter](xlsconverter/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | تنفيذ IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | يبدأ معالجة PdfToExcel بالمعلمات المحددة. |

## أمثلة

يوضح المثال كيفية تحويل PDF إلى مستند XLSX.

```csharp
// إنشاء محول XlsConverter
var converter = new XlsConverter();
// إنشاء PdfToXLSOptions
var opt = new PdfToXLSOptions();
// إضافة مسار ملف الإدخال
opt.AddInput(new FileDataSource(inputPath));
// تعيين مسار ملف الإخراج
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### انظر أيضًا

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


