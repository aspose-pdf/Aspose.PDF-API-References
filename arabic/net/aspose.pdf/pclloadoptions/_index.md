---
title: Class PclLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.PclLoadOptions. تمثل الخيارات لتحميل ملف PCL إلى مستند PDF
type: docs
weight: 8300
url: /ar/net/aspose.pdf/pclloadoptions/
---
## فئة PclLoadOptions

تمثل الخيارات لتحميل (استيراد) ملف PCL إلى مستند PDF.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | يحدد حجم الدفعة إذا كان التحويل المجمع قابلاً للتطبيق على زوج تنسيقات المصدر والوجهة. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون القيمة `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | يحدد محرك التحويل الذي سيتم استخدامه للتحويل |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | قائمة بأخطاء التحويل. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كانت أخطاء تحويل PCL يجب أن يتم كتمها. |

## أمثلة

يوضح المثال التالي كيفية تحويل ملف PCL إلى ملف PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PCL File.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### انظر أيضًا

* فئة [LoadOptions](../loadoptions/)
* واجهة [IPipelineOptions](../ipipelineoptions/)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)