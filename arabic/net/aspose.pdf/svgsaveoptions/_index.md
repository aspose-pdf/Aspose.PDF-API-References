---
title: "الفئة SvgSaveOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.SvgSaveOptions. خيارات الحفظ لتصدير إلى صيغة SVG"
type: docs
weight: 10410
url: /ar/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم إغلاق كائن Response بعد حفظ المستند في الاستجابة. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذا السمة تفعّل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | استدعاء رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | يحدد ما إذا كان سيتم إنشاء المخرجات كأرشيف zip واحد. يرجى الرجوع إلى التعليق على خيار 'TreatTargetFileNameAsDirectory' لرؤية قواعد تسمية ملفات svg للصفحات في مستند المصدر متعدد الصفحات، والتي تُطبق أيضاً على مجموعة الملفات المضغوطة. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | يمكن لهذا الحقل أن يحتوي على استراتيجية حفظ يجب استخدامها (إن وجدت) أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المرجعية التي تم إنشاؤها (مثل BMP أو JPEG المضمّن) المضمّنة في SVG المحفوظ. يجب أن تقوم هذه الاستراتيجية بمعالجة الموارد وإرجاع سلسلة تمثل URI المطلوب للموارد المحفوظة في SVG المُولَّد. إذا كان من الضروري معالجة هذا الملف أو ذاك الملف لسبب ما بواسطة كود المحول نفسه، وليس عبر كود مخصص، يرجى تعيين علامة 'CustomProcessingCancelled' في المتغيّر الخاص بمعامل 'imageSavingInfo' في الكود المخصص. هذا يُشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة ذلك المورد يجب أن تُنفّذ داخل المحول كما لو لم يكن هناك أي كود مخصص خارجي. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | يحدد ما إذا كان سيتم تحويل مقياس المستند الناتج من النقاط الطباعية إلى البكسلات. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | تحدد هذه الخيار ما إذا كان سيتم إنشاء دليل هدف (إن لم يكن موجوداً) يحمل نفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج نفسه. وبالتالي سيحتوي الدليل على جميع صور SVG للصفحات (كما هو موضح أدناه). إذا كان الجواب لا، فسيتم إنشاء ملفات الصفحات الأخرى غير الأولى في الدليل المطلوب نفسه كملف الإخراج الرئيسي، ولكن سيُضاف إلى اسم الملف اللاحقة _[2...n] التي تُحدَّد برقم الصفحة، على سبيل المثال إذا حددت ملف الإخراج "C:\AsposeTests\output.svg" وكان الإخراج يحتوي على عدة ملفات svg للصفحات، فسيتم إنشاء ملفات الصفحات أيضاً في الدليل "C:\AsposeTests\" وستكون أسماؤها 'output.svg', 'output_2.svg', 'output_3.svg' إلخ. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية مكررة موضوعة بجانب بعضها. في هذه الحالة قد يولد مُعالج صيغ الهدف (مثل MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنياته في تنعيم حواف الصورة (مضاد التعرج) عن Acrobat Reader. إذا بدا أن المستند المُصدّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب. انتباه! عادةً ما تُبطئ هذه تحسين الجودة عملية التحويل بشكل ملحوظ، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف PDF إلى ملف SVG

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// المسار إلى ملف SVG الناتج.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// تهيئة SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// حفظ ملف SVG
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


