---
title: Class MhtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.MhtLoadOptions. تمثل الخيارات لتحميل/استيراد ملف .mht إلى مستند PDF
type: docs
weight: 6970
url: /ar/net/aspose.pdf/mhtloadoptions/
---
## MhtLoadOptions class

تمثل الخيارات لتحميل/استيراد ملف .mht إلى مستند PDF.

```csharp
public sealed class MhtLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MhtLoadOptions](mhtloadoptions/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون القيمة `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تمنع الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | يحصل أو يحدد معلومات صفحة المستند |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد الاتصال لمعالجة أي تحذيرات تم إنشاؤها. يُرجع WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

## Examples

يوضح المثال التالي كيفية تحويل ملف MHT إلى ملف PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MHT File.
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// Initialize MhtLoadOptions	
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MHT File.
    Dim mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf")
 
    ' Initialize MhtLoadOptions
    Dim mhtLoadOptions As MhtLoadOptions = New MhtLoadOptions()
 
    Using pdfDocument As Document = New Document(mhtFile, mhtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```
	
### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)