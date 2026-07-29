---
title: "الفئة TeXLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.TeXLoadOptions. تمثل الخيارات لتحميل/استيراد ملف TeX إلى مستند PDF"
type: docs
weight: 10550
url: /ar/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

يمثل خيارات تحميل/استيراد ملف TeX إلى مستند PDF.

```csharp
public class TeXLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | يحصل/يضبط قيمة معينة للأنواع الأولية للتاريخ/الوقت مثل السنة والشهر واليوم والوقت. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | يحصل/يضبط دليل إدخال TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | يحصل/يضبط اسم المهمة. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | يحصل/يضبط علمًا يلغي الروابط في جميع الخطوط. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | يحصل/يضبط دليل إخراج TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | يحصل/يضبط علمًا يسمح بتحويل صيغ الرياضيات إلى نقطية. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | يحصل/يضبط العلم الذي يحدد ما إذا كان من الضروري تشغيل مهمة TeX مرتين في حالة وجود مراجع في ملفات TeX المدخلة، على سبيل المثال. بشكل عام، يكون هذا السلوك مفيدًا عندما يجمع المحرك بعض البيانات أثناء عملية التنضيد ويخزنها في ملف مساعد خلال التشغيل الأول. وفي التشغيل الثاني، يستخدم المحرك تلك البيانات بطريقة ما. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | يحصل/يضبط دليل الإدخال المطلوب لـ TeX. الإدخال المطلوب هو الملفات التي تُضمّن بطريقة ما في ملف .tex الرئيسي، مثل الحزم التي لا يوجد لها دعم مدمج. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | يحصل/يضبط العلم الذي يحدد ما إذا كان يجب عرض مخرجات الطرفية على وحدة التحكم. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | يحصل/يضبط العلم الذي يحدد ما إذا كان سيتم تقليل مجموعة الخطوط في ملف الإخراج أم لا. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | يحصل على النتيجة لتحميل TeX وتكوينه - هل سارت الأمور بسلاسة أم كان هناك أي تعليقات/أخطاء. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف TeX إلى ملف PDF

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// المسار إلى ملف TeX الخاص بك.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// المسار إلى ملف PDF الناتج.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// تهيئة TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// حفظ ملف PDF
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

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


