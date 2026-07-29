---
title: "الفئة DocSaveOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.DocSaveOptions. خيارات الحفظ لتصدير إلى تنسيق Doc"
type: docs
weight: 3870
url: /ar/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | استخدم فواصل الفقرات أو الأسطر |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم إغلاق كائن Response بعد حفظ المستند في الاستجابة. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | الحصول أو تعيين التحويل للخطوط Type3. في خطوط Type 3، يجب تعريف الرموز عبر تدفقات من عوامل الرسومات. هذا يعني أنه في مخرجات DOC/DOCX نرى صورًا بدلاً من النص. اضبط هذا العلم إلى true لتحويل خطوط Type3 إلى TTF والحصول على النص في الملف الناتج. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذا السمة تفعّل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | تنسيق الإخراج |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | دقة الصور المحوّلة X. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | دقة الصور المحوّلة Y. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | يُستخدم هذا المعامل لتجميع أسطر النص في فقرات. يحدّد المسافة التي يمكن أن تكون بين سطرين نصيين نسبيين. يُحدّد بالمئات من نسبة ارتفاع أسطر النص. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | يحدد المسار (اسم الملف أو اسم الدليل) لحفظ البيانات المؤقتة عند التحويل في وضع الحفظ في الذاكرة. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | وضع التعرف. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | تشغيل التعرف على النقاط. |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | في Pdf قد يتم تمثيل الكلمات داخليًا باستخدام عوامل تُطبع الكلمات بطباعة حروفها أو مقاطعها بشكل مستقل. لذلك، لاكتشاف الكلمات أحيانًا نحتاج إلى اكتشاف مجموعات من الأحرف المستقلة التي هي في الواقع كلمات. يحدد هذا الإعداد عرض الفراغ بين عناصر النص (الحروف، المقاطع) الذي يجب معالجته كمسافة بين الكلمات أثناء التعرف على الكلمات في PDF المصدر. (وجود فراغ فارغ بعرض لا يقل عن هذا العرض بين الحروف يعني أن العناصر النصية تتبع لكلمات مختلفة). يتم تطبيعه وفقًا لحجم الخط - 1.0 يعني 100٪ من حجم الخط المفترض للكلمة. ATTENTION! يُستخدم فقط في الحالات التي يحتوي فيها PDF المصدر على خطوط نادرة الاستخدام لا يمكن حساب القيمة المثلى لها من الخط. لذا، في الغالبية العظمى من الحالات لا يغيّر هذا المعامل شيئًا في المستند الناتج. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | الحصول أو تعيين الإجراء لإعادة حفظ الخطوط. إذا تم تعيينه إلى true، نقوم بإعادة تحميل الخطوط في كل صفحة لتجنب تأثير خصائص الخط السابقة وتحميل الخط الذي تم إنشاؤه حديثًا من الصفر. اضبط هذا الخيار إلى false إذا كنت ترغب في تحسين الأداء. القيمة الافتراضية هي true؛ |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | استدعاء رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | يمكن استخدام هذا المعالج لمعالجة أحداث تقدم التحويل، على سبيل المثال يمكن استخدامه لعرض شريط تقدم أو رسائل حول عدد الصفحات المعالجة حاليًا، مثال على كود المعالج الذي يعرض التقدم في وحدة التحكم هو: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية مكررة موضوعة بجانب بعضها. في هذه الحالة قد يولد مُعالج صيغ الهدف (مثل MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنياته في تنعيم حواف الصورة (مضاد التعرج) عن Acrobat Reader. إذا بدا أن المستند المُصدّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب. انتباه! عادةً ما تُبطئ هذه تحسين الجودة عملية التحويل بشكل ملحوظ، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |

### أمثلة

المثال التالي يوضح كيفية تحويل ملف PDF إلى ملف DOC أو DOCX

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// المسار إلى ملف DOC أو DOCX الناتج.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// تعيين وضع التعرف كـ Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// تعيين القرب الأفقي إلى 2.5
			RelativeHorizontalProximity = 2.5f,
			// تمكين القيمة للتعرف على النقاط أثناء عملية التحويل
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### انظر أيضًا

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


