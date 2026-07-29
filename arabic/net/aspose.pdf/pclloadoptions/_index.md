---
title: "الفئة PclLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.PclLoadOptions. تمثل خيارات تحميل ملف PCL إلى مستند PDF"
type: docs
weight: 8440
url: /ar/net/aspose.pdf/pclloadoptions/
---
## PclLoadOptions class

يمثل خيارات تحميل (استيراد) ملف PCL إلى مستند PDF.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | يحدد محرك التحويل الذي سيُستخدم في التحويل |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | قائمة بأخطاء التحويل. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كان يجب قمع أخطاء تحويل PCL. |

## أمثلة

يوضح المثال التالي كيفية تحويل ملف PCL إلى ملف PDF

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// المسار إلى ملف PCL الخاص بك.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// المسار إلى ملف PDF الناتج.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// حفظ ملف PDF
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

* class [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


