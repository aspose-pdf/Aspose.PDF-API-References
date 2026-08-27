---
title: "الفئة EpubSaveOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.EpubSaveOptions. خيارات الحفظ لتصدير إلى تنسيق EPUB"
type: docs
weight: 4180
url: /ar/net/aspose.pdf/epubsaveoptions/
---
## EpubSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق EPUB

```csharp
public class EpubSaveOptions : UnifiedSaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EpubSaveOptions](epubsaveoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم إغلاق كائن Response بعد حفظ المستند في الاستجابة. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذا السمة تفعّل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [Title](../../aspose.pdf/epubsaveoptions/title/) { get; set; } | يحصل على عنوان مستند EPUB أو يضبطه. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | استدعاء رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ContentRecognitionMode](../../aspose.pdf/epubsaveoptions/contentrecognitionmode/) | عند تحويل ملف PDF (الذي عادةً ما يكون بتخطيط ثابت)، يحاول محرك التحويل إجراء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج نتيجة بتخطيط انسيابي. هذه الخاصية تضبط ذلك التحويل للطريقة المرغوبة لتعرف المحتوى. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية مكررة موضوعة بجانب بعضها. في هذه الحالة قد يولد مُعالج صيغ الهدف (مثل MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنياته في تنعيم حواف الصورة (مضاد التعرج) عن Acrobat Reader. إذا بدا أن المستند المُصدّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب. انتباه! عادةً ما تُبطئ هذه تحسين الجودة عملية التحويل بشكل ملحوظ، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف PDF إلى ملف EPUB

```csharp
	[C#]
	// المسار إلى دليل المستندات.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf");

	// المسار إلى ملف EPUB الناتج.
	var epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub");
		
	using (Document pdfDocument = new Document(pdfFile))
	{

		// تهيئة EpubSaveOptions \t
		EpubSaveOptions saveOptions = new EpubSaveOptions();
		
		// احفظ ملف EPUB
		pdfDocument.Save(epubFile, saveOptions);
	}
````

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf")

    ' The path to output EPUB File.
    Dim epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub")
 
    Using pdfDocument As Document = New Document(pdfFile)

        ' Initialize EpubSaveOptions    
        Dim saveOptions As EpubSaveOptions = New EpubSaveOptions()
 
        ' Save EPUB file
        pdfDocument.Save(epubFile, saveOptions)
    End Using
```

### انظر أيضًا

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


