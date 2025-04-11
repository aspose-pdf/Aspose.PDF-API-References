---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptions class. خيارات الحفظ للتصدير إلى تنسيق Doc
type: docs
weight: 3750
url: /ar/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | استخدم فقرات أو فواصل أسطر |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج تنسيقات المصدر والوجهة. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كانت رموز الخطوط ستُخزن مؤقتًا أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى تنسيقات أخرى ولكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | يحصل أو يحدد التحويل لخطوط Type3. في خطوط Type 3، يجب تعريف الرموز بواسطة تدفقات من مشغلات الرسوم. هذا يعني أنه في مخرجات DOC/DOCX نرى صورًا بدلاً من نص. قم بتعيين هذه العلامة إلى true لتحويل خطوط Type3 إلى TTF والحصول على نص في الملف الناتج. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذه السمة تفعيل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | تنسيق الإخراج |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | دقة الصور المحولة في الاتجاه X. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | دقة الصور المحولة في الاتجاه Y. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | تُستخدم هذه المعلمة لتجميع خطوط النص في فقرات. تحدد مدى بُعد خطي نص نسبيين عن بعضهما. يتم تحديده بمئات النسب المئوية لارتفاع خطوط النص. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | يحدد المسار (اسم الملف أو اسم الدليل) للاحتفاظ بالبيانات المؤقتة عند التحويل في وضع حفظ الذاكرة. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | وضع التعرف. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | تفعيل التعرف على النقاط |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | في PDF، قد يتم تمثيل الكلمات داخليًا بواسطة مشغلات تطبع الكلمات عن طريق طباعة حروفها أو مقاطعها بشكل مستقل. لذلك، لاكتشاف الكلمات، نحتاج أحيانًا إلى اكتشاف مجموعات من الأحرف المستقلة التي هي في الواقع كلمات. تحدد هذه الإعدادات عرض المسافة بين عناصر النص (الحروف، المقاطع) التي يجب اعتبارها مسافة بين الكلمات أثناء التعرف على الكلمات في PDF المصدر. (وجود مساحة فارغة على الأقل بهذا العرض بين الحروف يعني أن العناصر النصية تتعلق بكلمات مختلفة). يتم قياسها بحجم الخط - 1.0 يعني 100% من حجم خط الكلمة المفترض. انتبه! تُستخدم فقط في الحالات التي يحتوي فيها PDF المصدر على خطوط نادرة الاستخدام لا يمكن حساب القيمة المثلى لها من الخط. لذلك، في الغالبية العظمى من الحالات، لا تغير هذه المعلمة شيئًا في المستند الناتج. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | يحصل أو يحدد إجراء إعادة حفظ الخطوط. إذا تم تعيينه على true، نقوم بإعادة تحميل الخطوط في كل صفحة لتجنب تأثير خصائص الخط السابقة وتحميل الخط الجديد من البداية. قم بتعيين هذا الخيار على false إذا كنت ترغب في تحسين الأداء. القيمة الافتراضية هي true؛ |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | رد الاتصال لمعالجة أي تحذيرات تم إنشاؤها. يُرجع WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي ويستمر عملية الحفظ، ومع ذلك، يمكن للمستخدم أيضًا إرجاع Abort، وفي هذه الحالة يجب أن تتوقف عملية الحفظ. |

## Fields

| Name | Description |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | يمكن استخدام هذا المعالج للتعامل مع أحداث تقدم التحويل، على سبيل المثال، يمكن استخدامه لعرض شريط تقدم أو رسائل حول الكمية الحالية من الصفحات المعالجة، مثال على كود المعالج الذي يظهر التقدم على وحدة التحكم هو: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجدول) تم إنشاؤها من عدة صور خلفية متكررة موضوعة بجانب بعضها. في هذه الحالة، تقوم محركات التنسيق المستهدف (مثل MsWord لتنسيق DOCS) أحيانًا بإنشاء حدود مرئية بين أجزاء الصور الخلفية، لأن تقنياتهم في تنعيم حواف الصور (مضاد التعرج) تختلف عن Acrobat Reader. إذا بدا أن المستند المصدر يحتوي على مثل هذه الحدود المرئية بين أجزاء من نفس الصور الخلفية، يرجى محاولة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما تؤدي هذه التحسينات في الجودة إلى إبطاء التحويل بشكل كبير، لذا، يرجى استخدام هذا الخيار فقط عندما يكون ذلك ضروريًا حقًا. |

### Examples

المثال التالي يوضح كيفية تحويل ملف PDF إلى ملف DOC أو DOCX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
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

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)