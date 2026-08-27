---
title: "فئة XpsSaveOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.XpsSaveOptions. خيارات الحفظ لتصدير إلى تنسيق Xps"
type: docs
weight: 11710
url: /ar/net/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق Xps

```csharp
public class XpsSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpssaveoptions/batchsize/) { get; set; } | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم إغلاق كائن Response بعد حفظ المستند في الاستجابة. |
| [DefaultFont](../../aspose.pdf/xpssaveoptions/defaultfont/) { get; set; } | يحصل/يعيّن اسم الخط الافتراضي. يُستخدم إذا لم يتم العثور على اسم الخط المضمّن في النظام. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذا السمة تفعّل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts/) { get; set; } | يشير إلى ما إذا كان يجب الحفاظ على النص الشفاف (المعالج بـ OCR). |
| [UseEmbeddedTrueTypeFonts](../../aspose.pdf/xpssaveoptions/useembeddedtruetypefonts/) { get; set; } | يحصل/يعيّن العلامة لاستخدام خطوط TrueType المضمّنة. تجنّب استخدام خطوط TrueType المضمّنة يمكن أن يقلل من وقت التحويل. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | استدعاء رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية مكررة موضوعة بجانب بعضها. في هذه الحالة قد يولد مُعالج صيغ الهدف (مثل MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنياته في تنعيم حواف الصورة (مضاد التعرج) عن Acrobat Reader. إذا بدا أن المستند المُصدّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب. انتباه! عادةً ما تُبطئ هذه تحسين الجودة عملية التحويل بشكل ملحوظ، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف PDF إلى ملف XPS

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// المسار إلى ملف PDF الخاص بك
	var pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf");

	// المسار إلى ملف XPS الخاص بك
	var xpsFile= Path.Combine(dataDir, "PDF-to-XPS.xps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// تهيئة XpsSaveOptions	
		XpsSaveOptions saveOptions = new XpsSaveOptions();
		
		// حفظ ملف XPS
		pdfDocument.Save(xpsFile, saveOptions);
	}
```

```csharp
[VB.NET]
 
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf")

    ' The path to your XPS File
    Dim xpsFile = Path.Combine(dataDir, "PDF-to-XPS.xps")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XpsSaveOptions
        Dim saveOptions As XpsSaveOptions = New XpsSaveOptions()
 
        ' Save XPS file
        pdfDocument.Save(xpsFile, saveOptions)
    End Using
```

### انظر أيضًا

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


