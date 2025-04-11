---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXLoadOptions class. تمثل الخيارات لتحميل/استيراد ملف TeX إلى مستند PDF
type: docs
weight: 10370
url: /ar/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

تمثل الخيارات لتحميل/استيراد ملف TeX إلى مستند PDF.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | يحصل/يحدد قيمة معينة للبدائيات الزمنية مثل السنة، الشهر، اليوم والوقت. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | يحصل/يحدد دليل إدخال TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | يحصل/يحدد اسم الوظيفة. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | يحصل/يحدد علامة تلغي الربط في جميع الخطوط. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | يحصل/يحدد دليل إخراج TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | يحصل/يحدد علامة تسمح بتحويل المعادلات الرياضية إلى صورة نقطية. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | يحصل/يحدد العلامة التي تشير إلى ما إذا كان من الضروري تشغيل وظيفة TeX مرتين في حالة، على سبيل المثال، وجود مراجع في ملف TeX المدخل. بشكل عام، يكون هذا السلوك مفيدًا عندما يجمع المحرك بعض البيانات أثناء عملية التنضيد ويخزنها في ملف مساعد، كل ذلك في التشغيل الأول. وفي التشغيل الثاني، يستخدم المحرك تلك البيانات بطريقة ما. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | يحصل/يحدد دليل الإدخال المطلوب لـ TeX. الإدخال المطلوب هو الملفات التي يتم تضمينها بطريقة ما في ملف .tex الرئيسي، على سبيل المثال، الحزم التي لا يوجد لها دعم مدمج. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | يحصل/يحدد العلامة التي تشير إلى ما إذا كان يجب عرض مخرجات الطرفية على وحدة التحكم. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | يحصل/يحدد العلامة التي تشير إلى ما إذا كان يجب تقسيم الخطوط في ملف الإخراج أم لا. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُرجع WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

## Methods

| Name | Description |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | يحصل على نتيجة تحميل TeX وتجميعه - هل سارت الأمور بسلاسة أم كانت هناك أي تعليقات/أخطاء. |

## Examples

المثال التالي يوضح كيفية تحويل ملف TeX إلى ملف PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)