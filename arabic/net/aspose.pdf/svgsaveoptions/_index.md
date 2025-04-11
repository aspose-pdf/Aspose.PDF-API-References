---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.SvgSaveOptions. خيارات الحفظ للتصدير إلى تنسيق SVG
type: docs
weight: 10230
url: /ar/net/aspose.pdf/svgsaveoptions/
---
## فئة SvgSaveOptions

خيارات الحفظ للتصدير إلى تنسيق SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم تخزين رموز الخطوط أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى تنسيقات أخرى ولكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذه السمة تقوم بتفعيل الوظيفة لاستخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يقوم WarningHandler بإرجاع عنصر من تعداد ReturnAction يحدد إما الاستمرار أو الإنهاء. الاستمرار هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك يمكن للمستخدم أيضًا إرجاع الإنهاء وفي هذه الحالة يجب أن تتوقف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | يحدد ما إذا كان سيتم إنشاء المخرجات كأرشيف مضغوط واحد. يرجى الرجوع إلى التعليق على خيارات 'TreatTargetFileNameAsDirectory' لرؤية قواعد تسمية ملفات SVG للصفحات لمستند المصدر متعدد الصفحات، والتي تنطبق أيضًا على مجموعة الملفات الناتجة المضغوطة. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | يمكن أن يحتوي هذا الحقل على استراتيجية الحفظ التي يجب استخدامها (إذا كانت موجودة) أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المرجعية التي تم إنشاؤها (مثل BMP أو JPEG المضمنة) المضمنة في SVG المحفوظ. يجب أن تعالج تلك الاستراتيجية الموارد وتعيد سلسلة تمثل URI المرغوب فيه للموارد المحفوظة في SVG الناتج. إذا كان يجب معالجة هذا الملف أو ذاك لسبب ما بواسطة كود المحول نفسه، وليس في كود مخصص، يرجى تعيين في كود مخصص علامة 'CustomProcessingCancelled' لمتغير 'imageSavingInfo'. إنه يشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة تلك المورد يجب أن تتم في المحول نفسه كما لو لم يكن هناك أي كود مخصص خارجي. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | يحدد ما إذا كان يجب تغيير حجم المستند الناتج من نقاط الطباعة إلى بكسلات. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | تحدد هذه الخيارات ما إذا كان سيتم إنشاء دليل الهدف (إذا لم يكن موجودًا بعد) بنفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج المطلوب نفسه. إذا كان الأمر كذلك، فسيحتوي الدليل على جميع صور SVG الناتجة للصفحات (كما هو موضح أدناه). إذا لم يكن كذلك، فسيتم إنشاء ملفات الإخراج للصفحات الأخرى غير الأولى بالضبط في الدليل المطلوب كملف الإخراج الرئيسي، ولكن ستحتوي على لاحقة في اسم الملف _[2...n]، التي تحددها رقم الصفحة، على سبيل المثال، إذا قمت بتحديد ملف الإخراج "C:\AsposeTests\output.svg" وكانت الإخراج تحتوي على عدة ملفات SVG للصفحات، فسيتم أيضًا إنشاء ملفات الصفحات في الدليل "C:\AsposeTests\" وستكون أسماؤها 'output.svg'، 'output_2.svg'، 'output_3.svg'، إلخ. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجدول) تم بناؤها من عدة صور خلفية متكررة متجاورة. في هذه الحالة، تقوم برامج العرض للتنسيقات المستهدفة (مثل MsWord لتنسيق DOCS) أحيانًا بإنشاء حدود مرئية بين أجزاء الصور الخلفية، لأن تقنياتهم في تنعيم حواف الصور (مضاد التعرج) تختلف عن Acrobat Reader. إذا بدا أن المستند المصدر يحتوي على مثل هذه الحدود المرئية بين أجزاء من نفس الصور الخلفية، يرجى محاولة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما تؤدي هذه التحسينات في الجودة إلى إبطاء التحويل بشكل كبير، لذا، يرجى استخدام هذا الخيار فقط عندما يكون ذلك ضروريًا حقًا. |

## أمثلة

يوضح المثال التالي كيفية تحويل ملف PDF إلى ملف SVG

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### انظر أيضًا

* فئة [UnifiedSaveOptions](../unifiedsaveoptions/)
* مساحة [Aspose.Pdf](../../aspose.pdf/)
* تجميع [Aspose.PDF](../../)