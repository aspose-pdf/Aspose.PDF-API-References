---
title: "الفئة ApsLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.ApsLoadOptions. الفئة تصف خيارات تحميل aps"
type: docs
weight: 2850
url: /ar/net/aspose.pdf/apsloadoptions/
---
## ApsLoadOptions class

الفئة تصف خيارات تحميل aps.

```csharp
public class ApsLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ApsLoadOptions](apsloadoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف APS إلى ملف PDF

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// المسار إلى ملف APS الخاص بك.
	string apsFile = Path.Combine(dataDir, "APS-to-PDF.aps");

	// المسار إلى ملف PDF الناتج.
	string pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf");

	// تهيئة ApsLoadOptions 	
	ApsLoadOptions apsLoadOptions = new ApsLoadOptions();

	// تهيئة المستند باستخدام ApsLoadOptions     
	using (Document pdfDocument = new Document(apsFile, apsLoadOptions))
	{
	 
		// حفظ ملف PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your APS File.
    Dim apsFile = Path.Combine(dataDir, "APS-to-PDF.aps")
	
    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf")
 
    ' Initialize ApsLoadOptions    
    Dim apsLoadOptions As ApsLoadOptions = New ApsLoadOptions()
 
	' Initialize Document wiht ApsLoadOptions
    Using pdfDocument As Document = New Document(apsFile, apsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


