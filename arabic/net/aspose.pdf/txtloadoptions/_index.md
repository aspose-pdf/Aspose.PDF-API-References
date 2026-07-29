---
title: "الفئة TxtLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.TxtLoadOptions. خيارات التحميل لتحويل TXT إلى PDF."
type: docs
weight: 11320
url: /ar/net/aspose.pdf/txtloadoptions/
---
## TxtLoadOptions class

خيارات التحميل لتحويل TXT إلى PDF.

```csharp
public class TxtLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TxtLoadOptions](txtloadoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف TXT إلى ملف PDF.

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// المسار إلى ملف TXT الخاص بك.
	string txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt");

	// المسار إلى ملف PDF الناتج.
	string pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf");

	// تهيئة TxtLoadOptions	
	TxtLoadOptions txtLoadOptions = new TxtLoadOptions();
		
	using (Document pdfDocument = new Document(txtFile, txtLoadOptions))
	{
	 
		// حفظ ملف PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TXT File.
    Dim txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf")
 
    ' Initialize TxtLoadOptions
    Dim txtLoadOptions As TxtLoadOptions = New TxtLoadOptions()
 
    Using pdfDocument As Document = New Document(txtFile, txtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


