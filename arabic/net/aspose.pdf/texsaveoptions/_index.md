---
title: "الفئة TeXSaveOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.TeXSaveOptions. خيارات الحفظ لتصدير إلى تنسيق TeX"
type: docs
weight: 10580
url: /ar/net/aspose.pdf/texsaveoptions/
---
## TeXSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق TeX

```csharp
public class TeXSaveOptions : UnifiedSaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TeXSaveOptions](texsaveoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم إغلاق كائن Response بعد حفظ المستند في الاستجابة. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذا السمة تفعّل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [OutDirectoryPath](../../aspose.pdf/texsaveoptions/outdirectorypath/) { get; set; } | خاصية للمعامل _outDirectoryPath. |
| [PagesCount](../../aspose.pdf/texsaveoptions/pagescount/) { get; } | يعيد عدد الصفحات بعد التحويل. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | استدعاء رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddFontEncs](../../aspose.pdf/texsaveoptions/addfontencs/)(params string[]) | يضيف ترميز خط إلى قائمة ترميزات الخط |
| [ClearFontEncs](../../aspose.pdf/texsaveoptions/clearfontencs/)() | يمسح قائمة ترميزات الخط |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية مكررة موضوعة بجانب بعضها. في هذه الحالة قد يولد مُعالج صيغ الهدف (مثل MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنياته في تنعيم حواف الصورة (مضاد التعرج) عن Acrobat Reader. إذا بدا أن المستند المُصدّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب. انتباه! عادةً ما تُبطئ هذه تحسين الجودة عملية التحويل بشكل ملحوظ، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف PDF إلى ملف TeX

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf");

	// المسار إلى ملف TeX الناتج.
	var texFile= Path.Combine(dataDir, "PDF-to-TeX.tex");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// تهيئة TeXSaveOptions	
		TeXSaveOptions saveOptions = new TeXSaveOptions();
		
		// حفظ ملف TeX
		pdfDocument.Save(texFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf")

    ' The path to output TeX File.
    Dim texFile = Path.Combine(dataDir, "PDF-to-TeX.tex")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize TeXSaveOptions
        Dim saveOptions As TeXSaveOptions = New TeXSaveOptions()
 
        ' Save TeX file
        pdfDocument.Save(texFile, saveOptions)
    End Using
```

### انظر أيضًا

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


