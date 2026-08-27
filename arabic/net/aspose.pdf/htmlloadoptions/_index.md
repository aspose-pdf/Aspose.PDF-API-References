---
title: "فئة HtmlLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.HtmlLoadOptions. تمثل خيارات تحميل/استيراد ملف html إلى مستند pdf"
type: docs
weight: 5660
url: /ar/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

يمثل الخيارات لتحميل/استيراد ملف html إلى مستند pdf.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | ينشئ خيارات التحميل لتحويل html إلى مستند pdf مع مسار أساسي فارغ. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | ينشئ خيارات التحميل لتحويل html إلى مستند pdf مع مسار أساسي محدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | المسار/الرابط الأساسي لملف html. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | يحصل أو يعيّن أنواع الوسائط الممكنة المستخدمة أثناء العرض. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | يحصل أو يضبط السمة التي تحدد الترميز المستخدم لهذا المستند عند التحليل. إذا كانت هذه السمة فارغة، سيُحدد الترميز من سمة مجموعة أحرف المستند. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | يحصل أو يضبط تضمين الخطوط في المستند الناتج |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | يحصل أو يضبط العلم الذي يحدد أن قواعد @page المعرفة في css ستتجاوز القيم المعرفة في PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | يحصل أو يضبط تحويل كامل المستند إلى صفحة واحدة |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | يحصل أو يضبط معلومات صفحة المستند |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | يحصل أو يعيّن خيار التخطيط. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | في بعض الأحيان يكون من الضروري تجنب استخدام المحمل الداخلي للموارد الخارجية (مثل الصور أو ملفات CSS) وتوفير طريقة مخصصة للحصول على الموارد المطلوبة من مكان ما. على سبيل المثال، أثناء استخدام Aspose.PDF في السحابة لا يمكن الوصول المباشر إلى الملفات المشار إليها: في هذه الحالة يجب استخدام بعض الشيفرة المخصصة الموضوعة في طريقة خاصة، ويجب تعيين المفوض الذي يشير إلى تلك الطريقة إلى هذه السمة. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | إذا كان تحميل البيانات الخارجية المشار إليها في HTML يتطلب بيانات اعتماد، يمكنك وضعها في هذا المعامل - سيتم استخدامها أثناء تحميل الموارد الخارجية |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف HTML إلى ملف PDF

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// المسار إلى ملف HTML الخاص بك.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// المسار إلى ملف PDF الناتج.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// تهيئة HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// حفظ ملف PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


